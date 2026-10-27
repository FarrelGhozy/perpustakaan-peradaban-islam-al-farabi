# Naskah — cara kompilasi

Sumber utama: `main.tex` + `referensi.bib` (biblatex-chicago, backend Biber).
Wajib **LuaLaTeX** (fontspec) + **Biber**, bukan pdflatex+bibtex.

```bash
cd naskah
lualatex -interaction=nonstopmode main.tex
biber main
lualatex -interaction=nonstopmode main.tex
lualatex -interaction=nonstopmode main.tex
cp main.pdf ../output/naskah.pdf
```

Dependensi TeX Live: `biblatex`, `biblatex-chicago`, `fontspec`,
`geometry`, `setspace`, `booktabs`, `tabularx`, `enumitem`, `caption`,
`microtype`, `fancyhdr`, `tcolorbox`, `hyperref`, `graphicx`,
dan font TeX Gyre Termes (`texlive-fonts-opentype`).

Format wajib (dipertahankan): A4, 12pt, single spacing, margin 2,54 cm.
Fitur kerapian: halaman sampul UNIDA, header/footer + nomor halaman,
kotak tesis dan kotak batas analogi, Tabel 1 via `tabularx` selebar teks,
daftar isi + daftar tabel.

Catatan font: dokumen memakai `\setmainfont{TeX Gyre Termes}` — klon metrik
Times yang tersedia bebas. Times New Roman asli tidak tersedia di host ini,
sehingga PDF **tidak diklaim** memakai Times New Roman. Jika Anda memiliki
lisensi Times New Roman, ganti satu baris `setmainfont` dan kompilasi ulang.

Kompilasi terakhir yang terverifikasi: 15 halaman A4, 0 error, 16 entri
pustaka, lihat `../log/catatan_verifikasi.md`.

## Versi Word (DOCX)

`../docx/naskah.docx` dibangun dari `main.tex` ini (bukan dari PDF) dengan
python-docx: Judul/Heading 1/2 memakai Word Styles, 61 catatan kaki Chicago
NB sebagai footnote Word asli, 2 tabel ber-caption (SEQ Tabel), Daftar
Pustaka 16 entri, A4 + margin 2,54 cm + Times New Roman 12 pt + single
spacing + nomor halaman. Sitasi berupa teks statis terverifikasi — BUKAN
field aktif Zotero (lihat status integrasi di `../log/catatan_verifikasi.md`
dan cara menghubungkan ulang di `../docx/README.md`). Setiap perubahan isi
wajib dilakukan di `main.tex` lalu bangun ulang DOCX; jangan edit DOCX
sebagai sumber kebenaran.

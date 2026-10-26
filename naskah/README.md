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

Kompilasi terakhir yang terverifikasi: 10 halaman A4, 0 error, 16 entri
pustaka tersitasi semua, lihat `../log/catatan_verifikasi.md`.

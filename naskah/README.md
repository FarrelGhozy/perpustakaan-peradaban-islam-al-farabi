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

Dependensi: TeX Live dengan `biblatex`, `biblatex-chicago`, `fontspec`,
`geometry`, `setspace`, `booktabs`, `enumitem`, `hyperref`, dan font
TeX Gyre Termes (`texlive-fonts-opentype`).

Catatan font: dokumen memakai `\setmainfont{TeX Gyre Termes}` — klon metrik
Times yang tersedia bebas. Times New Roman asli tidak tersedia di host ini,
sehingga PDF **tidak diklaim** memakai Times New Roman. Jika Anda memiliki
lisensi Times New Roman, ganti satu baris `setmainfont` dan kompilasi ulang.

Kompilasi terakhir yang terverifikasi: 10 halaman A4, 0 error, 16 entri
pustaka, lihat `../log/catatan_verifikasi.md`.

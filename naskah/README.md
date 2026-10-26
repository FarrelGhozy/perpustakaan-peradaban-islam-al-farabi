# Naskah LaTeX

- `main.tex` — sumber naskah (kerangka + aturan sitasi di komentar baris atas).
- `referensi.bib` — bibliografi BibTeX, hanya entri terverifikasi.

Kompilasi:

```bash
cd naskah
pdflatex -interaction=nonstopmode main.tex
bibtex main
pdflatex -interaction=nonstopmode main.tex
pdflatex -interaction=nonstopmode main.tex
cp main.pdf ../output/naskah.pdf
```

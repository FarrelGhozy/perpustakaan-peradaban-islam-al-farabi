# Perpustakaan dalam Peradaban Islam: Dari Katalog Manuskrip Menuju Konsep Perpustakaan Digital dan Basis Data

Fokus: kontribusi Abu Nasr al-Farabi dalam perkembangan logika, serta persamaan, perbedaan, dan relevansinya
dengan logika formal dalam Teknik Informatika (pengorganisasian pengetahuan, representasi informasi,
pencarian informasi, dan basis data).

> Prinsip: kebenaran akademik di atas segalanya. Dilarang mengarang sumber. Setiap klaim penting harus
> dapat ditelusuri. Fakta sejarah, interpretasi peneliti, analogi konseptual, dan kesimpulan sendiri
> dibedakan secara eksplisit. Lihat `log/catatan_verifikasi.md`.

## Struktur proyek

- `naskah/` — sumber LaTeX (`main.tex`) + bibliografi (`referensi.bib`). Output PDF di `output/naskah.pdf`.
- `kutipan/` — bukti kutipan per sumber (foto/scan secukupnya + catatan halaman) + `daftar_sumber.md` + `metadata/`.
- `riset/` — rumusan masalah, peta argumen, matriks sumber, catatan sejarah.
- `presentasi/` — rangkuman bahan presentasi.
- `output/` — PDF hasil kompilasi.
- `log/` — catatan verifikasi (sumber diperiksa vs belum).

## Cara kompilasi

```bash
cd naskah
pdflatex -interaction=nonstopmode main.tex
bibtex main
pdflatex -interaction=nonstopmode main.tex
pdflatex -interaction=nonstopmode main.tex
cp main.pdf ../output/naskah.pdf
```

## Status verifikasi

Lihat `log/catatan_verifikasi.md` — satu-satunya acuan status sumber yang sudah/belum diverifikasi.
Jangan mengutip sumber berstatus "belum diverifikasi" di dalam naskah final.

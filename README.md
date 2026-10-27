# Perpustakaan dalam Peradaban Islam: Dari Katalog Manuskrip Menuju Konsep Perpustakaan Digital dan Basis Data

Fokus: kontribusi Abu Nasr al-Farabi dalam perkembangan logika, serta persamaan, perbedaan, dan relevansinya
dengan logika formal dalam Teknik Informatika (pengorganisasian pengetahuan, representasi informasi,
pencarian informasi, dan basis data).

> Prinsip: kebenaran akademik di atas segalanya. Dilarang mengarang sumber. Setiap klaim penting harus
> dapat ditelusuri. Fakta sejarah, interpretasi peneliti, analogi konseptual, dan kesimpulan sendiri
> dibedakan secara eksplisit. Lihat `log/catatan_verifikasi.md`.

## Status ringkas

- Naskah: `naskah/main.tex` → PDF `output/naskah.pdf` (15 hlm A4, 12pt, single, margin 2,54 cm,
  LuaLaTeX + Biber, 0 error, 16 sumber tersitasi semua).
- Referensi: 16 unik, **7 teks-penuh** (5 HTML resmi SEP di `kutipan/sep/` + 2 PDF jurnal di
  `kutipan/artikel_jurnal/`) + 9 metadata resmi (buku/artikel paywall, hanya klaim umum tanpa halaman).
- Semua DOI/URL di `kutipan/daftar_sumber.md` adalah URL resmi (official): DOI resmi atau halaman
  resmi penerbit (ACM, UCP, Springer, CUP, Brill, De Gruyter, Routledge, OJS Richtmann, SEP Stanford).
- Presentasi: `presentasi/rangkuman_ppt.md` (10 slide, setia pada naskah, tiap klaim ada sumber).
- Word: `docx/naskah.docx` (dari `main.tex`, 61 footnote Chicago asli, 2 tabel,
  A4/TNR 12pt/single; sitasi teks statis — lihat `docx/README.md`).
  Zotero Desktop 140.17.0esr terunduh & berjalan, tapi integrasi Word butuh GUI
  sehingga status field-aktif BELUM TERPENUHI; `.bib` lolos translator resmi
  Zotero 16/16 bersih (`kutipan/zotero-csl.json`).
- Lisensi: file proyek sendiri MIT (lihat `LICENSE`); PDF pihak ketiga di `kutipan/` tetap milik
  penerbit masing-masing — repo ini **private**, bukan untuk redistribusi publik.

## Struktur proyek

- `naskah/` — sumber LaTeX (`main.tex`) + bibliografi (`referensi.bib`). Output PDF di `output/naskah.pdf`.
- `kutipan/` — bukti kutipan per sumber + `daftar_sumber.md` + `README.md` tata kelola:
  - `kutipan/sep/` — 5 HTML resmi SEP + README;
  - `kutipan/artikel_jurnal/` — 2 PDF (S13 OA, S14 mirror fair-use) + 3 catatan resmi S12/S13/S14;
  - `kutipan/buku/` — 8 catatan resmi per buku (URL resmi penerbit, DOI, batas akses);
  - `kutipan/sumber_primer/` — petunjuk akses legal karya al-Farabi;
  - `kutipan/metadata/` — 10 JSON Crossref/Open Library.
- `riset/` — rumusan masalah, peta argumen, matriks sumber, catatan sejarah.
- `presentasi/` — rangkuman bahan presentasi (Markdown, bukan PPT).
- `output/` — PDF hasil kompilasi (`naskah.pdf`).
- `docx/` — versi Word (`naskah.docx` + `README.md` berisi status Zotero & cara hubung-ulang).
- `log/` — catatan verifikasi (sumber diperiksa vs belum; termasuk yang gagal).

## Cara kompilasi

```bash
cd naskah
lualatex -interaction=nonstopmode main.tex
biber main
lualatex -interaction=nonstopmode main.tex
lualatex -interaction=nonstopmode main.tex
cp main.pdf ../output/naskah.pdf
```

Font: TeX Gyre Termes (klon metrik Times; Times New Roman asli tidak
tersedia di host ini — lihat `log/catatan_verifikasi.md` dan `naskah/README.md`).
Halaman sampul: Universitas Darussalam Gontor, Fakultas Sains dan Teknologi, TI.

## Cara verifikasi

1. Buka `kutipan/daftar_sumber.md` — tiap ID (S01–S16) ada penulis, tahun, DOI/URL resmi,
   status verifikasi, status berkas, lokasi berkas, bagian yang digunakan.
2. Buka bukti fisik di `kutipan/` sesuai kolom lokasi berkas.
3. Silangkan dengan `log/catatan_verifikasi.md` (riwayat HTTP, kutipan persis, kegagalan jujur).
4. Jangan mengutip sumber berstatus `metadata` dengan nomor halaman.

## Status verifikasi

Lihat `log/catatan_verifikasi.md` — satu-satunya acuan status sumber yang sudah/belum diverifikasi.
Jangan mengutip sumber berstatus "belum diverifikasi" di dalam naskah final.

## GitHub

Remote: `https://github.com/FarrelGhozy/perpustakaan-peradaban-islam-al-farabi.git` (private).
Setelah edit lokal: `git add -A && git commit -m "..." && git push origin main`.

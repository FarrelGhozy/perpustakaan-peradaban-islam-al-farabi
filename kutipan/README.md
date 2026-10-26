# Kutipan — bukti yang dapat diperiksa

Setiap sumber yang disitasi di naskah WAJIB punya bukti di sini.
Satu sitasi = satu baris di `daftar_sumber.md` = satu berkas/bukti di direktori ini.

## Struktur

- `artikel_jurnal/` — PDF resmi yang open access (S13) atau mirror institusional
  publik untuk verifikasi fair-use (S14) + satu file `*_catatan.md` per artikel
  berisi URL resmi (official), DOI, status akses, dan kutipan kunci.
- `sep/` — arsip HTML resmi 5 entri Stanford Encyclopedia of Philosophy
  (S01–S04, S15) + `README.md` + `OFFICIAL_URLS.md`. SEP terbuka untuk dibaca;
  arsip lokal untuk verifikasi, bukan redistribusi.
- `buku/` — satu file `*_catatan.md` per buku berisi URL resmi penerbit, DOI,
  status akses, dan batas penggunaan. TIDAK ada PDF bajakan.
- `sumber_primer/` — petunjuk akses legal karya al-Farabi (lihat README di dalamnya).
- `metadata/` — hasil verifikasi Crossref / Open Library per sumber (JSON).

## Penamaan

`<kunci-bibtex>_<halaman>.<ext>` untuk bukti halaman, atau
`S<nn>_<penulis><tahun>_catatan.md` untuk catatan resmi per sumber.

## Aturan akses

1. PDF OA (S13, lisensi CC BY-NC-ND) boleh disimpan dan disitasi penuh.
2. Mirror publik (S14) hanya untuk verifikasi riset; repo WAJIB private,
   jangan redistribusi publik. URL resmi ACM tetap dicatat sebagai otoritas.
3. Buku paywall: metadata + catatan saja, tanpa nomor halaman.
   Klaim isi logika Farabi dirujuk via SEP teks-penuh (S01), bukan klaim baca langsung.
4. Tanpa bukti di direktori ini, sitasi dianggap BELUM terverifikasi.
5. Daftar resmi per sumber: lihat `daftar_sumber.md` kolom DOI/URL (semua URL
   adalah URL resmi penerbit atau DOI resmi) dan `log/catatan_verifikasi.md`.

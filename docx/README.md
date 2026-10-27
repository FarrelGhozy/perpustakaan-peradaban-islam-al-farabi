# Versi Word — `naskah.docx`

Dibangun dari `../naskah/main.tex` (15 hlm, terkompilasi bersih 0 error),
bukan dari PDF. Isi, urutan, tabel, catatan kaki, dan Daftar Pustaka sama
dengan PDF final.

Isi paket:

- 94 paragraf, 10 Heading 1, sub-bab Heading 2, 2 tabel ber-caption
  (`Tabel 1–2`, SEQ field), 16 entri Daftar Pustaka Chicago NB.
- 61 catatan kaki Chicago Notes & Bibliography sebagai footnote Word asli
  (kutipan pertama penuh, pengulangan bentuk singkat).
- A4, margin 2,54 cm, font Times New Roman 12 pt, spasi single, nomor halaman.

## Yang harus dilakukan di Word (sekali saja)

1. Buka di MS Word → klik kanan **Daftar Isi → Update Field → Update entire table**.
   Lakukan hal yang sama pada **Daftar Tabel**.
2. Cek cepat: 13 ± 2 halaman, tabel tidak terpotong, catatan kaki di tiap
   bagian ada.

## Status manajer referensi (jujur)

- **Zotero Desktop 140.17.0esr diunduh dan dijalankan di host ini** (terbukti
  bisa start), tetapi **tidak dapat dipakai untuk mengelola sitasi**: host
  ini headless (tanpa layar) dan tidak ada MS Word — integrasi Word/Zotero
  butuh aplikasi GUI yang berjalan.
- **Mendeley: tidak tersedia** (tidak ada paket desktop/Linux yang resmi
  dan tidak ada Word).
- Sebagai gantinya, `../naskah/referensi.bib` **divalidasi dengan translator
  BibTeX resmi Zotero** (translation-server v2.0.5 + 748 translator resmi):
  16/16 item terurai bersih tanpa artefak — bukti di
  `../kutipan/zotero-csl.json`. Markup LaTeX (`\emph`, `\"u`, `\=a`) sudah
  dibersihkan jadi Unicode agar impor ke Zotero bersih.
- **Sitasi di DOCX ini adalah teks statis terverifikasi, BUKAN field aktif
  Zotero.** Jangan diklaim sebaliknya.

## Menghubungkan ulang ke Zotero (di laptop Windows, ±10 menit)

1. Instal Zotero Desktop + plugin Word (dari zotero.org/download).
2. Buat collection `Perpustakaan Peradaban Islam - al-Farabi`.
3. File → Import → pilih `naskah/referensi.bib` (format BibTeX) ke collection
   tersebut. Cocokkan dengan `../kutipan/daftar_sumber.md` (16 item).
4. Di Word: Zotero → Document Preferences → gaya
   **Chicago Manual of Style 17th edition (note)** / "Chicago Notes and
   Bibliography".
5. Ganti catatan kaki statis dengan sitasi Zotero satu per satu
   (Add/Edit Citation) bila field aktif dibutuhkan untuk revisi dosen.
6. Jika hanya butuh dibaca/dikumpulkan: dokumen ini sudah final tanpa
   langkah 5.

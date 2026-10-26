# Catatan Verifikasi

Log pemeriksaan sumber. Jujur dan lengkap: catat juga yang GAGAL diverifikasi.

## Format entri

```
### [YYYY-MM-DD] <Kunci BibTeX> — <Penulis, Judul singkat>
- Klaim yang diperiksa: ...
- Metode: teks-penuh / sebagian (hlm. x-y) / abstrak-saja / metadata-saja
- Akses: <URL katalog/penerbit/DOI + status HTTP> / <katalog perpustakaan>
- Hasil: terverifikasi / sebagian / gagal (alasan)
- Kutipan persis + halaman: "..." (hlm. ...)
```

## Riwayat

### [2026-10-26] hodges-druart2019 — Hodges & Druart, "Al-Farabi's Philosophy of Logic and Language" (SEP)
- Klaim yang diperiksa: keberadaan entri; penulis; tanggal publikasi/revisi; isi bagian 5–7 (definisi logika,
  silogisme kategoris, demonstrasi); bibliografi karya al-Farabi (Ihsa al-Ulum, komentar Organon).
- Metode: teks-penuh (HTML entri diunduh utuh, 135 KB, dianalisis per bagian).
- Akses: https://plato.stanford.edu/entries/al-farabi-logic/ — HTTP 200.
- Hasil: TERVERIFIKASI teks-penuh.
- Sitasi resmi: Hodges, Wilfrid & Druart, Therese-Anne. "Al-Farabi's Philosophy of Logic and Language",
  _The Stanford Encyclopedia of Philosophy_, pertama terbit 16 Apr 2019, revisi substantif 9 Mei 2023.
- Kutipan kunci (siap pakai, dgn konteks bagian):
  1. "[Demonstration] (64.5-7) al-Farabi tells us: Two arts or sciences differ through having different
     subjects (mawdhu'). ..." (bagian 5, tentang subjek ilmu).
  2. "In his book [Syllogism] 27.6f he claims that the following argument is a valid syllogism:
     No stone is an animal. Some body is an animal. This yields: Some body is not a stone." (bagian 5,
     contoh silogisme valid ala al-Farabi).
  3. "[Catalogue] (59.9-11): As for the subjects of logic, about which it gives rules, they are concepts
     insofar as expressions signify them, and expressions insofar as they signify concepts." (bagian 5,
     definisi subjek logika dalam Ihsa al-Ulum).
  4. "In [Syllogism] and [Short Syllogism] Al-Farabi recognizes three figures of categorical syllogisms,
     following Aristotle... four, four, and six valid moods..." (bagian 6.1).
  5. "the earliest logician on record as having spelled out this implication of 'Every B is an A'"
     (bagian 6.1, klaim keaslian: eksistensial import).
  6. "formalizes an argument at his [Short Syllogism] 90.6-9" — silogisme majemuk hipotetik (bagian 6.2).
  7. "[Demonstration] are categorical syllogisms in mood Barbara with extra pieces clamped on...
     ([Demonstration] 33.1-39.4... quoted in Strobino 2019)" (bagian 6.4).
  8. "a syllogism is things that are arranged in the mind in an order (tartib)..." — [Expressions] 100.3-5
     (bagian 7, definisi silogisme).

### [2026-10-26] druart2024 — Druart, "Al-Farabi" (SEP, entri umum)
- Klaim yang diperiksa: keberadaan entri umum al-Farabi; penulis; tanggal.
- Metode: metadata + judul (teks-penuh tersedia, belum digali per bagian).
- Akses: https://plato.stanford.edu/entries/al-farabi/ — HTTP 200.
- Hasil: TERVERIFIKASI (metadata). Sitasi: Druart, Therese-Anne. "Al-Farabi",
  _The Stanford Encyclopedia of Philosophy_, pertama terbit 15 Jul 2016, revisi substantif 14 Mei 2024.
- Status sitasi isi: METADATA-SAJA (boleh untuk fakta biografis umum dgn hati-hati; klaim logika
  merujuk ke hodges-druart2019).

### [2026-10-26] codd1970 — Codd, "A Relational Model of Data for Large Shared Data Banks" (CACM)
- Klaim yang diperiksa: metadata bibliografis (jurnal, vol, no, hlm, tahun, DOI) + isi teks-penuh
  (predikat kalkulus, normal form, data sublanguage, system catalog).
- Metode: teks-penuh (PDF 11 hlm dari mirror UPenn, dicocokkan dgn metadata Crossref).
- Akses: DOI https://doi.org/10.1145/362384.362685 (Crossref HTTP 200, metadata cocok);
  ACM langsung HTTP 403 (blokir bot, BUKAN bukti tidak ada — terverifikasi via Crossref);
  PDF https://www.seas.upenn.edu/~zives/03f/cis550/codd.pdf — HTTP 200 application/pdf.
- Hasil: TERVERIFIKASI teks-penuh.
- Sitasi resmi: Codd, E. F. "A Relational Model of Data for Large Shared Data Banks",
  _Communications of the ACM_ 13(6): 377-387, Juni 1970. DOI 10.1145/362384.362685.
- Verifikasi internal PDF: "Volume 13 / Number 6 / June, 1970", footer "Communications of the ACM 377",
  afiliasi "IBM Research Laboratory, San Jose, California" — semua cocok dgn Crossref.
- Kutipan kunci:
  1. "The adoption of a relational model of data... permits the development of a universal data
     sublanguage based on an applied predicate calculus." (hlm. 381, bag. 1.5).
  2. "Declared relations are added to the system catalog..." (hlm. 381).
  3. "the class of qualification expressions... must have the descriptive power of the class of
     well-formed formulas of an applied predicate calculus." (hlm. 381).

### [2026-10-26] algeriani-mohadi2017 — Algeriani & Mohadi, House of Wisdom (MJSS)
- Klaim yang diperiksa: isi artikel (manajemen, pengatalogan Bayt al-Hikmah); metadata jurnal.
- Metode: teks-penuh (PDF 9 hlm, open access CC BY-NC-ND).
- Akses: https://www.richtmann.org/journal/index.php/mjss/article/download/10072/9704 — HTTP 200
  application/pdf; DOI 10.1515/mjss-2017-0036 terkonfirmasi di halaman OJS + meta citation.
- Hasil: TERVERIFIKASI teks-penuh.
- Sitasi: Algeriani, Adel Abdul-Aziz & Mohadi, Mawloud. "The House of Wisdom (Bayt al-Hikmah) and
  Its Civilizational Impact on Islamic libraries: A Historical Perspective",
  _Mediterranean Journal of Social Sciences_ 8(5): 179-187, September 2017. DOI 10.1515/mjss-2017-0036.
- Kutipan kunci: "the house of wisdom has had a very organized management system especially in
  collecting and book cataloguing" (abstrak).
- CATATAN KEHATI-HATIAN: artikel sekunder tingkat survei; untuk klaim historis kuat (tanggal pendirian,
  angka koleksi) WAJIB silang dgn Gutas1998 / Pedersen1984 / Fihrist bila tersedia teks-penuh. Selama
  belum ada, angka-angka spesifik TIDAK dikutip.

### [2026-10-26] gutas1998 — Gutas, Greek Thought, Arabic Culture (Routledge)
- Klaim yang diperiksa: keberadaan buku; penerbit; tahun; edisi.
- Metode: metadata (penerbit 200, Crossref DOI 10.4324/9780203316274, Open Library, metadata archive.org
  cocok: judul/pengarang/tahun/penerbit).
- Akses: Routledge HTTP 200; archive.org item greekthoughtarab0000guta_v3l3 (metadata cocok) tetapi
  akses pinjam-terbatas (access-restricted: true, teks djvu tidak dapat diunduh).
- Hasil: TERVERIFIKASI metadata; TEKS-PENUH BELUM.
- Status: BOLEH disitasi untuk keberadaan/konteks umum gerakan penerjemahan; TIDAK BOLEH untuk
  kutipan halaman spesifik sampai teks-penuh diperoleh legal.

### [2026-10-26] zimmermann1981 — Zimmermann (ed./trans.), Al-Farabi's Commentary and Short Treatise
  on Aristotle's De Interpretatione (Oxford UP / British Academy)
- Klaim yang diperiksa: keberadaan; penerbit; tahun.
- Metode: metadata (Crossref DOI 10.2307/602239 + resensi CUP 10.1017/s0020743800029111 konsisten:
  London, British Academy by Oxford UP, 1981, 287 hlm).
- Hasil: TERVERIFIKASI metadata; TEKS-PENUH BELUM.
- Status: sumber primer-sekunder kunci; perlu akses perpustakaan untuk kutipan langsung.

### [2026-10-26] chatti2019 — Chatti, Arabic Logic from al-Farabi to Averroes (Birkhauser/Springer)
- Klaim yang diperiksa: keberadaan; penerbit; tahun.
- Metode: metadata (Crossref DOI 10.1007/978-3-030-27466-5, Springer 2019 — cocok dgn daftar pustaka SEP).
- Hasil: TERVERIFIKASI metadata; TEKS-PENUH BELUM.

### [2026-10-26] black1990 — Black, Logic and Aristotle's Rhetoric and Poetics in Medieval Arabic
  Philosophy (Brill)
- Klaim yang diperiksa: keberadaan; penerbit; tahun.
- Metode: metadata (Crossref DOI 10.1163/9789004452398, Brill 1990; Open Library cocok).
- Hasil: TERVERIFIKASI metadata; TEKS-PENUH BELUM.

### [2026-10-26] pedersen1984 — Pedersen, The Arabic Book (Princeton UP)
- Klaim yang diperiksa: keberadaan; penerbit; tahun; penerjemah/editor.
- Metode: metadata (Crossref DOI 10.1515/9781400856374, Princeton UP; resensi CUP konsisten:
  trans. Geoffrey French, ed. Robert Hillenbrand, 1984; edisi asli Denmark 1946).
- Hasil: TERVERIFIKASI metadata; TEKS-PENUH BELUM.

### [2026-10-26] dge2009 — MuslimPhilosophy.com, halaman al-Farabi (situs dokumentasi)
- Klaim yang diperiksa: daftar karya al-Farabi yg tersedia (teks Arab Ihsa al-Ulum ed. Bumelham, dsb.).
- Metode: sebagian (halaman terunduh, diverifikasi memuat "Kitab 'Ihsa' al-Uloom (Categories of Science)
  Ed. Bumelham Arabic PDF format" + karya logika lain).
- Akses: http://www.muslimphilosophy.com/farabi — HTTP 200.
- Hasil: SEBAGIAN (direktori karya, bukan sumber primer itu sendiri).
- Status: petunjuk akses teks Arab; BUKAN otoritas sitasi akademik. Setiap file PDF yg dipakai harus
  diverifikasi terpisah (edisi, editor, kelengkapan).

### GAGAL / DITOLAK
- Britannica "Bayt al-Hikmah" — HTTP 403 (Cloudflare, blokir bot). BUKAN bukti tidak ada; tidak dipakai.
- Encyclopaedia Iranica "Farabi ii. Logic" (Black) — HTTP 403 (blokir). Tidak dipakai sampai akses legal.
- IEP (iep.utm.edu) slug farabi / farab-soc / farabi-arabic-philosophy — HTTP 404 semua. Tidak dipakai.
- Michigan mirror Codd (web.eecs.umich.edu) — HTTP 000 (host mati). Diganti mirror UPenn (200).
- Open Library API sesekali gagal (rate limit) — diulang hingga dapat, tidak disimpulkan apa-apa darinya.

### [2026-10-26] smith2022 — Smith, "Aristotle's Logic" (SEP)
- Klaim yang diperiksa: keberadaan entri; tanggal publikasi/revisi; definisi deduksi
  (Prior Analytics I.2, 24b18-20) untuk pengantar doktrin silogisme.
- Metode: teks-penuh (HTML entri diunduh, diperiksa per bagian).
- Akses: https://plato.stanford.edu/entries/aristotle-logic/ — HTTP 200.
- Hasil: TERVERIFIKASI teks-penuh.
- Sitasi resmi: Smith, Robin. "Aristotle's Logic",
  _The Stanford Encyclopedia of Philosophy_, pertama terbit 18 Mar 2000,
  revisi substantif 22 Nov 2022 (tertera di halaman entri).
- Kutipan kunci: "A deduction is speech (logos) in which, certain things having been
  supposed, something different from those supposed results of necessity because of
  their being so. (Prior Analytics I.2, 24b18-20)" (bagian 3, "The Subject of Logic").

### [2026-10-26] gutas2025 — Gutas, "Ibn Sina [Avicenna]" (SEP)
- Klaim yang diperiksa: keberadaan entri; tanggal; klasifikasi korpus logika
  (Eisagoge, Categories, De interpretatione, Syllogism/Prior Analytics,
  Demonstration/Posterior Analytics, Dialectic, Sophistics, Rhetoric, Poetics).
- Metode: teks-penuh (HTML entri diunduh, diperiksa bagian klasifikasi ilmu).
- Akses: https://plato.stanford.edu/entries/ibn-sina/ — HTTP 200.
- Hasil: TERVERIFIKASI teks-penuh.
- Sitasi resmi: Gutas, Dimitri. "Ibn Sina [Avicenna]",
  _The Stanford Encyclopedia of Philosophy_, pertama terbit 15 Sep 2016,
  revisi substantif 31 Okt 2025 (tertera di halaman entri).
- Status: dipakai untuk kesinambungan kurikulum logika pasca-al-Farabi;
  klaim spesifik logika Farabi tetap merujuk ke hodges-druart2019.

### [2026-10-26] adriaans2023 — Adriaans, "Information" (SEP)
- Klaim yang diperiksa: keberadaan entri; tanggal; kedudukan filsafat informasi
  dan informasi semantik (Floridi) sebagai sub-disiplin filsafat.
- Metode: teks-penuh (HTML entri diunduh, diperiksa per bagian).
- Akses: https://plato.stanford.edu/entries/information/ — HTTP 200.
- Hasil: TERVERIFIKASI teks-penuh.
- Sitasi resmi: Adriaans, Pieter. "Information",
  _The Stanford Encyclopedia of Philosophy_, pertama terbit 26 Okt 2012,
  revisi substantif 1 Nov 2023 (tertera di halaman entri).

### [2026-10-26] dipasquale2019 — DiPasquale, Alfarabi's Book of Dialectic (CUP)
- Klaim yang diperiksa: keberadaan; penerbit; tahun; judul.
- Metode: metadata (Crossref DOI 10.1017/9781108277822 HTTP 200;
  judul "Alfarabi's Book of Dialectic (Kitab al-Jadal)", Cambridge University Press,
  terbit 31 Okt 2019 — cocok dengan sitasi SEP).
- Akses: https://doi.org/10.1017/9781108277822 — HTTP 200.
- Hasil: TERVERIFIKASI metadata; TEKS-PENUH BELUM.
- Status: dirujuk sebagai literatur sekunder dialektika Farabi; tanpa kutipan halaman.

### [2026-10-26] mahdi1969 — Mahdi (ed./trans.), Alfarabi's Philosophy of Plato and Aristotle
- Klaim yang diperiksa: keberadaan; penerbit; tahun; isi (terjemahan tiga karya).
- Metode: metadata (Open Library work OL10704602W: "Alfarabi's philosophy of Plato
  and Aristotle", Cornell paperbacks, 1969, "translated, with an introduction";
  resensi JSTOR konsisten).
- Hasil: TERVERIFIKASI metadata; TEKS-PENUH BELUM.
- Status: dirujuk untuk ketersediaan terjemahan Inggris (Attainment of Happiness,
  Philosophy of Plato, Philosophy of Aristotle); tanpa kutipan halaman.

### [2026-10-26] mackensen1932 — Mackensen, "Four Great Libraries of Medieval Baghdad"
- Klaim yang diperiksa: keberadaan; jurnal; volume/nomor; tahun; DOI.
- Metode: metadata (Crossref DOI 10.1086/613127: University of Chicago Press,
  _The Library Quarterly_ 2(3), Juli 1932, judul cocok).
- Akses: DOI landing HTTP 403 (blokir bot penerbit, BUKAN bukti tidak ada —
  diverifikasi via Crossref seperti kasus Codd/ACM).
- Hasil: TERVERIFIKASI metadata; TEKS-PENUH BELUM.
- Status: dipakai sebagai penopang historiografis awal (adanya kajian empat
  perpustakaan Baghdad abad pertengahan); tanpa kutipan halaman.

### [2026-10-26] manning2008 — Manning, Raghavan & Schutze, Introduction to Information Retrieval
- Klaim yang diperiksa: keberadaan; penerbit; tahun; DOI.
- Metode: metadata (Crossref DOI 10.1017/CBO9780511809071 HTTP 200:
  "Introduction to Information Retrieval", Cambridge University Press, 2008).
- Akses: https://doi.org/10.1017/CBO9780511809071 — HTTP 200.
  Mirror PDF nlp.stanford.edu tidak terjangkau dari host ini (HTTP 000, masalah
  jaringan lokal — tidak disimpulkan apa-apa); edisi HTML terbuka tidak diverifikasi
  penuh sehingga TIDAK diklaim sebagai teks-penuh.
- Hasil: TERVERIFIKASI metadata; TEKS-PENUH BELUM.
- Status: dirujuk sebagai buku teks standar temu kembali informasi; klaim teknis
  IR yang dikutip merujuk ke Codd1970 (teks-penuh) dan Adriaans2023.

### [2026-10-26] Berkas PDF legal yang diarsipkan
- kutipan/artikel_jurnal/codd1970-relational-model.pdf — 11 hlm, terverifikasi
  pymupdf (hal. 1: "A Relational Model of Data for Large Shared Data Banks",
  E. F. Codd). Lisensi: salinan penulis/mirror institusional publik.
- kutipan/artikel_jurnal/algeriani-mohadi2017-house-of-wisdom.pdf — 9 hlm,
  terverifikasi pymupdf (MJSS Vol 8 No 5, September 2017). Lisensi: CC BY-NC-ND
  (open access, tercantum di halaman OJS).
- Font: Times New Roman tidak tersedia di host ini; kompilasi memakai
  TeX Gyre Termes (klon metrik Times) via fontspec — dinyatakan di naskah/README.md,
  bukan diklaim sebagai Times New Roman asli.

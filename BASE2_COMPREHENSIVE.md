# Comprehensive Operations Manual — Base 2
> Sumber: `base2.pdf`
> Dokumen ini mencakup seluruh departemen operasional secara lebih lengkap & formal.
> Referensi silang: `LEGAL_FIDUSIA_DETAIL.md`, `ARCHIVE_MANAGEMENT_DETAIL.md`, `CRM_CS_DETAIL.md`

---

## Daftar Isi
1. [Customer Care](#customer-care)
2. [Operation Area (OA)](#operation-area)
3. [Operation Support & Development (OSD)](#osd)
4. [CS Digital (CSD)](#cs-digital)
5. [Legal Admin](#legal-admin)
6. [Admin Fidusia](#admin-fidusia)
7. [Resume AHU](#resume-ahu)
8. [Operation Quality Assurance (OQA)](#oqa)
9. [BPKB Admin](#bpkb-admin)
10. [Document Support (Doc Support)](#document-support)
11. [Asuransi](#asuransi)

---

## 1. Customer Care {#customer-care}

### Profil Departemen
- **Fungsi:** Menangani keluhan konsumen yang dieskalasikan ke KP
- **Kategori Priority:** Keluhan dari media massa · Keluhan dari layanan OJK
- **Kategori Handling:** Aspek hukum (KPK, MA, KY, kuasa hukum) · Perbaikan kolektibilitas SLIK OJK/lelang
- **SLA:** 10 hari kerja (POJK 22/2023) · **9 hari kerja (KPI CC)**
- **Catatan:** Pengaduan langsung dari konsumen (bukan APPK OJK & bukan perbaikan kolektibilitas) → ditangani PIC cabang

### Alur Proses Penanganan Pengaduan Konsumen

**Pembagian Kategori Penanganan:**

| Kategori | Penangan |
|---|---|
| Priority (media massa / OJK) | PIC Priority (Kak Mora) |
| Perbaikan Collect (kendaraan lelang) | PIC Perbaikan Collect (Kak Deva) |
| Kuasa Hukum | PIC Perbaikan Collect (Kak Deva) |
| APPK OJK | PIC Priority Handling |
| Motor | PIC Motor (Kak Fajar) |

---

### PIC 1 — Admin (Kak Rema)

**a. Perbaikan Collect:**

| Kondisi | Dokumen |
|---|---|
| Konsumen baru pengajuan (status Close ET/Close WO) | Form Register, Form IDEP/SLIK, Surat Permohonan, Salinan KTP |
| Banding (sudah pernah mengajukan) | + Surat Kesanggupan Bayar; nominal harus menutup baki debet (hutang ke BCA & BCAF) |

- Cut off registrasi: **jam 15.00** (setelah jam 15.00 → register hari berikutnya)
- Setelah register → email ke Credit Settlement (info hasil lelang) + email ke Accounting (info biaya tarik)

**b. Monitoring Kehilangan BPKB:**
- Hanya area **JABODETABEK**
- Cek nopol di PCC → jika released → tidak diproses
- Jika tidak ditemukan di PCC → tidak diproses
- Jika ditemukan & bukan released → koordinasi BPKB Admin → blokir → hubungi konsumen/emergency contact
- Jika tidak bisa dihubungi 1–2 hari → koordinasi ASR untuk kunjungan langsung

**c. Monitoring Media:**

| Sumber | Yang Dimonitor KP | Output |
|---|---|---|
| Media Online | Kompas.com · Detik.com · Okezone · Bisnis.com · MediaKonsumen.com · OJK | Memo perihal penanganan pemberitaan |
| Media Koran | Kompas · Warta Kota · Pos Kota · Media Indonesia | Klipping |
| Selain di atas | Dimonitor cabang | — |

---

### PIC 2 — Perbaikan Collect (Kak Deva)

Konsumen dengan kendaraan ditarik/diserahkan ke BCAF untuk dilelang namun hasil lelang belum menutup kewajiban.

**Alur Perbaikan Collect — Kendaraan Lelang (Permohonan Pertama):**
1. PIC terima dari admin → input di PCC (hari yang sama)
2. Input kronologi, data konsumen, penanganan
3. Koordinasi Unit Terkait:
   - Credit Settlement → rincian hasil lelang, Risalah Lelang, SPHL
   - Accounting → biaya tarik
   - Isi Jotform ASR → kelengkapan dokumen penarikan kendaraan
   - Email FSM → rincian sisa kewajiban pasca lelang → FSM input di aplikasi **WOSS**
4. Cek kelengkapan dokumen (KTP salinan, surat kuasa jika diwakilkan)
5. Konfirmasi pengaduan ke pelapor (hari H) → infokan alur, SLA, kronologis
6. Koordinasi unit terkait: ASR (SP, SPT, BAST, Kronologis), Asuransi, Operation
7. Pembuatan Memo Perbaikan Kolektibilitas

**Besaran Waive:**
| Jenis Pengajuan | Denda | Bunga Berjalan |
|---|---|---|
| Pertama | 50% | 100% |
| Banding | Disesuaikan identitas (konsumen ternama → lebih kecil; biasa → mulai 80% ke atas, sesuai approval BOD) | — |

**Memo dibuat dan disetujui:** UH CC, Dept Head DCRM, Dept Head FSM, 3 BOD → kirim ke cabang → cabang buat ST (TTD BOH & BASH/BM) → kirim ke konsumen

**Pembuatan Surat Tanggapan (ST):**
- Cabang → apabila pengajuan pertama kali di cabang
- KP (CC) → apabila pengajuan dari KP

**Tanggapan Konsumen:**
- Setuju → konsumen bayar → lampirkan ke CS: Bukti Bayar + Surat Pernyataan Penyelesaian + Surat Itikad Baik (khusus hapus tagih)
- Output: **Surat Keterangan Tidak Ada Kewajiban**
- Bukti bayar dikirim ke FSM (pengkinian SLIK ke BCA) + ke Accounting (pengkinian SLIK BCAF)

**Kondisi Banding (Dokumen Tambahan):**
- SP, SPT, SPHL, BAST, SK Fidusia, SPPI
- Surat Pernyataan Kesanggupan Bayar
- Draft ST → Legal → TL, UH, DH DCRM & FSM

**Kondisi Khusus:**
- Pelunasan Sebagian/Remedial (konsumen WO): ada SKL / tidak ada SKL (masuk bucket CC → hitung sisa pokok)
- Gagal Klaim: tambahkan pengecekan Claim Car di awal

> **PENTING:** Jika dalam 90 hari kerja nominal tidak dibayar → hari ke-91 harus buat **MEMO PERPANJANGAN**

---

### PIC 3 — Priority Handling / APPK OJK & Media Massa (Kak Mora)

**APPK OJK (Aplikasi Portal Pelindungan Konsumen)**

Alur 13 langkah:
1. Terima pengaduan → input PCC
2. Cek kelengkapan dokumen (KTP, kronologis, PPK, Surat Pernyataan tidak dalam proses pengadilan/arbitrase)
3. Isi Form Pengaduan Konsumen
4. Konfirmasi pengaduan ke pelapor
5. Koordinasi unit terkait
6. Analisa & Investigasi
7. Drafting Surat Tanggapan
8. Review Legal
9. Review TL & UH
10. TTD Pejabat (BOD + DH CRM + DH Unit Terkait)
11. Kirim fisik Surat Tanggapan ke pelapor
12. Upload softcopy ke APPK OJK
13. Close penanganan di PCC

**Respons OJK setelah upload surat tanggapan (10 HK untuk pelapor membalas):**
1. Menerima penyelesaian → closed
2. Keberatan → BCAF wajib tindaklanjuti kembali (SLA 10 HK)
3. Menolak → closed
4. Menolak + teruskan ke LAPS → mediasi (via Zoom, dihadiri PIC CS, UH CS, Legal, unit terkait, BOH cabang)

> Jika 10 HK tidak ada tanggapan pelapor → auto-closed by system

**Media Massa (Media Sosial, Media Online, Media Cetak):**
1. Terima pengaduan → cek data pembiayaan → isi Form Pengaduan Konsumen
2. Konfirmasi → koordinasi unit terkait → analisa & investigasi
3. Buat Memo Penanganan Media (rekomendasi: Hak Jawab / Surat Tanggapan)
4. Jika Hak Jawab: minta persetujuan DH CRM & DD Nat. Opr. → kirim ke media → maintain hingga terposting
5. Jika Surat Tanggapan: drafting → review Legal → review TL & UH → TTD pejabat → kirim fisik ke konsumen

---

### PIC 4 — Perlindungan Konsumen (Kak Adam)
Dasar hukum: POJK 22/2023 · SK 047/2025

**7 Prinsip Pelindungan Konsumen:**
1. Edukasi yang memadai
2. Keterbukaan dan transparansi informasi produk/layanan
3. Perlakuan yang adil dan perilaku bisnis yang bertanggung jawab
4. Pelindungan aset, privasi, dan data konsumen
5. Penanganan pengaduan dan penyelesaian sengketa yang efektif & efisien
6. Penegakan kepatuhan
7. Persaingan yang sehat

**8 Tugas:**
1. Sosialisasi ke karyawan (blast email, SocNet, FLA)
2. Koordinasi perencanaan & pelaksanaan kepatuhan BCAF terhadap ketentuan OJK
3. Koordinasi dengan unit terkait untuk pemantauan & evaluasi
4. Laporan ke Direksi mengenai implementasi pelindungan konsumen
5. Koordinasi penyusunan laporan (Self Assessment tiap semester → OJK setiap 30 September)
6. Menerima, menangani, dan menyelesaikan pengaduan konsumen
7. Menyusun materi untuk laporan tahunan/website/media
8. Menjadi penghubung antara konsumen, OJK, LAPS, dan BCAF

---

### PIC 5 — Motor (Kak Fajar)
- Menangani semua keluhan konsumen motor (kecuali monitoring kehilangan BPKB)
- **SLA:** 10 hari kerja
- Alur kurang lebih sama dengan handling mobil
- **Perbedaan motor:**
  - FSM tidak input di WOSS → permintaan & penerimaan data via email
  - Tidak ada besaran WAIVE denda yang mengikat → didasarkan pada kondisi sudah menutup baki debet

---

## 2. Operation Area (OA) {#operation-area}

Departemen perantara cabang dan kantor pusat.

**Pembagian Area:**
- OA Area 1: Dept Head Pak Billy
- OA Area 2: Dept Head Pak Yudi
- OA Area 3: Dept Head Bu Puji Astutik

### Admin OA

**Monitoring email/memo dari cabang:**

| Jenis Memo | Keterangan |
|---|---|
| **BBNNK** (BPKB Balik Nama Non Konsumen) | Usia >21 th: persetujuan DD; <21 th: naik ke BOD |
| **PPDJ** (Permohonan Pengambilan Dokumen Jaminan) | Regular, WO (SKL→DD, Non SKL→DH OA), ahli waris, dikuasakan ke LN, VidCall |
| **Permohonan Update Konsumen** | Approval update data → DH OA → FSM; approval maintenance data jaminan → DD → cabang (DRONE) |
| **Revisi BPKB** | Approval DD; revisi sumbu/bagian kendaraan; kirim ke BPKB Admin |

**Flow Memo:**
1. Delivery memo ke area multitasking
2. Area multitasking analisa memo
3. Jika ada revisi → dikembalikan ke cabang
4. Jika sesuai → naik ke approval DH & DD

---

### Area Spesialis (OA 2)

1. **BORC** (Branch Operational Risk & Control) — pengecekan proses operasional cabang kelas D
2. **KPI Cabang** (tahunan) — target PM dari OSD, nilai audit; OA olah data sebelum cabang input di HRIS
3. **KOAR** (bulanan) — meeting transfer knowledge dengan cabang
4. **Over Kredit** — konsumen lama ke konsumen baru; cek SLIK konsumen baru, analisa BOH

**Kunjungan ke Cabang (BORC):**
- H1–H4: Sampling BPKB & Cover Note, SO Petty Cash (Reguler, Service, BDC), minta dokumen tiap unit kerja
- H5: Draft hasil pemeriksaan sementara → diskusi dengan BOH → SARAN dan DROP
- Cek CCTV semua bagian operasional → tambahkan ke draft
- Draft final → email ke cabang untuk tanggapan (SLA 5 hari kerja)
- Susun Laporan Hasil Kunjungan + tanggapan cabang → Approval DH + DD
- Dokumen final → email ke cabang → minta bukti perbaikan & laporan tindak lanjut (SLA 1 bulan)

---

### Area Multitasking

- Pergantian MPP cabang (CS, AMB, AMAF) selama 1–6 bulan menunggu rekrutmen HR

**Analisa Memo Waive Denda (SLA 2 jam dari approval DH → DD):**

| Besaran Waive | Kewenangan Approval |
|---|---|
| >Rp 5 juta, maks 50% denda | DD Operation |
| >Rp 1 juta – <Rp 5 juta, maks 30% denda | DH |
| <Rp 1 juta, maks 20% denda | UH atau BOH |

> Waive denda 100%: **wajib Strong Rekomendasi dari BCA**

**Alur Pengajuan Waive:**
1. Cabang ajukan via JOGET
2. Approval sesuai kewenangan
3. Final approve → OS teruskan ke CS → CS informasikan ke konsumen

**Pengecekan BASO & BAST:**
- **BASO** (Berita Acara Stock Opname): 1 tahun 2 kali, juga saat ada pergantian AMAB/AMAF
  - SO Fisik: tembak barcode BPKB
  - SO Detail: cek isi BPKB
- **BAST Jabatan:** saat ada mutasi pejabat

---

## 3. Operation Support & Development (OSD) {#osd}

**Fungsi:** Monitoring performance cabang dengan 3 indikator:

1. **People** — Tes PPK (Product Process Knowledge) setiap 6 bulan; jika tidak memenuhi → berpengaruh ke KPI individu
2. **Process** — Pengembangan sistem kerja operation KP & cabang; bisa visit ke cabang; Pemekaran/penurunan kelas cabang direview 1×/tahun; Implementasi IOM ke cabang + sosialisasi
3. **Performance Management**

**Sumber Data Pembuatan Memo:**
- Pengajuan atas ke bawah / bawah ke atas
- Temuan audit
- Target penilaian performance management (survei konsumen, realisasi capaian, temuan cabang)

**Struktur Memo OSD:**
1. Nomor memo
2. Unit yang ditujukan + CC tembusan
3. Unit pembuat memo
4. Perihal/judul
5. Latar belakang
6. Referensi memo terkait
7. (Sesuai kebutuhan)
8. Flow pelaksanaan
9. Approval: DD Operation → Dept Head OSD → Direktur
10. Lampiran

**Penilaian Performance Management:**

| Skala | Nilai |
|---|---|
| A | >90 |
| B | 80–90 |
| C | 70–80 |
| D | <70 |

**Indikator:**
1. Optimized service level & quality (waktu layanan)
2. Enhance control & quality assurance (report)
3. Increase employee competency (tes)
4. Customer satisfaction (CSI)
5. Cleaning day
6. Transformasi digital

---

## 4. CS Digital (CSD) {#cs-digital}

Melayani permohonan/permintaan konsumen dari digital. Sumber: Website, AVA, Email, FINA, ASTARI.

### 1. Kontak Website (Kak Septi)
- Sumber: Website BCAF & email customercarebcaf@bcaf.id
- Data ditarik TL/UH: **Batch 1 jam 09.00** · **Batch 2 jam 12.00–13.00**

**Case yang Ditangani:**
1. Pengambilan BPKB (hanya konsumen reguler via telepon/email)
2. Informasi tunggakan konsumen
3. Pengembalian uang tanda jadi
4. Pengajuan kredit (tidak perlu konfirmasi, langsung forward ke unit terkait)
5. Pengembalian dana double (syarat: bukti bayar; proses 5–6 hari)
6. ET (batas pembayaran jam 12.00)
7. Perpanjangan STNK — membuat SKPS sebagai surat pengantar ke SAMSAT
8. Pengambilan BPKB Badan Usaha dikuasakan (konfirmasi by telepon + email; order manual reservasi setelah dokumen dilengkapi)
9. Pengkinian Data (approval UH; konsumen kirimkan: copy KTP, form pengkinian data, data lama, foto konsumen)

**Verifikasi Konsumen saat Telepon:**
- Nama debitur · Informasi kendaraan · Tanggal jatuh tempo · Besaran angsuran · Data diri · Nama ibu kandung · Alamat KTP

---

### 2. AVA (Astari Virtual Assistant)
**Sumber:** ZOOM · Website · VINA · Cabang · S2P

**Aplikasi:**
- Financore / One View · Aplikasi Gabungan · DMS · Dolphin (email) · Aplikasi Reservasi BPKB · CMS · CRM Halo Life

**Layanan Utama:**
1. **Pelunasan Dipercepat** — Konfirmasi Financore → konsumen tunjukkan KTP → hitung ET di Aplikasi Gabungan → create VA → bukti TF dikirim ke email customercare → ambil BPKB H+1
2. **Reservasi BPKB** — Area: JABODETABEK (WPI, WTC, Tangerang, Bogor, Depok, Bekasi, Season City, Kelapa Gading) + luar JABODETABEK

**Syarat Reservasi:**
- Individu: via ASTARI/VINA/BCA vidcall
- TANPA pengambilan reservasi di WPI (form konfirmasi tetap dilengkapi): nasabah >60 tahun, konsumen prioritas, konsumen titipan cabang/pejabat
- Showroom rekanan: tunjukkan kartu identitas
- PT: wajib email dengan berkas (jenis kendaraan, nopol, no kontrak, data pengurus, NIB, SIUP dll)

---

### 3. Email (Kak Jefri)
- 4 PIC email; tiap PIC maks 40 bucket; pembagian bergantung availability
- Aplikasi: **3Dolphins** — bot AI auto-reply untuk mengisi data diri; alur: Assign → Open → Pending → Close
- **Makro:** template email pertanyaan umum
- **Tag:** pengelompokan kategori untuk identifikasi masalah yang sering muncul

**Case Terbanyak:**
1. Reservasi BPKB (individu → arahkan ke FINA/AVA; BU → tangani, rekap ke PIC Order BPKB Jabodetabek: Kak Tia / Non-Jabodetabek: Kak Demi)
2. Informasi Produk BCAF (angsuran, pengajuan kredit, pelunasan dll)
3. Pengaduan
4. Permintaan SKPS

**SLA Email:**
- Masuk sebelum jam 16.00 → close hari yang sama
- Masuk setelah jam 16.00 → close H+1

---

### 4. FINA & Reservasi BPKB Manual (Kak Tia)

**FINA:**
- Reply atas review konsumen di aplikasi FINA
- Telepon atas kendala konsumen (jika nama ada di Financore dan hanya 1)
- Register hasil reply → kirim rekap ke MIKOM FINA tiap awal minggu

**Order Manual BPKB:**
- Konsumen PT
- Konsumen blacklist (melewati batas waktu reservasi)
- Konsumen status borrow multiguna
- Dokumen ke Docust: order borrow BPKB · order Jabodetabek · order WPI

---

## 5. Legal Admin {#legal-admin}

5 Bagian Legal Admin:

### 1. Reprint (H+1 pasca realisasi)
- Menerima dossier asli & copy dari cabang
- Cek kelengkapan dokumen
- Cap hari, tanggal & print data kendaraan di Ikhtisar:

| Data yang Diprint | Sumber |
|---|---|
| Warna kendaraan, No BPKB, No Rangka, No Mesin | Aplikasi Approva & Financore |

**Bagian dalam Ikhtisar yang di-cap:**
- PK bagian depan · Pasal-pasal · SKPB (opsional) · SP Reply

**Isi Dossier Asli:**
1. PK · Pasal-pasal · Ikhtisar · Lampiran (perjanjian) · Tabel angsuran · Riplay personal · SKPB · SP Reply · BAST (mobil bekas) · SK Fidusia

**Isi Dossier Copy:** Di luar dossier asli (PO, kwitansi dll)

**Isi Dossier BU:** Tambahkan SP Direksi (wajib) · SP Komisaris · Form Final (wajib)

**Output Reprint:** Rekapan dokumen dikirim ke Checker untuk cek kembali

---

### 2. Checker
- Aplikasi: One View · Resume · DMS
- Cek data konsumen & kendaraan di DMS (KTP & CN/BPKB)
- Data tidak sesuai → tembak sistem via **DRONE**
- Register maintenance untuk data salah/tidak sesuai → kirim ke tim Resume
- Register juga dikirim ke tim Renvoi untuk revisi penulisan dokumen
- PT: gunakan aplikasi Resume untuk cek data pengurus, NIB dll

---

### 3. Tera Materai
- Proses pembubuhan materai pada kontrak:
  - Ikhtisar halaman 3
  - SK Fidusia
- Opsional (jika belum ada materai): SKPR dan F04 (surat pernyataan dealer)

---

### 4. Renvoi
- Terima data dari admin (list registeran maintenance)
- Pengetikan ulang (revisi) sesuai list → beri keterangan "dibenarkan"
- Kirim kembali ke Legal Admin → cek apakah ada yang terlewat
- Legal Admin kirim ke Tera untuk pembubuhan materai

---

### 5. Scan
**Urutan Scan Dossier Asli:**
1. PK halaman depan
2. Pasal PPK
3. Ikhtisar
4. Lampiran
5. Tabel angsuran
6. Riplay personal

- Hasil scan upload ke DMS oleh tim Archive
- Dossier Copy di-scan oleh cabang

---

## 6. Admin Fidusia {#admin-fidusia}

> Lihat juga: **`LEGAL_FIDUSIA_DETAIL.md`** untuk detail lengkap

### PIC 1 — Prepare/Order

**JABODETABEK:**
- Konsumen B2B (perorangan) → SK Fidusia dicek H+4 setelah realisasi (data konsumen, pasangan, kendaraan dicocokkan di One Me, One View & DMS) → H+5 terorder sertifikat ke notaris rekanan via B2B
- Konsumen Non-B2B (PT, Yayasan, CV) → pengecekan sama → order manual di aplikasi Fidusia (search by tgl realisasi + notaris → klik order)

**Dokumen Fisik Non-B2B ke Notaris (via messenger):**
FC PPK · SK Fidusia (asli) · NIB · Akta · KTP komisaris & direksi · NPWP perusahaan · SK Domisili · SIUP · SIB · CN/BPKB

**Non-JABODETABEK:**
- Cabang scan dokumen → email ke KP; dokumen fisik dikirim ke KP
- Proses order B2B & Non-B2B sama dengan Jabodetabek
- Setelah order → tarik Bukti Tanda Terima di aplikasi Fidusia → TTD Legal Admin sebagai Authorized

---

### PIC 2 — Adendum (Mas Adam)

2 jenis adendum: **BBN** (Balik Nama) · **UBJ** (Ubah Jaminan)

**Dokumen Perorangan:**
Form Addendum · PPK · Sertifikat Fidusia · SK Fidusia Asli · SKPB · SP Bersama (Dealer) · Permohonan Balik Nama BPKB · PBNB (BBN) · IOM (UBJ) · Surat Pernyataan Konsumen · KTP & KK Konsumen · KTP & KK a.n. BPKB Baru · STNK · BPKB/Cover Note · FC Blanko Kwitansi a.n. BPKB Baru

**Dokumen PT:** KTP Pengurus · NPWP · NIB · Akta Perusahaan · SK Menkumham

**Flow BBN Non-Jabodetabek:** Terima berkas dari cabang/sekretariat → bongkar dokumen → susun → registrasi di excel → TTD signer (Mba Latifah) → order ke notaris

**Flow BBN Jabodetabek:** Setelah TTD signer → tera materai (adendum, SK Fidusia, SP Bersama) → insertion (serah terima ke Archive)

---

### PIC 3 — Sertifikat Fidusia

**Ketentuan OJK:**
- Wajib didaftarkan dalam **30 hari**
- Jika melebihi → wajib dilengkapi SP Notaris

**Alur via Aplikasi B2B:**
- Notaris kirim sertifikat via sistem → verifikasi data → approve/reject
- Jika belum sesuai → reject + notes → dikembalikan ke notaris

**Alur Manual (Aplikasi Fidusia):**
- Input nama notaris, order date, receive date, nomor & tanggal sertifikat, nomor invoice

**Satu Set Dokumen Serah Terima:**
Salinan akta · Minuta (untuk notaris individu) · Invoice · Sertifikat fisik (untuk BU)

**Perbedaan Sertifikat Fidusia:**

| | Sebelum Perubahan | Setelah Perubahan |
|---|---|---|
| Nomor sertifikat | 01 | 02 |
| Tulisan | Sertifikat Jaminan Fidusia | Perubahan Jaminan Fidusia |
| Keterangan | — | Apa yang diubah + mengacu nomor sebelumnya |

**Catatan:**
- Pemohon tunggal/pisah harta → tidak semua notaris mau proses; wajib ada akta pisah harta
- Mobil baru → nama konsumen atau pasangan
- Mobil bekas → nama konsumen; jika ingin mengubah nama → ajukan adendum
- Aging order fidusia: **15 hari**; ketentuan OJK 30 hari

---

### PIC 4 — Fidusia Motor (Mas Robby)

**Aplikasi:** Fast APP · Fast Move · Fast Web Report · Document Imaging

**Alur:**
- Safari → Fast App → Order Management → 2 menu: Report Monitoring Fidusia + Report Penambahan Booking
- Fast Web Report → data yang dikirim ke notaris via email
- Notaris: 4 rekanan (Ario, Leodi, Joniva, Hafidz)
- Cek No Rangka (17 digit) & No Mesin (12 digit)
- Pengiriman data ke notaris → notaris isi No Akta, No Sertifikat, Tanggal Sertifikat
- Random sampling **20%** dari total sertifikat
- Pastikan tidak ada tanda baca `() ; "` → upload manual ke VAS App (format: Kode Cabang - No Kontrak - Fidusia) → upload sertifikat ke Order Management
- Tagihan di-hold dahulu; setiap minggu proceed tagihan di Fast menu tagihan notaris

---

## 7. Resume AHU {#resume-ahu}

> Lihat juga: **`LEGAL_FIDUSIA_DETAIL.md`** untuk detail lengkap

**Alur Umum:** Marketing order Resume → Order Profile AHU → Request akta ke marketing → Cek Dokumen → Approval → Process

### PIC Order (Mas Sandi)
SLA: 1×24 jam

**Aplikasi:** Aplikasi Resume AHU · Ditjen AHU · AHU Fidusia Online

**Alur Beli Voucher:**
1. Buka Ditjen AHU → SIMPADHU → Pemesanan Badan Hukum → isi data BCAF → keluar kode voucher (maks 5/pembelian)
2. Registrasi kode voucher → download tanda terima
3. Kirim ke Finance untuk pembayaran (input di eiger)
4. Cek apakah sudah dibayar via SIMPADHU
5. **Jangka waktu voucher: 60 hari sejak dibayar lunas**
6. Download history voucher → report harian ke Finance

**Alur Order AHU:**
1. Copy nama PT → cek di Ditjen AHU (terdaftar/tidak)
2. Cek di AHU Fidusia (sudah ada fidusia/tidak)
3. Cek pemilik manfaat di Ditjen AHU
4. Cek Inquiry Status Resume (repeat order/tidak)
5. Cek Next Cloud (resume pernah download/tidak)
6. Order AHU jika belum ada atau sudah expired
7. Registrasi di excel (keterangan pending/tidak)
8. Klik Proses → keluar voucher → input data + nomor voucher di Ditjen AHU → muncul resume PDF → download
9. Upload Resume AHU → klik "Process" → masuk ke bagian Request

> **Catatan:** Jika PT menggunakan RAD dari BCA → tidak perlu order AHU, gunakan RAD; action pilih "Internal" di aplikasi resume

---

### PIC Request
- Cek kesesuaian data antara Resume AHU dengan akta perusahaan
- Kelengkapan akta: SK Pengesahan, TTD Notaris di atas materai
- OK → masuk ke Cek Dokumen
- Not OK → keterangan, masuk ke bucket marketing, setelah dilengkapi → Cek Dokumen

---

### PIC Cek Dokumen
- Cek kelengkapan & isi dokumen; lengkapi field yang belum terinput (sudah OCR)

**Dokumen Berdasarkan Klasifikasi Risiko NIB:**

| Risiko | Dokumen |
|---|---|
| Rendah | NIB saja |
| Menengah Rendah | NIB + sertifikat standar |
| Menengah Tinggi | + sertifikasi standar terverifikasi |
| Tinggi | + Izin |

> Kalau hanya NIB biasa → tambahkan Izin Usaha dan Izin Lokasi/SK Domisili

- Badan usaha baru (<2 tahun) → perlu memo penyimpangan
- Approve → masuk ke Process; Pending → marketing lengkapi → kembali ke Cek Dokumen

---

### PIC Approval
- Cek dokumen, pilihan: OK / Not OK
- Not OK → keterangan → kembali ke Cek Dokumen
- Approve → selesai; marketing bisa lihat resume untuk data entry

---

## 8. Operation Quality Assurance (OQA) {#oqa}

Unit yang menjalankan fungsi mitigasi risiko operasional dan kepatuhan prosedur.

**Perbedaan OQA vs Audit:**
- OQA → penilaian atas procedural flow kerja cabang operation
- Audit → pemeriksaan atas risiko dari setiap aspek yang rawan fraud

**Dasar:** IOM No. 001 Tahun 2023 (bobot penilaian checklist operation)

**Cakupan Pemeriksaan:**
1. Data dan dokumen
2. Rekaman CCTV (cabang: 2 bulan; KP: 3 bulan)
3. Tes pemahaman prosedur kerja (PUT — Process Understanding Test)

**Bobot Penilaian Checklist Process:**
1. Pemeriksaan proses kerja
2. Pengerjaan PUT
3. Pemeriksaan CCTV

**Bobot Penilaian Checklist Umum:**
1. Pembuatan insentif
2. Komunikasi
3. Matriks rumah tangga
4. Pengelolaan umum
5. Pemeriksaan CCTV

**Faktor Pengurang:**
- Temuan checklist process sebelumnya yang berulang
- Temuan CCTV sebelumnya yang berulang
- Temuan audit yang berulang

**Flow Kunjungan:**
- Pasif: pemeriksaan data dari cabang diolah di KP
- Onsite: pemeriksaan dengan kunjungan langsung (2×/bulan; 4–5 orang per kunjungan)
1. Pengajuan anggaran tahunan (hotel, pesawat)
2. Koordinasi dengan tim audit agar tidak bentrok jadwal
3. Booking hotel & pesawat mandiri
4. Bagi list cabang ke tim OQA
5. Kunjungan sesuai jadwal

**Output:**
1. Laporan hasil pemeriksaan cabang (dalam 20 hari – 1 bulan)
2. Tindak lanjut dari cabang beserta buktinya
3. Filling dokumen oleh tim OQA

---

## 9. BPKB Admin {#bpkb-admin}

**Fungsi:**
- Pra Realisasi: cek absah dan blokir BPKB (khusus used car)
- Pasca Realisasi: follow up dealer pengurusan CN → BPKB; perpanjangan STNK

**Pembagian:** Used Car · New Car · STNK

---

### 1. Used Car

**Cek Absah & Blokir:**
- **Cek Absah:** memastikan keaslian BPKB dan status BPKB
- **Blokir:** mitigasi agar BPKB tidak dijaminkan ke leasing lain / digandakan

**Dokumen yang Diterima:**
1. BPKB
2. Faktur
3. NIK (Nomor Induk Kendaraan)
4. Form A (kendaraan CBU — terbit dari Bea Cukai)
5. Blanko kwitansi a.n. BPKB (untuk proses balik nama)
6. SP Hak (a.n. PT)

**Flow:**
1. Messenger kirim dokumen BPKB + APP ID (tertulis di amplop)
2. Register/input di **Aplikasi Cek Absah (ACA)**:
   - Masukkan APP ID → cek kesesuaian data kendaraan (sistem vs fisik)
   - Checklist dokumen yang diterima (pilih ASLI); isi kolom faktur dengan nama sesuai faktur
   - Submit → keluar Tanda Terima Set BPKB → TTD PIC BPKB Admin & messenger → print
   - Satukan tanda terima + faktur → simpan
3. BPKB ke TL untuk double check → jika approve → kirim ke Biro Jasa untuk cek absah
4. Scan BPKB untuk upload di DMS
5. BPKB link ke aplikasi FINA (perpanjangan STNK tidak perlu borrow BPKB lagi)

**Sistem E-Blokir (SLA ±1–2 hari):**
1. Buka aplikasi blokir → input nomor rangka → keluar data kendaraan
2. Cek data dengan fisik → save
3. Setelah cek absah → BJ info by WA → kepolisian approve by sistem → TL approve
4. Surat Blokir dapat di-download

**Cabut Blokir:** Minta surat buka blokir dari konsumen → konsumen kirimkan ke Biro Jasa → BJ kasih kepolisian untuk cabut blokir; **biaya Rp 50.000**

**Order Biro Jasa:**
1. Buka ACA → klik Received BPKB Pra Realisasi → pilih semua nama → klik Order → confirm + masukkan nama BJ
2. Output: Tanda Terima Penyerahan Set BPKB + Surat Pengantar Absah + Surat Pengantar Blokir
   - Khusus JABODETABEK: tidak perlu print surat pengantar (menggunakan E-Blokir)

**Biro Jasa rekanan:** DEWIJANTI, ARMANDO

**Area Pengurusan:**
- KP: khusus 8 cabang Jabodetabek
- Cabang: sesuai wilayah yang mengeluarkan BPKB

**Biaya Cek Absah:**
- Luar kota: Rp 500.000 (cek absah + blokir + ongkos BJ)
- KP: Rp 110.000

**Batch Penerimaan BPKB:**
- Batch 1: >jam 10.00 hari sebelumnya
- Batch 2: <jam 10.00 hari yang sama
- Batch 3: maks jam 10.30 (khusus akhir bulan)

- Dokumen set BPKB dikirim ke Docust **H+1** setelah realisasi
- Ref Top Up → tidak perlu cek absah & blokir (BPKB sudah ada di BCAF)

---

### 2. New Car
- Tidak perlu cek absah (BPKB diterima langsung dari dealer)
- Jika ada perubahan di BPKB → wajib cek absah
- CN harus ditukar menjadi BPKB maks **90 hari**; tanggal CN maks **60 hari sebelum** tanggal realisasi

**PIC Penerimaan CN + Blanko:**
1. Terima CN + Blanko + dokumen kelengkapan dari APP
   - Dokumen: SP Hak (non-B2B), Kwitansi Jual Beli Putus (jika nama konsumen ≠ nama di BPKB), SP Konsumen/SP Hak (jika ada ketidaksesuaian)
2. Cek & ceklist dokumen → approval TL (cek: nopin, nama konsumen, BPKB owner, nama dealer, alamat dealer, noka/nosin)
3. CN + Blanko masuk ke map → brankas (kode cabang, nama dealer, alamat dealer)
4. Balancing dokumen (CN yang hanya copy → minta asli)

**PIC Order CN:**
1. Tarik data dari email + JOGET DX → buat register
2. Cari CN di brankas → pisahkan CN dan blanko (4 angka pertama CN = kode cabang)
3. Order BPKB di **JOGET DX** (pilih cabang WPI → pilih BJ → tanggal penyerahan → submit → cetak tanda terima)
4. Pengecekan TL
5. BJ hanya membawa CN → tanda terima TTD PIC Order & BJ

**PIC Follow Up:**
- Follow up dealer via email/WA/kunjungan (setiap akhir bulan, dilakukan harian berdasarkan report)
- Jika 90 hari BPKB belum jadi → dealer mendapat **Surat Peringatan**
- BPKB jadi → input di JOGET DX → plotting BJ untuk pengambilan

**PIC Penerimaan BPKB (dari dealer):**
1. BJ bawa BPKB jadi dari dealer
2. Cek BPKB + ceklist tanda terima (Faktur, NIK, Form A, Sertifikasi Register Uji Type dari Kemenhub)
3. TL cek kuantitas & approval
4. Scan halaman 1–6 + halaman belakang
5. Cek sebelum input di Financore (nama BPKB = faktur, NIK, alamat, merk, type, warna, noka/nosin, BBM, no faktur & tanggal)
6. Input di Financore (No BPKB, BPKB date, nopol, no faktur)
7. Dokumen kelengkapan masuk amplop (depan: ceklist + TTD + No RF ID) → amplop masuk ke BPKB + stiker (no kontrak + nama konsumen + No BPKB)
8. H+1: digabungkan dengan Blanko Kwitansi (perorangan) / SP Hak (non-B2B)
9. **H+2**: diserahkan ke Docust melalui TL ke AS Docust

---

### 3. STNK
- Perpanjangan STNK tidak perlu borrow BPKB (BPKB sudah link di FINA)
- Proses via Biro Jasa sesuai wilayah cabang

---

## 10. Document Support (Doc Support) {#document-support}

**Fungsi:** Pemrosesan dokumen awal tahap pra-realisasi

**5 Bagian Doc Support:**
1. Checker ME & NON ME (One ME, ME Corporate, PDP)
2. SHF (Showroom Financing)
3. CC
4. AWC & Revisi
5. CIC (Checker Information Center)

---

### ONE ME (Mobile Entry)
**Untuk:** Pengajuan konsumen perorangan (CS, DS, KKB)

**Target:**
- Karyawan lama: 38 get data/hari · Karyawan baru: 32 get data/hari
- Bulanan: 250/bulan
- **SLA:** 15–20 menit; PDP 25–30 menit

**Flow Umum One ME:**
1. Marketing input
2. Checker cek
3. Naik ke MA (One ME tidak pakai K3)
4. Jika OK → Final Check → kontrak masuk ke PDP
5. Jika belum OK → AWC

---

### ME CORPO (ME Corporate)

**Klasifikasi:**

| Kondisi | Aplikasi | Keterangan |
|---|---|---|
| Pengajuan regular ≤3 unit & ≤5M | ME Corpo (Naik MA) | Tidak boleh ada K3 |
| Semua di luar kondisi di atas, ada memo plafon, ada penyimpangan | ME Corpo (harus K3) | — |

**5 Bucket yang Dicek:**
1. Corporate Data (nama PT, NPWP, FAP, alamat, CP, Resume AHU, penjamin, financial, dokumen)
2. Loan Data & Collateral (cluster, mutasi rekening, data kendaraan, asuransi)
3. Matching Result (cek by cust ID, NIK, tanggal lahir, status pernikahan, RO)
4. Point Rekomendasi
5. Watchlist (jika 2 kesamaan nama & tgl lahir → PENDING)

---

### SHF (Showroom Financing)

**Dokumen:** KTP · FAP · Data kendaraan (BPKB, STNK, faktur, foto unit)

**Aplikasi:** ME SHF (perorangan) · PDP (BU/tidak RO) · Financore · Approva · Plafon

**Flow SHF:**
1. Cek watchlist (history konsumen)
2. Download FAP → cek email, alamat, no HP, CP, OTR, paraf BM
3. Cek collateral kendaraan (BPKB, STNK, faktur, foto unit) — data noka/nosin, jatuh pajak harus cocok di 4 dokumen
4. Cek matching konsumen (RO / ada APP ID berjalan)
5. Asset registry (dijaminkan ke showroom lain?)
6. Cek plafon showroom (apakah masih bisa pengajuan); DP minimal 30%
   - Jika DP <30% → wajib memo + showroom harus ada di list 200 showroom
7. Cek OTR → samakan dengan FAP
8. Flat rate SHF: **9%**; Loan: In Arreaf
9. Cek nomor rekening di FAP
10. Done → langsung masuk ke APP

---

### CC (Checker)
Output: pengeluaran KONTRAK

**Data yang TIDAK bisa dimaintain:** NIK · Nama · Tempat/Tanggal Lahir · Jenis Kelamin → harus pending

**Alur Umum:**
Data Entry → Recommend (checker selesai cek) → Prossed → Approval CC1 (dicek CC) → Approval CC2 (AWC) → 5 menit kemudian → Final Check (Revisi)

**Yang Masuk ke CC:**
- NON ME
- Ada Deviasi EP

**Deviasi EP (cetak kontrak manual):**
1. Pengajuan COP
2. Self Cover
3. RUPS
4. Refinancing
5. SP Kom terpisah
6. Kontrak gabungan
7. Kendaraan chasis & karoseri (split PO / PO gabungan)
8. Pasangan lebih dari 1
9. Usia <21 tahun dan belum menikah

---

## 11. Asuransi {#asuransi}

### Jenis Asuransi yang Di-order
1. **Asuransi Kendaraan:** Comprehensive/All Risk · TLO
2. **Asuransi Credit Protection (CP)**
3. **Asuransi Showroom Financing (SHF)**

**Maskapai Kendaraan:** BCAI · SIMAS · SAHABAT · CAKRAWALA · ASTARINDO · ASWATA · CHUBB

**Asuransi Penyerta (nempel pada asuransi induk):**
- TLP (Total Loss Protection) → asuransi utama TLO
- PA (Personal Accident)
- CPR (asuransi mesin kendaraan)

---

### Order Asuransi Kendaraan (Otomatis)
1. H+1 secara API → terorder otomatis
2. Monitor status order:
   - Unordered (bug sistem → lapor IT)
   - Unreceive (H+1 belum terima e-polis → konfirm ke maskapai)
3. Idealnya hari H setelah order → e-polis terkirim ke DMS
4. H+14 dari DMS → link ke FINA → konsumen dapat download mandiri
5. **Pembayaran: H+60 setelah order**

---

### Order Manual Asuransi
Kondisi order manual:
1. Asuransi cover mundur (Refinancing/Top Up)
2. Unit mewah (LEXUS dapat premi 1 tahun free; BCAF order manual untuk tahun berikutnya)
3. Asuransi order penutupan baru (aksesori >5)

**Flow Order Manual:**
1. Hari H realisasi → cabang input di B2B untuk menangkap no kontrak (agar tidak auto-order API)
2. PIC Asuransi kirim data by email ke maskapai
3. Maskapai feedback berupa SOA (Statement of Account)
4. Maskapai kirim e-polis di DMS → link ke FINA

> Self Cover: konsumen sudah memiliki asuransi di luar BCAF → isi tiring "lainnya" agar tidak auto-order; **WAJIB melampirkan leasing clause**

---

### Asuransi CP (Credit Protection)
- **Syarat:** Usia <65 tahun, usia >17 tahun saat realisasi, PH <1M, konsumen bukan PT, tidak punya penyakit bawaan berat
- **Maskapai:** CIPUTRA · CHUBB · TMLI (Tokyo Marine Life Insurance)
- Order: H+1 API otomatis → Payment → Nembak Financore → e-polis terkirim di DMS
- **Pembatalan Polis:** via JOGET oleh cabang; PIC Asuransi KP hanya informasikan ke maskapai

---

### Asuransi SHF (Showroom Financing)
1. **PAR** (Property All Risk) — bencana alam di luar gempa bumi
2. **EQ** (Earthquake) — gempa bumi
- Order via JOGET

---

### Change Insurance (Pergantian Maskapai)
1. **Perawal** (realisasi <2 bulan): cabang buat memo → approval s.d. 1 BOD → ajukan via email ke maskapai
2. **Prorate** (realisasi >2 bulan): sertakan lembar survei + perhitungan selisih + kurang bayar → via email ke maskapai
- **SLA:** H+2 setelah request pembatalan → konfirmasi ke konsumen

---

### Endorsement Asuransi
**Jenis:**
- **Premi** (Upgrade) — peningkatan jenis pertanggungan
- **Non Premi** — pengkinian data yang tidak mengubah struktur premi

**Jenis Upgrade:**
1. Perluasan 1: All Risk + RSCC + RSMB + TJH 10 juta
2. Perluasan 2: All Risk + RSCC + RSMB + TJH 50 juta
3. Comprehensive: TLO → All Risk

| Jenis | Rate / Tarif |
|---|---|
| All Risk | Cover seluruh kerusakan |
| TLO | Cover kerusakan >75% |
| RSCC (Riot Strike Sipil & Commotion) | 0,50% |
| RSMB (Riot Strike Machine Breakdown) | 0,22% |

- Rate Comprehensive = Rate TLO

**Kondisi Survey:** wajib jika sudah melewati jatuh tempo

**Channel Upgrade Premi:**
1. **ONTRACE** (VA berlaku 7 hari) — via telesales → create VA → konsumen bayar → status "UPGRADE" di Financore → e-polis ke DMS → FINA
2. **FINA** (VA berlaku 7 hari) — tarik report Financore → order API → cek e-polis & premi
3. **TELESALES** (VA berlaku 14 hari) — telesales kirim perhitungan, bukti bayar, lembar survei → cek + approval TL → req ke maskapai → e-polis ke DMS; PIC manual upgrade status di Financore

**Endorsement Non Premi:**
Cabang ajukan via **DRONE** → PIC tarik data → kirim report ke maskapai by email

---

### Maintenance Data Asuransi
Flow: Cabang/Asuransi KP ajukan via JOGET → buat IT Service (ditujukan ke IT + unit kerja terdampak) → setiap unit kerja informasikan masalah → eksekusi by IT → solved

---

### Rekonsil Asuransi
Pencocokan nominal perhitungan premi untuk pembayaran ke maskapai.

**Yang Direkonsil:** Asuransi Manual Order · Asuransi Upgrade

**Pembayaran SHF dan CPR via EGER:**
1. Pembuatan memo naik s.d. Dept Head → upload di EGER → Payment bayar

**Pembayaran Close ET:**
1. Pembuatan memo naik s.d. Dept Head → naik fisik memo + dokumen pendukung ke Payment → Payment bayar

---

### Invoice Saving
1. Konsumen mengajukan upgrade
2. Financore → Activity History → Upgrade
3. Info ke FSM terkait alokasi dana → hari H muncul history tanggal PAID
4. Maskapai kirim e-polis + invoice
5. Saving/perhitungan invoice & polis (nominal harus sama)

---

### Klaim CP (Credit Protection)
**Tujuan:** Menutup sisa angsuran konsumen menggunakan uang CP

**Jenis Klaim:**
1. Meninggal dunia
2. Ketidakmampuan Total (cacat permanen) · Ketidakmampuan Sementara (ada kemungkinan sembuh)

**Poin Pengecualian (menggugurkan klaim):**
1. Terlibat perang
2. Terlibat masalah hukum
3. Kegiatan berbahaya
4. Penerbangan selain sebagai penumpang
5. HIV dan lainnya
6. Waiting Period: pinjaman 1 tahun → 3 bulan awal tidak bisa klaim; pinjaman >1 tahun → 6 bulan awal tidak bisa klaim
7. Tolakan klaim: jika lapor >H+90 sejak kejadian

**Pengajuan Klaim CP:**
1. Cabang terima pengajuan dari konsumen/ahli waris + dokumen:
   - KTP konsumen · Nama & no telepon ahli waris · Tanggal kejadian/meninggal
   - K1 (form klaim) · K2 (form keterangan dokter) · Surat keterangan kronologis · Surat kuasa ke maskapai · Riwayat pengobatan · (jika terlambat lapor) surat keterangan terlambat lapor
2. Upload ke MOVE (JOGET DX) → approval BOH → PIC → TL
3. PIC input di Acces untuk pembuatan **SURAT PENGANTAR** (isi: branch, data polis, data konsumen, data kejadian)
4. Perhitungan sisa tenor & angsuran (LOAN LEDGER) → input di MOVE
5. Download Surat Pengantar → approval s.d. Dept Head & UH Asuransi
6. Surat Pengantar + Loan Ledger + dokumen pengajuan → kirim ke maskapai by email
7. Cabang/CS isi deskripsi di Financore + CP Plus (tanggal kejadian, tujuan pengajuan)
8. Maskapai berikan feedback (persetujuan/tolakan/pending)

---

*— Akhir catatan Base 2 Comprehensive —*

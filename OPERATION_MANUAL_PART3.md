# OPERATION MANUAL — BCA FINANCE (PART 3 dari 3)

> Mencakup: **Docust & Archive** · **Asuransi** · **Operation Area** · **OSD** · **OQA**

---

# 7. DOCUST & ARCHIVE

## 7.1 DOCUST MOBIL

### Fungsi & Media Penyimpanan
- Mengelola BPKB, Polis (self cover + cover mundur), Surat Blokir, Dokumen Lelang (KP)
- Bagian dari Account Management: Docust + BPKB Admin + Archive + Asuransi

**2 Media Penyimpanan:** Kluis (Lemari tahan api/fireproof safe); Brankas (Besi tahan api)

**Dual Custody & Dual Control:**
- Dual Custody: Angka kombinasi + anak kunci (dua mekanisme pengaman)
- Dual Control: Pemegang anak kunci ≠ pemegang kombinasi
- Alternatif jika pejabat berhalangan: ada prosedur backup
- Memo penunjukan: approval DH
- Kunci tidak boleh dibawa pulang!
- Register buku akreditasi kluis wajib diisi

**Pra Realisasi:** Cek asset registry via COFICO; FKB pembatalan refinancing (jika ada)

### Receive BPKB

**New Car (6 Langkah):** Serah terima AS vs TL/UH BPKB Admin → Amplop + segel TTD PIC+Pejabat → Input Financore → QR Code dibuat → TAG sent to kluis → Simpan di laci

**Used Car:**
- Manual: H+2 dari BPKB Admin, sama seperti New Car
- Aplikasi: H+1, ACA input "sent to kluis", nembak Financore H+1

### Borrow BPKB — SLA Plan Return
| Keperluan Borrow | SLA Return |
|---|---|
| Perpanjangan STNK | 1 bulan |
| BBN (Balik Nama) | 2 bulan |
| Mutasi | 3 bulan |
| Revisi BPKB | 1 bulan |
| Ubah nopol | 1 bulan |
| Blokir | 1 bulan |

**Alur Borrow STNK:** Konsumen walk-in → CS konfirmasi → DP biaya → Report ke BPKB Admin → Borrow via RPA → Report borrow → Birojasa proses → Return + report

**Alur Borrow Lainnya:**
- Lelang: CS credit settlement memo → borrow (belum closed) → status berubah setelah BAP+memo FSM, SLA 1 bulan
- Klaim TLO: Borrow karena belum closed, SLA 1 bulan / PPJGR 3 bulan
- Dijual OLX: Borrow purposes digital platform → released setelah memo FSM
- BCA Prioritas: SLA 10 hari, released setelah terima surat dari BCA
- Reservasi Cabang: Borrow 15 hari/30 hari luar kota, perpanjangan approval DH OA + CS

### Released BPKB & Stock Opname

**Kondisi Released:**
- Konsumen Lunas: Borrow 15 hari → H+1 tarik data → pencocokan → Return → Released → penyerahan ke CS
- WO (Write-Off): Remedial CS, cek SKL dari Recovery unit
- SHF: Ada cap BPKB, disimpan cabang saat realisasi

⚠️ PENGIRIMAN BPKB MAKSIMAL HARI RABU

**Stock Opname:** S1 (Jan–Jun): SO DETAIL (dilakukan 2 tahun sekali); S2 (Jul–Des): SO FISIK menggunakan RF Id (KP)/barcode (cabang)

## 7.2 DOCUST MOTOR

### Definisi & Kebijakan Dasar
| Istilah | Definisi |
|---|---|
| BPKB | Aset perusahaan yang berfungsi sebagai jaminan atas kredit nasabah dan harus dikontrol dengan ketat |
| Stok Opname BPKB | Kegiatan membandingkan hasil pemeriksaan fisik BPKB beserta dokumen kelengkapannya dengan pencatatan stok yang ada di sistem |
| Sentra Kustodi (Docust) | Lokasi terpusat untuk penyimpanan dan pengelolaan BPKB dari beberapa cabang dalam satu area operasional |
| Laci Transit | Laci khusus dalam strong room untuk menyimpan BPKB yang sudah diterima secara sistem tetapi belum melalui proses pemindaian (scanning) untuk di-upload ke Document Imaging |

Dasar kebijakan pengelolaan BPKB di Sentra Kustodi: **KBP/DOP/1109** — mengatur siklus hidup BPKB mulai dari pengambilan di cabang hingga penyimpanan akhir

### Kriteria BPKB yang Disimpan di Sentra Kustodi
- Kontrak aktif (Active) dengan sisa angsuran > 1
- BPKB atas kontrak Write Off (WO)
- BPKB yang sudah berada di cabang selama 6 bulan sejak didistribusikan dari Sentra Kustodi (jika tidak ada reservasi oleh konsumen)

### Proses Pick Up, Distribusi & Penomoran Lemari

**Jadwal Pick Up:**
- Kepala Unit Sentra Kustodi menginformasikan jadwal setiap awal bulan melalui email
- Reschedule diperbolehkan maksimal H-1 dari jadwal awal
- Target keberhasilan Pick Up BPKB: 100%
- Evaluasi dilakukan setiap tanggal 1 oleh Kepala Departemen Layanan Pendukung Operasional

**Transportasi (berdasarkan jarak pulang-pergi)**
| Kondisi | Moda Transportasi |
|---|---|
| Jarak < 120 km | Sepeda motor pribadi staf terdaftar atau ekspedisi |
| Jarak > 120 km | Mobil operasional atau ekspedisi (peminjaman dilakukan H-1 kegiatan) |

**Tata Cara Penomoran Lemari:** Format: xx.yy.zz → xx = nomor lemari · yy = nomor laci · zz = nomor kolom. Kapasitas per kolom: 40–80 BPKB (dibatasi untuk mencegah kerusakan fisik)

**Pelaporan & Closing Harian:**
- Closing Harian: Staf mengajukan rekonsiliasi harian melalui sistem MOVE setiap akhir hari kerja
- Berita Acara: Hasil SO dan rekonsiliasi harus dituangkan dalam BA yang disetujui pejabat berwenang dan diarsip berdasarkan urutan tanggal

### 4 Lokasi Docust Motor & Perbedaan dengan Mobil

| Lokasi | Area Cakupan |
|---|---|
| Ciputat | Jabodetabek + Cikarang |
| Bandung | Jawa Barat + Karawang |
| Solo | Jawa Tengah (Semarang, Magelang, Yogyakarta, Solo, dll) |
| Gresik | Jawa Timur (Malang, Sidoarjo, Surabaya Darmo, Kediri, dll) |

**Perbedaan Docust Mobil vs Motor**
| Aspek | Mobil | Motor |
|---|---|---|
| Borrow BPKB | Langsung ke Docust | Hanya via TL Operation Cabang (1 pintu) melalui MOVE Approval |
| SKL | Dibuat oleh Docust KP | Dibuat oleh TL Cabang |
| Max BPKB di cabang | 16 hari | 6 bulan |

### Flow Docust Motor & SLA

**Mutasi IN:** Terima BPKB dari cabang/pick-up tiap awal bulan; BPKB yang diterima dari dealer (Covernote); BPKB yang dipinjam untuk pengurusan BBN, Mutasi, atau STNK; Input di FAST dengan nomor BAST (fisik sudah diterima)

**Mutasi OUT:** Distribusi BPKB ke cabang (H-1 bulan konsumen lunas); Input di FAST dengan nomor BAST; TL Operation cabang yang melakukan pengecekan dan mengeluarkan SKL

**SLA Docust Motor**
| Proses | SLA |
|---|---|
| Receive ke sistem FAST | H+2 dari BPKB diterima |
| Scan & Upload Document Imaging | H+2 dari receive |
| Barcoding | H+24 hari kerja setelah scan |
| Masuk lemari BPKB | H+1 setelah barcode |

**Ketentuan Pengiriman BPKB Motor**
| Kondisi | Moda Transportasi |
|---|---|
| Jarak >120 km atau >150 BPKB | Mobil operasional |
| Jarak <120 km dan <150 BPKB | Motor |

Cut-off pengiriman: Hari Kamis (agar tidak sampai di hari libur). Biaya titip BPKB: Rp 5.000/hari mulai hari ke-61 setelah pelunasan (per website BCAF). Khusus Multiguna: BPKB tetap diambil oleh konsumen — yang melakukan cek absah dan blokir adalah MC Operation Cabang (bukan Docust)

### 7 Tugas Rutin TL Docust Motor
1. Setiap awal bulan membuat jadwal pick-up distribusi BPKB
2. Mengirimkan BPKB ke cabang untuk konsumen yang sisa angsuran tinggal 1x (H-1 bulan lunas)
3. Jangka waktu BPKB di cabang maksimal 6 bulan; jika tidak diambil → pick-up kembali ke sentra docust
4. Penyimpanan selain sentra docust: di cabang masing-masing menggunakan brankas
5. Setiap minggu sampling BPKB via video call (VC) dengan TL cabang untuk memastikan penyimpanan sesuai ketentuan
6. Register proses mutasi IN dan OUT dapat ditarik dari Fast App (export Excel)
7. Balancing akhir hari di aplikasi My Report → diapprove oleh UH Docust

### Stock Opname BPKB Motor (SK No.008/SK/DIR/2025)
| Jenis | Frekuensi | Isi Pemeriksaan |
|---|---|---|
| SO Detail | 1x per 2 tahun | Fisik BPKB + Faktur + NIK + SPH + SP konsumen + Form A |
| SO Fisik | 2x per tahun (S1 Jan-Jun/S2 Jul-Des) | Fisik BPKB saja (RF Id KP/barcode cabang) |
| SO Non-Rutin | Jika ada pergantian pejabat/staf kluis/perpindahan kluis | Sesuai kebutuhan |

**Pihak Independen Internal:** Wajib hadir jika cabang memiliki >3.500 BPKB. Cabang dengan <3.500 BPKB: sampling 50 BPKB dengan foto dikirim ke PIC Sampling maks H-1. Tugas: memastikan pelaksanaan SO, membantu prosesnya, menjadi saksi pembuatan Berita Acara

Jika SO non-rutin sudah dilakukan → SO rutin tahun tersebut tidak diperlukan lagi

## 7.3 ARCHIVE

### 5 Fungsi Archive
1. Terima dan simpan dokumen (dossier)
2. Peminjaman dokumen (request retrieval)
3. Pembayaran tagihan vendor penyimpanan
4. Rekonsil nasional (pencocokan data)
5. Sampling nasional

**Alur Penerimaan Dossier:**
- Dossier Copy: H+3 dari Legal Admin
- Dossier Asli B2B/Individu: Pisahkan SK Fidusia → fidusia admin; dossier → archive
- Dossier Asli Non-B2B: Semua ke fidusia admin; SLA H+5

**Register & Indexing:** Serah terima dokumen dicatat; Indexing: sampling 10% per box

**Kapasitas Box**
| Jenis Box | Kapasitas |
|---|---|
| Box Asli | 135 dokumen |
| Box Copy | 120 dokumen |
| Box Fidusia | 300 dokumen |

**MMI (Vendor Penyimpanan Eksternal):** Scan CD: greyscale untuk dossier copy + insertion; Scan CD: hitam putih (b&w) untuk sertifikat fidusia; SLA BA (Berita Acara): H+6 dari tanggal realisasi

---

# 8. ASURANSI

Unit Asuransi KP mengelola semua aspek asuransi: endorsement polis, order asuransi, pembayaran premi, refund, dan klaim — untuk kendaraan mobil maupun motor.

## 8.1 ENDORSEMENT

### PIC Endorsement Premi — Upgrade Asuransi

Endorsement Premi = ubah data polis bagian data pertanggungan (manfaat/upgrade premi asuransi)

**3 Macam Asuransi Kendaraan:** TLO (Total Loss Only); Komprehensif (All Risk); Kombinasi

**Asuransi CP (Credit Protection) & Penyerta:** PA (Personal Accident); TLP (Total Loss Protection); TJH (Tanggung Jawab Hukum) pihak ketiga; Perluasan: RSCC, RSMB

**3 Macam Perluasan**
| Perluasan | Isi |
|---|---|
| Perluasan 1 | Komprehensif + RSCC + RSMB + TJH Rp 25 juta |
| Perluasan 2 | Komprehensif + RSCC + RSMB + TJH Rp 50 juta |
| Perluasan 3 | Komprehensif (tanpa RSCC/RSMB/TJH) |

**3 Sumber Pengajuan Upgrade:**
- Ontrace (RPA): Robot blast WA ke konsumen → konsumen tertarik → bayar via VA → otomatis order ke maskapai → PIC hanya tarik report
- Fina: Konsumen ajukan di Fina → maskapai hitung premi → keluar VA → konsumen bayar → order otomatis → polis masuk DMS → H+60 baru kirim ke maskapai
- Telesales (Manual): Telesales telepon → konsumen bayar via VA telesales → telesales kirim report H+1 (bukti bayar + lembar survey + perhitungan) → PIC create di Financore → kirim/alokasikan dana ke FSM → kirim order ke maskapai → H+1 feedback polis

**Perhitungan Premi TJH:** TJH Rp 10 juta = Rp 100.000/tahun; TJH Rp 25 juta = Rp 250.000/tahun; TJH Rp 50 juta = Rp 300.000/tahun

**Asuransi Kendaraan — TSI (Total Sum Insured):** Tahun 1: TSI = OTR (Rp 200 juta); Tahun 2: TSI = OTR – 5% (Rp 190 juta); Premi = TSI × Rate Premi (berbeda tiap tahun)

Cover Mundur: Jika konsumen refinancing top-up atau punya self cover yang tidak menutupi seluruh tenor

Self Cover: Konsumen punya asuransi sendiri → marketing input "Asuransi Lainnya" di Financore. Wajib lampirkan polis fisik ke BCAF. Periode tidak boleh lebih pendek dari tenor kredit. Jika konsumen ET → asuransi kendaraan masih aktif, bisa upgrade. CP jadi inactive saat ET

### PIC Endorsement Non-Premi — Ubah Data Polis

Non-Premi = ubah data tertanggung atau data kendaraan di polis (bukan premi/manfaat). Tidak ada biaya.

**Contoh Perubahan:** Warna kendaraan berubah; Nama di STNK berubah (pengkinian data); Nomor polisi berubah

**Alur Non-Premi:** Cabang input di JogetDX/Drone → Unit parallel (BPKB Admin/CS/Asuransi/Fidusia/Docust/JF&LM) cek & input deskripsi → PIC tarik data → Excel → PDF → Kirim ke maskapai (order endorsement) → H+1 maskapai kirim feedback polis

**Feedback dari Maskapai:** Via API (BCAI dan Aswata): polis langsung masuk DMS otomatis; Non-API: Maskapai reply email dengan polis PDF

**Monitoring Polis:** PIC tarik data maskapai yang belum feedback → follow-up via email/WA

No BPKB tidak bisa di-endorse di Non-Premi (tidak ada field-nya di JogetDX/Drone)

### Asuransi SHF (Showroom Financing)

**2 Jenis Asuransi SHF:** PAR (Property All Risk): bencana alam di luar gempa bumi; EQ (Earthquake): gempa bumi

**Maskapai Asuransi SHF:** BCAI; SIMAS; CAKPRO (Cakrawala)

**Alur Order SHF (via JogetDX Infinity):**
- Tim SHF email ke maskapai → maskapai kirim SP3 (Surat Pemberitahuan Penutupan)
- Input di Infinity: order baru/perpanjangan/endorsement + upload SP3
- PIC cek nilai premi SP3 dan kelengkapan data (KTP, bukti bayar)
- Jika sesuai → Approve di Infinity → masuk bucket Bu Sherry + Pak Rahmat
- Maskapai kirim feedback: maks H+5 → polis PDF via email

**Refund Asuransi SHF:** Lampiran Memo Internal; Approval sampai Pak Frans (DD Operation); Asuransi order ke maskapai via email; Dapat feedback bukti bayar refund ke showroom

## 8.2 ORDER ASURANSI (MOBIL)

### PIC Order — Maskapai & Metode

**Maskapai Asuransi Kendaraan & CP:** BCAI · SIMAS · SAHABAT · CAKRAWALA · ASTARINDO · ASWATA · CHUBB

**Maskapai CP (Credit Protection):** CIPUTRA LIFE; CHUBB LIFE; TMLI (Tokyo Marine Life Insurance)

**Metode Order Otomatis (API):**
- H+1 setelah realisasi: otomatis order via API → nembak Financore
- Monitoring status: Unordered (bug sistem) → lapor IT · Unreceive (H+1 belum ada polis) → konfirmasi maskapai
- Idealnya hari H setelah order, e-polis terkirim ke DMS
- H+14 dari DMS → link ke Fina (konsumen bisa download mandiri)

**Kondisi Order Manual:**
- Cover Mundur Non-EXPO: Refinancing/top-up yang masih on-going → cabang input di Aplikasi Asuransi B2B sebelum realisasi
- EXPO: Promo gratis asuransi 1 tahun dari dealer (contoh: Lexus) → cabang input B2B sebelum realisasi → PIC input order manual via email ke maskapai
- Aksesori >5 item: Mempengaruhi OTR → cabang input B2B (capture no kontrak) → hari H kirim ke maskapai → maskapai kirim SOA → polis masuk DMS → link ke Fina

**Asuransi Penyerta (Nempel pada Induk):** TLP (Total Loss Protection): asuransi utama TLO; PA (Personal Accident): cover semua penumpang, tidak perlu survey; CPR (Comprehensive Protection): cover mesin kendaraan

**Syarat Asuransi CP Mobil:** Usia konsumen <65 tahun saat realisasi; Usia >17 tahun saat realisasi; PH (Pokok Hutang) <Rp 1 miliar; Konsumen bukan PT; Tidak memiliki penyakit bawaan berat

**SLA Order Asuransi Mobil:** Order: H+1 realisasi; Feedback maskapai: H+1 dari order (EXPO: H+14); Pembayaran ke maskapai: H+60 dari order

Mini 4 Max Tahap 2: Order asuransi pertama = min 4 max tahap 1. Jika konsumen lanjut tahap 2 → order asuransi lagi via API, tapi pembayaran manual.

**Change Insurance (Ganti Maskapai)**
| Kondisi | Proses |
|---|---|
| Realisasi < 2 bulan (Perawal) | Cabang buat memo approval sampai 1 BOD → ajukan via email ke maskapai |
| Realisasi > 2 bulan (Prorate) | Dokumen: Lembar survey + Perhitungan selisih + Kurang bayar → ajukan via email ke maskapai · SLA: H+2 setelah request pembatalan akan dilakukan konfirmasi ke konsumen |

### PIC Pembayaran & Rekonsil
- Pembayaran asuransi kendaraan: H+60 setelah order
- Pembayaran CP dan penyerta lain: dilakukan oleh Akuntan/Finance/FSM
- Pembayaran sudah otomatis → input invoice manual di Financore jika order manual
- Jika ada kurang bayar → ditagih ke konsumen

**Rekonsil:** Pencocokan nominal perhitungan premi dengan pembayaran ke maskapai. Yang dilakukan rekonsil: Asuransi Manual Order + Asuransi Upgrade

**Alur Pembayaran SHF & CPR via EGER:** Buat memo (naik ke DH) → Upload di EGER → Payment melakukan pembayaran

### PIC Maintenance — Ubah Data Financore

Beda dengan Endorsement: Endorsement = ubah data di polis · Maintenance = ubah data di Financore (sistem internal)

**Alur:** Cabang/Asuransi KP ajukan via JogetDX → Approve pejabat DD dulu → Masuk bucket Admin Asuransi → Buat IT Service Request ke IT + unit terkait → Eksekusi oleh Team IT → Solved

**Form di Joget:** Request identity; Form service request; Form data maintenance: nama, NIP, kronologi, akibat, permintaan

- SLA: 5 hari kerja hingga data berubah di sistem
- PIC Maintenance juga narik data dari datamart untuk PIC Order (unreceived & unordered)
- Berlaku nasional
- Perubahan data selalu dari Cabang/KP, maskapai tidak pernah minta perubahan

## 8.3 REFUND ASURANSI

### Refund Asuransi CP (Credit Protection) — Mobil

**Syarat Refund CP:** Status di Financore: Close ET – Release (BPKB sudah diambil); Nominal refund minimal Rp 25.000; Tidak berlaku pada Mini 4 Max tahap 2

**2 Sumber Pengajuan:**
- Dari Cabang: Email berisi rekap order + Form Permohonan Refund CP (approval BOH + TTD konsumen bermaterai) + KTP + Inquiry rekening + Polis (wajib jika maskapai Chubb Life)
- Dari KP/WPI: Konsumen walk-in ke CS → dokumen diambil oleh CS → dianter ke atas

**Perhitungan Refund CP:** Rumus: (Sisa hari yang belum terpakai / Tenor) × Premi yang dibayar konsumen = Y. **Nominal Refund = Y × Persentasi Refund Maskapai**

| Maskapai CP | % Refund |
|---|---|
| Ciputra Life | 30% |
| Chubb Life | 8–10% |
| TMLI | 10% |
| BCA Life | 30% |

**Proses Setelah Hitung:** Buat surat pembatalan (perihal pembatalan + pengembalian refund + no kontrak, nama, no polis, tanggal batal, nominal, rekening) → Memo naik ke Privy → approval DD Accounting + DH Account Manager → Jika full approve → kirim email ke maskapai → Refund CAIR! → langsung ke rekening konsumen

**Balancing:** Harian: Email ke semua cabang nasional list pengajuan yang masuk per hari (mulai jam 4 sore); Bulanan: Email ke semua cabang nasional list pengajuan per bulan

Jika konsumen pernah claim CP sebelumnya → refund CP akan ditolak maskapai. Pengajuan yang masuk sebelum jam 16.00 → diproses hari ini. Setelah jam 16.00 → diproses besok.

### Refund Asuransi Kendaraan — Mobil

**Syarat:** Status: Close ET – Released (BPKB sudah diambil); Sisa periode polis minimal 90 hari (sisa 89 hari tidak bisa); Tidak ada batas nominal minimum

**Dokumen Pengajuan:** Form Pengajuan (TTD Konsumen + Materai); KTP Konsumen; Cover buku tabungan; Rekap Order (khusus pengajuan dari cabang); Approval BOH, TL, dan Staff Asuransi

**Alur:** Register di MS Access → Minta estimasi perhitungan ke maskapai (tanggal batal H+5) → Maskapai kirim feedback H+1 → Cocokkan perhitungan internal vs maskapai → Buat Memo Refund (approval TL UH DH DD) → Order batal ke maskapai (approval TL) → Maskapai TF maks H+5 → FSM kirim dana unknown → buat permohonan kelebihan dana → TF ke konsumen

TLP: Jika ada TLP meski pengajuan hanya asuransi kendaraan → wajib diajukan refund juga. Langsung buat itungan, memo refund, memo order batal, langsung TF (tidak perlu minta estimasi maskapai). Pengajuan di atas jam 14.00 → diproses besok

## 8.4 KLAIM ASURANSI

### Claim Asuransi CP — Mobil

CP Cover: Menutup sisa pokok hutang dari tanggal kejadian sampai tenor selesai (jika konsumen meninggal/cacat permanen)

**Jenis Klaim CP:** Meninggal Dunia; Cacat Total Tetap (Lumpuh permanen/kehilangan anggota tubuh); Cacat Total Tidak Tetap (Lumpuh sementara, contoh: stroke, bisa sembuh)

**Syarat Pengajuan Awal (Minimal):** Pengajuan oleh ahli waris; Tanggal kejadian/kematian; Nama + nomor HP ahli waris atau konsumen; Soft copy/scan KTP konsumen (atas nama); Pengajuan cabang/internal: deskripsi di Aplikasi CP Plus + Financore

Telat lapor: Lebih dari 90 hari kalender dari tanggal kejadian → klaim DITOLAK

**Aplikasi yang Digunakan:**
- One View (bukan Financore): karena konsumen bisa punya banyak kontrak → One View cari by Cust ID semua akun muncul
- JogetDX Move: Pengganti email (email: size terbatas, bisa hilang/error). Approval: BOH → TL Asuransi → Staff Claim CP

**Alur Klaim CP (Lengkap):** Pengajuan via Move (cabang)/walk-in CS → Register di Microsoft Access (surat pengantar) → Buat Loan dari One View (tabel angsuran PDF) → Gabung dokumen → Privy → Approve TL Asuransi → Kirim ke maskapai (pengajuan awal) → Maskapai kirim dokumen pendingan → Lengkapi dokumen (maks 30 hari) → Kirim ulang ke maskapai → Maskapai beri keputusan

**Dokumen Pendingan dari Maskapai:** Formulir klaim (K1) → diisi ahli waris; Surat keterangan dokter (K2) → wajib jika meninggal di RS/sakit keras, TTD dokter + cap basah RS; Surat keterangan kronologis meninggal (detail, diisi keluarga); Surat pernyataan penyerahan kuasa informasi medis; Form pengobatan pasien (TTD dokter + cap RS); Copy resume medis; Copy hasil pemeriksaan LAB; Surat keterangan kematian/surat keterangan polisi

**Tolak Klaim CP:** Telat lapor (lebih 90 hari); Berperang; Minum alkohol → kecelakaan/serangan jantung; Aktivitas berbahaya (terjun payung, menyelam, balap); Tindak kejahatan; Melanggar hukum (tidak berhelm, tidak punya SIM); Penyakit seksual; Waiting periode: Tenor 1 tahun = 3 bulan / Tenor ≥1 tahun = 6 bulan

**Klaim Disetujui — Perhitungan Bunga Berjalan (Maks 60 Hari):** Maskapai cover bunga berjalan maks 60 hari dari tanggal kejadian; SLA pengiriman perhitungan: 5 hari; Approval: TL + UH (UH tidak ada, diapprove DH); Klaim CP ditransfer ke rekening asuransi BCAF

**Klaim CP + PA Bersamaan:**
- Jika CP approved duluan → penerima = ahli waris (nomor rekening ahli waris)
- Jika PA cair duluan → penerima = BCAF unit asuransi (untuk nutup pokok hutang dulu)
- PA: maskapai hanya SIMAS · Alur PA = email Simas → Simas kirim LOD (Letter of Discharge)
- Presentase PA: meninggal = 100% (Rp 100–200 juta)

### PIC Memo ET — Penutupan Akun via Klaim CP

**Komponen Pelunasan:** OS Principal (sisa pokok); Total overdue → di-waived jika konsumen meninggal; Pinalti overdue; Bunga berjalan; Pinalti ET (5%) → di-waived jika meninggal; Admin fee → di-waived jika meninggal

**Alur:** Treasury/FSM kirim rekapan harian dana unknown → Identifikasi dana dari klaim CP → Verifikasi nominal sesuai register → Buat memo bukti bayar (approve TL Insurance) → Naikkan ke FSM untuk tutup akun

**Approval Waive ET**
| Nominal Waive | Approver |
|---|---|
| ≤ Rp 1 juta | Pak Ika (DH) |
| Rp 1 juta – 50% pinalti overdue | Pak Frans (DD) |
| >50% pinalti overdue | 1 BOD |

Lebih bayar → generate di MS Access (approval DH via Privy) → kirim ke FSM → tutup akun + sisa dana di deposit

### Claim Asuransi Kendaraan — Mobil (TLO/Kehilangan)

**Tipe Klaim:** Perbaikan Parsial: All Risk → konsumen langsung ke maskapai; TLO/CTL: Kerusakan >75% atau kehilangan → bisa via BCAF atau maskapai langsung

**Dokumen Awal:** FC KTP · FC SIM · FC BPKB/Faktur/Surat Keterangan Leasing · FC STNK

**Tolak Klaim:** Telat lapor (>5 hari kalender sejak kejadian); Kerusakan <75%; Kehilangan karena penipuan/penggelapan/hipnotis; Melanggar lalu lintas

**Alur Jika Disetujui:** Maskapai kirim SPGR (TTD konsumen) → BCAF kirim SPNP → Maskapai TF ke BCAF via VA 55000 → Cek TLP di Financore → Proses buyback (JF update SF)

**Isi SPGR/SPNP:** Nilai ganti rugi (harga pasar kendaraan); Resiko sendiri (OR): Rp 300.000 pickup/mobil besar / Rp 500.000 mobil biasa; Pinalti dokumen (jika tidak lengkap)

**TLP (Total Loss Protection) — Maskapai: Axa & BCAI:** TLP = 20% dari nilai kendaraan; Dokumen klaim TLP: Formulir TLP + SPGR TLO + KTP + SPNP

**PPKD Approval (Kelebihan Dana)**
| Nominal | Approver |
|---|---|
| 0 – 30 juta | DH |
| 30 – 100 juta | DD |
| 100 – 200 juta | 1 BOD |
| >200 juta | 2 BOD |

SLA: 14 hari maskapai cairkan dana · SLA keseluruhan: 90 hari

## 8.5 ASURANSI MOTOR

### Ketentuan & Order Asuransi Motor

**Jenis Asuransi Motor:** TLO: untuk produk KSM dan KSMM (KPM juga bisa); All Risk: hanya untuk motor >Rp 75 juta (berlaku KSM dan KPM)

**8 Maskapai Asuransi Kendaraan Motor:** ASCPI (Cakrawala) · ASHBT (Sahabat) · BCAI · Sompo · Astob · Raksa · SIMAS · ASMW

**Ketentuan CP Motor:** Bottom Rate 19% · Max umur 65 tahun saat pengajuan · Nasabah individu; BCA Life: PH 0–200 juta · Simas Jiwa: PH 200–500 juta

**Aplikasi:** Fast App; Fast Web Report

**Alur Order Asuransi Motor:** Fast App → Create Text Order Insurance → Tarik data (Buyback/Non-Buyback) → Fast Web Report → file TXT → Kirim TXT ke maskapai via email → Maskapai feedback TXT + no polis → Upload TXT → Input order resume → Masukan ke rekapan

Khusus BCAI: sudah API, tidak perlu upload-upload — cek di menu report asuransi motor

### Endorse & Tagihan Premi Motor

**Endorse Non-Premi Motor:** Ubah data administrasi: Change due date, nama, tanggal, dll. Muncul di text order non-buyback (menu Fast). Alur: Create text endorse → set type CDD → checklist amount Rp 5.000 → tarik data dari Fast Web Report → buat perhitungan excel → kirim ke maskapai → maskapai feedback → maskapai kirim kwitansi → upload ke Move (approval TL+UH) → kirim hardcopy ke FSM/Payment

**Endorse Premi Motor:** Case: WO (debitur hilang 2–3 bulan)/Sold (lelang). Seminggu sekali: tarik data Create Text Endorse → ambil di Fast Web Report → totalin premi per batch

**Approval Endorse Premi**
| Nominal | Approval |
|---|---|
| 0 – 25 juta | TL + UH + Accounting |
| 25 – 40 juta | TL + UH + DH + Accounting |
| >40 juta | TL + UH + DH + DD Accounting |

**Tagihan Premi Motor (Setahun Sekali):** Tarik Data: Fast Web Report → Insurance → New Rekap Tagihan Premi → pilih maskapai. Muncul data tahun 1, 2, 3 → jadikan Excel → kirim ke maskapai. Maskapai kirim Debit Note + kwitansi. Upload debit note di Fast App → buat memo pembayaran → approval sesuai nominal → hardcopy ke Payment

**SLA Asuransi Motor:** Order, refund, CP: H+1; Tagihan premi dan endorse: 14 hari kerja; Feedback maskapai: H+1

### Klaim Asuransi Kendaraan Motor

**Alur:** Pelaporan awal cabang (Move + Fast Tracking Claim), SLA 5 hari → Approve TL Cabang → Cek no kontrak di Fast → Email ke maskapai → Maskapai feedback dokumen → Move kembali ke cabang → upload kelengkapan → Kirim ke maskapai (soft+hard copy) → Tunggu H+14 feedback

**Jika Disetujui:** BCAF kirim SPNP (approval TL dan DH Asuransi); SPNP + CL dikirim ke maskapai; Tunggu pencairan H+10 dari maskapai

**Presentase Depresiasi Klaim Motor**
| Tahun Claim | Presentase |
|---|---|
| Tahun 1 | 100% |
| Tahun 2 | 85% |
| Tahun 3 | 75% |
| Tahun 4 | 70% |

Kunci motor dan STNK juga diserahkan ke maskapai saat klaim. Konsumen bisa langsung klaim ke maskapai tanpa melalui BCAF.

### Klaim & Refund CP Motor

**CP Motor Cover:** Yang di-cover: pokok hutang sisa saja; Bunga tetap jadi tanggungan konsumen; Khusus nasabah BCA

**SLA Klaim CP Motor:** Dokumen lengkap: 90 hari kalender; SPGR: 60 hari setelah dokumen fisik diterima maskapai; Pencairan: 10 hari kerja setelah SPNP dikirim

**Penolakan Klaim CP Motor:** Waiting periode: 6 bulan setelah masa pertanggungan; Pre-existing condition selama waiting periode: Stroke, tumor/kanker, diabetes, gagal ginjal, penyakit hati

**Alur Klaim CP Motor:** Cabang laporan awal via Move → Buat KP (Kartu Piutang) → approval UH via Privy → Upload KP + dokumen awal ke maskapai → Maskapai feedback dokumen pendingan → Cabang kirim dokumen fisik → PIC cek → kirim ke maskapai → Maskapai beri keputusan

**Refund CP Motor:** CP tidak bisa di-refund — CP hanya manfaat asuransi utama, bukan asuransi baru yang bisa dibatalkan. Jika ada kelebihan dana dari pencairan klaim → proses refund motor via Ex Deposit. Proses Ex Deposit CP: Fast → Finance → Invoice → Ex Deposit → pilih deposit no → isi nominal → process → SS → buat memo refund → ajuin ke Move Payment. Approval: TL + UH + Head Accounting + Staff Accounting. SLA Refund: 2 hari setelah pre-term atau dokumen syarat fisik diterima

---

# 9. OPERATION AREA (OA)

OA = perantara antara cabang dan kantor pusat untuk kebutuhan & kendala operasional cabang. Dibagi: **Area Specialist · OA Admin · Area Multitasking**

## 9.1 Struktur Pembagian Area

- OA Area 1 — DH: Pak Billy
- OA Area 2 — DH: Pak Yudi
- OA Area 3 — DH: Bu Puji Astutik (tanpa Area Specialist)

Pembagian area bukan berdasarkan wilayah geografis, tapi berdasarkan kelas cabang agar tiap area menangani kelas yang sama rata.

**Jumlah Cabang per Kelas**
| Kelas | Jumlah |
|---|---|
| A | 8 Cabang |
| B | 3 Cabang |
| C | 25 Cabang |
| D | 39 Cabang |

## 9.2 ADMIN OA

### Fungsi & Alur Admin OA

Admin OA = gerbang masuk pertama untuk semua kebijakan dari cabang yang di luar wewenang BOH. SLA: 2 jam (hari yang sama)

**Alur:** Cabang kirim memo ke Admin Area → Admin cek (2 jam) → Deliver ke Area Multitasking → PIC Multitasking analisa → Jika revisi → kembali ke cabang → Jika sesuai → Privy approval DH & DD

Area 3 tidak punya Admin sendiri → bebas kirim ke Admin Area 1 atau Area 2

**Yang Diperhatikan Admin saat Review:** Isi memo tidak terlalu berbelit; Apakah diatur oleh SK atau belum; Format lengkap atau tidak; Masuk akal atau tidak; Lampiran sudah lengkap atau belum

### 3 Kategori Pengajuan dari Cabang

**1️⃣ Pengajuan Terkait Konsumen**

*Waive Denda (di Operation)*
| Nominal Denda | Approver | Maks Waive |
|---|---|---|
| 0 – 1 juta | BOH | 20% |
| 1 – 5 juta | DH | 30% |
| 5 – 50 juta | DD | 50% |
| ≥ 50% denda | BOD | Sesuai BOD |

BOH cuti → naik satu tingkat ke DH. DH cuti → naik ke DD.

*Refund Dana:* Paling sering: refund angsuran terbayar double. Kasus PT: biasanya punya 5–10 kontrak, bayar via 1 no kontrak → disuruh refund. CEK ke FSM/Financore apakah benar-benar sudah bayar. Dokumen: Form Refund Dana + KTP + Mutasi rekening + Keterangan/alasan + TTD Konsumen

*BBNNK (BPKB Balik Nama Non-Konsumen):* Syarat usia: <21 tahun → persetujuan DD · ≥21 tahun → persetujuan naik ke BOD. Dokumen: KTP konsumen + KTP tujuan BBN + KK konsumen + KK tujuan BBN + STNK. Biaya: Birojasa + PKB (lihat di STNK) + Fidusia (Adendum, tergantung OSAR tiering). Setelah BBN → BPKB diblokir lagi agar tidak duplikat

*PPDJ (Permohonan Pengambilan Dokumen Jaminan)*
| Jenis PPDJ | Keterangan |
|---|---|
| Regular | Konsumen lunas normal |
| WO dengan SKL | Approval DD |
| WO tanpa SKL | Approval DH OA |
| Ahli waris | Surat kematian + KK + surat kuasa |
| Dikuasakan (LN) | Konsumen di luar negeri → surat kuasa |
| Via Vidcall | Form Vidcall + screenshot vidcall + bukti chat + Surat Kuasa |

*Permohonan Update Konsumen:* Update data diri → Approval DH OA → kirim ke FSM (update by system). Maintenance data jaminan → Approval DD → kirim ke cabang (update di Drone). Aplikasi DRONE: hanya digunakan OA jika BOH cuti; link dengan Financore (hanya view)

*Revisi BPKB:* Approval: DD. Revisi yang dilakukan: sumbu (bagian dari kendaraan). Dokumen: Memo + BPKB + Surat dealer → dikirim ke BPKB Admin

**2️⃣ Pengajuan Terkait Karyawan — Detasering**
- Untuk TL dan BOH
- Single boleh pulang 3 bulan sekali
- Jarak berdasarkan tempat rekrutmen (bisa disimpangkan jika lebih dekat ke domisili)
- Dapat uang kost yang masuk ke gaji (dibedakan kota khusus vs non-khusus)
- Wajib ada bukti bayar kost
- Jika sudah menikah dan bawa keluarga → bisa ajukan kontrakan (perlu surat administratif HR)
- Luar pulau: reimburse cargo maks Rp 3 juta, dalam pulau: setengahnya
- Approval: DH (berapapun nominal detasering)

**3️⃣ Pengeluaran Biaya Umum Operasional**
- Tagihan kurir vendor (JNE diblacklist — kasus BPKB hilang)
- Tagihan service, kebersihan, keamanan, dll
- Masa expired kwitansi: 55 hari
- Pengajuan biaya cabang via E-GER → pencarian oleh FSM/Procurement

**Wewenang E-GER**
| Nominal | Approver |
|---|---|
| 0 – 500 ribu | BOH |
| 500 ribu – 1 juta | DH |
| >1 juta | DD |

Advance vs Non-Advance: Advance = minta reimburse dana di depan, maks 14 hari kerja untuk pertanggungjawaban (lewat → potong gaji + SP). Non-Advance = reimburse biasa setelah bayar.

## 9.3 AREA SPECIALIST

### BORC (Branch Operational Risk and Control) — Cabang Kelas D

BORC = setara OQA tapi untuk cabang kelas D. Dilakukan oleh Area Specialist.

**Sampling BPKB:** Minimal 50% BPKB yang ada di cabang; Cover Note: minimal 30%; Dilakukan 2x setahun; Cek kesesuaian antara fisik, sistem, dan faktur; Barcode sticker BPKB di-scan → muncul no kontrak (untuk memudahkan stock opname)

**Saat Kunjungan (5 Hari Kerja):**
- Hari 1–4: Minta dokumen pelengkap per unit kerja, sampling BPKB + CN, Stock Opname Petty Cash
- Hari 5: Buat draft hasil pemeriksaan sementara → diskusi dengan BOH → hasil diskusi: Saran & Drop, cek CCTV

**Petty Cash**
| Jenis | Nominal (Kelas D) |
|---|---|
| Petty Cash Reguler | Rp 5.000.000 |
| Petty Cash Service (AC, dll) | Rp 1.500.000 |
| BDC (penutup kekurangan/kelebihan) | Rp 200.000 |

**Alur Pasca Kunjungan:** Draft final di-email ke cabang → cabang beri tanggapan (SLA 5 hari kerja); Susun Laporan Hasil Kunjungan (approval DH + DD); Email ke cabang untuk bukti perbaikan + laporan tindak lanjut (SLA 1 bulan); Laporan BORC ke DH dulu, baru ke DD

**CCTV:** Pengecekan CCTV: ambil beberapa tanggal acak sebelum 30 hari (retensi 30 hari, setelah itu dihapus); Cek apakah CCTV nyala dan ter-record; Download ke USB; Area yang dicek: ruang operation + brankas

### KPI Cabang (Tahunan)
- Setiap awal tahun: buat KPI Cabang
- Penilaian: Semester 1 + Semester 2 (tengah tahun + akhir tahun)

**KPI Wajib dari HR (5 Komponen):** Coaching; SELLA (sistem evaluasi); Kaizen; 4DX; 5R

**KPI Cabang:** Nilai PM → dikeluarkan OSD, diolah OA. Ada tiering nilai dan bobot (contoh: >98 = 120%, 91–98 = 100%); Nilai Audit → Sangat Baik (A) = 120% pencapaian; Nilai OQA → masuk ke PM

Jika KPI bagus → penghargaan cabang terbaik. Jika jelek → bisa tidak dapat bonus/insentif atau ada mutasi.

### MIKOR & KOAR

Minimal 3x per semester · Ada notulen yang di-input di Jotform (jadi penilaian)

**MIKOR:** Meeting Koordinasi tiap Cabang dengan Marketing dan ASR. Ada notulen yang di-input di Jotform

**KOAR:** Zoom Meeting antara OA dan Cabang. Dibagi kelompok: isi 3 TL dari cabang berbeda. Kelompok siapkan materi presentasi (bebas: kendala cabang/knowledge cabang). Tiap bulan sekali ada KOAR

### Proses Over Kredit & Update Data via Drone

**Over Kredit (Ganti Konsumen):** Konsumen ke cabang (IDEP TTD + KTP) → Cek SLIK konsumen baru oleh OA (gen SLIK by Excel → upload → Approved DH OA) → Analisa BOH (cek kredit berjalan, angsuran <30% penghasilan) → Keputusan di BOH

SLIK yang diambil: calon konsumen baru + pasangannya. Perlu Form Permohonan SLIK + TTD + Copy KTP (pemrosesan data pribadi)

**Update Data via Aplikasi DRONE:** Dilakukan jika BOH cabang sedang cuti. Drone link dengan Financore (hanya view). Data yang bisa diubah: data kendaraan (warna, noka/nosin, nopol, nama STNK) dan no BPKB. Approval: DH OA. Setelah approve → perubahan data dilakukan oleh cabang masing-masing unit (Asuransi, BPKB Admin, dll)

## 9.4 AREA MULTITASKING

### Fungsi Multitasking & BASO/BAST

**Fungsi Utama:** Penggantian MPP cabang (CS, AMB, AMAF) selama 1–6 bulan menunggu rekrutmen HR. Termasuk cabang motor yang bergabung dengan BCAF. Ada report ke DH terkait kondisi real cabang + kendala di lapangan

**Jobdesc Lainnya:** Analisa memo yang dideliver dari Admin OA (SLA 2 jam sampai approval DH/DD); Pengecekan BASO + BAST

**BASO (Berita Acara Stock Opname):**
- Dilakukan 1 tahun 2 kali
- Dilakukan juga jika ada pergantian AMAB (Docust) atau AMAF (BPKB Admin)
- SO Fisik: Tembak barcode BPKB
- SO Detail (2 tahun sekali): Cek Faktur + NIK + SPH + SP konsumen + Form A
- Jika BPKB >1.500 → cabang laporkan ke KP. Jika <1.500 → OA yang datang ke cabang
- Ada saksi pembuatan Berita Acara

**BAST Jabatan:** Dilakukan jika ada mutasi pejabat

**Format Penugasan (Setelah Selesai):** Aktivitas yang dilakukan; Uraian masalah di cabang; Usulan perbaikan; Jumlah CN dan BPKB di cabang; Jumlah brankas + anak kunci; Daftar rekanan (birojasa + notaris); Pending Meter (on-progress seperti pengajuan birojasa); Kondisi umum cabang; Daftar kunci kantor cabang; Approval DH dan DD Operation

### Lain-lain OA — Pemindahan Cabang & Issue

**Pemindahan Cabang (Pindah Gedung):** GS cari gedung sampai dapat; Meeting OA + GS → OA usulkan budget untuk pemindahan BPKB + covernote; Memo dari OA: budget premi BPKB + mekanisme pemindahan; Seluruh BPKB yang keluar dari BCAF wajib di-cover asuransi kehilangan; BPKB packing dalam karsud → dibawa BOH dengan mobil operasional atau vendor; Pengiriman BPKB didampingi polisi

**Alur Waive Denda di Operation:** Konsumen buat surat permohonan (free format) → BOH lihat kewenangannya → Input di aplikasi Waive Denda oleh CS → Approval pejabat berwenang

**Issue di OA (Masalah yang Masih Ada):** Register masih manual; CCTV belum bisa diakses dari KP; Rekonsil BPKB banyak dan ribet (ada yang borrow, sedang dikirim, sudah release) → masih manual

Jabodetabek: BPKB disimpan di KP (pusat), cabang hanya simpan yang reservasi. Di luar Jabo: BPKB disimpan di cabang masing-masing.

Biaya titip BPKB Rp 5.000/hari mulai hari ke-61 pelunasan. Untuk yang sudah close ET → sebelum jam 14.00 bisa dikirim besok.

**Reverse Disburse — Batal Realisasi:** Sudah cek absah tapi konsumen batal → CMO yang bayar lewat rekening ke BCAF. CMO nagih ke konsumen (pengaruh ke konsumen kalau batal tidak ada, tapi dikasih tau CMO bahwa batal ada biayanya)

**TTBJ (Tanda Terima Barang Jaminan) — Ambil BPKB:** Jika WO: harus ada memo recovery (dengan SKL/tanpa SKL) + Bukti bayar. Bisa dikuasakan: surat kuasa + KTP + Video call (jika konsumen di luar negeri). Ahli waris lebih dari 1 → semua harus datang; yang tidak bisa datang pakai surat kuasa

Rekap insentif dikirim dari cabang ke Admin Area (untuk monitoring dan penilaian)

---

# 10. OSD — OPERATION SUPPORT & DEVELOPMENT

OSD mendukung proses Operation melalui: **Support Data · Monitoring Performance Cabang · Pengembangan Sistem · Improvement Proses Kerja**

## 10.1 MONITORING PERFORMANCE CABANG

### Penilaian SDM (People)

**Test Prosedur Pejabat:** Peserta: minimal TL, maksimal UH/BOH; KKM: 90 untuk 20 soal; Waktu: pertengahan bulan setiap 6 bulan sekali; Pengaruh pada KPI individu jika tidak memenuhi nilai

**Test PPK (Product Process Knowledge):** Peserta: semua staff termasuk outsource + Authorized Signer + Analis; KKM: 85 (tahun 2022); Frekuensi: 6 bulan sekali; Tujuan: mengembangkan PPK karyawan + menciptakan nilai "Terpercaya"

### Skala & Kriteria Penilaian PM

**Skala Penilaian**
| Peringkat | Nilai |
|---|---|
| A (Sangat Baik) | ≥ 90.01 |
| B (Baik) | 80.01 – 90 |
| C (Cukup) | 70.01 – 80 |
| D (Perlu Perbaikan) | ≤ 70.00 |

**6 Kriteria PM (Performance Management)**
| Kriteria | Isi |
|---|---|
| a. Optimized SLA & Quality | CN Overdue, SLA order asuransi, SLA order birojasa (STNK/BPKB) |
| b. Enhance Control & QA | Report Management + hasil checklist OQA + BORC/OA (kelas D) |
| c. Increase Employee Capacity | Hasil Test PPK + Test Prosedur Pejabat |
| d. Customer Satisfaction Index | Hasil survey konsumen (ada gift per kuartal) |
| e. Cleaning Day | 5R dari GS (Ringkas, Rapih, Resik, Rawat, Rajin) |
| f. Transformasi Layanan Digital | Scan dossier asli + Sign up Fina + Pengurangan walkin |

**Target Transformasi Digital:** Upload Scan Dossier Asli: KP + Surabaya H+6 dari realisasi · Cabang lain H+3; Upload Scan BPKB: Target 85% (tahun 2023); Pengurangan Walkin: Pembayaran angsuran 0.2% defect · Pengurusan STNK/BPKB 0% defect · ET 0% defect (kecuali ASR, Multiguna, SHF)

Survey konsumen: tiap awal dan akhir kuartal ada gift. Permohonan gift harus TTD: Deputy Director + DH OSD + DD Bisnis Development.

## 10.2 SUPPORT DATA

### Jenis Data yang Dikelola OSD
Exception Report; Performance Report; CN Overdue; Monitoring BPKB; Data Fidusia; Hasil Test PPK; Data Asuransi; KPI Operation

- OSD dapat melakukan visit ke cabang jika ada temuan audit atau perlu tindak lanjut dari hasil meeting
- Pemekaran/penurunan kelas cabang: dinilai berdasarkan performance management, review 1x/tahun
- Implementasi IOM ke cabang: review 1 bulan setelah implementasi · Untuk tools baru: sosialisasi cara penggunaan terlebih dahulu

### Exception Report — Alur & Tujuan

Tujuan: Mencegah kerugian perusahaan dan mengurangi komplain konsumen akibat kesalahan input data operasi

**Alur:** OSD Dept olah exception report → Kirim harian ke function owner masing-masing unit (KP, OA, Cabang) → OA tindak lanjut di unit kerja terkait → OA lapor ke OSD (rekap bulanan, maks H+3 awal bulan) → OSD analisa → indikator PM + pengembangan exception report

**Isi Laporan Tindak Lanjut dari OA**
| Kolom | Isi |
|---|---|
| Tanggal Tindak Lanjut | Kapan ditindaklanjuti |
| PIC | Nama yang menangani |
| Hasil Investigasi | Contoh: "Data sudah sesuai / penyimpangan karena salah input" |
| Tindak Lanjut | Contoh: "Di-maintenance datanya / di-pending sampai diselesaikan" |

## 10.3 PENGEMBANGAN SISTEM & PROSES

### Contoh Pengembangan yang Dilakukan OSD

**Pengembangan Aplikasi/Sistem:** Pengajuan waive denda di JogetDX; Pengiriman kelebihan dana di JogetDX (contoh: urus STNK DP Rp 5 juta, terpakai Rp 4.5 juta → sisa Rp 500 ribu dikembalikan); RPA untuk received PPK + borrow BPKB (UIPath) dengan menu Collateral Tracking di SigmaFinance; Pengajuan User ID via JogetDX user maintenance

**Pengembangan Proses:** BPKB Showroom bisa diantar oleh Birojasa (diatur SLA, pembayaran, ketentuan wanprestasi birojasa); Alur distribusi BPKB Showroom: Showroom order → Marketing → Operation → konfirmasi konsumen + PIC Showroom → kirim BPKB via birojasa sesuai surat kuasa → birojasa terima + kirim ke showroom; Terlibat dalam project improvement, UAT (User Acceptance Testing), evaluasi implementasi via PIR (Post Implementation Review)

### Pendelegasian Wewenang & Pembuatan Memo

**Pendelegasian Wewenang:** Contoh: tour reward, acara yang melibatkan pejabat operation. Tugas pejabat didelegasikan sementara ke TL (bisa 1 TL atau lebih, sesuai departemen). Mencakup: persetujuan, penandatanganan, pengambilan keputusan (berdasarkan memo delegasi)

**Pembuatan Memo (Mengatur Kebijakan Cabang)**

Sumber Pembuatan Memo: Pengajuan dari atas ke bawah atau bawah ke atas; Temuan audit → dibuat memo regulasi; Membuat target untuk penilaian PM: survei konsumen + realisasi capaian + temuan exception report

**Struktur Memo:**
1. Nomor memo
2. Unit yang ditujukan + CC (tembusan) ke unit terkait
3. Unit pembuat memo
4. Perihal/Judul
5. Label (kategori)
6. Referensi memo-memo terkait (jika ada)
7. Flow pelaksanaan memo
8. Approval: DD Operation + DH OSD + Direktur
9. Lampiran

### Lain-lain OSD

**Penentuan Kelas Cabang:** Ditentukan oleh OQA (berdasarkan load kerja + jumlah MPP), tapi di-review juga sama OSD

**Outsource:** Jakarta/Surabaya/Bandung (2022): dari borongan kerja PT Exa Mitra, unit: Asuransi, Legal Admin, Fidusia Admin; Jasa Layanan Pengantaran BPKB (2023): vendor PT Abacus Dana Pensiuntama; KP biasanya pakai vendor untuk kirim dokumen antar unit; Kantor Cabang biasanya pakai messenger sendiri

---

# 11. OQA — OPERATION QUALITY ASSURANCE

Fungsi: mitigasi risiko operasional dan kepatuhan terhadap prosedur kerja cabang. Dasar hukum: **IOM No. 001 Tahun 2023** mengatur bobot penilaian checklist operation.

## 11.1 Man Power & KPI Staff OQA

**Komposisi Tim:** 2 Specialist; 1 Head; 2 Staff

**KPI Staff OQA:** Total cabang yang dikunjungi; SLA laporan hasil pemeriksaan (release); SLA laporan passive (tanggal 15 setiap bulan); Setiap orang OQA wajib jadi Team Leader tiap tahun; Pemeriksaan laporan tindak lanjut cabang; Nilai ikut test prosedur dari OSD; Lain-lain (4DX, Kaizen, dll)

## 11.2 HAL YANG DIPERIKSA

### 3 Area Pemeriksaan OQA
- Data dan Dokumen: Kelengkapan, kesesuaian isi, format standar
- Rekaman CCTV: Sampling 2 hari · Retensi cabang 2 bulan / KP 3 bulan
- Tes Pemahaman Prosedur (PUT): Process Understanding Test, untuk knowledge staff cabang

### Contoh Temuan di Cabang
| Unit | Temuan | Seharusnya |
|---|---|---|
| App Admin | Form CP tidak di-TTD BM | Wajib TTD Branch Manager |
| App Admin | Nosin di faktur & BPKB berbeda | Pastikan sesuai sebelum input sistem |
| Insurance Admin | Input aktivitas klaim TLO tidak konsisten | Update setiap ada aktivitas klaim |
| Insurance Admin | Beda tanggal terima dokumen awal klaim CP di register vs sistem | Harus sinkron |
| AM Admin Front | Biaya STNK/BPKB tidak sesuai PKS | Cek PKS yang disepakati |
| AM Admin Front | Ada biaya cek absah/blokir yang tidak sesuai PKS | Pejabat wewenang harus cek ulang |
| Customer Service | Update register STNK/BPKB tidak sesuai | Update realtime sesuai ketentuan |
| CS Transaction | Buku register aktivitas brankas tidak realtime | Isi langsung saat transaksi |
| Support Function | Barang elektronik tidak terpakai di gudang | Harus ditindaklanjuti/dimusnahkan |
| Umum | Barang tidak terpakai di ruang server | Bersihkan ruang server |
| CCTV | Staff sharing User ID (dengan persetujuan) | Tidak boleh sharing User ID |
| CS Transaction | Cash diterima tanpa cek dengan lampu UV | Wajib cek keaslian uang |

## 11.3 BOBOT PENILAIAN

### Bobot Penilaian Checklist Process & Umum

**Checklist Process:** Pemeriksaan proses kerja (sesuai SK/SE/IK/IOM); Pengerjaan PUT (Process Understanding Test); Pemeriksaan CCTV (retensi: cabang 2 bulan/KP 3 bulan)

**Checklist Umum:** Pembuatan insentif; Komunikasi antar unit; Matriks rumah tangga (kebersihan/kerapian); Pengelolaan umum; Pemeriksaan CCTV (umum)

Penentuan bobot/kategori penilaian = hak prerogratif OQA, berdasarkan temuan sebelumnya. Biasanya diperbarui setiap tahun.

**Faktor Pengurang Nilai:** Temuan checklist process yang berulang; Temuan pemeriksaan CCTV yang berulang; Temuan audit yang berulang

Tidak ada nilai minimum di OQA — yang menggunakan nilai adalah OSD dan OA, terserah mereka mau diapakan hasilnya

## 11.4 ALUR KERJA OQA

### Alur Kerja Tahunan

Awal tahun: tentukan 20 cabang prioritas (1 cabang 1x/tahun) → Tentukan anggaran akomodasi → Koordinasi dengan Audit (atur jadwal agar tidak bentrok) → Kunjungan 5 hari (dalam 1 bulan ada 2x kunjungan) → Laporan dalam 60 hari → Tindak lanjut cabang maks 30 hari

**Jadwal Kunjungan 5 Hari:** Senin–Kamis: Pemeriksaan dokumen, sampling BPKB, PUT, cek CCTV; Jumat: Diskusi hasil temuan dengan BOH, buat draft sementara

Kunjungan ke cabang bersifat mendadak — cabang harus bisa siapkan data dengan cepat

**Tindak Lanjut Cabang:** Maks 30 hari dari tanggal terima laporan hasil pemeriksaan. Bisa diperpanjang dengan kirim email + alasan yang jelas (contoh: sedang expo)

**Kondisi yang Bisa Mengubah Rencana Kunjungan:** Perintah dari atasan; Mutasi cabang (disetujui Pak Frans DD); Ada kasus audit yang minta dicek OQA terkait prosedurnya

### Passive Checklist
- Pemeriksaan atas semua data dari cabang yang diolah di KP (tanpa kunjungan)
- Berlaku untuk semua kelas cabang A–D
- Dilakukan 2 tahun sekali (karena prioritas adalah kunjungan cabang)
- Tujuan: cek data penting agar temuan bisa segera diperbaiki

### Hal-hal Penting & Perbedaan OQA vs Audit

| | OQA | Audit |
|---|---|---|
| Fokus | Penilaian atas procedural flow (sesuai SK/SE/IK/IOM) kerja cabang operation | Pemeriksaan atas risiko dari setiap aspek yang rawan menimbulkan fraud |
| Output | Rekomendasi perbaikan (bukan sanksi) | — |
| Posisi | Langsung di bawah DD (independen) | Jadwal dikoordinasikan dengan OQA agar tidak bentrok |

**Pembagian Kelas Cabang yang Diperiksa**
| Kelas | Diperiksa oleh |
|---|---|
| A, B, C | OQA (kunjungan langsung) |
| D | BORC (bagian dari Operation Area) |

BORC dan OQA tidak bisa merger karena beda kepentingan (OQA harus independen)

**Ketentuan Kunjungan per Kelas:** Cabang C: 4 orang yang kunjungan; Cabang A & B: 5–6 orang (pinjam orang jabatan Specialist ke atas); Proses di cabang A belum tentu ada di cabang B/C → nilai N/A jika tidak ada prosesnya

**CCTV:** CCTV cabang hanya bisa diakses di cabang (server KP tidak kuat jika remote); Sampling CCTV: 2 hari (pilih acak); CCTV yang dicek: ruang kerja operation + ruang dossier; Pemeriksaan CCTV KP: 1 tahun sekali; Yang ada unit operation saja — UOB dan WTC tidak ada pemeriksaan CCTV KP

**Kolaborasi dengan Audit:** Atur jadwal agar tidak bentrok; Cek hasil temuan audit: jika belum fix saat OQA kunjungi → kurangi nilai

---

*— Akhir Part 3 dan akhir dari Operation Manual BCA Finance (3 bagian lengkap) —*

# OPERATION MANUAL — BCA FINANCE (PART 1 dari 3)

> Mencakup: **CS (Customer Service)** · **Customer Care** · **CS Digital (CSD)** · **Central Disburse Motor**

---

# 1. CS (CUSTOMER SERVICE)

CS terbagi menjadi 5 bagian: **CS Front**, **CS Back**, **QC / CS Pengiriman**, **Analyst**, dan **Authorized Signer**.

## 1.1 CS FRONT

### Jenis Pelayanan CS Front
- ET Walk In (Pelunasan Dipercepat)
- Bea Balik Nama (BBN) + Perpanjangan STNK
- SKPS (Surat Keterangan Perpanjangan STNK)
- Pengambilan BPKB non-reservasi — untuk: Lansia, Disabilitas, Rekanan Showroom, BCA Prioritas & Solitaire, Eskalasi TL/Atasan, Ahli Waris
- Asuransi (Klaim kendaraan, Klaim jiwa, Refund asuransi, Upgrade)
- Permohonan Pengembalian Kelebihan Dana (PPKD)
- WAIVE (Biaya titip BPKB dan denda)

**SLA CS Front**
| Layanan | SLA |
|---|---|
| SKPS / FC BPKB | 5 menit |
| ET Walk In | 10 menit |
| Pengambilan BPKB | 12 menit |
| OVK, Reschedule, Refund Asuransi, dll | 15 menit |

### Syarat Ambil BPKB oleh Ahli Waris
Syarat umum: KTP Asli semua ahli waris yang masih berlaku.

| Usia Ahli Waris | Dokumen | Catatan |
|---|---|---|
| < 17 tahun | Akta Lahir | Gunakan **Surat Pernyataan Wali** (bukan surat kuasa) |
| 17 – 21 tahun | Akta Lahir + KTP | Gunakan **Surat Pernyataan Wali** (bukan surat kuasa) |
| > 21 tahun | Akta Lahir + KTP | Gunakan **Surat Kuasa** |

**Syarat Ambil BPKB Langsung Tanpa Reservasi (Jabodetabek)**
- SLA: 30 menit – 1 jam
- Kategori yang bisa langsung ambil: Showroom, Lansia, Nasabah Prioritas/Solitaire, Ahli Waris, Eskalasi dari Atasan

### Global Proses CS Front
Flow: Security Cek → ASTARI (input antrian) → Qmatic (nomor antrian) → CS Front Layani

**SLL (Sistem Level Layanan)**
- 🟢 HIJAU — Kondisi normal, SLA terpenuhi
- 🟡 KUNING — Antrian mulai padat, perlu perhatian
- 🔴 MERAH — Antrian over, butuh eskalasi segera

**Verifikasi KTP**
- Gunakan KTP Reader (scan sidik jari) untuk verifikasi identitas konsumen
- Jika KTP tidak terbaca → gunakan SIM sebagai pengganti

### 1️⃣ ET Walk In (Pelunasan Dipercepat)
Hanya bisa dilakukan oleh **debitur atas nama**. Selain debitur harus menggunakan kuasa.

**Alur:** Konsumen Walk In, minta nopol/nama debitur → Cek data Financore (angsuran berjalan) → Simulasi ET (Financore & Aplikasi Gabungan — nilai harus sama) → Print lembar detail ET, TTD TL Front → Generate VA (Aplikasi Gabungan) → Konsumen Bayar → CS Close di Financore → Konsumen tunggu ambil BPKB 30–60 mnt

**Cut-off jam 12.00** — Kenapa jam 12? Karena cut-off JF/SF jam 14.00, jadi perlu jeda 2 jam untuk proses.

**Biaya:** Ada biaya pinalti ET dan biaya admin (dari DMS → dossier asli kontrak konsumen)

**Engine ET (Robot ET)**
- Robot yang otomatis proses close account di Financore
- Syarat: nominal harus sama persis antara Aplikasi Gabungan dan Engine ET
- Jika gagal dari sisi IT → akan ada email pemberitahuan untuk diproses manual

### 2️⃣ BBN + Perpanjangan STNK

**Dokumen yang Diserahkan Konsumen**
- STNK asli
- KTP asli (ditahan sampai STNK/BBN selesai)
- Copy KK
- Foto gesek Noka dan Nosin — hanya jika STNK mati (perpanjang tahunan tidak perlu)

**Alur:** Cek data di Financore → Buat form simulasi BBN/STNK, print → TTD TL + TTD konsumen → CS create VA, konsumen bayar → CS buat OTTPSB (4 lembar)

**OTTPSB — 4 Lembar**
| Warna | Untuk |
|---|---|
| Putih | BPKB Admin |
| Pink | CS |
| Kuning | Konsumen (selama proses berlangsung) |
| Hijau | Birojasa |

Alur dokumen setelah OTTPSB: CS → Birojasa → Samsat → STNK kembali ke BPKB Admin → CS → Disimpan AS. Untuk DKI proses memakan waktu ±5 hari.

Konsumen bisa mengurus sendiri di SAMSAT dengan SKPS + copy BPKB yang dilegalisir oleh CS (bisa juga download di FINA).

**Surat Kuasa ke Birojasa:** CS membuatkan surat kuasa bermaterai atas nama konsumen kepada birojasa untuk mengurus perpanjangan/BBN

### 3️⃣ Pengambilan STNK / BPKB (Output Proses BBN)
- CS konfirmasi nama konsumen
- Konsumen menyerahkan slip kuning dari OTTPSB
- CS fotocopy KTP konsumen
- CS mengambil form konfirmasi STNK, cek ada kelebihan dana atau tidak, nopol, STNK asli
- CS informasikan konsumen terkait kelebihan dana (jika ada) → konsumen TTD slip kuning
- Jika kurang bayar: konsumen harus bayar kekurangan sebelum ambil STNK/nopol
- Konsumen akan dihubungi dan direminder via WA bila STNK/BBN sudah selesai.

### 🔖 SKPS (Surat Keterangan Perpanjangan STNK)
Surat keterangan yang diterbitkan untuk membantu konsumen melakukan perpanjangan STNK apabila BPKB masih berada di BCA Finance.

**Alur:** CS verifikasi data konsumen → Jelaskan biaya materai → Create VA (Aplikasi Gabungan) → Konsumen bayar → Buat SKPS di Financore → Ambil copy BPKB di DMS (legalisir) → Kirim/serahkan ke konsumen

Konsumen bisa mengurus langsung ke SAMSAT membawa SKPS + copy BPKB yang dilegalisir, atau bisa download di FINA.

### 4️⃣ Pengambilan BPKB
- CS minta nopol → cek kontrak di Financore
- CS konfirmasi nama dan unit kendaraan
- CS minta KTP asli → validasi dengan KTP Reader
- CS konfirmasi angsuran sudah selesai dan kisaran angsuran per bulan
- CS buat PPDJ (Permohonan Pengambilan Dokumen Jaminan) → konsumen TTD
- CS fotocopy KTP asli
- Jika KTP tidak terbaca: minta SIM asli, foto konsumen memegang KTP+SIM
- CS mengarahkan konsumen ke konter Docust (counter no. 10–13)

### 5️⃣ Dikuasakan

**Dokumen yang Diperlukan**
- Surat kuasa format BCAF bermaterai (jika tidak sesuai format, bisa tetap diproses dengan deviasi ke UH)
- KTP Asli Pemberi Kuasa
- KTP Asli Penerima Kuasa (jika tidak ada KTP, boleh SIM atau paspor)
- PPDJ 2 lembar (kuning + putih) — isi: no kontrak, nama konsumen, nama pengambil, hubungan
- Screenshot KTP Reader → Word → Print (dokumentasi)

**Proses Konfirmasi di CS Back (Admin)** — CS Front membawa dokumen ke CS Back untuk konfirmasi melalui telepon kepada debitur:

| Tipe | Pertanyaan Konfirmasi |
|---|---|
| Sigma (no HP surat kuasa = Financore) | No HP sesuai sistem, nama penerima & hubungan, alamat, jenis+tipe+nopol, tipe angsuran, nama ibu kandung |
| Non-Sigma (no HP berbeda) | Semua di atas + nama istri/suami, tanggal jatuh tempo |

3 form konfirmasi: Perorangan (walk in) · Badan Usaha · Ahli Waris. Perorangan & ahli waris ditangani admin CS; Badan Usaha ditangani PIC Reservasi BPKB BU.

**Alur Setelah Konfirmasi:** Dokumen dari CS Front ke CS Back → Konfirmasi via Telp ke Debitur → Admin CS isi & registrasi form konfirmasi → Dokumen + form konfirmasi ke TL Front (cek ulang) → TL Front kirim ke Docust

**Penyimpangan (Tanpa Verifikasi Form):** Write Off, Lansia, Nasabah Prioritas BCA, Ahli Waris (tetap ada verifikasi tahap lanjut), Showroom, Disabilitas

Tawarkan SKL kepada konsumen: jika iya, dikenakan biaya Rp 10.000

### 6️⃣ PPKD (Pengembalian Premi / Kelebihan Dana)
- Form PPKD diisi konsumen
- Bukti bayar dilampirkan
- FC KTP dan FC KK konsumen
- Proses ditangani CS dan diteruskan ke unit terkait

### 7️⃣ FC BPKB SAMSAT
- Konsumen butuh FC BPKB untuk keperluan SAMSAT (pajak tahunan dll)
- Surat keterangan leasing dari BCAF
- VA dengan materai diproses via Aplikasi Gabungan

### 8️⃣ WAIVE (Penghapusan Denda)

**Yang Bisa Di-Waive:** Denda keterlambatan; Biaya penyimpanan BPKB (Rp 5.000/hari, mulai H+61 setelah lunas)

**Alur:** Konsumen buat surat pengajuan Waive → CS analisa kemampuan konsumen → CS input di jogetDX (aplikasi waive) → Approval sesuai tiering → Jika approved → konsumen dihubungi via WA

**Batas Wewenang Approval**
| Nominal Denda | Approver | Maks % Waive |
|---|---|---|
| 0 – 1 juta | BOH | 20% |
| 1 – 5 juta | DH | 30% |
| 5 – 50 juta | DD | 50% |
| ≥ 50 juta / ≥ 50% | BOD | Sesuai keputusan |

Waive Bunga Berjalan: UH = max Rp 200.000 | TL = max Rp 100.000

- Konsumen harus lunas dulu baru bisa waive
- Waive bersifat pengajuan, tidak disarankan langsung — konsumen diupayakan bayar dulu
- Jika ada program special → otomatis waive 50% (input di jogetDX)
- Mau ET sekalian Waive → tidak bisa di CS, harus melalui Marketing

### 9️⃣ OVK (Over Kredit)

**Syarat OVK**
- Over kredit minimal 1 bulan sebelum JT selanjutnya
- Suku bunga dan ketentuan mengikuti yang terbaru
- Status rumah calon konsumen tidak bisa kontrak
- Usia maks calon konsumen: 64 tahun
- Cek SLIK — maks C1; C2 ovd <10 hari bisa diajukan tapi penyimpangan ke DD
- CS hanya menangani OVK individu–individu. Individu↔PT lewat Marketing.

**Dokumen Konsumen Lama:** FC KTP; Membayar angsuran terakhir + denda (jika ada); Kwitansi 1 lembar bermaterai TTD konsumen; FC STNK (berlaku sampai realisasi OVK)

**Dokumen Konsumen Baru**
| Jenis | Dokumen |
|---|---|
| Karyawan | Slip gaji, SK kerja, KTP, KK |
| Profesional | Izin praktik, bukti penghasilan, KTP, KK |
| Wiraswasta | SIUP/TDP, laporan keuangan, KTP, KK |

Copy rekening koran 3 bulan terakhir (semua jenis konsumen)

**Proses Walk In:** Konsumen & calon konsumen datang ke CS → Cek SLIK calon konsumen → CS isi FAO (interview, DSR, pekerjaan, pendapatan, status kerja, sektor ekonomi, riwayat restruktur, data kendaraan) → Analisa lebih lanjut → Tolak → email konsumen / Setuju → upload ke PDP → approval komite kredit → kontrak baru → TTD

Biaya admin ada tiering dilihat dari OS AR. Kalau OVK individu ke badan usaha → melalui CMO (Marketing), hitungan tetap dari CS.

### 🛡️ Klaim Asuransi
**Alur:** Konsumen/ahli waris isi form klaim asuransi → CS cek kelengkapan dokumen (K1, K2, dll) → Catat dokumen yang ada & yang belum → TTD CS → Dokumen dibawa messenger ke unit Asuransi

### 💰 Refund Asuransi
**Dokumen yang Diperlukan:** Form permohonan refund (isi oleh konsumen); FC KTP; Cover buku tabungan; TTD konsumen + materai

**Alur:** Konsumen isi form permohonan refund → CS TTD form permohonan refund → CS cek status di Financore: harus Closed ET Released → TTD TL → Dokumen dibawa messenger ke unit Asuransi

### 📋 Tugas Tambahan CS Front (Setelah Layanan)
- Pengiriman data angsuran fisik ke perusahaan
- Rekap STNK (new / sudah jadi) harian
- Balancing akhir hari (kas, VA, dokumen)
- Balas pesan CRM Lite

## 1.2 CS BACK MOBIL

Mendapat sumber data dari nasabah yang telpon ke Halo BCA. Reservasi berlaku 14 hari kalender setelah order. Biaya penyimpanan Rp 5.000/hari setelah H+60. Batch I jam 11.00, Batch II jam 13.00. SLA H+2 setelah ticket masuk.

Status di CRM Lite: Assigned → Owned (setelah klik Done) → Done

### PIC 1: ET WPI (Pelunasan Dipercepat Walk-in)
**Input Sumber:** CRM (HaloCRMlite); Email; FINA (aplikasi konsumen); Titipan (dari cabang)

**Output:** Hardcopy Detail ET; Status Close di Financore

**Alur via Email:** SLA hari yang sama, Cut-off jam 14.00, 8 langkah proses (terima email → cek data → hitung ET → kirim VA → konfirmasi bayar → close Financore → simpan dokumen → update status)

**Alur via CRM:** SLA 2 hari kerja, Sumber dari HaloCRMlite

Catatan Khusus: Relaksasi/restruktur, overdue, Borrow BPKB, refinancing, BPKB belum jadi, KYC — masing-masing ada prosedur tambahan

### PIC 2: Order BU WPI (Badan Usaha — Mobil Jabodetabek & WPI)
**Sumber:** HaloBCA via HaloCRMlite

**Alur:** Buka CRM Lite, pilih workgroup Jabo → Cek laporan (nama, no kontrak, no HP, biaya, cabang, alasan) → Cek Financore — status wajib Closed, cek denda & biaya penyimpanan → Registry di Excel 'Order WPI' → Buat lampiran Word (data Financore, ID laporan, SS laporan + checklist gantungan) → Simpan ke folder sharing + PDF Excel → Tambah note di CRM Lite → klik Done → Kirim 4 file ke Docust via email

**Batch:** Batch 1: Maks jam 11.00; Batch 2: Maks jam 13.00 (termasuk order kedua jika sudah pernah reservasi tapi lewat masa)

**Checklist Gantungan (isi di lampiran):** STNK, Asuransi, akun Relaksasi, biaya titip ada/tidak, PDC

Jika dikuasakan: wajib ada form konfirmasi terlebih dahulu sebelum kirim ke Docust. Ahli waris: ada alur khusus dengan dokumen surat kematian + KK + surat kuasa

### PIC 3: Order Individu + BU (Non WPI / Mobil Non-Jabo)
- Non WPI: Email ke cabang terkait (BOH atau TL cabang). Rekap di Excel, dikirim jam 13.00.
- WPI Individu: Tarik dokumen rekapan dari CSD (CS Digital)
- Badan Usaha Non-WPI: PIC langsung infokan ke cabang via email, lampirkan dokumen umum (Akta pengurus, KTP pemberi & penerima kuasa, surat kuasa)

Cek status di hari H pengambilan: status Closed-Released di Financore = sudah diambil → ticket bisa di-close. Belum diambil → follow-up terus.

### PIC 4: Admin CS Back
**3 Form Konfirmasi:** Form konfirmasi perorangan (walk in); Form konfirmasi badan usaha (BU); Form konfirmasi ahli waris

**Konfirmasi via Telepon (Tujuan: Keamanan BPKB):** Verifikasi nomor HP sesuai sistem; Konfirmasi nama penerima dan hubungan dengan debitur; Alamat konsumen, jenis dan tipe kendaraan, nopol; Tipe angsuran, nama gadis ibu kandung; (Non-Sigma) + nama istri/suami, tanggal jatuh tempo

**Dokumen dari CS Front → CS Back (4 item):** Form PPDJ; FC KTP debitur + FC KTP penerima kuasa; Surat kuasa (sudah ditempel materai); Print KTP Reader

**Dokumen Dikembalikan ke CS Front (5 item):** Form PPDJ; FC KTP debitur + penerima kuasa; Surat kuasa; Print KTP Reader; Form Konfirmasi Konsumen

### 🌙 After Hour
Khusus untuk pengambilan BPKB di WPI.
- Telepon konsumen: informasikan wajib bawa KTP Asli saat pengambilan
- Jika ada note pengambilan dikuasakan → wajib verifikasi ke debitur sesuai form konfirmasi
- Tarik report di Reserve BPKB setelah jam 13.00 (Batch 2). Filter hanya KP dan U55.
- Telepon nasabah yang sudah reservasi tapi belum ambil
- Ticket dianggap close: konfirmasi via telepon + BPKB sudah diambil

**Order BPKB Hari Lain (Non H+1):** Buka aplikasi reservasi BPKB → Klik reservasi → Search by no kontrak/nopol → Isi: NIK, nama, tgl lahir, no HP konsumen & penerima kuasa, lokasi, tanggal → Jika dikuasakan → tambahkan data penerima kuasa

Form konfirmasi ditandatangani oleh CS Staff dan TL CS. Selalu bawa dokumen pendukung yang lengkap.

## 1.3 CS BACK MOTOR

Terbagi menjadi 2 PIC: **PIC Reservasi** dan **PIC Non-Reservasi**.

### CS Back Motor — PIC Reservasi
Input dari Halo BCA. SLA: 4–10 hari.

**Tempat Penyimpanan BPKB Motor:** Ciputat · Gresik · Solo · Bandung (berbeda dengan cabang mobil yang punya kluis masing-masing)

**Syarat Bisa Reservasi:** Status akun di FAST harus Close; Status collateral di FAST harus OHD (On Hand) dengan kode salah satu tempat penyimpanan

**Alur Reservasi:** Nasabah input ke Halo BCA → Data masuk CRM Lite → PIC regist di Excel → drop ke group nasional → Email ke cabang realisasi konsumen → Cabang input MOVE → Approval (TL Cabang / BOH Area / TL Docust Asal / Pejabat Area Solo) → PIC cek status collateral berkala

**Status Collateral:** In Transit (sedang dalam perjalanan); Release (sudah diambil konsumen → close ticket CRM Lite); OHD kode berubah (BPKB sudah berada di cabang baru)

Konsumen dihubungi oleh cabang. PIC regist di Excel setelah ticket close.

### CS Back Motor — PIC Non-Reservasi
Ticket di CRM Lite di-close ketika ada feedback dari cabang.

| Layanan | Cara Penanganan |
|---|---|
| Perbaikan Collect | Lempar ke cabang, cabang yang proses |
| Tanya status pengajuan | WA ke Marketing |
| Refund DP | Cabang yang urus, CS Back lempar saja |
| Klaim asuransi kendaraan | Cabang yang urus, CS Back lempar saja |
| Bayar denda belum masuk | Cabang yang urus, CS Back lempar saja |
| Tabel angsuran | Print → kirim email ke konsumen |
| Copy Kontrak | Input di MOVE → approval UH Archive + UH SPTD → Closed → Archive kirim copy kontrak |
| Reset FINA | CS Back bisa lakukan sendiri |

**Reset FINA (Detail):** FINA tidak bisa login karena data di sistem tidak sesuai data login. Penyebab: beda nama, beda NIK, beda tempat/tgl lahir, email berganti.

Alur: Cek data konsumen di aplikasi CMS → CS isi form pengkinian data (no kontrak, nama, NIK, data lama & baru, SS CMS) → TL approve → Informasikan ke konsumen bahwa reset selesai

## 1.4 CS PENERIMAAN DOKUMEN & QC PENGIRIMAN

Khusus dokumen kontrak untuk mobil. Cabang upload kontrak ke DMS, lalu masuk bucket verifikasi dokumen outstanding di CS Pengiriman. Kontrak dikirim ke konsumen H+15 hari setelah realisasi.

### QC Verifikasi Dokumen Kontrak
**Alur QC:** Login DMS → bucket verifikasi dok. outstanding → Input norekpin dari tarikan excel → muncul data → Lakukan pengecekan dokumen → OK → centang OK → save → set Excel OK

Not OK → centang Not OK → save → set Excel Not OK → kembali ke cabang untuk revisi → cabang upload ulang → di-QC lagi

**Item yang Dicek (10 poin):**
1. Norekpin di kontrak = di sistem
2. Stempel hari dan tanggal realisasi sesuai
3. Nama konsumen di kontrak = di sistem
4. TTD Kreditor (SPV/PIC dokumen kontrak)
5. TTD Debitur
6. TTD Pasangan Debitur
7. Materai ada
8. Estimasi tabel angsuran (TTD kreditur & debitur)
9. RIPLAY — ada 3 lembar TTD CMO dan debitur
10. Halaman pasal lengkap, kertas tidak terlipat/blur/sobek

Contoh yang ditolak: Kertas terlipat, TTD tidak ada, halaman hilang

QC pengecekan untuk Not OK berlaku hanya KP. QC nasional berlaku untuk semua cabang.

Di sore hari: buat rekap Excel Not OK + SS → kirim ke group. Sore hari juga buat reporting sendiri.

### Pengiriman Kontrak ke Konsumen
**Mekanisme Pengiriman:**
- Perorangan: Dikirim otomatis H+15 via email. Jika tidak ada email → WA.
- PT: Hanya via email (tidak via WA)
- Dokumen kontrak juga masuk ke FINA dalam 15 hari kerja
- Adendum → dikirim fisik menggunakan kurir SAP

**Alur Gagal Kirim:** 5x percobaan email → Gagal → 5x percobaan WA → Repeat (total >13x) → Konfirmasi ke CMO email terupdate → kirim manual via Outlook

Jika konsumen tidak mencantumkan no HP dan email → konfirmasi ke Marketing → Marketing request fisik → harus persetujuan konsumen (PDP) → Marketing bikin memo ambil kontrak fisik → approval sampai BM

**Adendum (SAP / Kurir Fisik):** Jika gagal dikirim = di-retur. Ditelpon 7x → jika diangkat baru kirim ulang.

### RETUR Dokumen
- Proses retur memakan waktu 1–2 minggu
- Konfirmasi ke konsumen maksimal 7x telepon
- Update di Financore + manual amplop
- H+1: kurir ambil dokumen retur
- H+3 sampai H+5: pengiriman ulang ke konsumen

## 1.5 ANALYST (CS)

Tugas utama: kumpulkan data → olah data → report ke manajemen. SLA: H+2 terima data cabang, H+5 laporan ke manajemen, H+10 laporan triwulan.

### Penarikan & Pengolahan Data
Semua cabang mengirim report maksimal 2 hari kerja awal bulan. Terlambat → berpengaruh pada penilaian OSD.
- Cabang dengan QMATIC → isi Google Form
- Cabang tanpa QMATIC → isi Spreadsheet

Data berisi jumlah konsumen dan layanan (1 konsumen bisa >1 layanan). Diolah menjadi laporan: Harian · Mingguan · Bulanan · Triwulan · Semester.

### 9 Report Bulanan
| Report | Tujuan | Keterangan |
|---|---|---|
| Walk In Cabang Nasional | OSD | Total konsumen & layanan dari Google Form + Spreadsheet |
| Pengiriman & Retur Dokumen PPK Nasional | OSD | Status pengiriman kontrak; pengiriman H+15 realisasi |
| Pengambilan BPKB oleh Showroom di WPI | OSD | Jumlah ambil BPKB oleh showroom (SHF/jual unit) |
| Permohonan Pengambilan BPKB WPI | OSD | Pengambilan reguler di WPI (termasuk Prioritas, Lansia, Disabilitas) |
| Laporan Keluhan | OSD | Tarikan CRM & PCC — total + kategori keluhan |
| Data Layanan Walkin vs Digital | CorPlan | Perbandingan layanan digital (AVA/FINA/Website/Astari/Email) vs walk in per cabang |
| Kebutuhan Kertas Walk In Nasional | GS | Estimasi kertas (1 konsumen ≈ 3–5 lembar) |
| Laporan Layanan Digital | OSD | Jumlah konsumen & layanan di 5 platform digital |
| Layanan Walkin vs Digital (versi detail) | OSD | Lebih detail dari yang ke CorPlan |

Deadline laporan bulanan: ke OSD maks tanggal 5 (H+5). Ke OSD final maks tanggal 10 (H+10).

### Laporan Triwulan & Semester
**Triwulan (ke Pak Gito / Manajemen):** Berisi seluruh 9 report bulanan; Mencakup cabang motor dan mobil; Manajemen meminta 3 keluhan terbanyak (kategori, perihal, pihak terkait, mitigasi); Deadline: H+10

**Semester (ke OJK):** Yang lapor ke OJK: Pak SAM (UH CC). Tugas PIC Analyst: hanya menyiapkan data untuk Pak SAM

**Kasus Layanan Terbanyak Nasional:** Pengambilan BPKB; Pelunasan Dipercepat (ET); Proses STNK BBN / Mutasi

14 cabang menggunakan QMATIC: Bandung, Bekasi, Bogor, Cilegon, Daan Mogot, Lampung, Malang, Medan, Pekanbaru, Semarang, Surabaya, Tangerang, WPI, WTC Mangga Dua.

## 1.6 AUTHORIZED SIGNER & KASIR

Perbantuan CS Front, CS Back, CC, dan CSD. Fungsi umum: monitoring OTTPSB, perbantuan BOH cabang, support dan administrasi. Ada fungsi help desk untuk cabang yang menanyakan proses kerja. SLA umumnya H+1, tidak ada target — service level saja.

### Authorized Signer — Tugas & Pengkinian Data
**Support:** Perbantuan CS Front, CS Back, CS Penerimaan; Helpdesk cabang (pertanyaan proses kerja); Delegasi dari OA (Operation Area); Perbantuan BOH saat cuti (misal: TTD ET/Waived)

**Pengkinian Data**
| Sumber Pengajuan | PIC Penanganan |
|---|---|
| Email | Email CC |
| Marketing | AS (Email AS) |
| Walk in | CS Front |
| Website | CSD |
| Walkin cabang | BOH Cabang |

Form pengkinian data (JABO only). Isi form: nama konsumen, tgl realisasi cabang, data lama & data baru, dokumen pendukung (misal: KTP terbaru).
- Setelah form di-approve TL → AS ubah di Financore → submit (tidak perlu approval lagi)
- Setiap hari AS narik report Financore untuk filing dan pengecekan kesesuaian
- CS hanya bisa update data konsumen; BPKB Admin yang update data kendaraan
- AS dapat tarik report perubahan data di Ginancore

**Salah Kait SLIK OJK:** 7 dokumen diperlukan (identitas konsumen + surat pernyataan + dll); 8 langkah alur penanganan; Memo penggantian 3 angka terakhir NIK; Approval: BOD

### Perpanjang STNK / BBN (AS sebagai Penyimpan)
**Alur Dokumen Perpanjangan STNK/BBN:** CS terima dok. (KTP, Surat Kuasa birojasa, bukti bayar) → CS create di sistem → masuk BPKB Admin → BPKB Admin kasih ke Birojasa → ke SAMSAT → STNK selesai → dikembalikan ke BPKB Admin → BPKB Admin serah terima ke CS → disimpan AS

**Yang Disimpan AS:** STNK · OTTPSB · Plat baru · KTP asli konsumen

**OTTPSB — 4 Lembar**
| Warna | Untuk |
|---|---|
| Putih | BPKB Admin |
| Pink | CS / PPKD |
| Kuning | Konsumen (ambil dokumen berharga) |
| Hijau | Birojasa |

CMO used car: salinan putih diserahkan ke APP terlebih dahulu untuk proses perpanjangan STNK jika pajak STNK mati.

**Pengecekan, Register & Pengambilan STNK:**
- Cek STNK jadi (masuk): register, cek nomor & nama kontrak, nopol, biro jasa, jenis proses, status released, dokumen
- Register STNK jadi: hitung dan catat biaya actual (ada yang sesuai, kurang, atau lebih dari DP awal). Reconfirm kelebihan/kekurangan, input juga di Financore.
- Pengambilan oleh nasabah: setelah proses selesai (est. perpanjangan 7–14 hari, mutasi ±3 bulan). Konsumen dapat email reminder otomatis dari IT (jika bermasalah, CS akan telepon manual).
- Balancing report harian & bulanan: STNK masuk vs keluar, cek Excel register dan Financore

Destroy STNK dan Plat: dilakukan jika BPKB sudah diambil lebih dari 1 tahun. Tidak ada biaya penyimpanan plat dan STNK.

### Tasklist BCA PRIO & Rekap Order
Order BPKB khusus nasabah Prioritas/Solitaire BCA.

**Alur:** Konsumen datang ke BCA Prioritas, isi form data kendaraan + lampir KTP (wajib konsumen sendiri, tidak bisa dikuasakan) → CSO input di aplikasi Tracking → approval Kepala Cabang PRIO → Data masuk bucket Tasklist AS → AS cek data & verifikasi (data pinjaman, gantungan STNK, TTD, NIK, dll) → Data valid → pilih "Lunas" → masuk bucket Docust → Docust kirim BPKB di sore hari (H+1) → BCA konfirmasi ke konsumen → Konsumen TTD BJ → masuk Docust → close di Financore

Cut-off: jam 11.00 pagi. Order di atas jam 11 → diproses hari berikutnya.

**Jika Ada Gantungan (Belum Lunas / Ada Denda):** Beri note di Tasklist → kirim VA (via aplikasi) → klik Koreksi → Kembali ke cabang BCA → konsumen bayar kekurangan → cabang input ulang aplikasi Tracking

AS buat Rekap Order perhari.

### Pembuatan Adendum
Adendum dibuat karena adanya perubahan/pembaruan dari dokumen PPK (kontrak). Yang membuat adendum: AS, yang memproses: CS.

**Trigger Adendum:**
- BBN mobil bekas (after sales CS used car)
- Perpanjangan STNK ke atas nama istri → perlu adendum (ke atas nama debitur sendiri = tidak perlu)
- Restruktur (perpanjangan/perpendekan tenor & ubah angsuran) — biaya Rp 250.000
- Reschedule (perubahan tanggal jatuh tempo) — biaya Rp 250.000
- UBJ (Ubah Barang Jaminan) — misal unit baru rusak saat terima, ditukar dealer, noka/nosin berubah

Sebelum adendum dibuat: buat surat permohonan dulu (misal: permohonan balik nama BPKB) → TTD sampai DD (Pak Frans).

**Order Fidusia:** Terjadi karena: adendum, permohonan BBN, ubah jaminan. AS daftarkan di Aplikasi B2B Fidusia → approve by Pak Fathur (UH). Proses selanjutnya ditangani Fidusia Admin

### Pembatalan Transaksi
Konsumen sudah create sistem → dibatalkan. Harus di-cancel, tidak bisa dibiarkan tergantung (kena audit).

**Alur:** Buat form permohonan pembatalan transaksi → approval DD → Konsumen buat surat permohonan → Buka Aplikasi Data Maintenance → input norekpin + alasan → approved → Otomatis hilang di Financore

Jika sudah ada order data (sudah ke birojasa) → harus melalui ITDM → approval BOD

### Lain-Lain Authorized Signer
**Jenis BBN dan Mutasi**
| Jenis | Keterangan |
|---|---|
| Mutasi | Pindah alamat SAMSAT (misal: BPKB Jakarta → konsumen pindah ke kota lain) |
| BBN (Balik Nama) | Balik nama ke atas nama konsumen / pasangan |
| Silang Nopol | Tukar nomor polisi antar BPKB |
| BBN Non-Konsumen | Biasanya di Used Car — BPKB atas nama konsumen X → mobil dijual showroom ke konsumen ABC |

**Report ET Perbantuan Cabang:** BOH cabang cuti → AS crosscheck nominal ET yang sudah dibuat untuk menghindari fraud/human error.

**Pembayaran EXA:** EXA = vendor pengiriman PPK fisik ke konsumen PT. Target: 18.000 kontrak/bulan. Fee dibayar setelah AS terima invoice → ajukan di aplikasi e-GER (memo pengajuan pembayaran).

**SO STNK & ATK:** Report Gantungan Dana STNK: dicek tiap akhir bulan — kelebihan/kekurangan dana after proses administrasi dokumen jaminan.

**Data Maintenance & Report OJK:** Report data bulanan ke FSM; Report OJK & Compliance; Monitoring email: perbantuan cabang (salah kait, ET perbantuan, perbaikan SLIK, dsb)

### Pembayaran Kasir
**5 Jenis Penerimaan:** Angsuran tunai; Biaya administrasi; Biaya BBN/STNK; Denda keterlambatan; Pembayaran lainnya

**Proses Harian:**
- Cash Opname: Penghitungan kas fisik vs sistem
- Reversal (4 step): Identifikasi transaksi → verifikasi atasan → proses reversal → update sistem
- Setor Bank: Setor seluruh kas akhir hari ke rekening BCAF

### PDC (Post-Dated Cheque)
**6 Proses PDC:**
- Penerimaan: Terima cek dari konsumen, cek kelengkapan
- Penyimpanan: Simpan di brankas dual custody
- Clearing: Proses pencairan cek sesuai tanggal jatuh tempo
- Tolakan: Jika cek ditolak bank, proses tindak lanjut
- Pengembalian: Kembalikan cek yang tidak terpakai ke konsumen
- Stock Opname: Penghitungan fisik cek secara berkala

---

# 2. CUSTOMER CARE (CC)

**Goals:** Menyelesaikan pengaduan konsumen sesuai service level. CC letaknya di departemen CS (sebelumnya DCRM), yang berada langsung di bawah National Operation. CC bukan PIC utama — peran utama adalah mediasi dan penyelesaian komplain eskalatif.

- **SLA OJK (POJK 22/2023):** 10 hari kerja
- **SLA KPI Internal:** 9 hari kerja
- **Priority:** Media massa + Layanan OJK (APPK)
- **Handling:** Aspek hukum + perbaikan kolektibilitas

## 2.1 Struktur & Fungsi Customer Care

**Struktur Tim:** Unit Head (Pak Samuel) → Team Leader (Pak Sobari) → PIC CC (Handling · Priority · Admin)

**Fungsi CC:** Penanganan Pengaduan Konsumen (termasuk layanan disabilitas dan lansia: tanpa reservasi, tempat landai, menyediakan kursi roda); Perlindungan Konsumen

**Kategori Pengaduan yang Ditangani CC**
| Sumber | PIC Penanganan |
|---|---|
| Pengaduan dari Media Massa | PIC Priority CC |
| Pengaduan dari OJK (APPK OJK) | PIC Priority CC |
| Pengaduan dengan aspek hukum | PIC Handling CC |
| Walk in CS (Kantor Pusat) | UH CS |
| Layanan Digital | UH CSD |
| Cabang | BOH Cabang |

## 2.2 PIC Admin (Rema) — Monitoring & Koordinasi

**1. Monitoring Email Perbaikan Collect & Surat Kuasa Hukum**
- Cabang kirim email permohonan
- Admin cek no kontrak di PCC: sudah pernah pengajuan sebelumnya atau belum
- Di surat permohonan harus ada nominal kesanggupan bayar
- Cek no kontrak di Financore: status harus Close ET Release dan Close WO
- Cek kelengkapan dokumen: Surat permohonan konsumen · KTP · Form Ideb/SLIK · Register perbaikan collect oleh BOH/BASH
- Setelah semua aman → admin registrasi (cabang, PIC, info konsumen) → print kelengkapan dokumen → kasih ke PIC
- Cut-off: jam 15.00 (di atas jam 15 dikerjakan besok)
- Kirim email ke Accounting dan Credit Settlement

Surat Kuasa Hukum → harus dari kuasa hukum, tidak bisa dibuat langsung oleh konsumen. Yang bisa di-handle: dari kuasa hukum, ormas, dan media massa.

**2. Tugas Lain Admin**
- Memo Gabungan: PIC isi kertas (nominal yang harus dibayar konsumen) → Admin gabungkan jadi memo gabungan → TTD Pak Lim Handoyo → kasih ke cabang. (Tidak semua masuk memo gabungan, ada syaratnya, contoh: Banding)
- Berita Acara: Setelah PIC selesai menangani (dapat form PCC → isinya list konsumen bayar/tidak). TTD: Bu Ninik → Pak Frans → Pak Robert

**3. Monitoring Koran**
Koran yang dipantau: Kompas · Warta Kota · Pos Kota · Media Indonesia. Dilakukan setiap hari. Hari Senin lebih banyak karena harus cek koran Sabtu dan Minggu.

Proses Monitoring Koran: Lihat judul headline koran — ada nama BCAF? → Ada → baca detail → negatif atau positif? → Negatif → bikin kliping → kasih ke PIC

BPKB Hilang (dari kolom koran): Catat nopol dari list BPKB Hilang di koran → Cek di PCC: nopol tersebut milik BCAF atau bukan → Yang masuk penanganan: milik BCAF + status bukan Close ET Release → Koordinasi ke BPKB Admin (konfirmasi blokir + nomor blokir) → CC Admin hubungi konsumen (tanya perlu bantuan terkait BPKB) → Tidak bisa dihubungi → minta ASR untuk kunjungi

**4. Monitoring Media Online**
Platform: Kompas.com · Detik.com · Okezone · Bisnis.com · Mediakonsumen.com · OJK

Lebih mudah dari koran — tinggal cari nama BCAF di search bar. Tindak lanjut sama: bikin kliping → register → kasih ke PIC.

## 2.3 PIC Perbaikan Collect (Deva) — Penyelesaian WO/Lelang

**Kelengkapan Dokumen Pengaduan**

Dari Konsumen Langsung: Surat Pengaduan + Kartu Identitas (KTP/SIM/Passport); No telp/HP + email + No kontrak; Detail kronologis kejadian; Dokumen pendukung (bukti bayar, surat kematian, surat ahli waris)

Dari Pihak Ketiga (Perwakilan): Surat Pengaduan + Surat Kuasa + Kartu Identitas pemberi & penerima kuasa

**Alur Perbaikan Collect (General):** Admin terima surat permohonan → print + kasih ke PIC → PIC input data di PCC (info konsumen, kronologis, penanganan) → Cek kelengkapan dokumen → Konfirmasi pengaduan ke pelapor hari H (info alur + SLA; SLA: 2–3 bulan sampai SLIK lancar) → Koordinasi unit terkait → Analisa & Investigasi → Buat Memo Perbaikan Kolektibilitas → Drafting Surat Tanggapan → Review Legal → Review TL&UH → TTD Pejabat → Fisik surat dikirim ke alamat pelapor → Close PCC

**Koordinasi Unit Terkait:**
- CredSet: Email minta rincian hasil lelang + Risalah Lelang + SPHL
- Accounting: Email minta informasi biaya tarik kendaraan
- ASR: Isi Jotform untuk permintaan kelengkapan dokumen penarikan
- FSM: Email minta rincian sisa kewajiban pasca lelang (biaya parkir, lelang, tarik, dll) → FSM input di aplikasi WOSS

**Memo Perbaikan Kolektibilitas:** Isi memo: info waive 50% denda + 100% bunga berjalan — Approval BOD. TTD: UH CC + BOD + DH CS + DH FSM

**Drafting Surat Tanggapan:**
- Cabang (jika pengajuan pertama kali di cabang): TTD BOH dan BASH/BM
- KP (CC) (jika pengajuan dari KP): dibuat oleh CC
- Wajib lampirkan dokumen pendukung: dokumen penagihan, pengamanan, pelelangan
- Review Legal → Review TL&UH → TTD Pejabat (DH CRM & DH unit terkait)

**Tanggapan Konsumen Setelah Terima Surat**

*Setuju:* Konsumen bayar + kirim ke CS: Bukti Bayar, Surat Pernyataan Penyelesaian, Surat Iktikad Baik (khusus hapus tagih). CS kirim dokumen ke CC → CC input di WOSS → Approval TL/UH CC. Output: Surat Keterangan Tidak Ada Kewajiban. Bukti bayar dikirim ke: FSM (pengkinian SLIK ke BCA), Accounting (pengkinian SLIK BCAF)

*Tidak Setuju → Banding:* Dokumen tambahan: Surat Kesanggupan Bayar (nominal tentative, harus menutup baki debet). Jika setelah hitung diskon denda konsumen tetap tidak sanggup → CC email bahwa tidak bisa diakomodir. Minta dari ASR: SP + SPT + SPHL + BAST + SK Fidusia + SPPI. Memo + draft ST ke Legal → review TL+UH+DH CS+FSM → kirim ST. Batas waktu bayar: 90 hari kerja atau memo perpanjangan

**Ketentuan Banding Waive:** Konsumen ternama: denda dikecilkan (lebih fleksibel). Konsumen biasa: mulai perhitungan denda 80% ke atas sesuai approval BOD

**Pelunasan Sebagian / Remedial (Khusus Konsumen WO)**
- Ada SKL → Proses normal
- Tidak Ada SKL → Masuk bucket CC untuk perbaikan kolek (hitung sisa pokok hutang). Ada memo dari tim Recovery untuk persetujuan Pelunasan Sebagian. Pelunasan ini untuk mendapatkan BPKB namun tidak ada SKL → status kolek tetap Coll 5. Dokumen: Form Registrasi · IDEB SLIK · KTP · Permohonan pembersihan SLIK · Memo 1 set Pengeluaran BPKB · PPK Lengkap

Gagal Klaim: gunakan PPJGR (Permohonan Penyelesaian Jaminan Ganti Rugi)

## 2.4 PIC Priority Handling (Mora) — APPK OJK & Media Massa

**APPK OJK (Aplikasi Portal Pelindungan Konsumen)**
Sumber pengaduan: Konsumen langsung / Ahli waris / Kuasa hukum / dll

**Isi Aplikasi APPK OJK:** Tanggal pelaporan; Deskripsi dan data diri pelapor; Jenis permasalahan; SLA penanganan

**Alur APPK OJK:** Terima pengaduan via APPK OJK → Cek kelengkapan dokumen → Isi Form Pengaduan Konsumen → Konfirmasi pengaduan ke pelapor → Koordinasi unit terkait (meeting jika diperlukan) → Analisa & Investigasi → Drafting Surat Tanggapan → Review Legal → Review TL&UH → TTD Pejabat → Fisik dikirim ke pelapor + Upload softcopy ke APPK OJK

**Respon Konsumen (10 HK setelah BCAF upload surat tanggapan):**
- Menerima → Pengaduan di APPK closed
- Keberatan → Pengaduan dikembalikan ke BCAF, wajib ditindaklanjuti dengan SLA 10 HK
- Menolak → Pengaduan di APPK closed
- Menolak → LAPS → Pengaduan masuk bucket LAPS untuk diverifikasi dan dijadwalkan mediasi

Auto-closed: jika konsumen tidak memberikan tanggapan dalam 10 HK

**Alur LAPS (Lembaga Alternatif Penyelesaian Sengketa)**
Dilakukan via Zoom meeting (online). Yang ikut LAPS: PIC CC, pejabat unit terkait, task force, legal (di balik layar).

Alur: Terima surat LAPS lewat email → BCAF kirim feedback bersedia mengikuti LAPS → BCAF lakukan meeting koordinasi dengan unit terkait → LAPS kirim email surat undangan (jadwal + link Zoom) → Laksanakan LAPS via Zoom

Jika LAPS tidak berhasil → bisa masuk ke Pengadilan Negeri. Dikerjakan oleh Legal, namun CC juga tetap memberi surat tanggapan ("dengan menghormati hukum yang berlangsung...")

**Media Massa**
Alur: PIC terima pengaduan dari Media Massa → Cek data pembiayaan konsumen → Isi Form Pengaduan (jika sifatnya keluhan) → Konfirmasi pengaduan → Koordinasi unit terkait (Operation/ASR/Marketing/FSM/Accounting/Credit Settlement/Asuransi/dll) → Analisa & Investigasi → Buat Memo Penanganan Media + Rekomendasi (Hak Jawab atau Surat Tanggapan)

*Hak Jawab ke Media:* Minta persetujuan narasi Hak Jawab → DH CRM + DD National Opr. Kirim Hak Jawab ke media. Maintain hingga Hak Jawab terposting

*Surat Tanggapan:* Drafting → Review Legal → Review TL&UH → TTD Pejabat. Fisik dikirim ke alamat konsumen

## 2.5 Surat Kuasa Hukum (Instansi Hukum)

Pengaduan yang masuk melalui instansi hukum seperti KPK, MA, KY (Komisi Yudisial), atau kuasa hukum (pengacara). Diterima di KP maupun Cabang.

**Alur:** PIC terima surat pengaduan dari Instansi Hukum (KP/Cabang) → Cek kelengkapan dokumen pengaduan → Isi Form Pengaduan Konsumen → Konfirmasi pengaduan ke pelapor → Koordinasi unit terkait → Analisa & Investigasi → Drafting Surat Tanggapan → Review Legal → Review TL&UH → TTD Pejabat → Fisik Surat Tanggapan dikirim ke alamat pelapor

Surat kuasa hukum harus berasal dari kuasa hukum resmi — tidak bisa dibuat langsung oleh konsumen. Yang bisa di-handle: dari kuasa hukum, ormas, dan media massa.

## 2.6 PIC Perlindungan Konsumen (Kak Adam)

**7 Prinsip Perlindungan Konsumen:**
1. Edukasi yang memadai
2. Keterbukaan dan transparansi informasi produk dan/atau layanan
3. Perlakuan yang adil dan perilaku bisnis yang bertanggung jawab
4. Pelindungan aset, privasi, dan data Konsumen
5. Penanganan pengaduan dan penyelesaian sengketa yang efektif dan efisien
6. Penegakan kepatuhan
7. Persaingan yang sehat

**Tugas PIC Perlindungan Konsumen**
| Tugas | Contoh |
|---|---|
| Sosialisasi kepada seluruh karyawan BCAF mengenai Pelindungan Konsumen & Masyarakat | WA blast, training front liner |
| Sosialisasi alur pengaduan konsumen | — |
| Koordinasi proses perencanaan & pelaksanaan kepatuhan terhadap ketentuan Pelindungan Konsumen | Koordinasi dengan Bispro & Compliance terkait ketentuan baru OJK dan pembuatan revisi SK |
| Koordinasi dengan unit terkait untuk pemantauan & evaluasi kepatuhan | Pada unit ASR: memastikan proses penagihan sesuai ketentuan POJK 22/2023 |
| Melaporkan kepada Direksi mengenai implementasi Pelindungan Konsumen & Masyarakat | Laporan + rekomendasi perbaikan setiap semester |
| Koordinasi penyusunan & penyampaian laporan ke OJK | Pelaporan Self Assessment tiap semester |
| Menerima, menangani, dan menyelesaikan pengaduan konsumen | Layanan khusus disabilitas & lansia: kursi roda, toilet kebutuhan khusus, tempat landai |
| Menyusun materi penanganan Pengaduan untuk laporan tahunan, website, dan media resmi lainnya | — |
| Menjadi penghubung penanganan Pengaduan ke OJK dan otoritas lainnya | APPK OJK |

**Self Assessment OJK (Tiap Semester):** 374 pertanyaan dari OJK. Setiap pertanyaan memerlukan jawaban pilihan ganda + lampiran SK pendukung.
- Pertanyaan dilempar ke unit terkait sesuai topik → hampir semua unit mengisi
- SLA pengisian per unit: 7 hari kerja
- Koreksi dikirim via email ke unit terkait jika belum sesuai
- Jika tidak ada SK spesifik → lampirkan SK yang mirip. Setelah self assessment diterima, baru diterbitkan SK yang spesifik
- Dilaporkan juga kepada Direksi setiap semester 1: update SK apa saja dan rujukan POJK-nya apa
- Setelah submit ke OJK → BCAF menerima feedback. Jika tidak sesuai → OJK minta klarifikasi (bisa via email atau OJK langsung datang ke BCAF)

## 2.7 PIC Motor (Fajar)

Proses PIC Motor pada dasarnya sama dengan mobil dengan 2 perbedaan utama:
- FSM Motor: Tidak input di WOSS — permintaan dan penerimaan data dilakukan via email
- WAIVE Denda Motor: Tidak mengikat — waive didasarkan pada menutup baki debet, bukan persentase denda

## 2.8 Catatan Review (Pak Bari)
- CC bukan PIC utama — peran mediasi dan eskalasi
- Tujuan SLA 9 HK (KPI internal)
- Sumber priority: media massa + APPK OJK
- Sumber non-priority: walk-in konsumen
- Konsumen hapus tagih → surat keterangan iktikad baik diperlukan

---

# 3. CS DIGITAL (CSD)

CSD adalah unit kerja yang mengelola permohonan/permintaan konsumen dari channel digital: **Website BCAF · Email · AVA (Video Call) · FINA · ASTARI · Instagram**.

## 3.1 Gambaran Umum Tim & Aplikasi

**Struktur Tim:** 1 Unit Head (UH) · 1 Team Leader (TL) · 10 Petugas Video Call (AVA) · 5 Petugas Email Customer Care · 1 Petugas Website

**Tentang AVA vs ASTARI:**
- **AVA** — layanan video call yang dapat diakses konsumen melalui Website BCAF dan FINA. Menggunakan teknologi Zoom Contact Center.
- **ASTARI** — chatbot yang dijawab otomatis oleh Bot. Jika bot tidak paham atau konsumen pilih menu 10 → submenu 1, terhubung ke Human Agent ASTARI (tim dari Halo BCA). Eskalasi → laporan di CRM Halo → masuk bucket CSD.
- Kendala sistem Chatbot/Human Agent ASTARI → diinfokan ke CSD → diteruskan ke IT.

**Aplikasi yang Digunakan CSD**
| Aplikasi | Fungsi |
|---|---|
| Financore | Lihat data kontrak, konsumen, pengkinian data; hitung denda ET (KKB 3% & BCAF 5%) |
| One View | Lihat no telepon & info dasar konsumen (tidak bisa hitung denda ET) |
| DMS | Lihat BPKB, kontrak, dokumen fidusia; cek dossier asli untuk ET, SKPS |
| Fast App | Data kendaraan motor |
| App Gabungan | Hitung ET, buat Virtual Account |
| FINA | Monitoring layanan, review aplikasi konsumen |
| 3Dolphins | Penanganan email konsumen dan Instagram DM/komen |
| Aplikasi Reservasi BPKB | Khusus konsumen individu (PT harus email) |
| CRM Halo Lite | History penanganan & tindak lanjut dari Halo BCA |

## 3.2 Website — Kontak Kami

**Sumber Data:** Website BCAF → menu Kontak Kami (hubungi kami); Email: customercarebcaf@bcaf.id (via 3Dolphins); Data ditarik oleh TL/UH agar tidak terjadi penumpukan

**3 Batch Kerja — Semua Harus Selesai di Hari yang Sama:** Batch 1: 09.00; Batch 2: 12.00–13.00; Batch 3: 15.00–16.00

**Alur Proses Website Kontak Kami:** Konsumen input di website → dapat no laporan by email → PIC tarik data (3 batch): Aplikasi BCA Finance Kontak Kami → Excel → File Sharingan → Konfirmasi 2 cara: Telp (3x percobaan) + Email → Register di Excel (Action Plan, Tindak Lanjut, Keputusan, Penyelesaian) → Input hasil di PCC menu Fitur Bucket Website

**Input PCC — 14 Field:** No asal · No register · PIC · Penanganan · Status credit · Cabang · Kategori · Jenis laporan · Kronologis · Tindak lanjut · Keputusan/persetujuan · Penyelesaian · Dokumen penyelesaian (opsional) · Email

Jika PIC balas konsumen via email → PDF-kan lalu input sebagai dokumen penyelesaian di PCC. Cukup sekali input — tidak perlu input ulang jika konsumen membalas lagi.

**9 Tipe Kasus Website**
| No | Tipe Kasus | Catatan |
|---|---|---|
| 1 | BPKB | Order via Aplikasi Reservasi (individu reguler). BU/blacklist/relaksasi/multiguna → manual ke Docust |
| 2 | Tunggakan | Cek Financore by nama; Fast App motor sudah tidak bisa. Cek apakah dana deposit/tidak, info ke IT jika tidak bisa. |
| 3 | Uang tanda jadi | Konfirmasi ke cabang |
| 4 | Pengajuan kredit | Tidak perlu konfirmasi telp/email. Forward ke Telesales via email (no registrasi + pesan pengajuan) |
| 5 | Dana double | Konsumen kirim bukti bayar → proses 5–6 hari |
| 6 | ET (Pelunasan) | Hitung via App Gabungan. Batas bayar konsumen jam 12.00. Vertel dulu → create VA (berlaku sehari karena ada bunga berjalan) |
| 7 | Perpanjangan STNK | Buat SKPS sebagai pengantar ke SAMSAT |
| 8 | BPKB BU dikuasakan | Konfirmasi telp & email. Jika dokumen lengkap → order manual reservasi → info pengambilan via email |
| 9 | Pengkinian data | Perlu approval UH. Konsumen kirim copy KTP + form pengkinian + data lama + foto konsumen |

**Lain-Lain Kontak Website:**
- EBIAM bisa isi dari website → CSD → Telesales (untuk pengajuan kredit)
- Jika tidak ada nopol/no kontrak → email dulu minta info sebelum ditindaklanjuti
- Jika ada nopol/no kontrak langsung → vertel. Tidak diangkat → email
- Info STNK tidak bisa langsung diberikan — sampaikan syarat, minusnya apa, baru minta datang ke cabang
- Nasabah Asuransi → arahkan ke maskapai asuransi (kontak ada di polis asuransi)
- Mobil ditarik pihak ke-3, mau tebus → arahkan ke cabang terdekat, temui ASR
- Konsumen pelapor beda dengan debitur → arahkan konsumen sendiri untuk datang ke cabang
- Review TL jika ada yang kurang tepat → bisa edit PCC, tidak perlu email ulang
- Balasan email berlanjut → masuk ke PIC email dulu, difilter → teruskan ke PIC website
- FINA error sering terjadi setiap hari. Jika konsumen keluhkan denda belum berkurang → cek Financore, info ke IT jika dana tidak bisa diidentifikasi

## 3.3 Instagram (@mybcaf)

CSD mengelola balasan DM dan komentar di Instagram @mybcaf. Pembuatan konten/postingan tetap oleh Bisdev. Aplikasi yang digunakan: 3Dolphins.

**Cara Kerja:**
- Semua DM dan komentar (feeds sendiri maupun di-tag di feeds orang lain) masuk ke 3Dolphins sebagai tiket baru
- Prioritas: balas DM dulu. Balas komentar harus koordinasi ke Atasan dahulu (hindari blunder)
- Pelayanan Instagram hanya sebatas informasi umum. Jika butuh proses/transaksi → arahkan ke email, AVA, atau FINA
- Setelah DM/komentar di-close → dimasukkan ke register Excel, di-drop ke sharing folder setiap hari

**Mekanisme DM:**
- Setelah chat dibalas: ada waktu 5 menit untuk konsumen membalas kembali
- Jika tidak ada balasan → ada auto message "apakah masih ada pertanyaan?"
- Tidak dibalas 2–3 menit → auto close
- Jika DM sudah close lalu konsumen chat lagi → reset dari awal. Riwayat bisa dilihat di history by no tiket

**Ketentuan Khusus:**
- Tiket >24 jam → tidak bisa dibalas (ada error) → langsung close
- Tidak bisa balas manual karena username @mybcaf dipegang Bisdev
- SPAM → tidak perlu dibalas tapi tetap masuk ke register
- Konsumen minta perbaikan koleksi → arahkan ke AVA atau CS cabang/KP dulu (bukan langsung ke CC)
- Konsumen minta kredit → arahkan ke Marketing → nomor marketing general → cabang terdekat atau website pengajuan
- Tag di feeds orang lain → masuk tiket baru, tapi jarang dibalas
- Tiktok dan X belum dikelola CSD (dikelola OSD)

**Volume & KPI:** Normal: ±50 tiket/hari. Ramai setelah libur panjang atau saat ada kuis. KPI: belum ada — yang penting balas DM dan komentar, usahakan habiskan semua tiket

**Yang Langsung Dibalas (tanpa perlu pengecekan):** Tanya alamat, cara reservasi, jam operasional, informasi umum lainnya

## 3.4 AVA — Astari Virtual Asisten (Video Call)

AVA adalah kanal pelayanan digital menggunakan media video call (Zoom Contact Center). Secara fungsi sama dengan CS biasa, bedanya hanya di media komunikasi — petugas bisa lihat langsung wajah konsumen, KTP, dan dokumen lainnya melalui kamera.

**Jam Operasional:** 07.45 – 16.00 WIB. Setelah jam operasional: bersihkan data konsumen di komputer, tutup aplikasi, pastikan tidak ada data tertinggal (pengamanan data konsumen).

**5 Sumber Konsumen AVA:** Website BCAF · AVA · FINA · Cabang · S2P · Zoom

**Cara Booking AVA:** Konsumen reservasi melalui Website BCA Finance → mendapat jadwal sesuai slot tersedia

**SLA Video Call:** Maksimal 15 menit. Jika >15 menit → dikategorikan over SLA. Jika membutuhkan waktu lebih lama → konsumen diarahkan untuk panggilan ulang

**Top Layanan AVA:** ET (Early Termination/Pelunasan Dipercepat); Reservasi BPKB; SKPS; Pengkinian Data; Info Kontrak (status, no kontrak, sisa angsuran, jatuh tempo, data kendaraan)

**Alur Pelayanan Video Call:** Greeting (salam + perkenalan diri) → Identifikasi Kebutuhan (tanya tujuan konsumen) → Verifikasi Data (KTP wajib ditunjukkan ke kamera) → Proses Penyelesaian Permintaan → Closing (sampaikan hasil, pastikan kebutuhan terpenuhi) → Registrasi Hasil (kronologi, catat hasil, input ke file monitoring)

**Verifikasi Data (3 Kategori):** Identitas (Nama lengkap, TTL, Alamat, KTP); Kendaraan (Nopol, Jenis, Warna, Tahun); Kontrak (Besar angsuran, Tanggal JT, Info kontrak lainnya)

**Detail ET via AVA:**
- Cut-off: jam 12.00
- < 1 tahun: biaya admin Rp 750.000 + pinalti
- ≥ 1 tahun: tidak ada biaya admin + pinalti
- Tidak kena pinalti jika: angsuran tinggal 2 kali lagi dan bayar tepat tanggal JT

Alur: Konfirmasi data di Financore → Konsumen tunjukkan KTP ke kamera Zoom → Hitung ET di App Gabungan → Create VA → Bukti TF dikirim ke email customercare (bukan CC) → Pengambilan BPKB H+1

**Reservasi BPKB via AVA:**
- Berlaku 15 hari kalender sejak tanggal reservasi
- Individu → via Aplikasi Reservasi BPKB
- Badan usaha → via email (ada dokumen yang dilengkapi)
- Pengiriman BPKB bisa diminta via FINA/ASTARI: biaya Rp 150.000
- Tanpa reservasi di WPI: nasabah >60 tahun, konsumen Prioritas BCA, titipan cabang/pejabat, showroom

**SKPS via AVA (6 Langkah):** Verifikasi data → Jelaskan biaya materai → Buat VA → Buat SKPS → Kirim via room chat Zoom → Jelaskan langkah selanjutnya

**Penggunaan Surat Kuasa:** Bawa surat kuasa + identitas pemberi kuasa + identitas penerima kuasa. Petugas validasi dokumen melalui kamera: identitas, tanda tangan, kesesuaian data sistem.

**Penanganan Kendala**
| Kendala | Solusi |
|---|---|
| Sinyal buruk | Lakukan panggilan ulang atau arahkan ke media lain |
| Video tidak muncul tapi suara ada | Minta konsumen panggilan ulang (verifikasi visual wajib) |
| Wajah berbeda dengan foto KTP | Proses tetap lanjut jika kamera aktif, konsumen bisa jawab verifikasi, dan data sesuai sistem |
| Dokumen diragukan / data tidak sesuai | Eskalasi ke Team Leader untuk keputusan akhir |

**Syarat Reservasi PT/BU:** Wajib email dahulu, lampirkan: jenis kendaraan, nopol, no kontrak, jabatan ybs, nama direktur aktif, tenor.
- Setelah dokumen dilengkapi → PIC order manual reservasi BPKB → info pengambilan via email
- Pengiriman BPKB ke Jabodetabek: Rp 100.000

## 3.5 Email (customercare@bcaf.id)

Email: customercare@bcaf.id — berlaku secara nasional. Semua email masuk ke CSD KP.

**Struktur Tim:** 5 PIC email handler. Masing-masing pegang 25 bucket. Selama bucket belum penuh, email random masuk ke PIC. Bisa di-assign manual oleh TL. Ada PIC khusus: PIC pengkinian data, PIC pembayaran — email terkait langsung di-assign ke PIC spesialis

**3 Kategori Pelayanan:** Informasi; Permohonan (pengkinian data, reservasi BPKB PT, perbaikan collect); Keluhan (tergantung jenis keluhannya)

**4 Status Tiket Email:** Assign (Tiket baru); Open (Sedang dikerjakan); Pending (Menunggu info/dok. dari konsumen); Close (Selesai — setiap kirim reply → close, tidak ada auto-close)

**Tools:**
- Makro: Template email untuk pertanyaan umum. Tidak semua tersedia, sebagian dibuat manual.
- Tag: Kategorisasi email untuk mengetahui permasalahan yang sering muncul
- CRM Halo Lite: Lihat history penanganan dan tindak lanjut dari Halo BCA

**SLA Email:** Email masuk sebelum 16.00: dibalas hari yang sama. Email masuk setelah 16.00: dibalas H+1

Jika email tidak bisa langsung dijawab → koordinasi dulu dengan unit/cabang → baru balas. Bisa juga langsung arahkan konsumen ke cabang terkait.

## 3.6 Email — Alur Detail Per Jenis Permohonan

**Reservasi BPKB PT via Email:** PT tidak bisa via Aplikasi Reservasi (dokumen perlu dicek manual). Individu: cukup via FINA/aplikasi reservasi.

*Jabo Non-WPI:* Terima email → Cek Financore (checklist verifikasi) → Buat Word (SS Financore + SS email + checklist) → Drop di sharing folder → TTD Ko Steven → Isi spreadsheet → kasih ke PIC Order → Kirim email balasan (on progress)

*Non-Jabo:* Terima email → Isi spreadsheet → kasih ke PIC Order (tidak perlu checklist/word, cabang yang cek dokumen)

*WPI:* Cek status Financore (harus Closed), cek info mobil → Cek aplikasi B2B Fidusia + surat kuasa → Cek resume AHU (direktur masih valid) → Cek stempel, TTD, alamat direktur, nama di sistem vs lampiran → Jika tidak sesuai → email minta perbaiki/lengkapi

**Case Reservasi BPKB via Email:**
- Ada biaya penyimpanan outstanding: tetap bisa reservasi — PIC info jadwal & syarat beserta jumlah biaya yang harus dibawa
- Ada denda outstanding: belum bisa reservasi karena status belum Closed

**Pengkinian Data via Email:** Terima form pengkinian data → Cek perubahan sesuai dokumen pendukung (misal: perubahan alamat = cocokkan dengan KTP) → Tidak sesuai → balas email minta dokumen terbaru → Sesuai → drop form di sharing folder → TTD Ko Steven → PIC pengkinian data update di Financore

Tidak perlu register karena PIC langsung cek bucket di sharing folder. Report perubahan bisa ditarik di Ginancore.

**Perbaikan Collect via Email:** Terima dokumen lengkap dari konsumen via email → Forward email ke email Customer Care → Buka PCC untuk cek PIC CC yang menangani (jika konsumen nanya progress)

**Pembayaran Kasir via Email (Bukti Bayar ET/Waived):**
- Proses ET atau Waived sendiri tidak bisa melalui email — hanya terima bukti bayar
- Setelah terima bukti bayar: cek deposit di Financore apakah sesuai bukti transfer
- PIC proses deposit di Financore (alokasikan dana)

**SKPS via Email:** Create VA (App Gabungan) → Konsumen bayar & kirim bukti bayar → Cek pembayaran di App Gabungan (tetap perlu bukti bayar sebagai dokumentasi resmi) → Create SKPS di Financore → Ambil copy BPKB di DMS (ada tools legalisir soft copy) → Kirim SKPS + copy BPKB ke email konsumen

## 3.7 FINA — Review Monitoring

PIC bertugas melakukan respons terhadap review/ulasan konsumen di aplikasi FINA pada Google Play dan Apple Store. Hasil dilaporkan setiap Senin ke Ibu DH (Ibu Ninik).

**Alur:** Cek review Play Store & App Store secara berkala → Daftarkan review di Excel (tgl, bulan, tahun, tipe perangkat, bintang, tanggapan) → Cari data konsumen di Financore (by nopol, nama Gmail, atau no kontrak jika ada) → Reach out konsumen via Vertel (telp/WA/email) — tanyakan kendala yang bisa dibantu → Kirim Excel setiap Senin ke: Micom + Ibu DH (Ninik) + Bispro + IT + unit terkait

Template respons sudah tersedia untuk review bagus maupun buruk.

**Order Manual BPKB:** Konsumen PT (Badan Usaha); Blacklist yang melewati batas waktu reservasi; Borrow multiguna

**3 Jenis Dokumen ke Docust:** Borrow BPKB (umum); JABODETABEK (area WPI/cabang Jabo); WPI (khusus Walk-in ke WPI)

## 3.8 Authorized Signer CSD

**Order BPKB Prioritas (9 Langkah):** Terima permintaan → Cek aplikasi Tracking → Approval kepala cabang BCA → Cut-off jam 11 → Proses pengiriman

**Pengkinian Data:** NIK + KK (untuk perubahan data kependudukan); Perubahan nama: butuh keputusan pengadilan; BU: NPWP + NIB + Akta (untuk perubahan data perusahaan)

**Pengambilan STNK:** Terima: 4 langkah verifikasi masuk; Ambil: 4 langkah verifikasi keluar; Stock Opname: 1x/bulan

**Salah Kait SLIK OJK:** 7 dokumen diperlukan; 8 langkah alur penanganan; Memo penggantian 3 angka terakhir NIK; Approval: BOD

## 3.9 Analyst CSD

**5 Timeline Laporan:** Harian: monitoring tiket masuk/selesai per channel; Mingguan: rekap performa per PIC; Bulanan: report ke OSD (maks tanggal 5); Triwulan: report komprehensif ke OSD (maks tanggal 10); Semester: laporan semesteran

**14 Cabang dengan Qmatic:** Bandung, Bekasi, Bogor, Cilegon, Daan Mogot, Lampung, Malang, Medan, Pekanbaru, Semarang, Surabaya, Tangerang, WPI, WTC

**Flow Pengumpulan Data:** Google Form (input data) → Spreadsheet (olah data) → Report ke OSD

**3 Kasus Terbanyak Nasional:** BPKB (pengambilan, pertanyaan status); ET (pelunasan dipercepat); STNK BBN / Mutasi

---

# 4. CENTRAL DISBURSE MOTOR (SENTRA APP MOTOR)

**Tujuan:** melakukan verifikasi dokumen dari cabang melalui telepon dan mencocokkannya dengan data di sistem, setelah unit diterima oleh konsumen. Area cakupan: seluruh Indonesia. Centra disburse motor berperan sebagai checker — penentu keputusan final adalah Centra Kredit (Pak Mahendra).

## 4.1 Gambaran Umum Tim
- MPP: 14 orang · 5 TL · 1 Head (Bu Vero)
- Shift 1: 09.00 – 18.00
- Shift 2: 10.00 – 19.00
- Staff Backup: Dipanggil jika aplikasi ramai
- SLA: 2 jam dari aplikasi masuk sampai TL Approved
- Rata-rata Vertel: 8 menit (max 5 menit ideal)
- Cut-off Vertel: Jam 19.00 (kecuali saat closing)
- Target Insentif Staff: Min 500 aplikasi/bulan

**2 Produk yang Ditangani**
| Produk | Jalur | Pembayaran |
|---|---|---|
| KSM (Kredit Sepeda Motor) | Cabang BCA | Wajib Autodebet |
| KPM (Kredit Pemilikan Motor) | Melalui Dealer | Manual (non-autodebet) · bisa autodebet juga |

Penting: Unit wajib diterima dulu oleh konsumen sebelum diproses Sentra APP Motor. Jika belum diterima → dikembalikan ke cabang (return).

## 4.2 Aplikasi CDA (Central Disbursement APP)

**5 Tab Input Dokumen:** Customer Data; Tagihan Dealer; Object; Autodebet; Other

**5 Bucket Dashboard Monitoring:** Reguler; Cluster A — Prioritas; Multiguna (Gadai BPKB); Company (Nasabah PT); Appointment (Tidak diangkat 2x)

Staff mengambil aplikasi dengan sistem rebutan. Aplikasi terupdate setiap kelipatan 5 menit (ex: 08.30, 08.35, …)

## 4.3 Alur Kerja — Dari Cabang ke Disburse

Marketing input di MOSS → Marketing beri dokumen fisik ke ADS (Staff Admin Cabang) → TL ADS cek dokumen → Staff ADS scan + upload via DissApp → masuk ke CDA → Staff CDM klik "Get Data" → Regist ke Excel → Cek Customer Data + Tagihan + Object + Autodebet → Vertel / Piloting / SS WA → Submit → TL WF Approval → Approve → Disburse (No Kontrak muncul 1–5 menit)

- Vertel maksimal 2x termasuk appointment
- Jika gagal vertel → cabang koordinasi langsung dengan konsumen
- Jika ada perubahan no telp / nama ibu kandung → perlu Form OTS dari cabang
- No kontrak dikirim ke konsumen via WA & Email dalam 1–3 hari
- H-3 closing: broadcast ke cabang untuk info konsumen agar mau angkat telepon (no 1500850)
- Data per hari harus diselesaikan hari itu juga (cut-off jam 19.00), kecuali saat closing

## 4.4 Pengecekan Dokumen

### Cek Customer Data
- Pastikan nama dan tanggal lahir di CDA sama dengan nama dan tanggal lahir di KTP yang diupload
- Pastikan status perkawinan di sistem sama dengan di KTP
- Jika di KTP status kawin tapi tidak ada nama pasangan → return ke cabang, lampirkan KK / Surat Tanda Menikah / Surat Kematian
- Jika di sistem ada nama pasangan tapi di KTP status lajang → return juga
- Untuk konsumen PT: tidak harus no perusahaan, biasanya no direksi atau PIC

### Cek Tagihan Dealer — KSM

**PO (Purchase Order) — TTD Pejabat Dealer + BM Cabang:** Jika ada PO baru karena penggantian → gunakan yang terbaru. Yang dicek (pastikan dokumen = sistem): No Pemesanan (No PP), Tanggal Pemesanan, No Aplikasi, Nama Konsumen, Pembayaran ke Dealer

**BASTK (Berita Acara Serah Terima Kendaraan) — TTD Pejabat Dealer:**
- Tanda terima unit: tanggal terbaru (jika ada banyak tanggal: cetak/kirim/terima → ambil yang terima)
- Data kendaraan: tipe, warna, gesekan noka nosin
- Nama & hubungan penerima unit (jika bukan konsumen sendiri)
- TTD PIC dealer dengan penerima unit harus sesuai KTP — jika beda: lampirkan surat pernyataan spesimen tanda tangan
- BAST tidak bisa diverifikasi jika sudah >21 hari dari tanggal terima → cabang lampirkan BA T21 (isi: kronologi, ubah tanggal terima, approve BM)

**Kwitansi Pelunasan:**
- Nama leasing harus tertuju ke BCA Finance + alamat sesuai
- Angka nominal pelunasan = pembayaran ke dealer (KSM tidak dikurang DP)
- Angka terbilang harus sesuai nominal
- Materai wajib (fisik / e-materai / bea materai); tanpa materai bisa kasih note dari cabang (1–2 dealer saja biasanya)

**Gesekan Noka Nosin:**
- No rangka selalu diawali kode MH1 — khusus Dealer Astra tidak wajib diawali MH1
- Ada kode digit tahun: T = 2026, V = 2027 → cocokkan dengan tahun kendaraan
- Selain Astra yang tidak diawali MH1 → return ke cabang

**KTP:** Diperlukan jika BPKB atas nama selain konsumen

**CN (Cover Note Pelunasan):**
- Struktur kredit: angsuran dan tenor
- Nama STNK / BPKB dan Nama Leasing
- Redaksi waktu penyerahan BPKB: max 3 bulan (dihitung dari tanggal TTD cover note, bukan dari tanggal jadi STNK) — khusus Benelli bisa sampai 6 bulan
- Jika nama konsumen pengajuan berbeda dengan nama di BPKB → lampirkan atas nama BPKB

Redaksi CN yang WAJIB ada salah satunya: "Selambat-lambatnya" / "Maximal" / "Dalam kurun waktu" / "Dalam periode". Redaksi yang TIDAK BOLEH: "kira-kira" / "kurang lebih" / "kemungkinan" → langsung return ke cabang

**Akta Perusahaan:** Opsional, jika konsumen PT atau atas nama PT → cek ada nama direktur/komisaris dan nama perusahaan

Revisi dokumen: Wajib ada paraf + cap Dealer. Paraf dealer harus sama dengan spesimen di Portal → jika beda, return ke cabang, minta MC Operation Cabang update di portal.

### Cek Tagihan Dealer — KPM & Multiguna

**KPM (Kredit Pemilikan Motor):**
- Dokumen tagihan sama dengan KSM + tambahan Kwitansi DP
- Kwitansi DP: konsumen yang langsung bayar DP ke dealer → mempengaruhi nilai pencairan
- Pastikan nominal DP sama dengan yang ada di Kwitansi Pelunasan
- Kwitansi Pelunasan KPM: tidak wajib ada nama leasing · wajib nama nasabah (bukan atas nama BPKB)
- DP KPM tidak ditanyakan saat vertel

**Multiguna (Gadai BPKB):** PO; BPKB (wajib); STNK; Noka Nosin; Inquiry tabungan (buku tabungan atau SS M-Banking); Faktur; KTP pemohon; Surat penggunaan fasilitas (tujuan, rekening pencairan, nominal)

Multiguna: tanggal JT & tanggal terima menyesuaikan tanggal vertel, dan wajib di-vertel semua (setelah semua Done/DV)

### Cek Object (Tab Piloting di CDA)
- Field Project Tanpa Vertel (Iya/Tidak) = Piloting
- Jika foto piloting diupload di tab Object → otomatis jadi IYA
- Jika diupload di tab lain → perlu di-invalid di Verification dulu, lalu ubah jadi IYA

**Ketentuan Foto Piloting:**
- Wajib foto dengan papan dan unit kendaraan
- Tidak harus papan BCAF — bisa kertas, kardus, dll, yang penting isinya: nama konsumen, angsuran, tenor, warna dan tipe unit
- Jika tidak ada kendaraan → lakukan vertel
- Jika yang foto bukan pengaju kredit (termasuk atas nama BPKB) → wajib lampirkan KTP · jika tidak ada KTP → vertel

**Pengajuan >1 Unit:**
- Cabang harus bikin list pengajuan lebih dari 1 unit (no aplikasi berbeda-beda)
- Vertel hanya 1x saja, acuan dari list tersebut
- Jika belum ada list → konfirm ke konsumen: jika semua unit sudah diterima → return untuk buat list · jika ada unit yang belum diterima → vertel yang sudah diterima dulu

### Cek Dokumen Autodebet
KSM wajib autodebet. KPM bisa autodebet juga (opsional).

| Dokumen | Detail Pengecekan |
|---|---|
| SKPR (Surat Kuasa Pendebetan Rekening) | TTD + materai · Bisa debet diri sendiri, PT, atau orang lain · Join 2 orang = wajib 2 TTD |
| SPADR (Surat Pernyataan Autodebet Rekening) | Sama seperti SKPR + ada tanggal pendebetan · Nama sesuai kontrak = data pengaju kredit · Ada keterangan hubungan (anak/ortu/istri) · Rekening PT → isi alamat PT |
| KTP a.n. Rekening | Boleh rekening anak atau orang tua |
| Inquiry (SS M-Banking) | Bukti rekening aktif |

**Ketentuan Tambahan:**
- Pakai rekening selain atas nama pengajuan → TTD pemilik rekening dan TTD atas nama pengajuan
- Nama di KTP dan inquiry berbeda (disingkat/typo) → lampirkan Form Beda Nama Rekening
- Jika kepotong karena keterbatasan sistem → tidak perlu form
- Rekening orang lain → wajib Form Beda Nama Rekening
- Ganti Tanggal Autodebet (CDD): Ada perbedaan JT dan tanggal autodebet → lewat pengajuan (ada biaya denda) · Wajib ada SKPR dan SPADR — jika salah satu tidak ada → tidak bisa CDD
- Dokumen yang dicoret untuk diperbaiki → TTD pemilik rekening di setiap kolom yang dicoret
- Tanggal JT Sabtu/Minggu → dipercepat ke Jumat (tidak bisa autodebet di akhir pekan)

## 4.5 Verifikasi Konsumen

**3 Metode Verifikasi**
| Metode | Ketentuan |
|---|---|
| Vertel (Verifikasi Telepon) | Aplikasi X-Lite · No 1500850 · Durasi ideal 3–5 menit · Max 2x percobaan termasuk appointment · Waktu tunggu jika tidak diangkat: ±30 menit |
| Piloting | Konsumen foto pegang papan berisi: nama, angsuran, tenor, warna & tipe unit · Jika penerima bukan YBS/pasangan → lampirkan KTP penerima · Tidak harus papan BCAF |
| SS WA (Screenshot WhatsApp) | Khusus Nasabah Prioritas/Solitaire yang tidak mau ditelpon · Marketing yang chat WA (cek tipe, tenor, angsuran, no/nama kontak) · SS harus disetujui BM (nama + jabatan jelas) · Jika SS tidak jelas → telp 1x, jika tidak diangkat → return ke cabang untuk revisi |

Saat vertel, jika yang mengangkat adalah pasangan/penjamin → boleh, validasi pakai nama yang tercantum di sistem. Jika yang angkat bukan pasangan/penjamin yang terdaftar → appointment, tunggu konsumen sendiri yang telpon balik.

**Pertanyaan Vertel (Script Standar):**
1. Nama lengkap konsumen
2. Tempat dan tanggal lahir
3. Nama ibu kandung
4. Tanggal terima unit kendaraan
5. Merk dan tipe kendaraan
6. Nominal angsuran per bulan
7. Tenor (jumlah bulan)
8. Nama di BPKB dan STNK
9. Penerima motor dan hubungannya dengan konsumen
10. Apakah sudah dilakukan TTD dokumen
11. Tanggal jatuh tempo
12. Informasi denda angsuran → 0.5% dari nominal angsuran

Khusus KSM: Tanyakan juga nominal DP. No rangka dan no mesin TIDAK ditanyakan ke konsumen saat vertel. Status kawin tanpa pasangan: Harus lampirkan KK / Surat Tanda Menikah / Surat Kematian

**Kode Hasil Penanganan (Output Vertel)**
| Kode | Arti | Tindak Lanjut |
|---|---|---|
| #GVE | Good Verified — verifikasi berhasil | Lanjut ke TL WF Approval |
| #VTS | Vertel Tidak Sesuai (cth: angsuran tidak sesuai) | Return ke cabang |
| #DTS | Data Tertanggung Tidak Sesuai — data dari marketing tidak sesuai | Return ke cabang |
| #ATS | Autodebet Tidak Sesuai | Return ke cabang |
| #DV | Don't Vertel = Piloting & Cluster A | Proses dengan metode Piloting atau SS WA |
| #DC | Done Check — pengecekan selesai | Lanjut submit |
| #RPC | Return Permintaan Cabang — cabang minta langsung direturn | Return ke cabang |
| #T21 | Tanggal vertel mendekati tanggal JT (maks 21 hari) | Pakai BA T21 dari cabang untuk majukan tanggal BASTK/tanggal terima → otomatis geser tanggal JT & tanggal autodebet |
| #RTD | Tagihan Tidak Sesuai — dokumen tagihan tidak sesuai / nama dealer di sistem ≠ di dokumen | Return ke cabang |

**Dial Result (11 Opsi):** Verified · Tidak Diangkat · Appointment · Rejected · Nomor Tidak Valid · Salah Sambung · Customer Sibuk · Nomor Tidak Aktif · Tidak Bersedia Verifikasi · Nomor Dialihkan · Telepon Tidak Selesai

Appointment cut-off jam 16.30 — jika sudah lewat dan tidak diangkat → langsung dialihkan ke cabang

**Verification — Invalid vs Return**
Setelah vertel selesai, staff bisa invalid data yang salah (akan diubah setelah masuk ke TL), atau return ke cabang untuk direvisi.

✅ Yang BISA di-Invalid (return saja, tidak perlu stop vertel): No telp 1 (revisi/ganti) · No telp 2 (tambah); Email; Nama ibu kandung; Tanggal Terima; Tanggal Jatuh Tempo; Warna unit; Metode bayar; Tanggal autodebet; No rekening & nama autodebet

❌ Yang TIDAK BISA di-Invalid (return + Stop Vertel — vertel ulang nanti): Nama debitur; Nama sesuai KTP; Tanggal lahir; Merk & model unit; Struktur kredit (angsuran dan tenor); Nama BPKB

**Syarat OTS (On The Spot — Form OTS):** OTS digunakan jika nasabah tidak bisa ditelpon. Marketing yang kunjungan ke konsumen dan mengisi form OTS.

Syarat Otomatis OTS: PK (Pengaju Kredit) tidak tau struktur kreditnya (angsuran dan tenor); PK tidak merasa mengambil kredit; Gagal vertel 3 kali selama 3 hari berturut-turut

Di Luar Syarat Otomatis: Tetap bisa OTS, tapi perlu nasabah TTD ke DD (penyimpangan) — contoh: naik haji, umroh, dll. Dokumen OTS dilampirkan dari cabang ke CDApps

## 4.6 Proses Khusus

**Disburse Manual**
- Tiap jam tarik report Disburse → Fast Report
- Cek di JogetDX → Inquiry Status CDA → cek aplikasi sudah di-disburse atau belum
- Cek yang error gagal disburse: no kontrak tidak ada, no invoice dan PV tidak ada

Alur: MC APP input manual via FAST (create invoice) → Gen AR → Send to AP → Cek AP → Dok Cek (No kontrak + Invoice + PV terbentuk)

Jika no kontrak terbentuk tapi invoice dan PV tidak → buat ticket ke IT

**Autodebet Manual (Khusus DSM — Direct Sales):**
- Produk DSM langsung di-disburse → perlu daftar autodebet manual
- Login FAST as SSPK (MC APP) → Input no rekening, nama nasabah, cabang autodebet → Submit → masuk bucket TL (KSPK) → TL Verified → Autodebet terdaftar
- Dokumen manual autodebet dimasukkan ke winSCP
- Data autodebet disebarkan oleh TL tiap minggunya (ada jadwal piket)

**Buyback, Dakor (Data Correction) & Updation**

*Buyback:* Aplikasi di-cancel → proses dari awal di cabang → vertel lagi. Salah satu penyebab buyback: salah input asuransi (masing-masing cabang punya plotting asuransinya sendiri)

*Dakor (Data Correction):* Noka/nosin salah (tanpa MH1) → pengajuan dengan fidusia untuk tembak data oleh IT

*Updation (Dilakukan oleh Cabang):* Perubahan nomor rekening dari cabang; Ubah no rekening konsumen karena tidak aktif ke yang aktif; Ubah tanggal jatuh tempo

## 4.7 Team Lead (TL)

**WF Approval:**
- Setelah MC APP (SSPK) vertel dan submit → masuk bucket TL untuk double-check (tidak vertel lagi)
- Approve → Masuk ke Finance (Disburse)
- Revise → Dikembalikan ke MC APP (SSPK)
- Return → Dikembalikan ke Cabang

- Setiap awal bulan: report SLA dan Ranking SSPK
- Tarik realisasi data + rekaman untuk sidak vertel
- TL monitoring pembagian tugas per bucket sesuai jadwal piket
- Revisi dari cabang tidak ada batas berapa kali, tapi cabang hanya bisa revisi dalam 3 hari jika debitur tidak angkat telp selama 3 hari tersebut

**Spesimen TTD di Portal:**
- Untuk pengecekan TTD pejabat dealer yang tercantum di dokumen tagihan
- Jika ada pergantian orang → dealer/cabang harus update TTD di portal
- Pendaftaran, verifikasi, upload ke portal = tugas TL Operation Cabang sesuai PKS dealer

**Penilaian SSPK (MC APP) — Tengah & Akhir Bulan**

KPI Staff (Penilaian Tengah & Akhir Bulan)
| KPI | Target |
|---|---|
| SLA vertel | Max 5 menit |
| Get data (jumlah aplikasi) | 500 per bulan (untuk insentif) |
| Sampling vertel | 25 rekaman/orang dari e-centrix |

6 Indikator Penilaian Rekaman Vertel
| Indikator | Keterangan |
|---|---|
| Salam pembuka & penutup | Sesuai standar |
| Volume suara | Stabil, tidak kencang dan tidak kecil |
| Artikulasi | Jelas, tidak terburu-buru |
| Cara bertanya | Terbuka/tertutup — jangan kasih tau jawaban duluan ke konsumen |
| Kelengkapan pertanyaan | Semua wajib ditanya, contoh: KSM tanya DP |
| Durasi vertel | Max 5 menit |

- Penilaian rekaman: 1x/bulan oleh TL · Berpengaruh terhadap KPI setiap staff
- Coaching: 1x/semester — TL sampaikan KPI dan Issue dari staff terkait

**KPI TL:** Coaching · 4DX · Improvement/Kaizen · 5R/Cleaning · Internal Audit; Time to Disburse: max 2 jam · Random sampling verifikasi dokumen; Jumlah aplikasi yang disburse (yang jadi no kontrak, bukan yang masuk data)

## 4.8 Lain-lain & Issue

- Nomor telepon vertel: 1500850 (sama seperti no deskcoll motor, hasil adopsi dari ASR)
- H-3 closing → broadcast ke cabang untuk kasih tau konsumen tentang vertel — no 1500850 sering dinilai aneh di get contact, konsumen takut angkat (ada yang sampai di-block provider)
- Alur jika tidak diangkat: telepon 1x → tidak diangkat → appointment (tunggu ±30 menit) → telepon 1x lagi → tidak diangkat → return ke cabang
- Cluster A / Nasabah Prioritas: dari marketing yang chat WA → SS chat dilampirkan ke CDA dengan persetujuan BM
- Tanggal di BAST diambil yang terbaru; jika ada pembaruan PO juga mengikuti tanggal terbaru
- Piloting tidak harus ada marketingnya, tapi marketing kadang bantu bawa papan ke rumah konsumen yang susah sinyal
- Sistem sering lemot di malam hari saat closing — sudah diidentifikasi sebagai issue infrastruktur IT
- Setelah vertel selesai: lakukan regis vertel di Excel → klik "Done Vertel" di sistem CDA
- Ada laporan bulanan: penilaian vertel (intonasi & informasi)

**Issue & Solusi**
| Issue | Solusi |
|---|---|
| Cabang upload dokumen → tidak terupdate ke terbaru di CDA (tidak boleh kirim via WA/email, di-save pun tidak boleh) | Sedang dalam perbaikan IT |
| No 1500850 banyak yang kasih komentar aneh di getcontact → konsumen tidak mau angkat / block | WA Coster dengan nomor official BCAF — konsumen diingatkan dulu sebelum vertel, bisa atur jadwal juga |

---

*— Akhir Part 1. Lanjut ke Part 2: Doc Support & APP, Legal & Fidusia —*

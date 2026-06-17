# Archive Management — Catatan Detail
> Sumber: `archive_management.pdf`
> Tab: **Docust & Archive** (id=doc) → Bagian Archive

---

## Gambaran Umum

Archive adalah **gerbang terakhir dokumen** sebelum dikirimkan ke jasa penyimpanan dokumen MMI.

**Aplikasi yang digunakan:** Eger · JogetDX Arsip · DMS · Move · OneView (untuk motor)

### 3 Jenis Dokumen Utama Konsumen

| Jenis | Keterangan |
|---|---|
| **Dossier Asli** | Dokumen kontrak |
| **Dossier Copy** | Dokumen tagihan |
| **Fidusia** | Sertifikat Fidusia |

### Cabang yang Di-handle Archive Management (9 Cabang)
- **JABO WPI:** Bekasi · Daan Mogot · Depok · Tangerang · Bogor · Karawang · Kelapa Gading
- **WTC:** 1 cabang
- Di luar 9 cabang di atas → dokumen disimpan di cabang masing-masing

### 5 Fungsi Archive
1. Terima dan simpan dokumen (dossier)
2. Peminjaman dokumen (request retrieval)
3. Pembayaran tagihan vendor penyimpanan
4. Rekonsil nasional (pencocokan data)
5. Sampling nasional

---

## Alur Serah Terima Dokumen ke Archive Management

Alur: **APP → Realisasi → Legal Admin**

Legal Admin memisahkan dossier asli dan dossier copy:
- **Dossier Asli:** di-reprint, di-tera, dicek kembali → kasih ke Archive **H+5 realisasi**
- **Dossier Copy:** tidak diapa-apakan → kasih ke Archive **H+5 realisasi**
- **Fidusia:** di-order dulu ke notaris, tidak ada SLA (secepatnya)

---

## Proses Pengelolaan Box & Register

1. Dossier Asli dan Dossier Copy diterima dari unit terkait
2. PIC melakukan registrasi → dimasukkan ke box sesuai kode box
3. Dilakukan sampling (cek) **10% per box**
4. Setiap **hari Kamis:** archive email ke MMI untuk pengambilan hari Jumat; dicantumkan jumlah box 01, 02, dst.
5. Setiap **hari Jumat:** MMI datang mengambil box
6. Yang diterima MMI: box + softcopy list data isi box (hasil registrasi archive)

### Kapasitas Box

| Kode Box | Jenis Dokumen | Kapasitas |
|---|---|---|
| Box 01 | Dossier Asli | 150 dokumen |
| Box 02 | Dossier Copy | 120 dokumen |
| Box 04 | Fidusia | 200 dokumen |

---

## Insertion (Penyisipan Dokumen)

Memasukkan dokumen susulan atau tambahan ke box induk yang ada di MMI.

| Jenis | Definisi | Contoh |
|---|---|---|
| **Dokumen Susulan** | Dokumen yang harus ada saat realisasi tapi terlambat (dari marketing telat) | Kontrak, tagihan, asuransi, SP Dir |
| **Dokumen Tambahan** | Dokumen yang timbul setelah kredit berjalan | Pengkinian data, addendum, ubah cara bayar, BBN |

> Saat ini yang di-scan saat insertion hanya **BBN**. Saat kirim register ke MMI ada kolom perintah scan; setelah scan baru disisipkan ke box.

> Untuk **top up, multiguna, dan restruktur** → tidak melalui insertion; diperlakukan seperti kontrak baru biasa.

---

## Berita Acara CD (BACD) & Proses Scan MMI

### Dokumen yang Di-scan MMI

| Box | Yang Di-scan |
|---|---|
| Box 02 (Dossier Copy) | Form survey dan peta lokasi (kalau ada) |
| Box 04 (Fidusia) | Sertifikat Fidusia — kalau B2B: tidak di-scan |
| Box 01 (Dossier Asli) | Tidak di-scan |

### Proses Lengkap Scan BACD
1. Semua cabang kirim box ke MMI di kota terdekat cabang BCAF
2. MMI scan (H+5) → kirim BA (2 rangkap) + CD + SS Aplikasi TIFF Teller ke KP; CD saja ke cabang untuk upload DMS
3. Isi CD dari MMI: hasil scan (image) · data hasil scan (PDF) · data register isi box
4. PIC scan KP cek: bandingkan file di-scan MMI vs file dikirim ke MMI (total harus sama); sampling per box 10%; cek jumlah file vs jumlah image (lembar)
5. Jika file scan kurang → email dokumen scan ke MMI
6. Buat Berita Acara pengecekan hasil scan → di-PDF-kan + SS Tiff Teller → TTD (Bu Emi)
7. Isi BA: nomor box · jumlah image · jumlah file · jumlah sampling image dan file
8. File hasil scan di-upload ke DMS (pakai BAT File / CLI)
9. Ada register upload DMS: keterangan ok/not ok
10. 16 cabang yang tidak bisa upload DMS → dibantu KP

### Macam-Macam Scan (Biaya Berbeda)

| Jenis Scan | Untuk |
|---|---|
| Grayscale | Dossier Copy |
| Black & White | Dossier Asli |

### Tiering Pengurangan Biaya Keterlambatan Scan MMI

Batas pengiriman hasil scan dari MMI: **H+6** setelah dokumen di-pickup. Keterlambatan mempengaruhi penilaian MMI dan berdampak ke PKS.

| Batas Hari | Reduction Biaya |
|---|---|
| ≤ H+6 | 0% (tidak ada pengurangan) |
| H+7 – H+15 | 5% |
| H+16 – H+30 | 25% |
| H+31 – H+60 | 50% |
| ≥ H+61 | 100% (gratis biaya scan) |

---

## Retrieve & Peminjaman Dokumen

### 4 Macam Retrieve

| Jenis | Ketentuan |
|---|---|
| **Scan** | Minta scan; syarat: tidak ada di DMS atau ada tapi tidak lengkap/tidak jelas |
| **Fisik tanpa memo** | Fisik tidak boleh dibawa keluar dari archive (harus bersama PIC); SLA maks H+7 harus kembali ke MMI |
| **Fisik dengan memo** | Fisik boleh dibawa keluar; SLA pengembalian sesuai memo; approval: dalam operation = s.d. DD; di luar operation = s.d. BOD |
| **Box** | Tidak direkomendasikan (biaya 5× lebih besar); self service ke MMI, hanya bayar admin |

### Alur Retrieve / Peminjaman
1. Pemohon mengajukan form ke email, cc ke TL & UH archive
2. Centang kebutuhan: copy dokumen / dossier copy / dossier asli / fidusia (atau dirinci)
3. PIC registrasi di excel laporan harian (nomor kontrak, nama kontrak)
4. Proses order dengan template form order di excel
5. PIC & UH/TL tanda tangan approval → file di-password → kirim ke MMI via email
6. Biasanya dikirim hari yang sama jika request sebelum jam 12 atau jam 3 sore; setelahnya dipending
7. Registrasi kembali di excel laporan harian: jam & tanggal order + terima · berapa lembar · berkas apa · alasan · unit mana · jumlah order
8. Balancing weekly dari report MMI → cocokkan → TTD + setujui → untuk invoicing (invoice sebulan sekali)

### Catatan Penting Retrieve
- Request fisik: wajib satu bundle map lengkap — tidak bisa hanya satu lembar (scan bisa satu lembar)
- Recheck apakah sudah pernah diminta sebelumnya di email atau DMS sebelum request
- PPK Pasal lengkap tersedia di DMS untuk order tahun 2024 ke atas; sebelum 2024 harus order scan ke MMI
- Dikumpulkan per batch (tergantung banyaknya permintaan); order via email
- **Perbaikan SLIK:** minta PPK Pasal lengkap | **ASR:** copy fidusia | **Legal:** dossier lengkap + fidusia
- Hasil scan dikirim MMI ke unit yang meminta, di-password (password tidak dikirim bersamaan)
- Fidusia manual bisa di-order ke MMI; kalau akta → B2B (order by sistem)
- Jika dokumen unregistered/tidak ada → lempar ke unit fidusia untuk dikirimkan fidusianya

### After Dokumen Diberikan
- PIC assign reminder via email untuk pengembalian sesuai memo
- Dokumen fisik pengembalian wajib lengkap sesuai yang diberikan di awal
- Sebelum diambil: tanda tangan di kertas tanda terima
- Saat dikembalikan: dicek kembali oleh PIC dan UH → TTD pemohon + PIC + TL/UH
- Pengiriman: normal by MMI atau emergency by kurir (biaya sesuai jarak + service)
- Untuk nomor kontrak: cek di OneView per cabang untuk proses order ke MMI cabang

---

## Invoicing & Biaya MMI

### Jenis Tagihan Nasional dari MMI

| Jenis | Keterangan | Biaya |
|---|---|---|
| **Data Entry** | Input rekonsil data di MMI, perhitungan dossier, scanning, double & triple check dokumen kontrak | Rp 350/dokumen |
| **Insertion** | Dokumen susulan yang posisinya sudah di MMI, penambahan cara bayar/KTP konsumen | Rp 3.900/dokumen |
| **Scan B&W** | Dossier Asli & Fidusia | Rp 630/lembar |
| **Scan Grayscale** | Dossier Copy | Rp 680/lembar |
| **CD BA** | Biaya CD + biaya pengiriman (biaya kurir + 12,5% admin) | Rp 6.300/CD |
| **Pengarsipan** | Biaya sewa tempat di MMI; sebelum di-destroy wajib bayar sewa | Box kecil: Rp 3.500 · Box besar: Rp 5.100 |
| **Destroy Shredding** | Per box | Rp 18.500/box |
| **Destroy Admin Pengkinian** | Per dokumen | Rp 2.600/dokumen |
| **Pulping & Bakar** | Metode destroy alternatif | Gratis |

### Harga Box

| Jenis Box | Pulau Jawa | Luar Jawa |
|---|---|---|
| Box Kecil | Rp 11.600 | Rp 16.500 |
| Box Besar | Rp 16.500 | — |

### Perhitungan Dossier (Sebelum Pickup Jumat)
- Setiap box dihitung jumlah dossier secara fisik → sesuaikan dengan data
- Perhitungan bayar per pickup (1 pickup = 20 box)
- Ditandatangani minimal PIC Pengiriman (tanggal scanning, tanggal realisasi, tanggal kirim)
- Box yang sudah jadi: di-sampling dan disetujui minimal TL

### Flow Invoice
1. Invoice diterima
2. Register manual di excel → cek lampiran fisik (invoice per tindakan berbeda: insertion / pengarsipan / scanning)
3. Cocokkan invoice dengan nota perhitungan dossier → konfirmasi ke cabang jika tidak ada TTD cabang
4. Input di e-GER (pilih biaya umum entry) → approval berdasarkan nilai:

| Nilai Invoice | Approval |
|---|---|
| s.d. Rp 2 juta | TL |
| Rp 2 juta – Rp 25 juta | UH |
| Rp 25 juta – Rp 40 juta | DH |
| Rp 40 juta – Rp 100 juta | DD |
| > Rp 100 juta | Minimal 1 BOD |

5. Cantumkan dari apa; upload dokumen tagihan (invoice dirinci per cabang)
6. Kirim ke Procurement + TTD approver + nomor BOP (e-GER)
7. Fisik invoice disimpan ke MMI kalau sudah full 1 box; retensi 10 tahun

---

## Masa Retensi Dokumen

### 10 Tahun

| Kode Box | Jenis Dokumen | Hitungan Sejak |
|---|---|---|
| Box 01 | Dossier Asli | Angsuran terakhir |
| Box 02 | Dossier Copy | Angsuran terakhir |
| Box 03 | Dokumen Pelunasan | Tanggal released |
| Box 04 | Sertifikat Fidusia | Angsuran terakhir |
| Box 05 | Hasil Blokir | Angsuran terakhir |
| Box 06 | Dokumen Penanganan | Tanggal pengaduan masuk |
| Box 08 | Tagihan | Tanggal pengaduan masuk |
| Box 09 | Berkas Klaim & Refund Asuransi | Tanggal pengajuan |

### 3 Tahun

| Jenis Dokumen | Hitungan Sejak |
|---|---|
| Box 07 — Dokumen Administrasi | — |
| Report / Laporan | Tanggal pembuatan/pencetakan |
| Balancing | Tanggal pembuatan/pencetakan |
| Register | Tanggal pembuatan/pencetakan |
| Tanda Terima | Tanggal serah terima |

> **ET (Early Termination):** Masa retensi tidak berubah — ikut tanggal angsuran terakhir awal

> **Write-Off (WO):** Tidak ada masa retensi

---

## Proses Destroy

- Tiap bulan MMI info dokumen yang akan di-destroy → diolah → destroy pakai mesin (shredding)
- Sekali destroy: 200–300 box; proses ±2 hari; diberi bukti CCTV proses destroynya
- H+60 setelah scan: CD di-destroy menggunakan gunting (shredding)
- Kadang Docust menitipkan box untuk di-destroy ke MMI

### Kenapa Destroy Pakai Shredding, Bukan Bakar?
- Pembakaran: harus menggunakan pihak ke-4 yang tidak boleh diawasi, tidak ada CCTV, tidak ada saksi
- Rawan data bocor (kertas bisa tidak sungguhan dibakar, malah dijual kembali)
- MMI hanya menggunakan shredding → lebih aman dan terpantau

---

## Sampling Tahunan

- 3 cabang MMI setiap tahun (semacam stock opname)
- Pergi ke cabang MMI → cek box dan isinya (urutan sesuai, standar penyimpanan)

---

## Dokumen Hilang

- Lihat tracking terakhir dari mana
- Hilang di BCAF → PIC terakhir bertanggung jawab
- Hilang di MMI → denda **Rp 50.000 per kehilangan** + buat surat polisi + surat kehilangan + penilaian berkurang (berdampak ke PKS)

---

## Lain-lain

- Yang upload ke DMS adalah Archive Management
- Dokumen yang masuk DMS hanya yang sering dipakai (storage mahal; dossier tagihan tidak worth it)
- Ada 13 cabang MMI → sudah ada plotingan masing-masing cabang BCAF; cabang bisa langsung ke MMI untuk pengecekan
- Di MMI ada proses data entry (input di sistem MMI) untuk triple check ulang
- Ada form survey meski ada M Survey: double survey BM pakai form BM; KKB pakai vendor survey (tidak upload ke M Survey)
- **Motor:** upload ke Document Imaging by cabang masing-masing (bukan DMS)
- **Motor ke MMI:** pengajuan lewat MOVE ke archive → email ke MMI (dari archive) → MMI pickup ke cabang motor; untuk retrieve & insertion: langsung kasih box, lebih murah biayanya
- Total box: **29.174** hanya di Cikarang

---

*— Akhir catatan Archive Management —*

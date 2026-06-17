# OPERATION MANUAL — BCA FINANCE (PART 2 dari 3)

> Mencakup: **Doc Support & APP** · **Legal & Fidusia**

---

# 5. DOC SUPPORT & APP

## 5.1 DOCUMENT SUPPORT

Checker (verifikasi & validasi data pengajuan pembiayaan dari marketing). Dibagi menjadi: **Non ME · ONE ME · SHF · CC (Checker2) · Revisi & AWC · CIC**

Target harian: 32–38 akun (rata-rata 35). SLA: 13–15 menit (Non-PT) · 30–40 menit (PT/Non ME)

### ONE ME (Perorangan) — CS / DS / KKB

ONE ME = pengajuan perorangan. **Review 1** = cek semua field. **Review 2** = bekas pending, cek field yang di-pending aja.

**SLA & Target**
| Kategori | SLA | Keterangan |
|---|---|---|
| ONE ME | 13–15 menit | Pengajuan perorangan |
| CS | — | Hanya 1 pengajuan per konsumen |

**TAP Konsumen (Calon Debitur)**
- KYC (NIK, Nama, Tgl Lahir): Jika ada salah di 1ME, cek di Aplikasi Gabungan (capil manual by APPID atau E-KTP Reader). Reject jika Nama+NIK+Tgl Lahir semua ❌
- KYC Wajah: Harus clean. Tidak boleh crop/pas foto kecuali KKB DS Klaster A (boleh pas foto) dan KKB DS lainnya (crop foto boleh)
- Watchlist: Cek apakah nasabah adalah PEP (Political Exposure Person)
- Data KTP (Nama/Tgl-Tempat Lahir/Agama/Status Kawin/Jenis Kelamin): Tidak boleh salah → jika salah = REJECT (bukan pending), karena mempengaruhi pengecekan SLIK. Nama dan marital status → penyimpangan ke BM
- Jika data sudah sesuai tapi KYC merah → suruh update dukcapil dan update KTP reader
- Segmentasi KKB: Sesuai inquiry dengan di sistem. Untuk DS → cek RO: >6 bulan = klaster mass, <6 bulan = klaster B
- Engine Scoring: Reject 2 → pastikan sudah ada penyimpangan atau pengajuan BOD
- SLIK: Pastikan SLIK berhasil ditarik
- Foto konsumen: Tidak boleh pas foto (kecuali Klaster A). Tidak boleh AI. Jika foto tidak sesuai dukcapil → wajib ada "Deviasi foto tidak sesuai dukcapil"
- Validasi rekening: Wajib valid (autodebet). Barter/rekening BCA → dicek apakah bisa autodebet
- Dokumen pekerjaan: Profesional = surat ijin praktek; Karyawan = slip gaji 1 bulan (nama harus sama di sistem); Pengusaha = SIUP/NIB/TDP
- Cover KLIK BCA: KKB & DS wajib (jika tidak ada → pending); CS = barter kontrak (lampiran menyusul setelah kontrak jadi)
- KK: Alamat di KK harus sama dengan KTP (kalau beda sedikit = pemekaran). Nama ibu kandung, barcode kelurahan, TTD Kepala Keluarga. Marital status+KTP+KK+NIK sama tapi alamat beda KTP/KK → harus paraf di KK oleh BM + note
- Slip Gaji: Tanggal wajib 1 bulan terakhir, pemilik = nasabah cadeb
- Mutasi Rekening: Kode 2211, 3 bulan terakhir, wajib bisa autodebet (KKB DS)
- Form Consent Konsumen: Wajib ada. Tanggal form consent tidak boleh lebih dari tanggal inisiasi
- Google Map (khusus CS): Jarak dari cabang BCA ke alamat domisili (minimal kelurahan) ≤60 KM. Jika >60 KM → biaya tambahan (tiering sesuai jarak) + penyimpangan BM
- Bukti Rumah (PBB): Nama di PBB harus sama dengan konsumen, tanggal ≤2 tahun. Tidak bisa → penyimpangan ke DD. Bukti: SHM / PBB 2 tahun terakhir / Rekening Listrik 1 bulan (capture website PLN). Maks kepemilikan = orang tua (kakek/nenek tidak boleh)
- M-Survey: KKB & DS Klaster A & B → tidak perlu survey. Selain itu harus survey, alamat survey harus sama dengan domisili. Reguler 2 atau reject 1 → wajib BM mengetahui

**TAP FAP**
- Nama di SID name (hanya nama tanpa gelar/singkatan)
- Patokan rumah: nomor rumah, blok, warna rumah, acuannya
- Rumah ECN tidak boleh sama seperti alamat pemohon. ECN boleh sedarah, tidak boleh sepupu jauh, maksimal kakak/adik/ipar/mertua
- Jumlah tanggungan
- Email wajib untuk KKB DS
- Nomor HP tertaut WA
- Jika ada UMKM → wajib ceklist wiraswasta
- Penyimpangan KKB (jika ada)
- Nominal penghasilan dan nomor rekening
- Data pinjaman: Refinancing = Produktif modal kerja; Mobil beban = Produktif investasi; PT = bisa keduanya; Individu = Non produktif konsumsi
- Cek maskapai asuransi di Gocek sesuai cabang
- KKB DS → input sales agent & sales office
- Penjamin wajib untuk: usia <21 tahun belum menikah, atau PT/Pemilik manfaat

**TAP Matching**
- Ada customer ID tapi tidak matching = REJECT
- Cek di OneView apakah orang yang sama atau bukan
- Data history RO (overdue atau tidak, ada salah matching) → dicek di Financore via Engine Matching
- Untuk PT → dicek per NPWP pengurus PTnya
- Pengajuan >1 → pending dan verifikasi ke CMO

**TAP Collateral**
- Mobil bekas: wajib ada tab watchlist kendaraan, asset registry, Approva, Financore. Mobil baru tapi ada field ini → pending
- CEK STNK tidak expired (bekas); mobil baru tidak ada STNK
- Samain data STNK dengan di sistem
- Tipe pembiayaan: Perorangan = konsumtif & multiguna; Usaha = produktif & modal kerja/investasi
- CEK unit kendaraan di memo ketentuan → jika tidak ada = biaya admin +Rp 1 juta (dipastikan ada)
- CEK bunga flat rate sesuai memo ketentuan (flat bottom + flat max)
- CEK biaya admin sesuai ketentuan (+1 juta jika unit di luar ketentuan; +tiering jika Google Map >60 KM)
- CEK biaya fidusia sesuai tiering
- CEK provisi maksimal 5,5%
- CEK plottingan asuransi sesuai wilayah pengajuan. CS wajib CP → pakai deviasi jika CS tidak pakai CP. CS dengan PH >1M → tidak perlu CP dan tidak perlu deviasi
- CEK nama paket: mobil bekas ada CPR = nama paket mulai dengan WM; DS selalu ada MASS di nama paket (kecuali Klaster A)
- Khusus CS Mobil: cek identitas kendaraan dari STNK (plat nomor, masa berlaku STNK, noka/nosin BPKB, tipe mobil, collateral/bukti kepemilikan rumah). Jika tidak ada bukti rumah → DP minimal 30%

**Dokumen Mandatory ONE ME**
| Dokumen | Status |
|---|---|
| KTP | WAJIB |
| Form Consent | WAJIB |
| FAP | WAJIB |
| Google Map (khusus CS) | WAJIB |
| Bukti rumah | Bisa deviasi jika tidak ada |
| Mutasi 3 bulan (bank sama) | Bisa deviasi jika tidak ada |
| Bukti usaha / slip gaji | Bisa deviasi jika tidak ada |
| Dokumen lainnya | Opsional |

**Barter Kontrak (CS New Car):** Login PDP → Masukkan APP ID → Pilih dokumen kredit (cover KLIK BCA / cover tabungan) → Submit → Masuk bucket APP

**Catatan Lainnya:**
- Minimal asuransi = TLO
- PA tidak boleh untuk pekerjaan membahayakan
- CS wajib TLP kecuali mobil beban. KKB & DS boleh tidak TLP tapi penyimpangan RM
- Setelah checker click proceed → masuk ke bucket MA (atau CC jika menggunakan K3)
- ECN sudah tidak dicek lagi → jika salah = kesalahan marketing
- Review 2 terjadi jika: field warna merah (di-pending checker), field kuning (sudah direvisi marketing), pengajuan >1 ada di engine matching, konsumen masuk daftar blacklist (DP min 30%), kendaraan sudah dijaminkan di asset registry, unit Pajero/Fortuner wajib survey 2x dengan BM

### NON ME — ME Corporate & PDP

Nasabah PT bisa melalui ME Corpo. NON ME individu (via PDP) biasanya karena TPH >5M atau >3 unit. Approval lebih tinggi, wajib ada K3 di beberapa kasus.

**SLA & Target NON ME**
| Kategori | SLA | Target Harian |
|---|---|---|
| NON ME (umum) | 30 menit | 15–17 aplikasi |
| PDP (banyak input data) | Lebih lama | — |
| ME Corpo (cek dokumen terlampir) | Lebih lama | — |
| CV / Yayasan | 2x lebih lama | — |

**Dokumen Mandatory Nasabah PT:** FAP; SS pemilik manfaat; K3; Mutasi 3 bulan; Memo gathering (tergantung paket); NPWP; SIUP; NIB; Bukti segmentasi

**Dokumen Mandatory Nasabah Perorangan:** FAP; KTP; KK; K3; Bukti Rumah; Mutasi rekening; Bukti usaha/slip gaji; Nomor rekening

**Alur Kerja PDP:** Pengajuan masuk PDP → Buka Approva → cari by APPID → Isi customer data (mengacu resume/FAP) → Isi loan data (mengacu K3/FAP) → Isi notary note → Isi resume PT (pemegang saham) — individu tidak ada → Proceed 1x → status jadi Recommendation → isi deviasi → Proceed lagi → naik ke CC untuk pengecekan inputan

Dokumen di PDP diberi keterangan OK atau Not OK (jika pending). Jika di-pending → balik ke marketing. 1 APP ID = 1 Unit.

**Alur Kerja ME Corporate:**
- Data masuk ke bucket ME Corpo (nasabah PT)
- Cek inputan ME Corpo berdasarkan dokumen pengajuan (FAP, K3, data diri)
- K3 dipakai jika PH >5M dan unit >3
- Kode lokasi proyek wajib diisi
- Pastikan alamat sesuai
- Pastikan ada email (konsumen PT biasanya KKB DS)
- ECN minimal Manager
- Pengurus wajib dilampirkan KTP
- Lihat loan dari masing-masing pengurus → sesuai resume atau tidak
- Cek 2211 (status rekening)
- Cek pemilik manfaat / beneficial owner
- Cek mutasi rekening
- Expo → cek SPK dari program yang diambil. Jika tidak ada di data expo → pending. Cek: Paket, Unit, APPID/MID
- FAP harus ada nomor registrasi
- Benefit bunga & admin sesuai
- Sesuaikan detail kendaraan dengan nama BPKB (jika beda nama BPKB → deviasi lagi)

**Tab di Aplikasi Checker ME Corporate:** Corporate Data; Collateral and Loan Data; Matching Result; Poin Rekomendasi

**Kondisi Reject Nasabah PT:** Nama PT salah atau NPWP salah → di-reject karena berpengaruh ke SLIK

**Catatan Lainnya NON ME:**
- ME Corpo → pemegang saham perorangan dan PT
- Jika tidak bisa lampirkan NPWP PT → masuk via PDP
- PDP = wadah untuk CMO lampirkan dokumen → bisa di-pending jika Not OK
- Khusus CV dan yayasan → proceed di ME dan approval juga diproses
- Aplikasi Gabungan untuk cek rekening autodebet dan NPWP valid
- Inquiry 2211 = bukti status rekening KKB/DS
- Inquiry 9433 = bukti segmentasi individu
- Inquiry 9435 = bukti segmentasi perusahaan
- Asuransi sudah ada plottingan per wilayah (diisi oleh marketing). Bisa pilih asuransi lain (tetap rekanan) tapi pengajuan ke DD

### SHF (Showroom Financing)

SHF = showroom gadaikan BPKB dengan bunga pasti 9% flat, tenor maks 3 bulan (min 1 bulan). Pengajuan via PDP atau ME SHF. Pengajuan pertama kali wajib via PDP.

**SLA & Target SHF**
| Kondisi | SLA |
|---|---|
| SHF normal | 10–15 menit |
| Pendingan (cek field di-pending saja) | Lebih cepat |

Tidak ada reject di ME SHF. SHF hanya diproses di WPI (tidak di WTC dan Surabaya).

**Aplikasi yang Digunakan:** One Plafond (pengecekan plafond showroom); One ME (s3 sso → QA SHF, bucket sama seperti One ME, 1 aplikasi); Aplikasi PDP (pengajuan pertama kali); Approva (cek watchlist & edit data)

**Alur Pengajuan SHF (Umum):** PDP / ME SHF → Approva → PDP (pending/pengajuan pertama) → Proceed → MA → Upload kontrak di PDP (kontrak manual di Approva)

**Dokumen Mandatory ME SHF (sudah pasti RO):** FAP; BPKB; STNK; Faktur; Foto kendaraan; KTP (opsional)

**Dokumen Mandatory PDP:** KTP YBS dan Pasangan; KK; K3; Asset Registry (SS → isi BPKB sedang dijaminkan atau tidak); BPKB; Faktur & STNK; Foto kendaraan; Cover buku tabungan

**Alur Pengecekan via ME SHF (dari sisi checker):**
- Register berkas di Excel untuk laporan ke TL / pendataan pribadi
- Cek plafond pakai nama showroom via Aplikasi Plafond KKB: masa berlaku, nominal dan sisa plafond, termasuk group plafond
- Cek engine matching untuk watchlist kendaraan atau konsumen, termasuk resume
- Cek validasi rekening di Aplikasi Gabungan (NIK valid, rekening bisa autodebet — wajib hukumnya)
- Cek watchlist perorangan: jika NIK invalid → update NIK ke CS. Data tagihan, kredit internal/eksternal, repo, political exposure, WO, notif tidak sesuai engine matching
- Cek FAP → samakan dengan sistem dan kertas FAP
- Cek STNK/BPKB identitas kendaraan & pemilik → STNK wajib hidup. Jika expired dan mau urus: pakai biro jasa BCAF = penyimpangan sampai BM; biro jasa luar = penyimpangan BOD. Jika tidak ada tipe umum di BPKB → penyimpangan RM
- Cek nomor rangka dan mesin di BPKB → inquiry Financore, cek body no
- Loan data: masa plafond max 3 bulan, DP 20% untuk rank 200 atau plafond 5M, bunga flat & effective 9%, loan harus in arrear, payment wajib autodebet
- Top 200: ada asset registry → cek BPKB di leasing lain. Jika ada deviasi sampai DD. Cek di BPKB admin untuk fisik BPKB

**Hal Penting Lainnya di SHF:**
- Untuk pengajuan RO = melalui ME SHF
- Ketentuan SHF sama seperti CS Used. Bedanya: SHF boleh lebih dari 2 unit; CS Used hanya 1 unit
- ME SHF = tidak pakai K3; PDP wajib pakai K3 + wajib input di Approva lagi
- Tipe kendaraan di BPKB, Faktur, dan STNK harus sama. Jika berbeda → harus ada penyimpangan (dokumen acuan). Jika tidak ada penjelasan = pending
- Selama pengajuan, plafond showroom harus tetap aktif
- Cek tenor → pending jika tenor lewat masa aktif plafond
- PH tidak boleh lebih dari plafond
- Cek tipe kendaraan via memo (tabel: tipe kendaraan, tahun, DP min). Jika di luar ketentuan → penyimpangan BOD. Ada biaya admin +Rp 1 juta jika pengajuan di luar ketentuan unit kendaraan
- Berlaku juga untuk KKB DS
- Setelah aplikasi proceed/pending → hilang dari bucket
- Jika di asset registry BPKB sudah dijaminkan: cek apakah showroom top 200 → jika ya bisa penyimpangan sampai DD → di-hold pas pencairan sampai jaminan di tempat lain diselesaikan
- SHF murni hanya ada PH saja, tidak ada biaya admin dan tidak ada asuransi (diisi no insurance)
- Alur SHF ME: Checker → KK → CIC. Alur SHF PDP: masuk bucket CC2 → final check → printing → disbursement
- Setiap revisi di ME SHF setelah final check → wajib pakai nomor kontrak baru. Biasanya Rp 100.000 untuk bukti bayar revisi
- Cek di VA Gabungan. Yang bisa direvisi sebelum final check: rubah hitungan, naikkan % DP. Ganti dokumen non-tagihan → tidak bayar. Setelah final check → semua inputan tidak bisa direvisi oleh Document Support
- Wiraswasta wajib lampirkan NIB/SIUP. NIB atas nama pemilik dan pasangan ada nama pengaju

**Mandatory SHF (Review TL):** Data FAP; Data kendaraan; Faktur kendaraan bermotor dari dealer; BPKB difoto lembar perubahan, identitas pemilik & kendaraan; STNK; Status beda (marital) untuk pemilik showroom atau nasabah RO; Cek masa berlaku resume AHU dan plafond (sisa nominal plafond SHF). Pengajuan tidak boleh lebih dari 3 bulan atau sebelum masa expired plafond SHF

### CC — Checker 2 (Kontrak Manual, Karoseri)

CC (Checker2) = pengecekan kembali dari inputan NON ME (ME Corpo & PDP), melakukan kontrak manual, dan revisi/data maintenance. Jobdesc utama: jembatan untuk proceed aplikasi jadi Printing tanpa lewat CC2.

**Aplikasi yang Digunakan:** PDP; Approva; Inquiry QA (ME Corpo)

**Pengecekan Kembali oleh Checker CC:**
- Meneruskan proses realisasi dari status CC1 menjadi Printing tanpa lewat CC2 (jika sudah pakai K3 di awal)
- Proses yang pakai K3 di awal: pengajuan NON ME via PDP atau aplikasi ME Corporate untuk konsumen yayasan, CV, dan Firma → perlu input lagi di Approva karena jabatan direksi di resume tidak ada di sistem Approva (misal: bendahara organisasi → di Approva hanya ada direktur, komisaris)
- Jika ada typo kecil → CC bisa langsung edit di Approva. Jika tidak sesuai tapi tidak ada deviasi/penyimpangan → di-pending
- Overkredit, Reschedule, dan Restruktur pengajuannya juga lewat PDP

**Karoseri (Mobil Box):** Karoseri = mobil box di mana chasis dan box bisa dilepas. Chasis dari dealer A, Box dari dealer B → bayar ke dua tempat.

- 3 K3: K3 Gabungan (diinput ke sistem); K3 Unit Chasis; K3 Unit Karoseri
- 3 PO: PO Gabungan (diinput ke sistem); PO Dealer Chasis; PO Dealer Karoseri
- Dokumen kontrak tetap jadi satu
- Boleh 1 K3 + 1 PO jika chasis dan box di perusahaan/dealer yang sama
- Tujuan 3 PO + 3 K3 = untuk memisahkan pembayaran

**Kontrak Manual — Kapan Dilakukan:**
- RUPS (perusahaan TBK)
- Surat dikuasakan
- Kontrak gabungan (1 kontrak berisi banyak unit dengan OTR/PH sama atau berbeda)
- Kontrak karoseri
- Juklak (program khusus dealer → PO dan kontrak berubah tapi sistem tidak)
- SP Kom Terpisah
- Istri lebih dari 1 → semua istri tanda tangan kontrak
- Konsumen <21 tahun belum menikah → sistem nama konsumen, tapi yang TTD kontrak adalah kedua orangtua

Untuk print kontrak manual → sistem perlu di-stop sampai status Printing. Caranya: pilih deviasi penyimpangan engine printing (di ME oleh marketing, atau di Approva Recommendation oleh checker)

**Alur Kontrak Manual:** CC1 → di-approve jadi Printing → Buka Approva → pilih signer (BOH cabang) → Pilih dokumen yang di-print (sesuai tipe) → output Word → Edit Word sesuai kebutuhan → save jadi PDF → Proceed dari Approva: Printing → Final Check → Upload PDF ke PDP (upload PO + Kontrak)

**Dokumen yang Di-Print (Kontrak Manual Badan Usaha):** Estimasi tabel angsuran; Ikhtisar; SKPB (SK Pengambilan Jaminan); Blanko kwitansi; PO; SP Direktur; SK Fidusia; SP Dealer; Riplay; Perjanjian Pembiayaan; SP Komisaris; Resume (RUPS)

**Dokumen yang Di-Print (Kontrak Manual Perorangan):** Estimasi tabel angsuran; Ikhtisar; SKPB; Blanko kwitansi; PO; SK Fidusia; SP Dealer; Riplay; Perjanjian Pembiayaan

**Dokumen yang Di-Print (Kontrak Manual SHF):** Estimasi tabel angsuran; Lampiran perjanjian pembiayaan modal kerja; Surat konfirmasi dan penarikan showroom financing

**Berkas Lainnya (SHF):**
- SHF wajib lampirkan Faktur Kendaraan, BPKB, dan STNK AKTIF (jika expired → pengajuan perpanjangan STNK ke BCAF dulu)
- Bisa lampirkan memo plafond. SHF wajib cek status BPKB di BCAF (perpanjangan harus status Released/Borrow), maks pengajuan 2x per showroom. Boleh pindah showroom jika status Closed
- Refinancing: wajib BPKBnya. Topup: status di Financore lancar & borrow. Refinancing 1: Close

**ONE ME — Catatan Tambahan:**
- Inputan dari CS, KKB, dan DS. KKB & DS boleh foto pas/crop. KKB DS wajib lampirkan email
- Peka terhadap perhitungan marketing (loan data) dan penyimpangan/deviasi (dicek di Gocek)
- Review 1 = cek semua; Review 2 = cek field yang di-pending saja
- Bisa edit langsung di Engine Printing (biasanya Ikhtisar, PO, Riplay/Juklak)
- Jika di-pending CC → langsung balik ke marketing
- Menggunakan One View untuk cek deskripsi kendaraan dan riwayat klaim asuransi di BCAF. Jika pernah klaim asuransi di BCAF → tidak boleh diajukan. Jika klaim di luar BCAF → boleh

**Perbedaan Refinancing**
| Jenis | Kondisi BPKB | Usia Kendaraan | Bunga | Branch Name |
|---|---|---|---|---|
| Semi Leaseback (Reff 2) | Belum jadi (Cover Note) | ≤3 bulan | Mobil baru reguler KKB | REFF 2 |
| Refinancing for New (Semi Reff) | Sudah jadi | 4–12 bulan | Mobil baru | REFF 1 (sistem = bekas) |
| Refinancing 1 | Sudah jadi | >12 bulan | Mobil bekas | REFF 1 |

Pengajuan refinancing melalui KKB/DS, bukan dari CS. Pengambilan BPKB → ada showroom yang hanya mau diambil oleh konsumen sendiri → BCAF dan konsumen ambil bersama ke dealer

### Revisi & AWC

Bucket Revisi → aplikasi PDP + Tasklist Revisi dokumen kontrak. Ada 2 pekerjaan PIC Revisi: **Revisi Kontrak** (status Approva = Final Check) dan **AWC** (status Approva = CC2).

| | AWC (Amendment Without Contract) | Revisi Kontrak |
|---|---|---|
| Status Approva | CC2 | Final Check |
| Biaya | Tidak berbayar | Rp 100.000 (jika kesalahan dari marketing) |
| Paling banyak karena | BBG | Hitungan (naik DP, ganti tenor) |

**Alur Revisi Kontrak:** Buka Approva → pastikan status Final Check → Buka PDP → buka K3 revisi → lihat penyimpangan (untuk tahu apa yang perlu direvisi) → Cek bukti bayar Rp 100.000 di PDP (bukti bayar maks hari H naikkan revisi, boleh H-1) → Cek pejabat wewenang approval dengan memo di K3 → jika belum sesuai = pending → Jika sesuai → revisi data di Approva (data maintenance), samakan dengan K3 → Recalculate loan value (selalu setiap ada perubahan data) → samakan dengan K3 (jika beda = pending) → Save Approva → Proceed PDP → Save

Revisi yang berhubungan dengan hitungan → wajib lampirkan K3 di PDP. Revisi tidak berhubungan hitungan → tidak wajib K3, tapi lampirkan print out MA (SS) + TTD penyimpangan (tergantung memo). Boleh tanpa bayar revisi jika ada memo revisi (contoh: Revisi tipe mobil).

**Alur AWC:** Buka Aplikasi MA → bucket AWC → lihat permintaan AWC (contoh: ubah OTR) → Pastikan di Approva statusnya CC2 → Cek di PDP → K3 AWC → apa yang perlu diubah → Bisa naik banding dengan approval DD → Ubah data sesuai K3 di Approva (data maintenance) → Recalculate → cek nominal loan benar sama seperti di K3 → Save Approva → OK & Proceed di PDP → Complete di MA

**BBG — Ubah Penjamin Showroom:** AWC paling banyak karena BBG (ubah penjamin showroom)

**Dokumen BBG:** KTP penjamin showroom (biasanya pemilik); FAP bagian belakang (ada data penjaminnya); Form BBG (penjamin showroom)

**Alur BBG:** Ubah di Approva → Customer Data → Recalculate → Save → Save Approva → PDP Proceed → AWC Complete

Inputan data KTP tidak bisa direvisi → pasti di-reject

**Catatan Lainnya di Revisi:**
- Renvoi: Alur sama seperti revisi → di kontrak tidak berubah tapi di sistem berubah
- Komponen nomor VA di Aplikasi Gabungan untuk revisi: `710000 + Revisi ke berapa (1) + APPID + 001`
- Cek app ID, tanggal, dan VA online di Aplikasi Gabungan (search by no VA)
- Jika belum bayar = revisi di-pending
- Bisa hapus deviasi di Approva → Recommendation → Deviation (jika deviasi sebelumnya tidak berlaku lagi karena AWC/revisi)
- AWC 1 = masih diproses marketing. AWC 2 = sudah di-OK/pending dari checker

### CIC (Checker Information Center)

CIC = penghubung antara BM/marketing dengan Checker, supaya aplikasi yang masuk minimal kesalahannya (berpengaruh ke insentif checker). CIC juga menjadi penengah antara target realisasi marketing dan kepatuhan SOP checker.

**3 Group Central CIC**
| Group | Lokasi | Keterangan |
|---|---|---|
| WPI | Jakarta | Handle cabang WPI + proses SHF (SHF hanya di WPI) |
| WTC | Jakarta | Handle cabang WTC |
| Surabaya | Surabaya | Handle cabang Surabaya |

Masing-masing group handle cabangnya masing-masing (sudah ada plottingan). Checker Surabaya boleh dapat aplikasi Jakarta, tapi jika ada pending → BM tetap koordinasi dengan tim CIC Surabaya. CIC tidak bisa cancel aplikasi di luar group centralnya.

**Aplikasi yang Digunakan:**
- Menu Inquiry Aplikasi di PDP — pengecekan meskipun sudah di-proceed atau sedang dibuka checker (tidak nabrak)
- Tools Maintain — logging staff checker. Cek by APP ID: log aktivitas, username, tanggal, status. Fungsi: (1) lihat pekerjaan checker (list proceed/pending); (2) regist kesalahan checker untuk penilaian; (3) reminder checker "seharusnya tidak di-pending ini". Dipegang CIC saja
- Sharing Go Check — rangkuman persyaratan pengajuan; cek deviasi (kode deviasi) untuk penyimpangan ke KK/Engine Printing; cek segmentasi (approve 1&2, regular 1&2, reject 1&2); cek order maskapai asuransi per cabang; cek cabang tertentu masuk ke group central CIC mana
- Approva — input manual data (struktur kepengurusan yayasan dengan banyak pemegang kuasa)
- Resume AHU — masa berlaku 15 bulan dari last proceed/dibuat. Biasanya sudah terlampir NIB, KTP, NPWP
- Engine Matching — melihat konsumen RO dan APP ID berjalan
- Aplikasi Gabungan — cek rekening (pending jika NPWP tidak valid/rekening tidak bisa didebet), cek capil manual jika NIK/nama di 1ME semua X (jika NIK dan nama beda = lampirkan surat dari kelurahan/pengadilan negeri)
- Financore + One View — data konsumen, cek RO. Konsumen Mass bisa naik ke Klaster B jika Active Order >6 bulan atau RO lunas ±6 bulan. Cek status BPKB dan Total Pokok Hutang (TPH)
- Watchlist — cek history kesamaan data (konsumen, showroom, BPKB sedang digadai atau tidak)
- PDP — lihat inputan kontrak manual/lainnya. Perorangan atau RO harus meet requirement TPH 5M dan/atau unit >3
- ME SHF — melihat pengajuan SHF via ME SHF (sejak 2023). Pengajuan SHF baru pakai PDP. Tidak boleh ada tanda baca. KTP pasangan wajib dilampirkan jika sudah menikah
- Asset Registry — cek BPKB sedang dijaminkan atau tidak

**Jobdesc CIC:**
- Update memo baru dari Bispro dan CMC (dari email) → dibaca, dirangkum, dishare ke group checker insight. Memo lengkap ditaruh di cloud
- Memo gathering: nasional = di-email oleh CMC; cabang = dilampirkan di pengajuan. Isi memo gathering: contoh biaya admin dikurangi (di luar ketentuan berlaku)
- Koordinasi dengan BM dan Marketing terkait pendingan atau pertanyaan dari cabang
- Jika ada AWC rancu dari RM/DD → konfirmasi lewat atasan dulu
- Inputan field pending terbatas → BM/marketing bisa informasikan ke CIC untuk tambahan pending
- Upload data urgent aplikasi yang diminta konsumen: data dari BM (send APP ID di WA Group CIC & BM cabang) → kabari checker untuk dikerjakan langsung
- Jaga registeran expo (data dari CMC, dikirim per 15 menit oleh IT) → data digunakan checker untuk cek nomor VM nasabah KKB DS yang order di periode EXPO. Pastikan nama, FAP tipe unit, dan benefitnya (paketnya) sudah sesuai
- Sosialisasi dengan checker terkait kesalahan pending; sosialisasi ke cabang oleh unit head
- Kesalahan pending paling banyak: salah paket, salah bunga, seharusnya tidak di-pending tapi malah di-pending

**Cancel Aplikasi**
| Status | Yang Bisa Cancel |
|---|---|
| Data Entry s/d CC2 | CIC |
| Final Check | Yang reject APP (bukan CIC) |
| Initiation | Marketing |

**Alasan Aplikasi Di-Cancel:** Pengajuan double (error sistem, atau konsumen setuju di 2 tempat sekaligus); Konsumen batal pengajuan; Data salah (NIK, tempat/tanggal lahir, agama, jenis kelamin, status nikah)

Untuk cancel → harus ada form cancel di PDP (dibuat oleh cabang). Bisa cancel printing di Approva (ada menunya) → status jadi cancel/gugur.

**Catatan Lainnya CIC:**
- APP ID vs MID: APP ID = dibuat di Approva (dari PDP) → Creator: angka; MID = dibuat dari mobile (ONE ME) → Creator: Mobile. Multiguna (dari MAC) → Creator: angka
- Pengajuan UMK3, Restruktur, COP, Overkredit = melalui PDP. Restruktur = kontrak baru, yang lama tertutup
- Perbedaan Deviasi vs Penyimpangan: Deviasi = sudah di-list Bispro, langsung connect ke aplikasi. Penyimpangan = dari pejabat wewenang, berupa free text
- Status CC3/CC4 di Approva sudah tidak ada → jika muncul biasanya karena error
- JF/SF dipilih oleh Finance → semua pengajuan default SF. Usia lunas maks 64 tahun; jika >64 tahun (khusus Klaster A & B) harus lampirkan strong rekomendasi dari kanwil (tanda tangan kepala kanwil) agar status JF. Jika tidak ada = SF
- Pengajuan mini for max = otomatis JF jenis pembiayaannya
- Multiguna: by system, no checker. Jika mau tanya struktur kredit atau plafond kurang → langsung ke Bispro, kecuali mau edit data non-KYC
- Untuk konsumen tanpa survei harus penyimpangan klaster: A & B → RM; Klaster Mass → DD
- Badan usaha wajib punya fixed line kantor (jika tidak ada → deviasi). ECN wajib ada, tidak boleh sama dengan alamat konsumen, minimal manager/direktur
- Klasterisasi PT = selalu reguler untuk engine scoring
- Hitung usia lunas: 2026 + tahun tenor – tanggal lahir
- Rekening tidak bisa autodebet biasanya karena baru buka rekening

---

## 5.2 APP — ACCOUNT PAYABLE PAYMENT

3 Proses Utama: **Register → Checker → Approval**. APP juga ada di cabang (handle semua jobdesc). APP di KP (WPI) handle: 8 cabang KKB · 5 Cabang DS · 2 Cabang CS Used · 2 Cabang CS New.

Tim KP: Register 2 orang · Checker 5 orang · TL 2 orang · Checker Non Jabo 2 orang · UH 1 orang

### Register APP (Jabo)

Bagian APP yang menerima dokumen Tagihan dan Dokumen Kontrak fisik yang sudah di-TTD CMO dan Konsumen. Status di Approva saat diterima = **Final Check**.

**Kode Warna MAP**
| Warna | Jenis Pembiayaan |
|---|---|
| Hijau | KKB (Kredit Kendaraan Bermotor) |
| Biru | CS New + CS Used |
| Kuning | DS (Dealer Subsidi) |
| Biru Dongker | UMK3 + Multiguna |
| — | SHF: via e-invoice, tanpa fisik MAP |

**Jam Penerimaan Dokumen (2 Batch)**
| Batch | Jam | Realisasi |
|---|---|---|
| Batch 1 | 08.30 – 10.30 | Hari H (langsung jika tidak ada pending) |
| Batch 2 | 10.30 – 16.00 | H+1 |

**Pengantar Dokumen:** Messenger; CMO; Dealer (tagihan saja); Marketing Support

**Alur Dokumen Masuk:** Pengantar stempel waktu di mesin (halaman Checklist Penyusunan Dokumen Tagihan & Kontrak) → Admin register terima → masukkan ke map berwarna sesuai asal + tempel stiker (nama konsumen, no kontrak, APP ID) + form checklist aplikasi APP → Cek form Checklist Penyusunan → lanjut ke Prepare Dokumen

**Form yang Ada:**
- Form Checklist Penyusunan Dokumen Tagihan & Kontrak — diisi CMO berdasarkan kelengkapan dokumen. Berbeda untuk mobil baru vs bekas. Dilampirkan di halaman depan set dokumen (untuk internal).
- Form Checklist Aplikasi APP — disteples di depan map. Isi: tanggal & jam tagihan/kontrak diberikan, PIC Register, PIC Checker.
- Form Permohonan Maintenance Data — menyatu dengan Form Checklist Aplikasi APP. Bisa diisi CMO saat menyerahkan dokumen (jika konsumen ingin perubahan data), atau oleh checker jika ada perubahan saat konfirmasi (contoh: perubahan nomor telepon). Ubah cara bayar/ubah CMO bisa via memo. Ubah tipe kendaraan → harus diajukan ulang oleh CMO via PDP. Maintenance dilakukan oleh Analis APP di Sigma Approva.

**Alur Prepare Dokumen:** Susun urutan dokumen sesuai form checklist → Dokumen kontrak = di-klip; Dokumen tagihan = di-bolongin → Jika dokumen lengkap → stamp semua lembar Form Checklist Aplikasi APP di mesin clock-in (dapat tanggal dokumen lengkap)

Jika hanya kasih tagihan → tanggal di tagihan saja, tanggal kontrak menyusul saat kontrak diserahkan.

**Alur Register:** Register di Excel (tanggal & jam masuk tagihan/kontrak · yang menyerahkan · PIC Checker) → Search APP ID di Approva → catat Branch ID, nama konsumen, no kontrak → Map dimasukkan ke box: "Tagihan Masuk" (kontrak+tagihan atau tagihan saja)/"Kontrak Masuk" (kontrak saja tanpa tagihan) → Checker ambil dari box → jika pending, masukkan map ke kotak pending masing-masing

Dokumen kontrak tidak boleh dibolongin, hanya di-klip. Dokumen tagihan boleh dibolongin dan disatukan di map. Jika pendingan sudah OK → stempel tanggal di bawah kanan Form Permohonan Maintenance Data.

**Dokumen Pasca Realisasi — Cek Autodebet:**
- Dokumen selesai realisasi masuk ke APP Register → cek autodebet: pastikan nama & nomor rekening di Financore = buku tabungan
- Jika nomor rekening buku tabungan ≠ Financore → konsumen ajukan SKPR (Surat Kuasa Pendebetan Rekening) ditempel meterai → approve perubahan nomor rekening
- Keesokan paginya → tim Register serah terima dokumen ke Legal Admin

**Dokumen Mobil Baru**

*Dokumen Tagihan:* Kuitansi Pelunasan; Blanko Kuitansi; Kuitansi DP; Delivery Order; Persetujuan Pembiayaan/PO; FAP; Formulir Aplikasi Asuransi

*Dokumen Kontrak:* 1 set PPK & Ikhtisar; Gesekan no rangka & no mesin; Estimasi tabel angsuran; RIPLAY Personal; Cover Note/SP BPKB; SK Fidusia; RIPLAY Maskapai Asuransi

*Dokumen Tambahan Mobil Baru:* Personal Guarantee/Corporate Guarantee (jika ada permintaan dari management/penyimpangan); Form Hasil Survey/SK Pengambilan Barang Konsumen (kalau tidak menggunakan M-Survey); Cover Buku Tabungan & Copy Klik BCA/Inquiry Status Rekening (2211); SP Dealer yang tidak mengeluarkan CN (F04 = surat dealer pengganti CN); Form Consent; Surat Pernyataan Pemahaman PPK & Riplay (customer consent); SKPR (jika didebet ke rekening selain debitur); SP Refinancing (jika refinancing)

*Dokumen Tambahan Khusus Badan Usaha (Baru & Bekas):* Surat Pernyataan Direktur/Surat Persetujuan Komisaris (salah satu, boleh keduanya); Surat Pernyataan Pemegang Saham (jika TBK); Berita Acara RUPS (jika TBK); Surat Pelepasan Hak (SP Hak); Form Pendaftaran di Aplikasi FINA (SS halaman Y/N)

**Dokumen Mobil Bekas**

*Dokumen Tagihan:* Kuitansi Pelunasan; PO + SPT (jika di PO ada lebih dari 1 no rekening showroom); Kuitansi Pelunasan khusus Penjual Non-Dealer (boleh kwitansi pasar: tertulis "telah terima dari PT BCAF/KKB qq Nama Konsumen", di-TTD Penjual Non-Dealer & bermaterai); FAP; Kuitansi Down Payment (kecuali Refinancing); Formulir Aplikasi Asuransi

*Dokumen Kontrak:* 1 set Perjanjian Pembiayaan Konsumen & Ikhtisar Fasilitas Pembiayaan; Estimasi tabel angsuran; Copy BPKB; RIPLAY Personal; RIPLAY Maskapai Asuransi; Copy STNK; SK Fidusia; Form Survey Maskapai, Foto Kendaraan & Gesekan no rangka/mesin (jika tidak ada di M-Survey)

*Dokumen Tambahan Mobil Bekas:* Personal Guarantee/Corporate Guarantee (jika ada permintaan management); Tanda Terima BPKB; SK Pengambilan Barang; SP Refinancing (jika refinancing); Form Hasil Survey Konsumen (jika tidak ada di M-Survey); SP Showroom; BAST; Cover Buku Tabungan & Copy Klik BCA/Inquiry Status Rekening (2211); Customer Consent; Surat Pernyataan Pemahaman PPK & RIPLAY; SKPR (jika didebet ke rekening selain debitur)

Mobil bekas → BAST; mobil baru → Delivery Order. Refinancing: set dokumen mirip used car, bedanya TTD di PO = konsumen sendiri (bukan dealer) + ada kuitansi pelunasan atas nama konsumen.

**Dokumen Tagihan Khusus Refinancing Top Up:** Kuitansi Pelunasan; Formulir Konfirmasi BPKB (cek melalui sistem); Memo Potong Pencairan melalui Controlling Account (MEMO CA)

**Catatan Lainnya di Register:**
- Tiap pagi ada rekap pendingan (Excel) → dikirim email ke BM cabang
- Register bisa cancel aplikasi (karena marketing request atau konsumen batal) dan cek autodebet-nya. Bisa juga change payment type
- Cancel aplikasi ≠ cancel realisasi. Cancel aplikasi: status masih Final Check
- Form cancel isinya: nama konsumen, APP ID, no kontrak, alasan batal, nama CMO, nama cabang. Di-TTD BM → Upload ke PDP → aplikasi cancel oleh CMO → PIC Register cek form cancel di PDP. Cancel hanya bisa dilakukan di cabang masing-masing
- Dokumen PO di-stamp: tanggal realisasi, diperiksa oleh (checker), disetujui oleh (approval)
- Mobil bekas → STNK 1 dan 5 tahunan harus aktif
- Register ngecek penyimpangan di ONE ME → di-pending jika dokumen penyimpangan tidak lengkap
- Personal Guarantee/Corporate Guarantee: tergantung komite minta yang mana. Jika konsumen tidak bayar 6 bulan → guarantee bertanggung jawab

### Register Non Jabo

Menerima dan mengelola dokumen yang dikirim oleh APP cabang. Untuk checker non jabo = ada di cabang masing-masing. Di KP hanya ada register non jabo (tidak melakukan pengecekan lagi karena sudah pernah dicek).

**Limit Approval — Di Kantor Pusat (KP)**
| Nominal | Pejabat |
|---|---|
| 0 – 500 juta | TL |
| 500 – 750 juta | UH |
| 750 juta – 1 miliar | DH |
| >1 miliar | DD |

DD/DH untuk tanda tangan & proceed. DD cuti bisa diganti DH OA.

**Limit Approval — Di Cabang Non KP**
| Kelas Cabang | Limit TL | Limit BOH |
|---|---|---|
| A & B | 250 juta | 500 juta |
| C | 250 juta | 350 juta |
| D | — | 300 juta |

BOH cuti → kewenangan naik ke KP

**Kenapa Cabang Masuk ke Register Non Jabo?**
- Dokumen realisasi via Bank Transfer >500 juta atau di luar batas approval kewenangan cabang
- Dokumen realisasi Control Account (refinancing, top up) → semua nominal pelunasan harus dikirim ke KP → dokumen diprint dan didistribusikan ke FSM (close akun lama) dan Payment (pencairan)

Jika realisasi Bank tapi limit approval melebihi cabang → langsung masuk ke aplikasi disbursement di KP (tidak perlu lewat register non jabo).

**Flow Register Non Jabo:** Cabang input regist di Excel tracking monitoring (via GForm): jam · nama cabang · APP ID · Batch ID → Cabang kirim memo disbursement lewat email ke KP → Admin register non jabo terima → cari APP ID di Sigma Approva → cek status "Approval Disbursement" → cek limit proceed → Jika limit masih dalam kewenangan cabang (misal control account) → dokumen dikumpulkan di keranjang → didistribusikan messenger → cabang proceed → masuk bucket payment → Jika melebihi kewenangan cabang → diberikan ke approver di KP (TL/UH/DH/DD) sesuai limit → ditandatangan & diproceed → Admin cek Sigma Approva memastikan pengajuan sudah diproceed approver terkait

**Distribusi Memo Disbursement (jika Controlling Account)**
| Tujuan | Kondisi |
|---|---|
| FSM | Ada proses buka tutup akun (top up, SHF Relokasi: SHF → laku mobilnya → jadi reguler) → dikembalikan ke APP → ke Payment |
| Payment | Karoseri, Hold Dana |
| CMC | Juklak (subsidi dealer) → di-approve CMC dulu → dikembalikan ke APP → up ke Payment |

Distribusi Memo Disbursement ke FSM = buka tutup akun: ada 2 akun (lama & baru), akun lama ditutup karena tidak digunakan lagi. Contoh: reff top up.

**Dokumen yang Dilampirkan:**
- Top Up: Memo disbursement · PO · Memo CA (dibuat marketing) · Hitungan ET · K3/MA
- Juklak: Memo disbursement · Memo paket (nominal dibayar sesuai PO + nominal disubsidi) · PO · Excel perhitungan juklak · MA/K3 · SPT · Ikhtisar · Form persetujuan paket · SPK
- Hold Dana: MD (ada note hutang/kekurangan dokumen, TTD BOH) · PO

**Catatan Lainnya:**
- Di Excel ada field jam distribusi → diisi jam berapa dokumen didistribusikan (dokumen fisik)
- Di Financore bisa narik report terkait memo dan approval disbursement → untuk tahu aplikasi yang belum diproceed (contoh: cabang lupa naikkan ke KP)
- Jika ada pending atau revisi → koordinasi via Sparks. Di Spark tidak bisa kirim file → jika revisi selesai, kirim ulang via email
- Cabang tidak bisa distribusi sendiri, harus lewat KP
- Di cabang: jika mau data maintenance, dari BOH-nya. Disbursement memo Bank = lewat AppDis. Disbursement memo CA = harus fisik memo disbursement

### Checker APP (Jabo)

Checker APP = validasi berdasarkan dokumen fisik + konfirmasi by phone. Berbeda dengan Docsup: pegang fisik dokumen, bekerja setelah kontrak terbit, merupakan **pintu terakhir** sebelum realisasi. Multiguna tidak dicek di sini (dicek di aplikasi multiguna).

**KPI & SLA**
| Metrik | Target |
|---|---|
| KPI harian | 15 konsumen pencairan |
| SLA APP | 2 jam (dari dokumen masuk register hingga proceed) |

**Alur Kerja Checker APP:** Ambil map dari kotak register (Tagihan Masuk/Kontrak Masuk) → Buka aplikasi: Engine Matching · Cek Absah · MA · Mobile Survey · Specimen Dealer · PDP (jika ada perubahan K3) → Cek dokumen di map vs sistem → Ceklis dokumen di Sigma Approva → Register ke Excel (lanjut pengisian yang sama dengan register) → Jika pending → letakkan map di File Pendingan, tunggu marketing lengkapi → Jika OK → konfirmasi by phone ke konsumen → Jika konsumen bisa dikonfirmasi → proceed di Approva: Final Check → Disbursement Memo (pilih CA atau Bank) → masuk bucket Approver

**Pengecekan Dokumen di Checker APP:**
- Cek penyimpangan di MA dan PDP (penyimpangan tambahan). Cari by MID di MA, by APP ID di aplikasi lainnya
- Pastikan dokumen pendukung berdasarkan pendingan tersedia
- Cek track record di Financore (jika dulu unit bekas lelang → jika diajukan pembiayaan lagi jadi SF agar tidak dobel jaminan)
- Cek K3 di PDP: jika ada → tidak perlu diprint dan ditaruh di map, kecuali ada penyimpangan tambahan baru → baru diprint dan dilampirkan
- Nasabah PT: cek pengurus dan SP Direktur di resume + ME Corpo. One View baru ada data setelah realisasi
- Cek validasi rekening dan NPWP (tidak valid → penyimpangan ke BM)
- Mobil bekas: cek STNK expired? Jika expired dan mau diperpanjang via BCAF → harus pakai dokumen Memo CA + OTTPSB (urus di CS manual) beserta hitungannya dari CS
- Multiguna: cek di OneView pastikan tenor multiguna ≤ tenor individu
- Cek nomor rangka & nomor mesin antara dokumen tagihan vs foto gesek di Mobile Survey
- Cek hasil cek absah di aplikasi ACA
- Cek PO (ada revisi dari komite kredit? Pastikan PO terbaru)
- Cek TTD di blanko kuitansi vs capture di MA (KTP konsumen, cover buku tabungan)
- Cek capture Klik BCA → memastikan keaslian nomor rekening
- Cek foto TTD kontrak di Mobile Survey → konsumen harus memegang kontrak bagian TTD. Jika tidak sesuai → pending, CMO ajukan penyimpangan ke RM via MA manual. Jika RM OK → baru konfirmasi konsumen. Klaster A KKB tidak perlu; KKB klaster B dan MASS perlu; CS Mobil perlu
- Cek TTD pejabat dealer di Specimen Dealer vs Kuitansi Pelunasan (harus sama). Jika tidak ada TTD+stempel di Specimen Dealer → minta CMO, register data dealer di aplikasi Specimen Dealer
- Cek hitungan pembiayaan
- Cek BPKB di FKB (menu konfirmasi BPKB di One ME) → jika sudah approve = sudah aman dari BM. KKB wajib ada inquiry; DS dan CS Mobil tidak wajib (cukup klik + cover tabungan)

**Data Krusial yang Dicek Checker APP**

*Customer Data (dicek):* NIK · Noka Nosin · SID name/pengurus · Nama gadis ibu kandung · Alamat email · Rekening konsumen · No HP · Tanggal lahir

*Customer Data (tidak perlu dicek):* ECN · Alamat rumah (juga tidak divertel) · Status kawin · Pekerjaan · Penghasilan konsumen

**Loan Data = SEMUA crucial** (dari atas sampai bawah, tidak bisa ditawar)

**Konfirmasi by Phone (bukan "vertel") — Siapa yang Wajib Dikonfirmasi?**
| Jenis Konsumen | Wajib Konfirmasi? | Pengecualian |
|---|---|---|
| Perorangan | Wajib SEMUA aplikasi | Multiguna & Refinancing 1 perorangan (BPKB sudah di BCAF, tidak perlu). Reff 2 = masih CN/SP BPKB → tetap dikonfirmasi |
| Badan Usaha | Wajib semua | Termasuk refinancing dan multiguna |

**Pertanyaan Konfirmasi by Phone:** Data konsumen (konfirmasi dengan FAP/sistem); Email dan nomor telepon; Tanggal lahir konsumen dan nama gadis ibu kandung; Data kendaraan (konfirmasi dengan PO): tipe mobil, tahun, warna, showroom/dealer, STNK atas nama siapa; Sudah terima unit atau belum, dan kapan terima kendaraan; Mobil dipakai untuk apa; Sudah tanda tangan kontrak atau belum; Angsuran per bulan berapa; Informasikan jatuh tempo; Konfirmasi cara bayar, nomor rekening jika autodebet; **TIDAK menanyakan alamat**

Jika konsumen tidak bisa jawab detail kendaraan → masih ditoleransi, yang penting bisa menyebutkan garis besar (tipe dan merk). Konfirmasi dilakukan jika unit sudah diterima konsumen.

**Kondisi Khusus Konfirmasi:**
- KKB: bisa penyimpangan BM jika unit belum diterima (agar tetap diproses) → MA manual. Penyebab unit belum diterima: tidak ada hubungan antara CMO dengan dealer, atau dealer tertentu (misal Auto 2000) harus pencairan dulu baru dikirim
- CS: info ke marketing → marketing beri tahu APP Checker jika unit sudah diterima → APP konfirmasi ulang
- 3x berdering tidak diangkat → informasikan ke marketing agar konsumen standby
- Data tidak sesuai saat konfirmasi → pending, minta marketing sesuaikan data
- Konsumen tidak ingin dikonfirmasi → penyimpangan dengan TTD BOD
- Unit belum turun & sudah dikonfirmasi → tidak perlu konfirmasi ulang, kirim email verifikasi via IT. APP menerima 'report konsumen realisasi belum terima kendaraan' di Financore

**Controlling Account vs Bank**
| Pilihan | Kondisi | Proses Tambahan |
|---|---|---|
| Bank | Tidak ada potongan pada pencairan | Proceed langsung → AppDis → Payment |
| Controlling Account (CA) | Ada potongan: Multiguna (perpanjang STNK), Reff TopUp, Paket subsidi/juklak, Perpanjangan STNK | Print Memo Disbursement (MD) di Approva dulu → proceed → TL (Approval Disbursement) → distribusikan MD fisik ke dept terkait |

**Hold Dana:**
- Karena hutang dokumen (FOGE belum ada): Marketing buat memo persetujuan proceed + TTD Pak Frans (DD Operation). Memo dikirim ke admin register non jabo untuk diprint dan dilampirkan ke Payment. Harus di-TTD UH dan Dept Head sebelum ke DD.
- Hold Dana 10%: Dana yang dicairkan ke dealer hanya 90%, ditahan 10% sampai BPKB jadi. Untuk dealer mobil mewah non-ATPM (meminimalisir risiko karena harga mahal dan pembuatan BPKB lama).

**Perbedaan TTD Tidak Sesuai:**
- Jika TTD berbeda antara dokumen kontrak dan sistem → masuk bucket Approver
- Jika menurut Approver TTD tidak bermasalah → dikembalikan ke checker untuk dikonfirmasi
- Jika menurut Approver memang beda TTD → masukkan ke File Dokumen Pending

Foto TTD kontrak dikirim konsumen ke CMO → diupload ke Mobile Survey → di-approve BM. Jika belum di-approve BM → tidak akan muncul di Mobile Survey bucket checker.

### Distribusi Dokumen Pasca Realisasi (H+1)
| Dokumen | Dikirim ke |
|---|---|
| Dossier asli + copy | Legal Admin |
| CN + Blanko BPKB | BPKB Admin (dipisahkan oleh Approver setelah proceed) |
| Polis Asuransi | Asuransi |
| OTTPSB | CS |

Setelah Approver proceed → blanko kuitansi dan CN dipisah dari set kontrak untuk BPKB Admin. Dokumen yang sudah diproceed di sistem kemudian diambil kembali oleh tim admin register.

### Approval APP

Approval dilakukan oleh TL. Status Approva di sini: **Approval Disbursement**. Tujuan: cek ulang apa yang sudah dicek checker, lalu proceed ke bucket Payment/FSM. Poin kritis = semua dokumen harus valid dan lengkap.

**Perbedaan Approval vs Checker**
| Aspek | Checker | Approval (TL) |
|---|---|---|
| Telepon konsumen | Ya | Tidak |
| Input noka/nosin, CN | Ya | Tidak |
| Input di Sigma Approva | Ya | Tidak |
| Cek usia & kendaraan | Ya | Ya (juga hitung usia & rate) |
| Cek bukti survei | Ya | Ya (di Mobile Survey) |

**Aplikasi yang Digunakan:** AppDis (Approval Disbursement) — proceed sebelum masuk ke FSM/Payment; Approva — melihat data lengkap yang diinput checker; MA (Mobile Approval) — cek penyimpangan dan persetujuan dari BM/RM/DD; PDP — melihat penyimpangan tambahan dari K3 atau dokumen lainnya yang tidak ada di ME; One View — data customer dan kendaraan; Aplikasi Gabungan — cek validasi rekening

**Pengecekan Dokumen Fisik:** Kelengkapan dokumen: jika PT → cek SP Direktur, samakan data perusahaan dengan resume di aplikasi resume; cek perhitungan pembiayaan di K3 dan PO; Cek tanda tangan; Cek jika ada revisi: apakah kontrak sudah direvisi atau belum

**Pengecekan Sigma Approva:** Loan Data (kondisi mobil, tipe mobil, nomor BPKB, no mesin, no rangka, total DP samakan dengan ME, bunga, tipe pembiayaan); Customer Data (nama tidak boleh ada tanda baca, cek jenis kelamin, nomor NPWP); Memo Pencairan (cek no rekening konsumen, nama rekening)

**Tab di AppDis:** Memo pencairan; MA vs Approva; Summary MA (Deviasi, Approval Komite Kredit); Customer Loan Data; Loan Data; Persyaratan Realisasi Lainnya (sudah survey/belum, dll)

**Status & Tombol di AppDis**
| Tombol/Status | Fungsi |
|---|---|
| Proceed | Realisasi |
| Pending | Dikembalikan ke cabang |
| Cancel | Batalkan aplikasi |
| Save | Simpan sementara |
| Reject (TL Docsup) | Status berubah dari Approval Disbursement → Final Check. TL Docsup checker hanya berwenang ubah noka/nosin jika salah input. Analis bisa ubah: email, nama ibu kandung, JF/SF, purpose pembiayaan, dana pencairan |

Ketika sudah masuk ke TL, harusnya dokumen sudah lengkap (tidak mungkin pending). Nominal >1M → bucket AppDis langsung ke DD, tetapi yang proceed = DH/UH. Sistem di AppDis tidak vertikal, langsung sesuai kewenangan.

**Alur Pencairan Setelah Proceed**
| Kondisi | Alur |
|---|---|
| Reguler | FSM dulu → Payment |
| Memo CA (topup, tutup akun) | FSM dulu → dikembalikan ke APP → Payment |
| Subsidi/Hold Dana | CMC dulu → dikembalikan ke APP → Payment |

Payment langsung full bayar ke dealer (tidak dicicil). Feedback dari Payment/FSM via memo tolakan → TL cek alasan dan informasikan ke marketing untuk pelengkapan dokumen.

**Memo CA (Control Account) — Berkaitan Dengan:** Perubahan nomor kontrak lama ke baru (contoh: Refinancing Top Up); Selisih nominal: juklak (subsidi dari dealer, biasanya paket) atau kepengurusan BBN (estimasi biaya dari CS); Showroom: tanggungan STNK harus diselesaikan dulu sebelum di-SHF-kan; Topup: bisa ada memo CA karena perpanjangan STNK atau BBN yang dilampirkan OTTPSB dari CS

**Keterkaitan APP dengan CMC (Memo Juklak):** Dokumen dilampirkan ke CMC by Messenger (analyst) via GForm (pilih juklak atau hold dana). Isi: a. Persetujuan dealer; b. Juklak; c. Memo CA; d. PO; e. SPT (opsional); f. Mobile Approva capture; g. SPK; h. Memo disbursement; i. Ikhtisar

Juklak kebanyakan dari electric vehicle: Cherry, Jaecoo, Geely, dsb. CMC akan melihat harga OTR dan berkas scan untuk dokumentasi berdasarkan PKS yang berlaku antara BCAF dengan dealer.

**Non-Jabo Checker — Dokumen Fisik di KP:** PIC Non-Jabo (Checker) bisa menerima dokumen fisik di WPI jika: cabang realisasi tapi dealer di Jakarta, atau sebaliknya, atau konsumen minta TTD kontrak di Jakarta. Alur: Cabang/KP verifikasi & informasikan ke PIC KP/Cabang → PIC terima & cek dokumen → TTD by nasabah → scan & kirim ke cabang/KP → realisasi → kirim berkas via messenger

### Aplikasi yang Digunakan di APP
| Aplikasi | Fungsi |
|---|---|
| AppDis (Approval Disbursement) | Proceed sebelum masuk FSM/Payment. Tab: Memo pencairan, MA vs Approva, Summary MA, Customer Loan Data, Loan Data, Persyaratan Realisasi Lainnya |
| Approva (Sigma Approva) | Melihat data lengkap yang diinput checker |
| MA (Mobile Approval) | Pengecekan penyimpangan dan persetujuan dari BM/RM/DD |
| PDP | Penyimpangan tambahan dari K3 atau dokumen lainnya yang tidak ada di ME |
| One View | Data customer dan data kendaraan |
| Aplikasi Gabungan | Cek validasi rekening |
| FKB | Konfirmasi keberadaan BPKB di BCA Finance. Masa berlaku 1 bulan. Diproses oleh document custodian, harus di-order dengan marketing (topup, refinancing, atau BPKB diambil lalu mau refinancing lagi) |
| M Survey | Pengecekan survei konsumen, TTD kontrak, kendaraan, dan konsumen |
| Engine Matching | Memastikan watchlist, double-check nomor rangka dan nomor mesin |
| ME (One ME, ME Corporate, ME SHF) | Pengajuan aplikasi |
| Aplikasi Multiguna (MAC) | Multiguna langsung dicek oleh APP (diisi CMO → masuk bucket APP). Multiguna tidak survey. Wajib autodebet. Terhubung otomatis ke Approva & AppDis. Ada info deviasi-deviasi |
| Resume | Cek resume, biasanya pengajuan dari PT |
| ACA (Cek Absah) | Mengecek keaslian BPKB dan blokir di BPKB Admin |
| Aplikasi B2B Asuransi | Jika ada kasus cover mundur |
| Specimen Dealer | Cek TTD pejabat dealer dan blokir di BPKB Admin |

### Analyst APP

**Tugas Utama:**
- Maintain Data — contoh: alamat email, SID name, alamat. Request datang dari map dossier (sticker Form Permohonan Update/Maintain Data), atau via chat Spark. Data yang tidak bisa diubah = berkaitan dengan hitungan kredit
- Perubahan data tidak perlu approval (terkait dokumen pendukung dan pengecekan → checker yang kerjakan). Perubahan data terlihat di report (siapa yang edit)
- Diusahakan proses data maintenance tidak ada kesalahan

**Report Bulanan**
| Laporan | Tujuan | Deadline |
|---|---|---|
| Report SL APP (2 jam) | OSD | H+5 awal bulan |
| Report SL Docsup (15–30 menit) | OSD | H+5 awal bulan |
| Exception Report | OSD | H+5 awal bulan |

SL dilihat berdasarkan rata-rata cabang (bukan per MPP). Report per cabang; untuk KP per group central (untuk Docsup). Exception report dari OSD → yang kerjakan TL, analyst hanya backup.

**Pembuatan Report:** Cabang kirim Excel regist via email → Analyst rekap dan olah data → Bandingkan dengan tarikan data di Microsoft Access → Diolah dalam bentuk PPT → Dikirim ke OSD

### Pendaftaran Autodebet

Tugas: memastikan tidak ada trouble dalam pendaftaran autodebet. SL pendaftaran: Mobil = H+2 dari tanggal realisasi; Motor = H+1 dari tanggal realisasi.

**Proses Harian:** Tiap pagi TL export Excel report list akun yang akan didaftarkan autodebet → Motor: tarik data via Fast App → report registrasi autodebet → lihat yang belum dapat status → Jam 11: dapat feedback dari BCA → tarik report lagi → list process harus sudah hilang semua (artinya berhasil) → Masih ada di list process → minta IT untuk pengecekan → Ada tolakan → monitor dan reminder cabang untuk segera diselesaikan

**Status Autodebet**
| Kode | Arti |
|---|---|
| NW | New Entry |
| UP | Updation (setelah ditolak lalu diselesaikan cabang) |
| RT | Return (tolakan) |
| AC | Active |
| CL | Close |
| PC | Process Close |

Saat order → pastikan status UP atau NW. Mata uang rekening = IDR. Rekening tidak boleh ada perjanjian khusus dengan BCA (misal lock dana).

**Penanganan Tolakan**
| Jenis Tolakan | Lokasi | Cara Beresin |
|---|---|---|
| Tolakan Autodebet | Aplikasi Gabungan | Beresin di Change Payment Method (Financore mobil) · Fast App (motor) |
| Tolakan Realisasi | Financore | Yang beresin = CS (pengkinian data) |

- Tolakan paling sering: nama rekening tidak sesuai → cek mobile banking ejaan nama vs Approva → sesuaikan
- Beresin di Financore (mobil): menu Change Payment Method → status harus dari Retur ke Autodebet
- Tolakan motor: di Fast App
- Akun dormant → konsumen harus ke BCA untuk isi form
- Rekening sudah tutup → buat rekening baru
- Akhir hari: tarik report perubahan payment → cek jika ada autodebet ke non-konsumen (nama tidak sesuai)
- Reporting internal ke UH jika ada perubahan data autodebet

**SKPR (Surat Kuasa Pendebetan Rekening):**
- Jika konsumen ingin change payment atau autodebet ke rekening berbeda → wajib lampirkan SKPR
- SKPR: 2 lembar (1 ada kop BCA Finance), keduanya ditempel meterai
- Setelah SKPR dilampirkan → ubah data di Financore oleh admin register (atas nama rekening baru)
- Jika ingin autodebet beda rekening dari awal → marketing harus minta konsumen isi SKPR + ajukan penyimpangan ke RM

**Penginputan Rekening di Sistem**
| Jenis Konsumen | Approva | Financore |
|---|---|---|
| Individu | No rekening di customer data & loan data saling terhubung (boleh input salah satu) | Tab Customer Data → Bank Info = rekening untuk realisasi; Tab Loan Data/Account → Bank Info = untuk autodebet |
| Badan Usaha | No rekening di customer data & loan data tidak terhubung → wajib input di loan data | Sama seperti individu |

Konsumen perorangan tapi rekening autodebet ke PT → pastikan orang tersebut adalah pengurus di PT tersebut (cek di resume). Field Handphone 1 di Approva → digunakan oleh CS Pengiriman untuk kirim kontrak via WA jika email gagal.

---

# 6. LEGAL & FIDUSIA

## 6.1 LEGAL ADMIN

### 5 Bagian Legal Admin
1. **Reprint** — H+1 pasca realisasi · Cap tanggal + tera materai · Data kendaraan dari Approva+Financore
2. **Checker** — One View + Resume + DMS · Tembak sistem DRONE · Register maintenance → renvoi jika perlu
3. **Tera Materai** — Ikhtisar hal. 3 + SK Fidusia wajib · SKPR + F04 opsional
4. **Renvoi** — Terima dari admin · Pengetikan ulang "dibenarkan" · Kirim ke Legal → Tera materai
5. **Scan & Upload** — 6 urutan scan · Upload DMS oleh archive · Dossier copy di-scan cabang

**Urutan Scan Dokumen (6 Urutan):**
1. PK depan (Perjanjian Kredit halaman pertama)
2. Pasal-pasal PPK
3. Ikhtisar kontrak
4. Lampiran (perjanjian tambahan)
5. Tabel angsuran
6. RIPLAY personal

### Isi Dossier Asli & Copy

**Dossier Asli — Perorangan:** PK (Perjanjian Kredit); Pasal-pasal PPK; Ikhtisar kontrak; Lampiran perjanjian; Tabel angsuran; RIPLAY personal; SKPB (Surat Keterangan Pembiayaan Berlaku); Sp Reply; BAST (khusus mobil bekas); SK Fidusia

**Dossier Asli — Badan Usaha (Tambahan):** SP Direksi — WAJIB; SP Komisaris (jika ada); Form Final — WAJIB

**Dossier Copy:** Dokumen di luar dossier asli, contoh: PO, Kwitansi dealer, lampiran tambahan

## 6.2 ADMIN FIDUSIA

### PIC Prepare — Order Sertifikat Fidusia

**Jabodetabek — B2B (Bank to Bank):**
- H+4: cek data One ME + One View + DMS
- H+5: order sertifikat fidusia ke notaris rekanan
- Proses via sistem, tidak perlu fisik ke notaris

**Non B2B:** Order manual via aplikasi FIDUSIA. Dokumen fisik dikirim ke notaris: FC PPK; SK Fidusia asli; NIB perusahaan; AKTA pendirian; KTP Komisaris + Direksi; NPWP perusahaan; SK Domisili; SIUP; SIB (Surat Izin Berusaha); CN + BPKB

**Non-Jabodetabek:** Cabang scan dokumen dulu → email ke KP; Setelah fisik diterima PIC → serah terima resmi; Bukti tanda terima → TTD Legal Admin Authorized

### Adendum (PIC Mas Adam)

**2 Jenis Adendum:**
- BBN (Balik Nama): Perubahan nama di dokumen jaminan fidusia
- UBJ (Ubah Barang Jaminan): Penggantian kendaraan jaminan

**Dokumen Adendum Perorangan (15 Dokumen):** KTP konsumen, KTP penerima baru, KK, Akta nikah/cerai (jika perlu); STNK baru, BPKB baru, Surat keterangan dealer; Form adendum yang sudah diisi lengkap; Dan dokumen pendukung lainnya (total 15 item)

**Dokumen Adendum PT (5 Dokumen):** Akta perubahan perusahaan; SK Pengesahan baru; NPWP baru; NIB baru; KTP pejabat baru

**Flow BBN Non-Jabo:** Terima berkas → Bongkar → Susun ulang → Registrasi → TTD Signer (Mba Latifah) → Order notaris

**Flow BBN Jabo:** Tera materai → Insertion

**Alasan Adendum:** Pajak progresif (perubahan nama agar pajak lebih rendah); Hadiah (kendaraan dihibahkan)

### Sertifikat Fidusia

SLA OJK: 30 hari (lebih dari 30 hari → SP Notaris)

**Alur B2B (Sistem):** Terima dari sistem → Verifikasi data → Approve/Reject

**Alur Manual:** Input: nama notaris + order date + receive date + no sertifikat + invoice

**Satu Set Serah Terima (BU):** Salinan akta fidusia; Minuta fidusia; Invoice notaris; Sertifikat fidusia fisik

**Perbedaan Sertifikat:**
- Kode 01: "Sertifikat Jaminan Fidusia" — akta baru
- Kode 02: "Perubahan Jaminan Fidusia" — adendum

### PIC Fidusia Motor (Mas Robby)

**4 Aplikasi:** Fast APP; Move; Web Report; Dok Imaging

**4 Notaris Rekanan:** Ario; Leodi; Joniva; Hafidz

**Pengecekan Nomor Kendaraan:** No rangka: 17 digit; No mesin: 12 digit

**Sampling:** 20% dari total sertifikat yang diterima; Upload manual format: Kode Cabang–No Kontrak–Fidusia

### Resume AHU (PIC Sandi) & Cek Dokumen BU

**Resume AHU:** SLA: 1x24 jam; Aplikasi: Resume AHU/Ditjen AHU/AHU Fidusia Online; RAD BCA: tidak perlu order AHU (sudah terintegrasi)

**Beli Voucher SIMPADHU (6 Langkah):** Maksimal 5 voucher per pembelian; Masa berlaku: 60 hari

**4 Klasifikasi Risiko BU**
| Risiko | Dokumen yang Diperlukan |
|---|---|
| Rendah | NIB saja |
| Menengah Rendah | NIB + Sertifikat Standard |
| Menengah Tinggi | NIB + Sertifikasi Terverifikasi |
| Tinggi | Izin penuh |

NIB saja → tambah Izin Usaha + Izin Lokasi/SK Domisili. BU baru <2 tahun → memo penyimpangan diperlukan

## 6.3 BPKB ADMIN

### Pra Realisasi — Cek Absah + Blokir
- Cek Absah: Verifikasi keaslian BPKB (bukan palsu/aspal)
- Cek Blokir: Pastikan BPKB tidak sedang dijaminkan ke leasing lain

### Used Car — Alur BPKB (11 Langkah)
ACA register (input APP ID) → Cek kesesuaian data → Checklist ASLI → Submit → Tanda terima TTD PIC+Messenger → Print tanda terima → Satukan dengan faktur → Scan BPKB upload DMS → Order birojasa → E-blokir (SLA 1–2 hari) → H+1 BPKB ke Docust

**Birojasa Used Car:** DEWIJANTI; ARMANDO

**Area Tanggung Jawab:** KP: 8 cabang Jabodetabek; Cabang: sesuai wilayah masing-masing

**Biaya:** Luar kota: Rp 500.000 (absah + blokir + ongkos birojasa); KP: Rp 110.000; Cabut blokir: Rp 50.000

**3 Batch Order Birojasa:** Batch 1: >jam 10 hari sebelumnya → diproses hari ini; Batch 2: <jam 10 hari yang sama; Batch 3: maks 10.30 akhir bulan

Ref Top Up: tidak perlu cek absah + blokir. Batal realisasi: tetap kena biaya absah + blokir + admin + birojasa

### New Car — CN & Blanko BPKB
- New Car: tidak perlu cek absah dan blokir
- CN (Cover Note) valid maksimal 90 hari
- Tanggal CN: maksimal 60 hari sebelum realisasi

**5 Birojasa New Car:** Bisa Aja; 858; Armando; Rudi Liwan; Karimuna

**PIC Penerimaan CN + Blanko (4 Langkah):** Terima CN dari dealer; Cek kesesuaian data; Input sistem; Simpan sesuai urutan

**PIC Order CN (5 Langkah):** 4 angka depan = kode cabang

**PIC Follow-up:** Metode: email/WA/kunjungan akhir bulan. >90 hari → kirim SURAT PERINGATAN

**PIC Penerimaan BPKB New (9 Langkah):** Terima dari birojasa → Cek fisik BPKB → Cocokkan dengan blanko → H+1 gabung blanko → H+2 kirim ke Docust

### Kepengurusan STNK

**Walk-in Luar Kota:** Layanan: Balik Nama/Mutasi BBN/Perpanjangan STNK. OTTPS + dokumen cabut berkas diserahkan konsumen

**WPI (Walk-in Pusat):** Email ke Docust untuk minta borrow BPKB. Sebelum jam 12 → BPKB bisa dikirim hari H. Setelah jam 12 → H+1

**Wewenang Pembayaran STNK/BBN**
| Nominal | Approver |
|---|---|
| Rp 2 – 25 juta | UH |
| Rp 25 – 40 juta | DH |
| Rp 40 – 99 juta | DD |
| >Rp 100 juta | BOD |

**Ex BBN (Setelah Balik Nama Selesai):** Terima dari birojasa → Cek BPKB vs FC STNK → Maintenance Financore → Register → Cek e-blokir → Blokir manual/online → Maintenance no blokir → Scan → H+1 ke Docust

---

*— Akhir Part 2. Lanjut ke Part 3: Docust & Archive, Asuransi, Operation Area, OSD, OQA —*

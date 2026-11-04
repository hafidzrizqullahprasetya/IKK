# Tugas IKK — Prioritas Fitur & Perumusan Minimum Viable Product (MVP)

- **Mata Kuliah:** Ide Kreatif dan Kewirausahaan (IKK)
- **Kelompok:** Dekat.in
- **Anggota:**
  1. Hafidz Rizqullah Prasetya (24/535493/SV/24243)
  2. Pralambang Bhayangkara Yhudanto (24/536223/SV/24414)
  3. Alfiz Desta Ariant Permana (24/543220/SV/25173)
  4. Danny Setiawan (24/541304/SV/24894)
- **Tautan Dokumen Google Docs:** [Buka Google Docs](https://docs.google.com/document/d/14LWd_ehOCGU3XGErlBbaGf-zYLgNBPdrEghfveJYrKQ/edit?usp=sharing)
- **Tahap:** Perumusan Nama Produk, Inventarisasi Fitur, & Seleksi MVP (Litmus Test)

---

## 1. Konteks Masalah & Solusi

Berdasarkan hasil wawancara lapangan (*Customer Discovery*) pada 10 responden dan pemetaan *Value Proposition Canvas* (VPC):
* **Masalah Inti:** Pelaku UMKM mikro dan penjual rumahan (*frozen food*, katering harian, kue basah, buket) kesulitan menjangkau calon pembeli di sekitarnya (<3–5 KM). Di media sosial jangkauan organiknya tenggelam oleh algoritma, sedangkan di aplikasi pesan-antar makanan konvensional margin keuntungannya tergerus potongan komisi (20%–30%) dan pembeli sering membatalkan transaksi karena tingginya biaya ongkos kirim kurir instan.
* **Solusi Terpilih:** Platform etalase digital *hyperlocal* berbasis radius mikro dengan pemesanan langsung terhubung ke WhatsApp (*Direct-to-WhatsApp*), mempertahankan margin keuntungan utuh 100% (0% komisi) dan membebaskan pembeli dari beban biaya ongkir kurir pihak ketiga melalui opsi *Self-Pickup* atau antar langsung oleh pedagang.

---

## 2. Usulan Nama Produk / Aplikasi

| No | Rekomendasi Nama | Rasional & Filosofi |
| :---: | :--- | :--- |
| **1** | **Deketan** *(atau Dekat.in)* <br>⭐ *Pilihan Utama* | Menggunakan bahasa Indonesia sehari-hari yang sangat komunikatif dan santai. Secara instan menyampaikan nilai utama platform: jarak fisik yang sangat dekat (<3–5 KM) dan kemudahan transaksi antar-warga sekitar. |
| **2** | **Larisin** | Diambil langsung dari fenomena organik riset Threads (*"Tolong Bantu Larisin Jualanku"*). Memiliki resonansi emosional yang kuat dengan harapan para pedagang rumahan pemula. |
| **3** | **TetanggaKu** *(atau EtalaseTetangga)* | Mengedepankan aspek *community-driven commerce* dan semangat saling dukung sesama tetangga (*support local*), sangat cocok untuk target lingkungan perumahan dan kos-kosan. |
| **4** | **WarungRadius** | Menggambarkan fungsi teknis produk secara eksplisit: menemukan aneka produk jualan rumahan dan warung terdekat berdasarkan batasan radius kilometer. |
| **5** | **PojokLokal** | Memberikan kesan ramah dan hangat (*homey*), merujuk pada direktori produk-produk rumahan unik (*hidden gem*) yang ada di sudut-sudut lingkungan sekitar. |

---

## 3. Inventarisasi 10 Kandidat Fitur Produk

Berikut 10 fitur fungsional yang dikumpulkan dari hasil ideasi dan sintesis kebutuhan pengguna:

1. **Pendeteksi Lokasi Otomatis & Filter Radius Mikro (<3–5 KM):**  
   Mendeteksi lokasi pembeli melalui GPS perangkat atau input kelurahan manual untuk menyaring produk yang hanya berada dalam radius terdekat.
2. **Katalog Produk Sederhana (Foto, Nama, Harga, Deskripsi Singkat):**  
   Halaman daftar etalase dan kartu detail produk yang menampilkan foto makanan/barang, harga yang jelas, dan profil ringkas penjual.
3. **Tombol *1-Click Direct-to-WhatsApp* dengan Template Pesan Otomatis:**  
   Tombol pemesanan langsung yang membuka aplikasi WhatsApp penjual dengan format teks pesanan yang terisi otomatis (nama produk, varian, jumlah, dan pilihan ambil/antar).
4. **Formulir Unggah Produk Kilat Ramah Ponsel (Tanpa Dasbor Rumit):**  
   Formulir web sederhana bagi penjual untuk memasukkan produk hanya dengan mengunggah foto, mengetik nama makanan, harga, dan nomor WhatsApp tanpa perlu membuat akun dasbor toko yang kompleks.
5. **Penanda Opsi Pengambilan: *Self-Pickup* (Ambil Sendiri) & Antar Mandiri:**  
   Label penanda yang jelas pada setiap produk mengenai metode pemenuhan pesanan: apakah pembeli bisa mengambil sendiri ke lokasi penjual atau diantar langsung oleh penjual.
6. **Gerbang Pembayaran Terintegrasi (*In-App Payment Gateway* / QRIS / Rekening Bersama):**  
   Sistem pembayaran otomatis di dalam aplikasi dengan penampungan dana (*escrow*) sebelum diteruskan ke rekening penjual.
7. **Peta Navigasi Interaktif (*Interactive Map Pinpoint*):**  
   Tampilan peta digital (seperti Google Maps / OpenStreetMap) yang dapat digeser dan diperbesar untuk melihat sebaran titik lokasi penjual secara visual.
8. **Sistem Ulasan dan Penilaian Bintang (*Review & Star Rating*):**  
   Fasilitas bagi pembeli untuk memberikan ulasan tertulis, foto ulasan, dan rating bintang 1–5 pada profil toko penjual.
9. **Fitur Promosi Berbayar (*Featured Listing / Top Badge*):**  
   Slot iklan berbayar terjangkau (misal Rp10.000/minggu) agar produk penjual tertentu disematkan pada baris paling atas etalase radius.
10. **Pelacakan Status Pesanan Real-Time (*Live Order Tracking*):**  
    Sistem pemantauan status pesanan secara bertahap (Diterima, Sedang Dimasak/Disiapkan, Siap Diambil/Diantar) dengan notifikasi pembaruan langsung.

---

## 4. Evaluasi & Uji Eliminasi Fitur (Metode *Litmus Test*)

> ### 🔍 Pertanyaan Penguji (*The Core Litmus Test*):
> **"Tanpa fitur ini, apakah masalah utama pengguna (produk UMKM rumahan ditemukan tetangga terdekat & bisa dibeli tanpa potongan komisi serta bebas ongkir mahal) masih dapat diselesaikan?"**
> * **Jika TIDAK:** Fitur tersebut adalah **Fitur Inti (Core MVP)** yang wajib ada pada peluncuran perdana.
> * **Jika MASIH BISA:** Fitur tersebut adalah **Fitur Tambahan** yang dapat ditunda ke fase pengembangan selanjutnya.

| No | Nama Fitur | Pertanyaan Uji: Tanpa fitur ini, apakah masalah utama pengguna masih selesai? | Status Klasifikasi | Rasionalisasi & Keputusan |
| :---: | :--- | :---: | :---: | :--- |
| **1** | **Pendeteksi Lokasi & Filter Radius Mikro (<3–5 KM)** | **TIDAK** | **FITUR INTI (MVP)** | Jika filter radius dihilangkan, etalase akan menampilkan produk acak secara nasional persis seperti media sosial. Pembeli tidak akan bertransaksi karena terbentur ongkos kirim. |
| **2** | **Katalog Produk Sederhana** | **TIDAK** | **FITUR INTI (MVP)** | Tanpa foto, nama, dan harga produk, calon pembeli tidak memiliki informasi dasar untuk mengambil keputusan membeli. Proses *discovery* gagal total. |
| **3** | **Tombol Direct-to-WhatsApp (1-Click)** | **TIDAK** | **FITUR INTI (MVP)** | Tanpa integrasi chat langsung, pembeli tidak punya saluran pemesanan, dan platform gagal menyediakan transaksi 0% komisi yang menjadi nilai tawar utama. |
| **4** | **Formulir Unggah Produk Cepat (Mobile)** | **TIDAK** | **FITUR INTI (MVP)** | Penjual mikro berjualan menggunakan smartphone. Jika proses unggah produk rumit dan membutuhkan dasbor komputer, platform tidak akan memiliki pasokan data katalog (*cold start failure*). |
| **5** | **Penanda Opsi Self-Pickup / Antar Mandiri** | **TIDAK** | **FITUR INTI (MVP)** | Batalnya pesanan makanan skala kecil mayoritas disebabkan mahalnya ongkir kurir pihak ketiga. Kejelasan opsi ambil sendiri atau antar langsung adalah solusi mutlak untuk masalah ini. |
| **6** | **In-App Payment Gateway (QRIS/Escrow)** | **MASIH BISA** | **FITUR TAMBAHAN (Dapat Ditunda)** | Pembeli dan penjual terbiasa bertransaksi via transfer bank langsung, QRIS statis milik pedagang via chat WA, atau bayar tunai/COD saat pesanan diambil. Menambahkan payment gateway justru memicu beban biaya MDR/biaya transaksi. |
| **7** | **Peta Navigasi Interaktif** | **MASIH BISA** | **FITUR TAMBAHAN (Dapat Ditunda)** | Pengguna cukup melihat daftar kartu produk (*card list*) yang diurutkan berdasarkan jarak terdekat (misal: "0.5 KM dari Anda"). Peta interaktif memperberat beban muat data dan kuota internet pengguna. |
| **8** | **Sistem Ulasan & Rating Bintang** | **MASIH BISA** | **FITUR TAMBAHAN (Dapat Ditunda)** | Pada tahap awal di lingkungan komunitas/perumahan, kepercayaan terbangun secara alami dari kedekatan geografis dan obrolan personal di WhatsApp. Jumlah ulasan di awal juga masih terlalu sedikit sehingga belum representatif. |
| **9** | **Featured Listing (Promosi Berbayar)** | **MASIH BISA** | **FITUR TAMBAHAN (Dapat Ditunda)** | Fitur ini adalah strategi monetisasi lanjutan pada model bisnis (BMC), bukan kebutuhan fungsional esensial agar pembeli dapat menemukan jualan tetangga saat ini. |
| **10** | **Pelacakan Pesanan Real-Time** | **MASIH BISA** | **FITUR TAMBAHAN (Dapat Ditunda)** | Konfirmasi status pesanan (*"Pesanan sudah siap ya kak, silakan diambil"*) dapat dikomunikasikan secara langsung dan fleksibel melalui chat WhatsApp pedagang. |

---

## 5. Pemetaan Prioritas Fitur: Kerangka Kerja MoSCoW

Untuk memperjelas batasan implementasi dan mencegah pemekaran cakupan (*scope creep*), seluruh fitur fungsional dipetakan ke dalam 4 kuadran **MoSCoW (Must Have, Should Have, Could Have, Won't Have)**:

| Kuadran Prioritas | Definisi & Kriteria Keputusan | Fitur yang Masuk | Alasan Penempatan |
| :--- | :--- | :--- | :--- |
| **MUST HAVE**<br>*(Wajib Ada di MVP)* | Fitur vital yang menjadi syarat mutlak produk berfungsi dan bernilai. Tanpa fitur ini, produk tidak bisa diluncurkan (*non-negotiable*). | 1. Deteksi Lokasi & Filter Radius Mikro (<3–5 KM)<br>2. Katalog Produk Sederhana<br>3. Tombol *Direct-to-WhatsApp* (1-Click)<br>4. Formulir Unggah Cepat via HP<br>5. Label Opsi Ambil Sendiri / Antar Lokal | Membentuk loop penemuan (*discovery*) dan transaksi dasar 0% komisi tanpa ongkir mahal. |
| **SHOULD HAVE**<br>*(Sangat Penting, Fase 2)* | Fitur dengan nilai tambah tinggi yang tidak menggugurkan peluncuran jika ditiadakan sementara, namun sangat penting untuk kenyamanan setelah rilis awal. | 1. Kolom Pencarian Kata Kunci (*Search Bar*) & Filter Kategori (Makanan, Minuman, Kerajinan)<br>2. Tautan Titik Penjemputan ke Google Maps (Tautan statis buka maps)<br>3. Indikator Status Toko (Buka / Tutup) | Membantu pembeli mencari barang spesifik dan navigasi ke rumah penjual tanpa perlu membangun peta interaktif kompleks di awal. |
| **COULD HAVE**<br>*(Bisa Dibuat jika Ada Waktu/Sumber Daya, Fase 3)* | Fitur yang diinginkan pengguna namun berdampak rendah pada keberhasilan awal. Hanya dikerjakan jika *Must* dan *Should* telah tervalidasi stabil. | 1. Sistem Ulasan & Testimoni Warga (Rating bintang & komentar)<br>2. Badge Profil Penjual Terverifikasi Komunitas / RT/RW<br>3. Fitur Promosi Berbayar Ringan (*Featured Listing* Rp10.000/minggu)<br>4. Tampilan Peta Interaktif (*Interactive Map View*) | Baru relevan ketika jumlah pengguna dan transaksi sudah besar serta mulai tercipta persaingan visibilitas antar-penjual. |
| **WON'T HAVE (This Time)**<br>*(Tidak Akan Dibuat Saat Ini / Dieliminasi)* | Fitur yang secara sadar disepakati **TIDAK** dibuat pada rilis perdana karena menambah kompleksitas ekstrem, merusak proposisi nilai, atau di luar domain solusi. | 1. *In-App Payment Gateway* & Sistem *Escrow*<br>2. Pelacakan Kurir Real-Time (*Live GPS Courier Tracking*)<br>3. Keranjang Belanja Multi-Penjual (*Multi-Merchant Cart*) | *Payment gateway* mengenakan potongan MDR (bertentangan dengan nilai "0% komisi") dan sistem *escrow* menahan uang kas harian pedagang kecil. Pelacakan kurir tidak relevan karena transaksi diserahkan langsung pada pedagang/pembeli. |

---

## 6. Spesifikasi Paket Minimum Viable Product (MVP)

Dari hasil pengujian *Litmus Test* dan pemetaan kuadran *Must Have* MoSCoW, paket MVP difokuskan secara disiplin pada **5 Fitur Inti**:

```text
┌────────────────────────────────────────────────────────────────────────┐
│                        PAKET MINIMUM VIABLE PRODUCT                    │
├────────────────────────────────────────────────────────────────────────┤
│ 1. Deteksi Lokasi & Radius Mikro (<3–5 KM)                             │
│ 2. Katalog & Kartu Produk (Foto, Nama, Harga, Estimasi Jarak)          │
│ 3. Formulir Unggah Cepat bagi Penjual (Ramah Smartphone)               │
│ 4. Label Opsi Pengambilan (Self-Pickup / Antar Lokal)                  │
│ 5. Tombol Pesan Instan via WhatsApp (Auto-Filled Order Message)        │
└────────────────────────────────────────────────────────────────────────┘
```

### Alur Pengguna pada MVP (*MVP User Flow*):
1. **Sisi Penjual (Seller):**
   * Penjual membuka platform web melalui peramban ponsel.
   * Mengisi formulir singkat: nama usaha, foto produk, nama produk, harga, nomor WhatsApp, dan pilihan metode pemenuhan (Bisa Ambil di Tempat / Bisa Diantar Penjual).
   * Produk langsung tayang di katalog lokal tanpa verifikasi rumit.
2. **Sisi Pembeli (Buyer):**
   * Pembeli membuka platform, mengizinkan akses lokasi (atau memilih area kelurahan terdekat).
   * Melihat etalase makanan dan produk rumahan di sekitarnya dalam radius <3–5 KM yang diurutkan dari jarak terdekat.
   * Memilih produk dan melihat opsi pengambilan (*Self-Pickup* atau Antar Mandiri).
   * Menekan tombol **"Pesan via WhatsApp"**, yang otomatis membuka aplikasi WhatsApp dengan draf pesan:  
     *"Halo [Nama Toko], saya ingin memesan [Nama Produk] seharga [Rp...]. Metode: [Ambil Sendiri / Antar ke Rumah]. Apakah masih tersedia?"*
   * Transaksi dan kesepakatan pembayaran diselesaikan langsung di WhatsApp tanpa potongan komisi perantara.

---

## 7. Rencana Pengembangan Pasca-MVP (*Roadmap*)

Fitur-fitur tambahan yang ditunda akan diimplementasikan secara bertahap setelah MVP berhasil memvalidasi volume transaksi lokal dan adopsi pengguna:
* **Fase 2 (Validasi Komunitas & Kenyamanan):** Penambahan pencarian kata kunci (*search bar*), kategori makanan halal/vegetarian, serta integrasi titik Google Maps statis untuk rute penjemputan barang (*self-pickup*).
* **Fase 3 (Kepercayaan & Reputasi):** Sistem verifikasi pedagang warga lokal via pengurus RT/RW atau paguyuban, serta ulasan berbasis testimoni warga sekitar.
* **Fase 4 (Monetisasi & Skalabilitas):** Fitur *Featured Listing* berbayar terjangkau untuk seller yang ingin menonjolkan produknya di baris teratas etalase wilayah.

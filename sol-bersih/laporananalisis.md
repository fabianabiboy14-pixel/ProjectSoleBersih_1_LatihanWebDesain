LAPORAN ANALISIS KEBUTUHAN DAN PENGUJIAN SISTEM
Layanan Pencucian Sepatu 'Sol-Bersih'

1. Pendahuluan & Informasi Usaha
Laporan ini disusun berdasarkan struktur dan file proyek 'sol-bersih' yang mencakup direktori aset gambar, halaman antarmuka (html&css), stylesheet kustom, serta dokumentasi spesifikasi kebutuhan dan pengujian sistem.
Nama Usaha dan Masalah yang Ingin Diselesaikan
Usaha ini bernama Sol-Bersih, sebuah platform layanan cuci sepatu profesional yang bertujuan untuk mengatasi masalah masyarakat perkotaan yang sibuk, tidak memiliki waktu atau keahlian khusus untuk merawat dan membersihkan alas kaki kesayangan mereka dari kotoran, noda membandel, serta bau.
Persona Serta Dasar/Asumsi Penyusunannya
Persona utama layanan ini adalah pekerja kantoran, mahasiswa, dan sneakerhead berusia 18–35 tahun yang memiliki mobilitas tinggi, peduli terhadap penampilan dan kebersihan alas kaki, namun terkendala oleh kesibukan harian sehingga membutuhkan layanan antar-jemput (pickup & delivery) atau pemesanan servis sepatu yang cepat dan transparan.
2. Analisis Kebutuhan Fungsional & Nonfungsional
Tujuan Website dan Tindakan Utama Pengguna
Tujuan utama dari website Sol-Bersih adalah memperkenalkan layanan pencucian sepatu, menampilkan informasi harga dan jenis layanan, serta memfasilitasi pengguna untuk melakukan pemesanan (booking/order) secara online dengan cepat. Tindakan utama pengguna (Call to Action) meliputi melihat galeri layanan, membaca testimoni, memilih paket cuci, dan menekan tombol pemesanan atau menghubungi layanan pelanggan via WhatsApp.
Tiga Kebutuhan Fungsional Utama
1. Sistem menampilkan halaman utama (landing page) yang informatif mengenai profil layanan, jenis layanan cuci sepatu (Deep Cleaning, Fast Cleaning, Unyellowing, Repaint), serta kontak yang dapat dihubungi.
2. Pengguna dapat melihat galeri foto dan aset visual (seperti ikon sepatu dan katalog pengerjaan) untuk meyakinkan kualitas layanan.
3. Sistem menyediakan tombol interaktif pemesanan dan formulir untuk konfirmasi order dan penjadwalan antar-jemput.

Tiga Kebutuhan Nonfungsional Utama
1. Performa dan Kecepatan: Website harus memuat (loading) dengan cepat (< 2 detik) menggunakan aset gambar terkompresi (seperti SVG) dan file CSS yang teringan.
2. Desain Responsif (Responsive Design): Antarmuka harus menyesuaikan dengan baik di berbagai ukuran layar perangkat, baik desktop, tablet, maupun smartphone.
3. Keandalan dan Aksesibilitas: Struktur HTML5 dan CSS yang bersih memastikan kompatibilitas serta kemudahan navigasi bagi pengguna.

3. Lingkup, Batasan, & Konten yang Diperlukan
Daftar Teks, Gambar, dan Kontak yang Diperlukan
• Teks: Judul layanan, deskripsi singkat keunggulan, daftar harga paket cuci sepatu, testimoni pelanggan, dan instruksi cara order.
• Gambar: Aset visual logo/ikon sepatu (seperti sepatu.svg), banner ilustrasi proses pembersihan, dan foto sebelum-sesudah (before-after) perawatan sepatu.
• Kontak: Nomor WhatsApp bisnis, Alamat, dan Email.
Ruang Lingkup dan Fitur yang Tidak Dikerjakan (Out of Scope)
• Sistem pembayaran terintegrasi penuh (Payment Gateway otomatis seperti kartu kredit/virtual account langsung di web) pada tahap awal — transaksi dialihkan melalui konfirmasi manual via formulir.
• Fitur pelacakan status kurir secara real-time via GPS untuk antar-jemput sepatu.

4. Kriteria Penerimaan & Laporan Pengujian (Testing)
Kriteria Penerimaan (Acceptance Criteria)
• Website berhasil diakses melalui file index.html tanpa error pada konsol browser.
• Tampilan antarmuka sesuai dengan desain (styling CSS termuat dengan sempurna).
• Seluruh tombol navigasi dan tautan berfungsi dengan baik dan mengarah ke tujuan yang benar.

Ringkasan Laporan Pengujian (Testing Report)
Berdasarkan dokumentasi dan struktur file proyek, berikut adalah hasil pengujian yang dilakukan terhadap sistem Sol-Bersih:
Deskripsi Pengujian
Pengujian Muat Halaman Utama (index.html)
Pengujian Responsivitas Tampilan (Mobile & Desktop)
Pengujian Tautan dan Tombol Pemesanan
Pengujian Kompatibilitas Aset & Styling

Hasil yang Diharapkan
Halaman terdapat sempurna dengan CSS dan aset SVG tampil baik.
Layout menyesuaikan dengan rapi di berbagai ukuran layar.
Tombol pesan aktif dan merespons klik pengguna.
File bisa di akses secara sempurna
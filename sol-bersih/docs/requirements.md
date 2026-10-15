# Dokumen Kebutuhan - Website Sol Bersih

## 1. Gambaran umum
Sol Bersih adalah landing page satu halaman untuk usaha jasa cuci sepatu di Depok.
Tujuan halaman: memperkenalkan layanan dan membuat pengunjung memesan.

## 2. Kebutuhan fungsional
| Kode | Kebutuhan | Bagian halaman |
|------|-----------|----------------|
| F-01 | Menampilkan halaman utama dengan gambar dan ajakan memesan | Homepage |
| F-02 | Menampilkan keunggulan, statistik, dan cara kerja | Keunggulan |
| F-03 | Menampilkan minimal tiga paket layanan beserta harga | Paket Layanan |
| F-04 | Menampilkan testimoni dan pertanyaan umum (FAQ) | Info |
| F-05 | Menampilkan kontak (alamat, WhatsApp, email, jam buka) | Info / Kontak |
| F-06 | Menyediakan formulir pesanan | Kontak |
| F-07 | Menyediakan navigasi ke Homepage, Keunggulan, Paket Layanan, Info | Header |

## 3. Kebutuhan non-fungsional
| Kode | Kebutuhan |
|------|-----------|
| N-01 | Dibuat dengan HTML dan CSS saja, tanpa JavaScript |
| N-02 | HTML dan CSS dipisah (index.html dan css/style.css) |
| N-03 | Tampilan responsif di layar HP dan desktop |
| N-04 | Gambar memakai lisensi bebas (ilustrasi SVG buatan sendiri) |
| N-05 | Setiap gambar memiliki teks alternatif (atribut alt) |
| N-06 | Tampilan cetak tetap terbaca (aturan @media print) |

## 4. Batasan
- Formulir memakai `action="proses_pesanan.php"` dan belum terhubung ke backend.
- Data kontak, ulasan, dan statistik masih contoh.

## 5. Teknik materi yang digunakan
Semantic tag (header, nav, main, section, article, footer), figure dan figcaption,
daftar, form, blockquote dan cite, details dan summary, selektor tag, class, ID,
atribut, dan universal, pseudo-class dan pseudo-element, variabel CSS, gradasi,
border-radius, Google Fonts, @media.

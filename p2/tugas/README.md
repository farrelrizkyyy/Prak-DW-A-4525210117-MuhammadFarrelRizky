# Laporan Praktikum Pertemuan 2 - HTML Lanjutan & Markdown

## Ringkasan Laporan Praktikum HTML Lanjutan
Pada praktikum Pertemuan 2 ini, saya mempelajari penggunaan elemen HTML lanjutan seperti penambahan media gambar, tautan navigasi (hyperlink), struktur daftar (list), komentar, serta penerapan atribut global dan CSS terpisah. Pada latihan utama, saya membuat halaman profil "SMK Negeri 8 Jakarta" yang tersusun secara semantik.

Dalam penyusunan konten, halaman web menampilkan beberapa media gambar serta daftar tautan navigasi internal maupun eksternal untuk memudahkan pengguna menjelajahi informasi sekolah.

### Elemen Gambar dan Tautan yang Digunakan
* **Gambar yang Ditampilkan:**
  * `images/gedung_smk8.jpg`: Menampilkan foto utama gedung SMKN 8 Jakarta pada bagian profil sekolah.
  * `images/lapangan_smk8.png`: Menampilkan foto area lapangan SMKN 8 Jakarta pada bagian fasilitas.
* **Daftar Tautan (`href`) yang Digunakan:**
  * `#profil`, `#jurusan`, `#pendaftaran`, `#fasilitas`, `#kontak`: Navigasi internal (*anchor link*) menuju bagian-bagian halaman.
  * `#beranda`: Tautan internal untuk kembali ke bagian atas halaman.
  * `mailto:info@smkn8jakarta.sch.id`: Tautan eksternal untuk membuka aplikasi email secara langsung.
  * `https://smkn8jakarta.sch.id/`: Tautan eksternal menuju situs resmi SMKN 8 Jakarta dengan atribut `target="_blank"`.

### Masalah dan Solusi
* **Masalah:** Navigasi *anchor link* sempat tidak merujuk ke bagian yang sesuai akibat perbedaan penggunaan huruf besar dan kecil (*case-sensitive*) pada nilai atribut `id`. Selain itu, gambar yang dimasukkan sempat berukuran terlalu besar.
* **Solusi:** Menyeimbangkan nama atribut `id` dan nilai `href` secara konsisten menggunakan huruf kecil, serta memberikan batas ukuran pada gambar menggunakan atribut `width` dan penataan `border-radius` melalui file CSS terpisah.

Secara keseluruhan, dokumen HTML lanjutan ini dapat dirender dengan baik, interaktif, serta memiliki struktur yang rapi pada perangkat desktop maupun seluler.
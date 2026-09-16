# Tugas 2 - Pengembangan Aplikasi Web

## 1. Alasan Penggunaan Struktur Semantik
Penerapan elemen semantik pada website Kebun Raya ITERA ini bertujuan agar setiap bagian kode memiliki fungsi yang jelas dan terstruktur sesuai dengan jenis kontennya. Berikut adalah rincian penggunaannya:

*   `<header>`: Digunakan untuk membungkus identitas utama website, seperti judul situs dan logo institusi.
*   `<nav>`: Berfungsi khusus sebagai wadah navigasi menu untuk memudahkan perpindahan antarhalaman.
*   `<main>`: Menjadi penampung utama dari seluruh isi konten inti website.
*   `<section>`: Digunakan di dalam `<main>` untuk mengelompokkan konten berdasarkan tema atau topik besar, seperti profil Kebun Raya ITERA dan daftar harga paket.
*   `<article>`: Digunakan secara spesifik untuk membungkus setiap item berita, karena berita merupakan entitas konten yang utuh dan dapat berdiri sendiri.
*   `<aside>`: Digunakan untuk meletakkan informasi tambahan (seperti pengumuman penting) yang relevan tetapi di luar alur konten utama.
*   `<footer>`: Menandai bagian penutup website yang berisi informasi kontak institusi dan tautan pendukung.

## 2. Tantangan dan Solusi
Selama proses pengerjaan, terdapat beberapa kendala teknis yang dihadapi beserta solusinya:

*   **Menentukan Elemen Semantik yang Tepat:** Sempat terjadi kebingungan dalam membedakan fungsi utama antara `<main>`, `<section>`, dan `<article>`. Kendala ini diatasi dengan menyesuaikan konteks kontennya—mengkhususkan `<section>` untuk membagi bab bahasan topik besar, dan menggunakan `<article>` khusus untuk item berita karena sifatnya yang independen.
*   **Error Validasi pada File Gambar:** Saat melakukan pengecekan di W3C Validator, muncul *error* yang disebabkan oleh penamaan *file* gambar yang menggunakan spasi. Solusinya adalah mengubah nama *file* gambar di dalam direktori penyimpanan agar tidak menggunakan spasi, lalu memperbarui nilai atribut `src` pada tag `<img>` di dalam kode HTML.

## 3. Hasil Validasi W3C
Berdasarkan hasil pengujian menggunakan W3C Validator, kedua file HTML (`index.html` dan `berita.html`) telah sepenuhnya memenuhi standar validasi web tanpa adanya *error* (setelah perbaikan pada atribut gambar dan penyesuaian tag usang diselesaikan).

- **Screenshot Validasi `index.html`:**
  ![Validasi Index](./images/validasiIndex.png)

- **Screenshot Validasi `berita.html`:**
  ![Validasi Berita](./images/validasiBerita.png)

## 4. Link GitHub Pages
*   **URL:** [https://gedevalendra.github.io/pemweb/tugas2](https://gedevalendra.github.io/pemweb/tugas2)
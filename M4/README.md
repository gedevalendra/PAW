
# Tugas 3 Pemrograman Web

## Deskripsi Proyek

Proyek ini merupakan pembuatan halaman web sederhana menggunakan HTML dan CSS yang terdiri dari halaman registrasi dan halaman detail informasi pendaftar.

## Struktur Halaman

Proyek memiliki dua halaman utama:

1. **Halaman Registrasi (`index.html`)**  
   Menggunakan elemen form dengan metode `GET` untuk menerima input nama lengkap, kata sandi, dan NIM. Formulir juga dilengkapi checkbox persetujuan syarat dan ketentuan.

2. **Halaman Detail (`detail.html`)**  
   Menampilkan informasi pendaftar dalam bentuk tabel yang berisi nomor, nama lengkap, kata sandi, NIM, dan tombol aksi Edit. Data yang ditampilkan masih berupa data dummy.

## Query String

Formulir pada `index.html` menggunakan atribut `method="GET"` dan `action="detail.html"` untuk merancang pengiriman data melalui query string. Parameter yang digunakan adalah `name`, `password`, dan `nim`.

Data dikirim melalui URL ketika formulir disubmit, tetapi belum ditangkap atau diproses secara otomatis pada halaman detail.

## Desain CSS

Desain kedua halaman diatur menggunakan file `style.css` dengan beberapa selector, antara lain:

- **Element selector**, untuk mengatur elemen HTML secara umum, seperti `body` dan `hr`.
- **Class selector**, untuk mengatur komponen tertentu, seperti `.FormContainer`, `.FormRight`, dan `.RegistrationTable`.
- **Pseudo-class selector**, seperti `:hover` dan `:focus`, untuk memberikan efek visual ketika elemen berinteraksi dengan pengguna.

CSS juga digunakan untuk mengatur layout menggunakan Flexbox, warna, ukuran, jarak, border, bayangan, tampilan form, serta tabel.

## JavaScript

JavaScript digunakan untuk mengatur fitur tampil dan sembunyi kata sandi melalui perubahan tipe input dari `password` menjadi `text` dan sebaliknya.

## Teknologi

- HTML5
- CSS3
- JavaScript
- Boxicons

## Struktur File

```text
task_3/
├── index.html
├── detail.html
├── style.css
└── README.md
```


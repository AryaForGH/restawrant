<h1 align="center">Selamat datang di repository Restawrant! 👋🏻</h1>



<p></p>

<h4 align="center">Website yang berisi informasi tentang restoran anda dilengkapi sistem reservasi  yang dibuat dengan <a href="https://laravel.com/" target="_blank">Laravel</a>.
</h4>

<p></p>

<p align="center">
	<img src="https://img.shields.io/github/issues/syauqi/restawrant?style=flat-square">
	<img src="https://img.shields.io/github/stars/syauqi/restawrant?style=flat-square"> 
	<img src="https://img.shields.io/github/forks/syauqi/restawrant?style=flat-square">
	<img src="https://img.shields.io/github/license/syauqi/restawrant?style=flat-square">
	<img src="https://img.shields.io/badge/maintained%3F-no-red.svg?style=flat-square">
	<img src="https://img.shields.io/github/followers/syauqi.svg?style=flat-square&label=followers">
</p>

<p align="center">
  <a href="#tentang">Tentang Project</a> •
  <a href="#fitur">Fitur</a> •
  <a href="#download">Download & Install</a> •
  <a href="#akun">Akun Default</a> •
  <a href="#lisensi">Lisensi</a>
</p>

<p></p>

<h2 id="tentang">☕️ Tentang Big Brew</h2>

Website ini berperan sebagai homepage untuk menampilkan menu dan kategori makanan atau minuman apa saja yang ada di restoran anda untuk mempermudah pelanggan melihat menu dimana saja dan kapan saja. Restawrant juga dilengkapi sistem reservasi meja untuk kemudahan pelanggan dalam memesan atau booking meja.

<p></p>

<h2 id="fitur">✨ Fitur Tersedia</h2>

-   Landing Page dan Autentikasi
    -   Halaman [homepage, menu, kategori, tentang, reservasi]
    -   Autentikasi [login untuk admin]
-   Pengelolaan Data Menu & Kategori
    -   Tambah, Update dan Delete Menu beserta relationship dengan kategori
    -   Tambah, Update dan Delete Kategori
    -   Tambah, Update dan Delete Data Meja di restoran anda
    -   Tambah, Update dan Delete Reservasi meja
- Dan masih banyak lagi
<p></p>

<h2 id="akun">🔑 Daftar Akun Tersedia</h2>

Berikut adalah daftar akun untuk keperluan testing saat anda mencoba aplikasi pertama kali, nemun anda harus melakukan seed terlebih dahulu dengan panduan dibawah

| Role      | Email             | Password    | URL                                        |
| --------- | ----------------- | ----------- | ------------------------------------------ |
| Admin     | admin@gmail.com   | password | http://localhost/login     |


<p></p>

<h2 id="syarat">💾 Prasyarat yang Diperlukan</h2>

Berikut adalah daftar layanan dan aplikasi yang wajib dan diperlukan selama anda menjalankan aplikasi restawrant jika anda belum menginstall nya maka disarankan untuk menginstall nya terlebih dahulu

-   PHP 8 & Web Server [XAMPP, LAMPP, MAMP]
-   Web Browser [Chrome, Firefox, Safari & Opera]
-   Internet [Karena menggunakan banyak CDN]

<p></p>

<h2 id="download">🐱‍💻 Panduan Menjalankan & Install Aplikasi</h2>

Untuk menjalankan aplikasi atau web ini kamu harus install XAMPP atau web server lain dan mempunyai setidaknya satu web browser yang terinstall di komputer anda.

```bash
# Clone repository ini atau download di
$ git clone https://github.com/AryaForGH/restawrant.git

# Kemudian jalankan command composer install, ini akan menginstall resources yang laravel butuhkan
$ composer install

# Lakukan copy .env dengan cara ketik command seperti dibawah
$ cp .env.example .env

# Generate key juga jangan lupa dengan command dibawah
$ php artisan key:generate

# Jangan lupa migrate database dengan cara membuat database di phpmyadmin atau aplikasi lainnya yang kalian pakai,
# lalu jangan lupa untuk mengganti variable DB_DATABASE di file .env yang di folder project
$ php artisan migrate:fresh --seed

# Lalu jalankan aplikasi kalian dengan command dibawah
$ php artisan serve

# Selamat aplikasi dapat anda nikmati di local!
```


<h2 id="lisensi">📝 Lisensi</h2>

-   Copyright © 2025 Big Brew
-   Restawrant adalah aplikasi web open-source yang berlisensi dibawah lisensi MIT

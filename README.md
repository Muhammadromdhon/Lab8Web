# Lab8Web
# Nama  : Muhammad Romdhon
# NIM   : 312010434
# Kelas : TI.20.A1

**Langkah-langkah Praktikum**<br>
**Persiapan**<br>
<br>Untuk memulai membuat aplikasi CRUD sederhana, yang perlu disiapkan adalah database server menggunakan MySQL. Pastikan MySQL Server sudah dapat dijalankan melalui XAMPP.<br>

**1. Menjalankan MySQL Server**<br>
<br>Untuk menjalankan MySQL Server dari menu XAMPP Control.<br>
![p](gambar/ssmysql.png)<br>

**Mengakses MySQL Client menggunakan PHP MyAdmin**<br>
<br>Pastikan webserver Apache dan MySQL server sudah dijalankan. Kemudian buka melalui browser: http://localhost/phpmyadmin/<br>

**2. Membuat Database: Studi Kasus Data Barang**<br>
**Membuat Database**<br>
![p](gambar/ss1.png)<br>
**Membuat Tabel**<br>
![p](gambar/ss2.png)<br>
![p](gambar/ss3.png)<br>
**Menambahkan Data**
![p](gambar/ss4.png)<br>
![p](gambar/ss6.png)<br>

**3. Membuat Program CRUD**<br>
Buat folder **lab8_php_database** pada root directory web server<br>
![p](gambar/ssfolder.png)<br>
Kemudian untuk mengakses direktory tersebut pada web server dengan mengakses URL:
http://localhost/lab8_php_database/<br>
![p](gambar/ss7.png)<br>
**Membuat file koneksi database**<br>
Membuat file baru dengan nama **koneksi.php**<br>
![p](gambar/ss8.png)<br>
Buka melalui browser untuk menguji koneksi database (untuk menyampilkan pesan
koneksi berhasil, ***uncomment pada*** perintah echo “koneksi berhasil”;<br>
![p](gambar/ss9.png)<br>
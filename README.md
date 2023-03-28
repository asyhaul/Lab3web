# Persiapan
Untuk memulai membuat aplikasi CRUD sederhana, yang perlu disiapkan adalah database server
menggunakan MySQL. Pastikan MySQL Server sudah dapat dijalankan melalui XAMPP.
# Menjalankan MySQL Server
Untuk menjalankan MySQL Server dari menu XAMPP Contol.
![2023-03-28 (1)](https://user-images.githubusercontent.com/116356016/228382585-2f5cb0d9-2ebd-4192-a13c-74338917e241.png)
Mengakses MySQL Client menggunakan PHP MyAdmin
Pastikan webserver Apache dan MySQL server sudah dijalankan. Kemudian buka melalui browser:
http://localhost/phpmyadmin/

# Membuat Database
CREATE DATABASE latihan_web;
![2023-03-28 (6)](https://user-images.githubusercontent.com/116356016/228382780-51cfdfcc-996a-4e8a-ae2e-6790d415b751.png)

# Membuat Tabel
![2023-03-28 (8)](https://user-images.githubusercontent.com/116356016/228383743-77774884-7729-481e-90b8-a162b8b68be3.png)


# Menambahkan Data
![2023-03-28 (9)](https://user-images.githubusercontent.com/116356016/228383854-6fd86418-d01e-471e-b7e9-5f50c4facf82.png)
![2023-03-28 (7)](https://user-images.githubusercontent.com/116356016/228383001-ea89f77a-f293-4a9f-8a7c-5b5d54420849.png)

# Membuat Program CRUD
Buat folder lab3_php_database pada root directory web server (c:\xampp\htdocs)
![2023-03-28 (10)](https://user-images.githubusercontent.com/116356016/228384043-74688530-8c69-43e7-92dd-9f12b956e34b.png)

# Membuat file koneksi database
Buat file baru dengan nama koneksi.php
Buka melalui browser untuk menguji koneksi database (untuk menyampilkan pesan koneksi berhasil,
![2023-03-25](https://user-images.githubusercontent.com/116356016/228384155-88c15d00-cfe9-4725-9a62-25c10c1a5ec9.png)
uncomment pada perintah echo “koneksi berhasil”;

# Membuat file index untuk menampilkan data (Read)
Buat file baru dengan nama index.php
![2023-03-25 (4)](https://user-images.githubusercontent.com/116356016/228384311-65610ead-379c-4d1d-a4c5-5d6fbec926bc.png)

# Menambah Data (Create)
Buat file baru dengan nama tambah.php
![2023-03-26 (3)](https://user-images.githubusercontent.com/116356016/228384474-1a4a9e9e-84aa-4fc7-9e04-56ced084dac5.png)

# Mengubah Data (Update)
Buat file baru dengan nama ubah.php
![2023-03-26 (2)](https://user-images.githubusercontent.com/116356016/228384431-ea3a914c-aceb-4a2e-8683-e1d8a7b47fea.png)

# Menghapus Data (Delete)
Buat file baru dengan nama hapus.php

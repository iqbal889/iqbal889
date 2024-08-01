# Instalasi Git Bash
## 1.download Git pada browser ketik 'git-scm'
![[WhatsApp Image 2024-07-31 at 21.02.50.jpeg]]

## 2.Lalu klik Git Hub yang telah di instal

## 3.Lalu akan muncul tampilan seperti gambar

![[WhatsApp Image 2024-07-31 at 21.02.51.jpeg]]

## 4.Maka klik 'next' terus hingga mendapatkan tampilan seperti gambar

![[WhatsApp Image 2024-07-31 at 21.02.51 (1).jpeg]]

# Login Akun Github
1. Buka aplikasi github di browser 
2. Lalu lakukan sign up pada github
![[0df41373-3ae9-4125-acd8-0d2c03e0224f.jpg]]

3. Jika sudah memiliki akun langsung masukkan password dan username yang ada
![[105f487e-d933-43e5-8438-ab218f6f67b3.jpg]]

4. Jika tidak memiliki akun klik tambahkan akun
![[Pasted image 20240731222938.png]] 

5. Setelah buat akun maka akan tampil seperti gambar
![[Screenshot (12).png]]
## Langkah-langkah

1. Buat Repositori GitHub Baru:
   - Login ke akun GitHub Anda.
   - Klik tombol "New" untuk membuat repositori baru.
   ![[Screenshot (15).png]]
   - Berikan nama repositori, pilih apakah akan bersifat publik atau privat, lalu klik "Create repository".
   ![[Screenshot (16).png]]

2. Konfigurasi Git Lokal:
   - Buka git di laptop/komputer anda.
   - Jalankan perintah berikut untuk mengatur identitas Anda:
    ~~~CS
     git config --global user.name "Nama Anda"
     git config --global user.email "email@example.com"
     ~~~
     contohnya :
     
![[Screenshot (18).png]]
![[Screenshot (22).png]]

	Note: untuk melihat apakah sudah terhubung konfigurasi git nya silakan ketik 
         git config --list
 contohnya : 
 ![[Screenshot (21).png]]

3. Inisialisasi Git Lokal:
   -  Buat direktori baru untuk proyek Anda dan navigasikan ke direktori tersebut menggunakan Git bash. Kemudian, inisialisasi Git di direktori tersebut dengan menjalankan perintah:
     ~~~cs
     git init
~~~
 contohnya :
![[Screenshot (19).png]]

4. Hubungkan ke Repositori GitHub:
   - Jalankan perintah berikut untuk menghubungkan repositori lokal Anda ke repositori GitHub yang telah Anda buat sebelumnya:
~~~cs
     git remote add origin https://github.com/username/nama-repository.git
  ~~~ 
   Ganti username dan nama-repository dengan nama pengguna GitHub Anda dan nama repositori yang Anda buat.kalo dah ada tulisan (master),berarti sudah terhubung ke repositori Githubnya
contohnya:
![[Screenshot (18) 3.png]]
5. Tambahkan file ke repositori: 
   - Perintah ini akan menambahkan semua file di direktori saat ini ke repositori.
   - Tambahkan file yang ingin Anda simpan di repositori Git dengan menjalankan perintah:
   ~~~cs
     git add .
     ~~~
contohnya :
![[Screenshot (20).png]]
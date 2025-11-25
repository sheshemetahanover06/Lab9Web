# NAMA: She She Metahanover 
# NIM: 312410432
# KELAS: TI.24.A.3

# PROJECT — Aplikasi PHP Modular
Aplikasi ini merupakan sistem berbasis PHP dengan arsitektur **Modular**, di mana setiap fitur dipisahkan ke dalam folder modul tersendiri.  
Struktur seperti ini membuat proyek lebih terorganisir, mudah dikelola, dan fleksibel untuk dikembangkan.


## Penjelasan Folder

##  assets
Menyimpan file pendukung seperti:
- CSS (desain tampilan)
- Gambar produk
- File statis lainnya

##  config
Berisi file konfigurasi:
- `database.php` → mengatur koneksi MySQL ke aplikasi
- `session.php` → mengecek apakah user sudah login atau belum

##  modules
Folder utama yang menyimpan fitur-fitur aplikasi.

Contoh:
- `modules/auth/` → fitur login & logout  
- `modules/user/` → fitur CRUD user  

Setiap modul memiliki file terpisah agar lebih rapi.

##  views
Berisi file tampilan umum yang dipakai banyak halaman, seperti:
- Header
- Footer
- Dashboard

##  index.php
Gerbang utama aplikasi yang meng-handle routing menggunakan `$_GET['page']`.

## Sistem Data Barang (Inventory Management System)
Sistem Data Barang adalah aplikasi web untuk mengelola inventory barang dengan fitur autentikasi pengguna dan manajemen data barang yang lengkap.

##  Fitur Utama

##  Sistem Autentikasi
**Login Page** 
<img width="1678" height="954" alt="image" src="https://github.com/user-attachments/assets/fc7e8024-1dbd-491c-be15-182955846252" />
- Form login dengan username dan password
- Validasi akses pengguna
- Tampilan profesional dengan header dan navigasi

##  Dashboard
**Dashboard** 
<img width="1661" height="945" alt="image" src="https://github.com/user-attachments/assets/0d4c70b4-df50-4447-9a37-6c8b49b34998" />

- Statistik ringkasan inventory
- Total Barang: 15 item
- Kategori: 3 kategori
- Stok Total: 125 unit
- Welcome message dengan nama pengguna
- Quick actions: Lihat Data Barang & Tambah Barang

##  Manajemen Data Barang
**Data Barang** 
<img width="1693" height="916" alt="image" src="https://github.com/user-attachments/assets/59c2d9a4-204c-49bb-af6d-34d4a9dad321" />

- Tabel daftar barang dengan kolom lengkap:
- Nama Barang
- Kategori
- Harga Jual
- Harga Beli
- Stok
- Aksi (Edit & Hapus)
- Tombol "Tambah Barang" untuk navigasi cepat

##  Tambah Barang
**Form Tambah Barang** 
[<img width="1678" height="954" alt="image" src="https://github.com/user-attachments/assets/bb5d7e31-31db-42e7-826d-318c0381cbad" />


- Input data barang baru:
- Nama Barang (text input)
- Kategori (dropdown/select)
- Harga Jual (numeric input)
- Harga Beli (numeric input)
- Stok (numeric input)
- Tombol aksi: Simpan Barang & Batal







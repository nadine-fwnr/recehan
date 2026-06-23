## **Recehan** 

Recehan adalah aplikasi pencatatan keuangan sederhana berbasis web dan mobile yang dirancang untuk membantu pengguna mencatat pemasukan dan pengeluaran sehari-hari secara cepat dan mudah. 

<img width="1349" height="676" alt="Recehan - Aplikasi Keuangan Sederhana" src="https://github.com/user-attachments/assets/68446035-5d9a-4ae1-bbd3-7b2b06963540" />

## **Recehan bukan sistem akuntansi.** 

Aplikasi ini tidak menyediakan fitur jurnal, buku besar, neraca, maupun laporan akuntansi kompleks. Fokus utama Recehan adalah pencatatan arus kas sederhana dan penyajian laporan keuangan yang mudah dipahami. 

## **Fitur Utama** 

## **Manajemen Pengguna** 

- Login berbasis API 

- Manajemen pengguna • Manajemen role dan hak akses 

- Activity Log seluruh aktivitas pengguna 

## **Role Pengguna** 

## **Admin** 

- Mengelola seluruh data aplikasi 

- Mengelola pengguna 

- Mengelola role dan permission 

- Mengakses seluruh laporan 

## **Bendahara** 

- Mengelola pemasukan 

- Mengelola pengeluaran 

- Mengedit transaksi 

- Mengakses laporan keuangan 

## **Staf** 

- Menambahkan pemasukan 

- Menambahkan pengeluaran 

## **Modul Keuangan** 

## **Pemasukan** 

- Tambah pemasukan 

- Edit pemasukan 

- Hapus pemasukan 

- Kategori pemasukan 

- Nomor transaksi otomatis 

## **Pengeluaran** 

- Tambah pengeluaran 

- Edit pengeluaran 

- Hapus pengeluaran 

- Kategori pengeluaran 

- Nomor transaksi otomatis 

## **Dashboard** 

- Total Pemasukan 

- Total Pengeluaran 

- Saldo Berjalan • Grafik Komposisi Pemasukan dan Pengeluaran • Ringkasan Transaksi Bulan Aktif 

## **Laporan Keuangan** 

- Harian • 3 Harian 

- Mingguan • Bulanan • Triwulan • Semester 

- Tahunan • 3 Tahunan 

## **Activity Log** 

Seluruh aktivitas pengguna dicatat secara otomatis: 

- Data yang diubah 

- Nilai sebelum perubahan 

- Nilai setelah perubahan 

- Tanggal dan waktu perubahan 

- Pengguna yang melakukan perubahan 

## **🛠️ Teknologi** 

## **Backend** 

- Laravel 13 

- PHP 8.4+ 

- MySQL / MariaDB 

- Laravel Passport 

## **Admin Panel** 

- Filament 

- Filament Shield 

- Spatie Permission • Spatie Activity Log 

## **Mobile** 

- Flutter 

## **System Requirements** 

## **Server** 

- PHP 8.4 atau lebih baru 

- Composer 

- MySQL 8+ atau MariaDB 10+ 

- Apache atau Nginx 

## **PHP Extensions** 

- BCMath
- Ctype
- Fileinfo 
- JSON
- Mbstring
- OpenSSL
- PDO
- Sodium
- Tokenizer 
- XML
- Zip

## **Instalasi ⚙️** 

## **Clone Repository** 

```
git clone https://github.com/username/recehan.git
cd recehan
```

## **Install Dependency** 

```
composer install
```

## **Konfigurasi Environment** 

Salin file  `.env` : 

## **Linux / MacOS** 

```
cp .env.example.env
```

## **Windows** 

```
copy.env.example .env
```

Edit file `.env` dan sesuaikan konfigurasi database: 

```
APP_NAME=Recehan
```

```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=recehan
DB_USERNAME=root
DB_PASSWORD=
```

## **Generate Application Key** 

```
php artisan key:generate
```

## **Migrasi Database dan Seeder** 

```
php artisan migrate:fresh --seed
```

## **Menjalankan Aplikasi** 

```
php artisan serve
```

Akses aplikasi: 

`http://localhost:8000` 

Akses panel administrasi: 

`http://localhost:8000/dasbor` 
```
`**Super Admin**`
Username : owner@recehan.com
Password : password

`**Bendahara**`
Username : bendahara@recehan.com
Password : password
```

**Struktur Modul** 
```
`Keuangan 
    ├── Kategori Pemasukan 
    ├── Kategori Pengeluaran 
    ├── Pemasukan 
    └── Pengeluaran 
Sistem 
    ├── Pengguna 
    ├── Role 
    └── Activity Log
```

` **Keamanan** 
- Role Based Access Control (RBAC)
- Permission Management menggunakan Spatie Permission
- Activity Log untuk audit perubahan data 
- Soft Delete pada data penting
- Nomor transaksi otomatis dan unik 

## **🗺️ Roadmap** 

## **Versi Berikutnya** 

- API Mobile Flutter 

- Export PDF 

- Export Excel 

- Backup Database 

- Multi Cabang 

- Multi Kas 

- Notifikasi Transaksi 

- Dashboard Analitik 


## **Lisensi** 

Aplikasi ini dikembangkan untuk kebutuhan pencatatan keuangan sederhana dan dapat digunakan serta dimodifikasi sesuai kebutuhan organisasi maupun pribadi. 



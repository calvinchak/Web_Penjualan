# Aplikasi Penjualan Dengan Framework CodeIgniter 3 & Template SB Admin 2


Untuk fiturnya masih sangas sederhana, contohnya sebagai berikut
1. **Modul Authentikasi**
   
   Di modul ini saya membuat fitur untuk login dan logout.
   
2. **Modul Data Barang**
   
   Di modul ini saya membuat fitur untuk melihat, menambah, mengubah, menghapus dan meng-ekspor data barang.
   
3. **Modul Data Kasir**

   Di modul ini saya membuat fitur untuk melihat, menambah, mengubah, menghapus dan meng-ekspor data kasir.
   
4. **Modul Transaksi Penjualan**

   Di modul ini saya membuat fitur untuk melihat, menambah, menghapus dan meng-ekspor transaksi penjualan.

5. **Modul Manajemen Akun**

   Di modul ini saya hanya membuat fitur untuk melihat dan menghapus akun.
	 
### Role
Terdapat Dua Role yaitu `admin` & `kasir`

### Instalasi & Konfigurasi

Untuk cara instalasi dan konfigurasi caranya sangat mudah

1. Kalian download atau clone repositori ini
2. Masuk ke folder project ini
3. Lalu buka terminal dan jalankan `composer install`
4. Selanjutnya kalian bisa buka file `application/config/config.php` 
5. Ubah isi dari variable `$config['base_url']` dengan `http://localhost/namafolder/`
6. Untuk `namafolder` silahkan kalian ganti sesuai nama folder dari aplikasi ini di komputer atau laptop kalian
7. Import `db/db_penjualan.sql` ke database milik kalian




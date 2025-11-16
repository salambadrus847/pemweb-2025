# UTS PEMWEB
### Oleh
## 20220803069 - Badrus Salam

# PROSES SLR
```bash
1. https://themewagon.com/themes/estore/
Rumpun Ilmu : Software Engineering
Deskripsi : Template website e-commerce berbasis web untuk penjualan produk UMKM
P (Platform) : Web Apps Penjualan UMKM
I (Intervention) : Teknologi Laravel dengan fitur katalog produk, keranjang belanja, checkout, dan laporan penjualan
C (Comparison) : Sistem penjualan masih dilakukan manual (WhatsApp, catatan buku, pembukuan sederhana)
O (Outcome) : Aplikasi web yang memungkinkan pelanggan melihat katalog produk, melakukan pemesanan, dan admin mengelola transaksi dan laporan secara otomatis
S (Suspect) : Aplikasi mempermudah dalam proses transaksi, pemasaran, dan pengelolaan penjualan UMKM

Berikan saya riset question (RQ) terkait ide penelitian diatas!

# RESPOND
```bash
Berdasarkan deskripsi ide penelitian yang Anda berikan, berikut adalah beberapa Research Question (RQ) yang dapat dikembangkan untuk mengarahkan penelitian dan implementasi sistem informasi penjualan UMKM berbasis web menggunakan Laravel.

Rumusan RQ mengikuti konteks PICOS yang telah ditentukan:
• P (Platform): Aplikasi Web Penjualan UMKM
• I (Intervention): Pengembangan sistem menggunakan Laravel
• C (Comparison): Sistem penjualan manual menggunakan WhatsApp dan pencatatan buku
• O (Outcome): Peningkatan efisiensi transaksi dan pengelolaan data penjualan
• S (Setting): UMKM sektor makanan/minuman atau retail

________________________________________
Kategori 1: RQ tentang Kebutuhan dan Analisis Sistem
• RQ1.1: Apa saja kendala yang dialami UMKM dalam proses penjualan dan pencatatan transaksi secara manual?
• RQ1.2: Fitur apa yang dibutuhkan pengguna (admin UMKM & pelanggan) dalam sistem informasi penjualan berbasis web?

________________________________________
Kategori 2: RQ tentang Desain, Implementasi, dan Teknologi
• RQ2.1: Bagaimana merancang arsitektur sistem penjualan berbasis Laravel dengan modul produk, pelanggan, keranjang, pesanan, dan laporan transaksi?
• RQ2.2: Bagaimana implementasi proses checkout dan manajemen pembayaran dalam aplikasi web berbasis Laravel?

________________________________________
Kategori 3: RQ tentang Evaluasi Fungsionalitas Sistem
• RQ3.1: Apakah sistem informasi penjualan yang dibangun mampu menjalankan seluruh proses bisnis penjualan dan pencatatan transaksi secara real-time?
• RQ3.2: Bagaimana tingkat keakuratan sistem dalam menghasilkan laporan penjualan dibandingkan metode manual?

________________________________________
Kategori 4: RQ tentang Pengukuran Dampak dan Manfaat
• RQ4.1: Apakah terdapat peningkatan efektivitas waktu transaksi setelah menggunakan sistem informasi penjualan berbasis web?
• RQ4.2: Bagaimana persepsi pengguna terhadap aspek kemudahan, kecepatan, dan efisiensi sistem dibandingkan proses manual?

________________________________________
RQ Utama:
"Bagaimana merancang dan mengimplementasikan Sistem Informasi Penjualan UMKM Berbasis Web Menggunakan Laravel untuk meningkatkan efisiensi proses transaksi dan pencatatan penjualan dibandingkan metode manual?"

# PROSES RQ
```bash
2. Kategori 2: RQ tentang Desain, Implementasi, dan Teknologi
RQ2.1: Bagaimana merancang arsitektur sistem penjualan berbasis Laravel dengan modul produk, keranjang, pesanan, dan laporan?
RQ2.2: Bagaimana implementasi proses checkout dan manajemen transaksi dalam aplikasi web berbasis Laravel?

# RESPOND
```bash
Berdasarkan RQ di atas, berikut judul penelitian yang baik dan menarik:

"Perancangan dan Implementasi Sistem Informasi Penjualan UMKM Berbasis Web Menggunakan Framework Laravel"

Alternatif lain:
"Pengembangan Aplikasi Web Penjualan UMKM dengan Modul Produk, Keranjang Belanja, dan Laporan Transaksi Menggunakan Laravel"

```bash
terlampir file SLR dengan nama SLR.pdf
```
# BRD
```bash
terlampir file BRD berdasarkan SLR dengan nama file BRD.pdf
```

# IMPLEMENTASI WEBSITE
```
1. cd root
2. cd boilerplate
3. ./start.sh uts-pemweb
4. cd src
5. code .
6. template website dengan ide saya diambil dari : https://themewagon.com/themes/business/
7. cd resources/views
8. mkdir layouts && mkdir pages && mkdir partials
9. cd layouts
10. touch app.blade.php
11. cd ../pages
12. touch home.blade.php
13. cd ../partials
14. touch navbar.blade.php
15. touch sidebar.blade.php
16. touch header.blade.php
17. touch about.blade.php
18. touch service.blade.php
19. touch pricing.blade.php
20. touch cta.blade.php
21. touch latest.blade.php
22. touch brand.blade.php
23. touch contact.blade.php
24. touch map.blade.php
25. touch footer.blade.php
26. touch script.blade.php
27. cd ../../../routes

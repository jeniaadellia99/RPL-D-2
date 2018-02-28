Software Requirement Specification (SRS)

Version 1.1

22 Febuari 2018

![Gambar](/img/POLINDRA.png)


Aplikasi Distribusi Pemesanan Kartu Telkomsel wilayah Indramayu Berbasis Web dan Android (DISPENKARTEL)

**kelompok 2**

- Jenia Adellia Puspita
- Astri Alisah
- Rizky Alief Satria
- Tuti Nurafni Amalia

D3 Teknik Informatika
Politeknik Negeri Indramayu


1. Pendahuluan
PT Telkomsel adalah sebuah perusahaan operator telekomunikasi seluler di Indonesia.telkomsel merupakan salah satu operator yang mempunyai kualitas sinyal yang bagus. Telkomsel memiliki tiga produk GSM, yaitu SimPATI, KartuAS, serta KartuHALO (paskabayar).
Pemakaian Kartu Telkomsel masih banyak diminati untuk kebutuhan seperti telepon SMS akses internet dan lain-lain. Karena unggul dalam jaringan sinyal dan harga yang masih terjangkau oleh masyarakat.
Pemesanan Kartu dalam jumlah yang banyak oleh Agen konter melalui sales tidak selalu berjalan dengan pendataan yang baik. Kadang bisa juga pemesanan ulang tidak berjalan dengan semestinya dimana kesulitan untuk pembelajaan stok barang yang banyak dan harus ke tempat pengambilan. Sehingga dengan adanya Aplikasi “Distribusi Pemesanan Kartu Telkomsel Berbasis Web dan Android (DISPENKARTEL)” dapat mempermudah Agen konter dalam memesanan Kartu dalam jumlah yang banyak dan pengiriman waktu yang singkat. Dan sales tidak harus menjelanjahi semua konter untuk publikasi penjualan yang membutuhkan waktu yang banyak. Serta aplikasi ini bisa diakses dimana saja yang terhubung oleh internet.
 
1.1 Tujuan
- Memudahkan konter dalam pemesanan jumlah banyak, untuk proses cek barang dan memudahkan sales tanpa harus membuat strategi penjualan dengan publikasi lisan.
- Merencanakan pembuatan aplikasi Distribusi pemesanan kartu telkomsel sesuai dengan kebutuhan pihak Telkomsel Suryalaya Indramayu.
1.2 Lingkup
- Data Stok Barang
- Pemesanan Kartu
- Laporan Penjualan

1.3 Akronim
|Nama|Penjelasan|
|--|--|
|Stok|persediaan barang keperluan untuk perbekalan|
|Kartu|Kartu perdana telepon yang bisa proses menelpon, SMS, dan Internet|

1.4 Referensi
- https://www.telkomsel.com/paket-simpati
- http://hanungnp.staff.telkomuniversity.ac.id/files/2015/04/contoh-SKPL-Sistem-informasi-tugas-akhir-SISTA.pdf


1.5 Overview
-
2. Gambaran Umum
Aplikasi DISPENKARTEL adalah aplikasi berbasis Web dan Android. dimana Admin bisa mengelola data barang, data barang masuk dan data barang keluar(laporan Penjualan) dan menampilkan grafik penjualan serta data yang lebih jelas.
		
2.1 Perspektif Produk
Pada Produk lain, yaitu aplikasi pendataan barang, tidak di sertai dengan pemesanan produk.
dengan adanya Aplikasi ini mudah dipakai untuk pemesanan barang dalam jumlah yang banyak/restok barang ke agen konter yang cepat dan efisien.

2.1.1 Antarmuka sistem
![Gambar](/img/DFD.jpg)

2.1.2 Antarmuka Pengguna

1. Rancangan Mockup Admin

![Gambar](/img/login Admin.jpg)
![Gambar](/img/HalamanUtamaAdmin.jpg)  		
![Gambar](/img/Stok.jpg)
![Gambar](/img/input barang.jpg)
![Gambar](/img/Status Pemesanan.jpg)
	*Belom*	  		
2.1.3 Antarmuka Perangkat keras
![Gambar](/img/Antar Muka Hardware.jpg)	

2.1.4 Antarmuka perangkat lunak
Aplikasi ini hanya bisa di gunakan pada hadphone yang memiliki OS Android.

2.1.5 Operasi-operasi 
|Peran|Penjelasan Operasi|
|--|--|
|Admin|menampilkan pilihan menu berupa Login, CRUD jumlah stock kartu perdana, dan melihat pesanan customer|
|Sales|Register untuk membuat acount, Login, Melihat stock kartu perdana dan juga pemesan|
|Customer/User|Register, Login, dan juga melihat Grafik penjualan, juga memesan kartu perdana|

2.1.7 Kebutuhan-kebutuhan dalam tahapan adaptasi 

2.2 Fungsi-fungsi Produk 
- Flowchart Admin
![Gambar](/img/Flowcart Admin.jpg)
- Flowchart Agen Konter
![Gambar](/img/Flowcart Konter.jpg)
- Flowchart Sales
![Gambar](/img/Flowcart Sales.jpg)

2.3 Karakteristik Pengguna
pengguna bisa melakukan pemesanan ketika sudah melakukan login.
juga dapat melihat status pemesanan untuk mengecek pesanan yang sudah di kirim.
2.4 Batasan-batasan 

- Pengguna bisa melakukan pemesanan ketika sudah melakukan login.
- Juga dapat melihat status pemesanan untuk mengecek pesanan yang sudah di kirim.  
2.5 Batasan-batasan 
- Transaksi pembayaran pada aplikasi  ini masih di lakukan secara manual.
- Pemesanan hanya dilakukan dalam lingkup wilayah indramayu kota.
2.6 Asumsi-asumsi dan ketergantungan/keterkaitan 
- pengguna hanya bisa login ketika sudah melakukan register.

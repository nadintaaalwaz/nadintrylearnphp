1. SOAL 1
   Tambahkan data penjualan sebagaimana berikut:
-	kode_penjualan	= 3
-	tgl			= 8 Februari 2021
-	kasir			= Dini
-	total_penjualan 	= 10.000
  ![image](https://github.com/nadintaaalwaz/nadintrylearnphp/assets/160230442/42e7f85c-b8a0-41e5-a7f9-4582fc556c06)
2. SOAL 2
 	Tambahkan data penjualan sebagaimana berikut:
-	kode_penjualan	= 2
-	tgl 			= 10 Februari 2021
-	kasir			= Dini
-	total_penjualan 	= 20.000
 ![image](https://github.com/nadintaaalwaz/nadintrylearnphp/assets/160230442/8d831357-17b7-458d-8dc9-327f0b286830)
 ![image](https://github.com/nadintaaalwaz/nadintrylearnphp/assets/160230442/cc4bf898-af0d-44d7-acc3-b4dd67e4cec5)

     Data penjualan tidak bisa ditambahkan, karena terdapat kesalahan saat menjalankan perintah ini.
     Kesalahan ini terjadi karena nilai kode_penjualan 2 sudah ada di tabel penjualan.Tabel penjualan memiliki kolom kode_penjualan sebagai kunci utama (primary key), yang berarti setiap nilai kode_penjualan harus unik.
   
3. SOAL 3
  Jelaskan bagaimana solusi agar data pada soal 2 dapat ditambahkan?
  Jawab: Solusi untuk mengatasi kesalahan tersebut adalah dengan mengubah nilai kode_penjualan pada baris kedua agar menjadi unik.
  Misal mengubahnya menjadi 4, 5, atau angka lainnya yang belum ada di tabel penjualan.
  Setelah mengubah nilai kode_penjualan. Perintah SQL akan berhasil dijalankan dan dua baris data baru akan ditambahkan ke tabel penjualan.
  ![image](https://github.com/nadintaaalwaz/nadintrylearnphp/assets/160230442/aa854f2a-efc9-474c-bb95-4e01a8983792)

4. SOAL 4
  Tambahkan data detail_penjualan sebagaimana berikut
-	kode_penjualan 	= 2
-	kode_barang 		= 3
-	harga			= 5.000
-	jumlah			= 5
  ![image](https://github.com/nadintaaalwaz/nadintrylearnphp/assets/160230442/f19d2965-bfbc-49b6-956a-f6c6c799f22a)

  Apakah data dapat ditambahkan? Jelaskan alasannya !
  Jawab: Bisa ditambahkan, karena semua nilai valid dan tidak ada pelanggaran terhadap aturan database.
  
5. SOAL 5
  Jelaskan bagaimana solusi agar data pada soal 4 dapat ditambahkan
  Jawab: Tidak perlu solusi karena tidak terdapat masalah dalam penambahan data

6.SOAL 6
  Terangkan apa yang bisa anda pahami dari soal 1-5 terkait dengan duplikasi dan inkonsisten data
  Jawab: Dari soal 1-5, terlihat bahwa duplikasi data dapat terjadi pada kolom kunci utama tunggal maupun kombinasi beberapa kolom.
  Duplikasi data ini dapat menyebabkan inkonsistensi data dan perlu diatasi untuk menjaga integritas data.



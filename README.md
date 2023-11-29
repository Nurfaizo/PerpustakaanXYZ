# PerpustakaanXYZ

Dalam class diagram terdapat 6 class yaitu Admin, Buku, Anggota, TransaksiPeminjam, TransaksiPengembalian dan notifikasi yang dimana sudah di implementasikan.
	Dalam implementasi class anggota terdapat perubahan seperti riwayat kembali yang dimana digunakan untuk menyimpan data buku yang sudah dikembalikan. Dalam transaksi peminjam juga terdapat beberapa perubahan berupa tambahan variabel dikembalikan.

	Serta terdapat perubahan penghilangan penggunaan variabel dengan tipe data time.

Berikut penjelasan dari masing-masing class :
1.	Notifikasi
-	Melakukan notifikasi kepada anggota berapa banyak buku yang masih dipinjam oleh anggota.
2.	Anggota
-	Melakukan penyimpanan data anggota perpustakaan
-	Menyimpan riwayat pinjam dan kembali
3.	Buku
-	Menyimpan data buku
-	Buku dipinjam oleh seorang anggota perpus menggunakan method pinjam dengan durasi serta status buku telah dikembalikan atau belum
-	Buku dikembalikan oleh seorang anggota perpus menggunakan method pinjam yang dimana akan merubah statu buku menjadi available dan buku telah dikembalikan serta menyimpad riwayat kembali dalam data anggota dengan data waktu kembali.
4.	TransaksiPeminjam
-	Menyimpan data buku yang dipinjam, tanggal pinjam, durasi dan status peminjaman.
-	Method constructor dan setter getter.
5.	TransaksiKembali
-	Menyimpan data transaksi pinjam dan tanggal pengembalian.
6.	Admin
-	 Menyimpan akses manajemen anggota, buku dan aktivitas.
-	Mengelola buku dengan dapat mengubah judul, ISBN dan penulis.
-	Mengelola anggota dengan dapat mengubah nama, id, dan Alamat dari anggota
-	generateLaporan memberikan informasi aktivitas pinjam anggota.


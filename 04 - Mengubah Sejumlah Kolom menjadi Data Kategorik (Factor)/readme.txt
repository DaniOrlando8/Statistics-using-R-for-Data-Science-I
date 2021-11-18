Mengubah Sejumlah Kolom menjadi Data Kategorik (Factor)
Pada data_intro beberapa variabelnya bersifat kualitatif yaitu variabel jenis kelamin, produk, dan Tingkat_Kepuasan. 
Variabel tersebut harus di ubah jenis datanya menjadi faktor untuk mendapatkan karakteristik dari setiap pelanggan 
(observasi).

Untuk mengubah tipe data menjadi factor dapat menggunakan syntax berikut:

data_intro$Jenis.Kelamin <- as.factor(data_intro$Jenis.Kelamin)

data_intro$Produk <- as.factor(data_intro$Produk)

data_intro$Tingkat.Kepuasan <- as.factor(data_intro$Tingkat.Kepuasan)

 

Tugas Praktek

Gantilah bagian [...1...] pada code editor untuk  merubah kolom Jenis.Kelamin, Produk dan Tingkat.Kepuasan menjadi tipe 
data faktor (Factor). Kemudian gantilah bagian [...2...] pada code editor untuk menampilkan struktur dari kolom Jenis.
Kelamin, Produk dan Tingkat.Kepuasan dengan function str.

Jika berjalan dengan lancar maka akan tampil sebagian dataset pada Console sebagai berikut.

> str(data_intro$Jenis.Kelamin)
 Factor w/ 2 levels "1","2": 1 2 2 1 2 1 1 2 2 2 ...
> str(data_intro$Produk)
 Factor w/ 5 levels "A","B","C","D",..: 1 4 4 1 4 2 2 5 5 5 ...
> str(data_intro$Tingkat.Kepuasan)
 Factor w/ 3 levels "1","2","3": 2 2 3 3 2 3 1 3 1 1 ...
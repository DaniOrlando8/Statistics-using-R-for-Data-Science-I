Estimasi Nilai Statistik Modus
Modus merupakan nilai yang menunjukan nilai yang sering muncul. Modus digunakan untuk data bertipe nominal dan ordinal.

Untuk menampilkan modus dari data dapat menggunakan syntax :

Mode(data_intro$Produk)

Berikut penjelasan function diatas :

Mode akan menampilkan nilai terbanyak pada variabel yang diamati.
data_intro$Produk, merupakan kolom Produk dari variabel data_intro.
Untuk menggunakan function Mode tersebut, menggunakan library tambahan bernama "pracma".

 

Tugas Praktek

Lengkapi bagian [...1...] pada code editor untuk  membaca file seperti yang ditunjukkan pada bagian Lesson. Dan lengkapi
bagian [...2...] untuk melihat modus pada kolom tingkat kepuasan.

Jika berjalan dengan lancar maka akan tampil sebagian dataset pada Console sebagai berikut.

> Mode(data_intro$Produk)
[1] "D"
> Mode(data_intro$Tingkat.Kepuasan)
[1] "3"
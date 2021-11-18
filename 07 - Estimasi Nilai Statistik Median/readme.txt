Estimasi Nilai Statistik Median
Median merupakan nilai tengah dari suatu kumpulan data. median digunakan untuk data bertipe interval dan rasio.

Untuk menampilkan median dari data dapat menggunakan syntax :

median(data_intro$Pendapatan)

Berikut penjelasan function diatas :

median akan menampilkan nilai tengah pada variabel yang diamati.
data_intro$Pendapatan, merupakan kolom Pendapatan dari variabel data_intro.
 

Tugas Praktek

Lengkapi bagian […1…], [...2...], [...3...], dan [...4...] pada code editor untuk  menghasilkan median dari kolom 
Pendapatan, Harga, Jumlah dan Total seperti yang diinstruksikan pada comment Lesson.

Jika berjalan dengan lancar maka akan tampil sebagian dataset pada Console sebagai berikut.

> median(data_intro$Pendapatan) 
[1] 875000

> ## carilah median untuk  kolom Harga dari variable data_intro
> median(data_intro$Harga) 
[1] 2e+05

> ## carilah median untuk kolom Jumlah dari variable data_intro
> median(data_intro$Jumlah) 
[1] 4

> ## carilah median untuk  kolom Total dari variable data_intro
> median(data_intro$Total) 
[1] 675000
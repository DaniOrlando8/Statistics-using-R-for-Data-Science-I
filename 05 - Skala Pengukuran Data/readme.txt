Skala Pengukuran Data
Setelah data diubah jenis tipe datanya, selanjutnya adalah pemeriksaan untuk memastikan apakah tipe data setiap variabel 
sudah sesuai dengan skala pengukuran masing-masing.

Untuk melihat data dan tipe data dapat menggunakan syntax berikut :

data_intro

str(data_intro)

 

Tugas Praktek

Lengkapi bagian [...1...] dan [...2...] pada code editor untuk menampilkan variable data_intro dan strukturnya dengan 
function str.

Jika berjalan dengan lancar, maka muncul 2 output berikut.

   ID.Pelanggan    Nama Jenis.Kelamin Pendapatan Produk  Harga Jumlah   Total
1             1    Arif             1     600000      A 100000      4  400000
2             2    Dian             2    1200000      D 250000      4 1000000
3             3   Dinda             2     950000      D 250000      3  750000
4             4   Fajar             1     400000      A 100000      2  200000
5             5     Ika             2    1200000      D 250000      4 1000000
6             6   Ilham             1     800000      B 150000      4  600000
7             7   Indra             1     950000      B 150000      5  750000
8             8 Kartika             2    1100000      E 300000      3  900000
9             9 Lestari             2     800000      E 300000      2  600000
10           10     Lia             2    1700000      E 300000      5 1500000
11           11   Maria             2     600000      A 100000      4  400000
12           12    Maya             2     950000      B 150000      5  750000
13           13    Mila             2     400000      C 200000      1  200000
14           14   Nurul             2    6450000      D 250000      5 1250000
15           15   Retno             2    1000000      C 200000      4  800000
16           16    Rini             2     800000      B 150000      4  600000
17           17   Rizki             1    1200000      C 200000      5 1000000
18           18    Sari             2     700000      D 250000      2  500000
19           19    Tyas             2     600000      A 100000      4  400000
20           20   Wahyu             1     800000      C 200000      3  600000
   Tingkat.Kepuasan
1                 2
2                 2
3                 3
4                 3
5                 2
6                 3
7                 1
8                 3
9                 1
10                1
11                3
12                3
13                2
14                1
15                2
16                1
17                3
18                1
19                3
20                1
 
'data.frame':	20 obs. of  9 variables:
 $ ID.Pelanggan    : chr  "1" "2" "3" "4" ...
 $ Nama            : chr  "Arif" "Dian" "Dinda" "Fajar" ...
 $ Jenis.Kelamin   : Factor w/ 2 levels "1","2": 1 2 2 1 2 1 1 2 2 2 ...
 $ Pendapatan      : int  600000 1200000 950000 400000 1200000 800000 950000 1100000 800000 1700000 ...
 $ Produk          : Factor w/ 5 levels "A","B","C","D",..: 1 4 4 1 4 2 2 5 5 5 ...
 $ Harga           : int  100000 250000 250000 100000 250000 150000 150000 300000 300000 300000 ...
 $ Jumlah          : int  4 4 3 2 4 4 5 3 2 5 ...
 $ Total           : int  400000 1000000 750000 200000 1000000 600000 750000 900000 600000 1500000 ...
 $ Tingkat.Kepuasan: Factor w/ 3 levels "1","2","3": 2 2 3 3 2 3 1 3 1 1 ...
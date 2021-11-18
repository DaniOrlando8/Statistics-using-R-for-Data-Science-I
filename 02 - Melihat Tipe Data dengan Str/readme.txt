Melihat Tipe Data dengan Str
Adalah praktek yang sangat baik untuk mengenal atau melakukan profile tiap dataset yang sudah dibaca ke dalam R – dan 
secara sederhana di R dapat kita lakukan dengan function str. Function str akan menyajikan informasi tiap kolom dataset 
dalam format yang compact – satu baris informasi saja per row. Pendekatan singkat dan jelas ini membuat str menjadi 
function favorit dan efektif untuk mengenal data di tahap awal.

Syntax-nya juga cukup sederhana, cukup masukkan dataset ke dalam function ini seperti pada contoh berikut.

str(data_intro)

Tugas Praktek

Gantilah bagian […1…] pada code editor dengan perintah str yang menggunakan input variable data_intro.

Jika berjalan dengan lancar, maka output-nya sebagian akan terlihat sebagai berikut.

> str(data_intro)
'data.frame':	20 obs. of  9 variables:
 $ ID.Pelanggan    : int  1 2 3 4 5 6 7 8 9 10 ...
 $ Nama            : Factor w/ 20 levels "Arif","Dian",..: 1 2 3 4 5 6 7 8 9 10 ...
 $ Jenis.Kelamin   : int  1 2 2 1 2 1 1 2 2 2 ...
 $ Pendapatan      : int  600000 1200000 950000 400000 1200000 800000 950000 1100000 800000 1700000 ...
 $ Produk          : Factor w/ 5 levels "A","B","C","D",..: 1 4 4 1 4 2 2 5 5 5 ...
 $ Harga           : int  100000 250000 250000 100000 250000 150000 150000 300000 300000 300000 ...
 $ Jumlah          : int  4 4 3 2 4 4 5 3 2 5 ...
 $ Total           : int  400000 1000000 750000 200000 1000000 600000 750000 900000 600000 1500000 ...
 $ Tingkat.Kepuasan: int  2 2 3 3 2 3 1 3 1 1 ...


Untuk baris di bawahnya adalah penjelasan dari tiap kolom/variabel data yang terdiri dari:

Nama kolom
Tipe data kolom
Isi dari kolom tersebut
Jika Factor maka ada tambahan indeksnya
Berikut penjelasan hasil dalam bentuk ilustrasi dari 3 kolom, yaitu ID.Pelanggan, Nama, dan Jenis.Kelamin.


Mengubah Tipe Data Kolom ID.Pelanggan menjadi Character

Variabel ID.Pelanggan merupakan kode unik dari setiap variabel dan tidak bisa dicari nilai statistiknya. Sehingga tipe 
data ID.Pelanggan perlu diubah menjadi character agar tidak ikut di analisis.

Untuk mengubah tipe data ID.Pelanggan menjadi character dapat menggunakan syntax :

data_intro$ID.Pelanggan <-as.character(data_intro$ID.Pelanggan)

Function as.character mengubah id tiap pelanggan menjadi string/character - ditandai dengan tanda petik diantara kode 
unik tersebut.
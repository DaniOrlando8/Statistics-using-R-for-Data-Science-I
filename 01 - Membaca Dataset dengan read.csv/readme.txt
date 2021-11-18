Membaca Dataset dengan read.csv
Untuk membaca dataset data_intro.csv tersebut kita akan gunakan function read.csv dengan konstruksi berikut:

data_intro <- read.csv("https://storage.googleapis.com/dqlab-dataset/data_intro.csv",sep=";")

Penjelasan terhadap function di atas adalah sebagai berikut:

Komponen                                                       Deskripsi

data_intro                                                   = nama variable yang digunakan untuk menampung pembacaan file dataset data_intro.csv
read.csv                                                     = function yang digunakan untuk membaca contoh dataset dengan format file teks (CSV)
https://storage.googleapis.com/dqlab-dataset/data_intro.csv  = lokasi dataset yang terdapat di web DQLab. Jika lokasi file dan aplikasi R terdapat 
                                                               di komputer lokal Anda, maka gantilah dengan lokasi file di lokal. Misalkan c:\data\data_intro.csv
sep=";"                                                      = Parameter pemisah (separator) antar kolom data. Kita gunakan tanda titik koma untuk dataset tingkat 
                                                               kepuasan pelanggan.

                                                              
# Tugas-5
# <p align="center">MEMBUAT PROGRAM SEDERHANA MENGGUNAKAN DICTIONARY</p>
# Dictionary
* Dictionaries adalah koleksi pasangan item-item berasosiasi dimana setiap pasangan terdiri dari suatu key dan value.
* Pasangan key-value ini ditulis seabagai key:value.
* Dictionaries ditulis dipisahkan koma dalam kurung kurawal

Buat program sederhana yang akan menampilkan daftar nilai mahasiswa, dengan ketentuan :

* Program dibuat dengan menggunakan Dictionary
* Tampilkan menu pilihan: (*Tambah Data, Ubah Data, Hapus Data, Tampilkan Data, Cari Data*)
* Nilai Akhir diambil dari perhitungan 3 komponen nilai (tugas: 30%, uts: 35%, uas: 35%)
* Buat flowchart dan penjelasan programnya pada README.md.
* Commit dan push repository ke github.
# <p align="center">Pembahasan Program</p>
Berikut adalah dictionary yang di definisikan terlebih dahulu :

      data = {}
      
Selanjutnya adalah perulangan yang digunakan :

      while True :
            statment
            
selanjutnya adalah membuat fungsi input data (Nama, NIM, Nilai Tugas, Nilai UTS, Nilai UAS,) :

![1k](https://user-images.githubusercontent.com/56942922/71726925-2e37ab00-2e6b-11ea-9d54-6b0130f0f715.png)
![c](https://user-images.githubusercontent.com/56942922/71778262-32d0a080-2fde-11ea-92b0-afe3cd7aa8c3.png)

# Mebuat Fungsi Lihat Data :
kodingan untuk menampilkan inputan data, ``if`` sebagai pembandin ketika data belum terinput maka akan menampilkan ``Belum ada data terinput`` dan ``else`` untuk menampilkan data yang sudah terinputkan,``no=1`` memulai penomoran dimulai dari angka 1 dan ``no +=1`` untuk setiap penomoran di tambahkan 1 sebanyak data yang diinputkan.

![c](https://user-images.githubusercontent.com/56942922/71778246-e84f2400-2fdd-11ea-9273-cc13d2b71040.png)

## Membuat sebuah program Tambah Data, Ubah Data, Lihat Data, Hapus Data, Cari Data, Keluar.

![p](https://user-images.githubusercontent.com/56942922/71778328-09fcdb00-2fdf-11ea-9a7b-f9a484ef90b4.png)
# OUTPUT
![lihat](https://user-images.githubusercontent.com/56942922/71778384-c22a8380-2fdf-11ea-842c-3b58ace3f973.png)

# 1. Tambah Data
memanggil fungsi Input data :

![tambah](https://user-images.githubusercontent.com/56942922/71778455-a1166280-2fe0-11ea-87eb-4c7b8ca6ceb8.png)
# output
![OT](https://user-images.githubusercontent.com/56942922/71778484-12561580-2fe1-11ea-897c-c8d6a60a1801.png)
# 2. Lihat Data
![3k](https://user-images.githubusercontent.com/56942922/71778516-7973ca00-2fe1-11ea-9963-445632459f65.png)
# OUTPUT
memaggil fungsi dengan ``cetak(data)`` sehingga data yg nanti sudah diinput akan ditampilkan.
      Data belum diinput :
<img width="371" alt="6" src="https://user-images.githubusercontent.com/56942922/71778534-cfe10880-2fe1-11ea-99bc-f8b92e669144.png">
      Tampilan data sudah diinput :
<img width="375" alt="2" src="https://user-images.githubusercontent.com/56942922/71778580-47af3300-2fe2-11ea-86b0-187a7b8a3cdb.png">
# 3. Cari data
kodingan untuk mencari data yg terinput sebelumnya :
![cari data](https://user-images.githubusercontent.com/56942922/71810851-e81a5b80-30a5-11ea-99f2-9c91e284f47f.png)
      dimana mencari data dengan format nama yang telah diinputkan diatas
# OUTPUT
<img width="308" alt="4" src="https://user-images.githubusercontent.com/56942922/71810979-34fe3200-30a6-11ea-869a-07302af79398.png">
# 4. Mengubah Data
Perintah dijalankan jika input yang di masukan adalah u, di dalam kondisi ini terdapat input dan kondisi, dimana jika input nama ada di dalam variabel daftar.keys maka akan muncul beberapa pilihan untuk mengubah semua data atau data tertentu saja.
![Ubah](https://user-images.githubusercontent.com/56942922/71811212-b3f36a80-30a6-11ea-9c9c-00dd33aaeb91.png)
# OUTPUT
<img width="297" alt="1" src="https://user-images.githubusercontent.com/56942922/71811305-ea30ea00-30a6-11ea-82ac-1ac62b0fa3eb.png">
# 5.Hapus Data
Data yang di hapus adalah data yang di input dalam variabel nama dimana berisi nama (string) yang mewakili data NIM, Nilai Tugas, UTS dan UAS.
![hapus data](https://user-images.githubusercontent.com/56942922/71811442-485dcd00-30a7-11ea-94d2-f20e2cb553e9.png)
# OUTPUT
![h](https://user-images.githubusercontent.com/56942922/71811615-bf936100-30a7-11ea-8c7c-2858d4a278c2.png)



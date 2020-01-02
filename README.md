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

``data = {} ``
Selanjutnya adalah perulangan yang digunakan :
``while True :\n
      statemen``
selanjutnya adalah membuat fungsi input data :

  `` def input_data(): 
      nama = input("Nama: ")
      nim = input("NIM: ")
      tugas = int(input ("Nilai Tugas : "))
    uas = int(input("Nilai UAS : "))
    uts = int(input("Nilai UTS : "))
    a = tugas * 30 / 100
    b = uas * 35 / 100
    c = uts * 35 /100
    akhir = a + b + c``
    

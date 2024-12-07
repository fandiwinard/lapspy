# lapspyTugas Praktikum 8 Mata Kuliah Program Komputer dan Praktek (Lab6)

Program ini dirancang untuk mengelola data mahasiswa dalam bentuk sederhana. Program ini memungkinkan pengguna untuk:

    Menambahkan data mahasiswa baru: Pengguna dapat memasukkan nama dan nilai mahasiswa baru, yang kemudian akan disimpan dalam sebuah list.

    Menampilkan semua data mahasiswa: Program akan menampilkan daftar lengkap semua mahasiswa yang telah tersimpan, beserta nama dan nilainya.

    Menghapus data mahasiswa: Pengguna dapat menghapus data mahasiswa tertentu dengan memasukkan nama mahasiswa yang ingin dihapus.

    Mengubah nilai mahasiswa: Pengguna dapat mengubah nilai mahasiswa tertentu dengan memasukkan nama mahasiswa dan nilai baru.

Penjelasan Detail:

List mahasiswa: 
List ini digunakan untuk menyimpan data mahasiswa. Setiap elemen dalam list adalah sebuah dictionary yang berisi dua key: 
'nama' (untuk menyimpan nama mahasiswa) dan 'nilai' (untuk menyimpan nilai mahasiswa).


Fungsi tambah(): 
Fungsi ini menambahkan data mahasiswa baru ke dalam list mahasiswa. Pengguna diminta memasukkan nama dan nilai, 
kemudian data tersebut disimpan dalam bentuk dictionary dan ditambahkan ke list.


Fungsi tampilkan(): 
Fungsi ini mencetak semua data mahasiswa yang tersimpan dalam format yang mudah dibaca. 
Jika list mahasiswa kosong, maka akan ditampilkan pesan bahwa data masih kosong.

Fungsi hapus(nama): 
Fungsi ini mencari mahasiswa dengan nama yang diberikan. Jika ditemukan, data mahasiswa tersebut akan dihapus dari list. 
Jika tidak ditemukan, akan ditampilkan pesan bahwa data tidak ditemukan.


Fungsi ubah(nama): 
Fungsi ini mencari mahasiswa dengan nama yang diberikan. Jika ditemukan, pengguna akan diminta memasukkan nilai baru, dan nilai lama akan diganti dengan nilai baru. 
Jika tidak ditemukan, akan ditampilkan pesan bahwa data tidak ditemukan.


Loop Utama: 
Loop while True menjalankan program secara berulang hingga pengguna memilih untuk keluar. Pada setiap iterasi, 
program menampilkan menu pilihan dan meminta pengguna untuk memilih tindakan yang ingin dilakukan.
![image](https://github.com/user-attachments/assets/ed80ba21-b482-4623-a098-07566d503aea)
![image](https://github.com/user-attachments/assets/cfa7b597-469d-4767-b511-587a520d28ff)
![image](https://github.com/user-attachments/assets/d9964fd7-ce7d-49bf-a9c1-9efb5ccfc585)



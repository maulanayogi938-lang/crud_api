# praktikum_api_crud

A new Flutter project

## Penjelasan tentang (API, REST, JSON & HTTP PACKEGE)
I.	API (Application Programming Interface) adalah seperangkat definisi, protokol, dan tools untuk membangun perangkat lunak aplikasi. Dalam praktikum ini, API bertindak sebagai jembatan yang memungkinkan aplikasi Flutter (klien) Anda berkomunikasi dengan server (backend) untuk mengambil atau mengirim data.
II.	REST (Representational State Transfer) adalah gaya arsitektur yang paling umum digunakan untuk membuat API berbasis web. REST API menggunakan metode HTTP standar untuk melakukan operasi pada resources.
III.	Metode HTTP 
Metode HTTP	Operasi CRUD	Deskripsi
GET	READ	Mengambil satu atau lebih resource.
POST	CREATE	Membuat resource baru.
PUT	UPDATE	Memperbarui seluruh resource.
PATCH	UPDATE	Memperbarui sebagian resource.
DELETE	DELETE	Menghapus satu atau lebih resource.

IV.	JSON (javascript Object Notation adalah format pertukaran data yang ringan dan mudah dibaca manusia serta diparsing oleh mesin. Hampir semua REST API menggunakan JSON sebagai format data utama sepert :

"id": 1,
"email": "george.bluth@reqres.in",
"first_name": "George",





Langkah-Langkah & Screenshot hal hal yang penting

I.	Add_user_page
 

Dari code di atas hal yang memliki bagian penting terletak di

 

Penjelasan :
 	Untuk memvalidasi suatu form apakah nama dan pekerjaan diisi
 	Menampilkan hasil ke pengguna lewat snakbar 
 	Ngirim data ke API 
 	_submitdata() memiliki funsgi/ logika sebagai pengiriman dan penyimpanan data ke server



II.	Api_Service.dart
 

Dari code di atas hal yang memliki bagian penting terletak di

 

 	Fungsi inti sebagai ,e,buat user baru 
 	Mengirim data keJSON berupa nama dan jobnya 


III.	Main.dart
 

Dari code di atas hal yang memliki bagian penting terletak di

 

 	Hal yang plaing penting di bag READ karena untuk menampilkan data pengguna
Fungsinya : 
 	Initstate() memanggil apiservice.fertchuser() pada saat halam pertama kali di buka 
 	_refereshuserList() untuk memuat ulang data setelah di add, edit dan delete




 Gambar flowchar agar lebih mudah di mengerti cara alur kerja tugas praktikum yang saya pelajari
 


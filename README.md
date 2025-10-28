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
 
<img width="666" height="375" alt="image" src="https://github.com/user-attachments/assets/1fd3efb8-d076-40ee-9287-279f500406af" />

Screenshot Code

<img width="661" height="468" alt="image" src="https://github.com/user-attachments/assets/1b63e9ab-24e6-442b-999b-5533c6f29a6e" />

Penjelasan :
 	Untuk memvalidasi suatu form apakah nama dan pekerjaan diisi
 	Menampilkan hasil ke pengguna lewat snakbar 
 	Ngirim data ke API 
 	_submitdata() memiliki funsgi/ logika sebagai pengiriman dan penyimpanan data ke server



II.	Api_Service.dart
 
<img width="901" height="510" alt="image" src="https://github.com/user-attachments/assets/5dddcac9-9593-4123-b5f0-2ec52cc95c5c" />

Dari code di atas hal yang memliki bagian penting terletak di

 <img width="904" height="380" alt="image" src="https://github.com/user-attachments/assets/0e36063e-8373-4c49-a0fa-93ade724bdfd" />


 	Fungsi inti sebagai ,e,buat user baru 
 	Mengirim data keJSON berupa nama dan jobnya 


III.	Main.dart
 
<img width="831" height="467" alt="image" src="https://github.com/user-attachments/assets/9486be05-7de1-4b1a-8754-d52a0ee0871b" />

Dari code di atas hal yang memliki bagian penting terletak di

 <img width="823" height="340" alt="image" src="https://github.com/user-attachments/assets/fa2d95e4-acec-4974-ab12-230b67655b6c" />

 	Hal yang plaing penting di bag READ karena untuk menampilkan data pengguna
Fungsinya : 
 	Initstate() memanggil apiservice.fertchuser() pada saat halam pertama kali di buka 
 	_refereshuserList() untuk memuat ulang data setelah di add, edit dan delete




 Gambar flowchart agar lebih mudah di mengerti cara alur kerja tugas praktikum yang saya pelajari
 
<img width="507" height="923" alt="image" src="https://github.com/user-attachments/assets/f9ed806e-f5e5-422d-acd2-1bf76c887db9" />


## Lab2Web - Pratikum 2: CSS Dasar

Nama: Marsya Nabila Putri

NIM: 312410338

Kelas: TI.24.A4

## Langkah Pratikum
## 1. Membuat Dokumen HTML Dasar

Langkah awal yaitu membuat file baru bernama ```lab2_css_dasar.html```. Di file ini dituliskan struktur HTML dasar yang mencakup elemen header, navigasi, dan div intro. Struktur tersebut disiapkan sebagai konten awal yang nantinya akan diberi tampilan menggunakan CSS.

<img width="1658" height="981" alt="1" src="https://github.com/user-attachments/assets/a76e1242-4fd2-4e4d-923e-01daf85c579e" />


Hasil tampilan di browser:

<img width="1914" height="645" alt="11" src="https://github.com/user-attachments/assets/8f3cbd1a-e63c-4d1c-9c63-a2f8b7a6ff54" />

## 2. Mendeklarasikan CSS Internal

CSS internal diletakkan pada tag ```<style>``` yang berada di dalam ```<head>```. Melalui cara ini kita bisa mengatur jenis huruf, warna tulisan, ukuran heading, serta gaya tambahan pada judul. Saat aturan CSS internal diterapkan, setiap elemen yang terkena selektor akan langsung menampilkan perubahan sesuai dengan deklarasi yang dibuat.

<img width="1640" height="609" alt="Screenshot 2025-10-02 194141" src="https://github.com/user-attachments/assets/7fdd8b07-3fbc-4959-866d-c8496b3a41fc" />


Hasil tampilan di browser:

<img width="1919" height="754" alt="Screenshot 2025-10-02 194302" src="https://github.com/user-attachments/assets/52fc5335-7e0e-4074-a709-6892f7ae41ba" />

## 3. Menambahkan inline CSS

Inline CSS diterapkan langsung pada tag HTML dengan menambahkan atribut ```style```. Misalnya pada paragraf bisa dituliskan ```<p style="text-align: center; color: #ccd8e4;"> ... </p>```. Aturan ini hanya berpengaruh pada elemen yang diberikan atribut tersebut dan tidak memengaruhi elemen lain. Dalam urutan prioritas, inline CSS berada di tingkat paling atas dibandingkan internal maupun eksternal, sehingga jika ada konflik gaya, inline CSS yang akan ditampilkan di browser.

<img width="1123" height="96" alt="Screenshot 2025-10-02 194855" src="https://github.com/user-attachments/assets/72c266fe-f701-4134-b72d-1118d919e409" />

Hasil tampilan di browser:

<img width="1916" height="755" alt="Screenshot 2025-10-02 195009" src="https://github.com/user-attachments/assets/33f6c774-cd9d-4b87-af4f-c775a49bfcdb" />

## 4. Membuat CSS eksternal

Langkah berikutnya adalah membuat sebuah file stylesheet eksternal dengan nama ```style_eksternal.css```. Di dalam file tersebut dituliskan berbagai aturan gaya, contohnya pengaturan untuk menu navigasi, tautan, serta desain tombol. Setelah aturan selesai dibuat, file CSS ini dihubungkan ke dokumen HTML menggunakan tag ```<link rel="stylesheet" href="style_eksternal.css">``` yang diletakkan pada bagian <head>. Dengan cara ini, tampilan halaman web akan menyesuaikan aturan yang ada di file CSS eksternal tersebut.

<img width="1580" height="415" alt="Screenshot 2025-10-02 195501" src="https://github.com/user-attachments/assets/f5ad55cd-5a5f-47d8-89a9-637973f3b75e" />

Hasil tampilan di browser:

<img width="1919" height="695" alt="44" src="https://github.com/user-attachments/assets/7cd6b005-7c51-4f9b-8c33-f87824384a42" />

## 5. Pilih  pemilih CSS

Selector digunakan sebagai cara untuk menentukan elemen mana yang akan diberi aturan gaya. Jika menggunakan ID Selector (```#id```), aturan tersebut hanya akan diterapkan pada satu elemen yang memiliki id spesifik saja. Sementara itu, Class Selector (```.class```) memungkinkan sebuah aturan dipakai oleh lebih dari satu elemen, sehingga bisa digunakan berulang kali di berbagai bagian halaman.

<img width="1569" height="602" alt="Screenshot 2025-10-02 200125" src="https://github.com/user-attachments/assets/4e7c408a-89bb-4abc-aad1-67a0d20dea89" />

Hasil tampilan di browser:

<img width="1919" height="818" alt="55" src="https://github.com/user-attachments/assets/552f4c57-ed57-45ae-892f-16bdf34d7e4c" />


## Pertanyaan Dan Tugas

<img width="1001" height="349" alt="Screenshot 2025-10-02 200634" src="https://github.com/user-attachments/assets/739a0f9a-1cad-45e9-95a6-4fa959d9a0a2" />

### 1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.

<img width="1576" height="802" alt="Screenshot 2025-10-02 201741" src="https://github.com/user-attachments/assets/2c023b37-9382-467c-9b9c-15716d90014b" />

Output:

<img width="1919" height="675" alt="Screenshot 2025-10-02 201711" src="https://github.com/user-attachments/assets/09d87769-38fb-490f-91a4-bc0ee1e90f01" />

Penjelasan: 

CSS digunakan untuk mengatur tampilan halaman web agar lebih menarik. Pada contoh ini, body diberi warna background agar tidak monoton putih, serta jenis font diganti ke Arial supaya lebih modern. Elemen h1 dijadikan lebih menonjol dengan transformasi huruf kapital (```text-transform: uppercase```) dan jarak antar huruf (```letter-spacing```). Sedangkan elemen p diberi gaya yang lebih lembut: abu-abu gelap, miring, dan ukuran lebih besar agar mudah dibaca. Eksperimen ini menunjukkan bagaimana hanya dengan beberapa baris CSS tampilan web bisa berubah drastis dari sekadar teks biasa menjadi halaman yang lebih estetik.

### 2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan penjelasannya!

<img width="1582" height="774" alt="Screenshot 2025-10-02 202957" src="https://github.com/user-attachments/assets/9b9293c2-caf1-427e-b119-248491dd588f" />

Output:

<img width="1919" height="557" alt="Screenshot 2025-10-02 202943" src="https://github.com/user-attachments/assets/37b8dbef-fec4-4d7d-9723-99f044e38696" />

Penjelasan:

Dalam CSS ada konsep selector yang menentukan elemen mana yang akan diberi gaya.

1. Selektor Umum ```(h1 {})```
   
- Aturan ini berlaku untuk semua elemen ```<h1>``` di halaman.
  
- Jadi kalau kita menulis ```h1 { color: red; }```, maka semua judul ```<h1>``` otomatis menjadi merah, tanpa peduli lokasinya.

2. Selektor Spesifik ```(#intro h1 {})```

- Aturan ini lebih sempit cakupannya: hanya ```<h1>``` yang berada di dalam elemen yang memiliki atribut ```id="intro"```.

- Misalnya kita punya ```<div id="intro"><h1>…</h1></div>```, maka ```<h1>``` di dalam div itu yang akan terkena aturan ini.

- Karena sifatnya lebih spesifik daripada ```h1 {}```, maka jika ada konflik, aturan ```#intro h1``` akan menggantikan aturan umum.

3. Hasil Akhir

- Pada contoh, ```<h1>``` di luar #intro tidak punya aturan lain selain h1 ```{}```, sehingga dia merah.

- Sedangkan ```<h1>``` yang ada di dalam #intro mendapatkan aturan dari kedua deklarasi (```h1 {}``` dan ```#intro h1 {}```). Tetapi karena ```#intro h1``` lebih spesifik, maka aturan inilah yang diikuti → teks jadi biru.


### 3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!

<img width="1570" height="771" alt="Screenshot 2025-10-02 203935" src="https://github.com/user-attachments/assets/583bc9a2-3f15-4502-9751-64b924aa0933" />

<img width="1578" height="156" alt="Screenshot 2025-10-02 203951" src="https://github.com/user-attachments/assets/4c437841-beb0-4b2f-89a7-a3541b3992aa" />

Output:

<img width="1919" height="637" alt="Screenshot 2025-10-02 203924" src="https://github.com/user-attachments/assets/fb487461-b447-4bc4-9ded-496b91983c7a" />

- Eksternal CSS (```style.css```) → Aturan ini berlaku untuk semua elemen <p> jika tidak ada aturan lain yang lebih spesifik.
Warna teks akan biru, ukuran teks 18px.

- nternal CSS (dalam tag ```<style>``` di HTML) → Aturan ini ditulis di dalam file HTML, dan biasanya lebih prioritas dibanding eksternal CSS jika selector-nya sama. Maka, warna teks akan berubah menjadi merah, ukuran teks 20px.

- Inline CSS (dalam atribut elemen HTML) → Inline CSS memiliki prioritas tertinggi, sehingga properti color akan mengikuti green (hijau), meskipun internal atau eksternal CSS sudah mengatur color berbeda.
Tapi karena inline hanya mengatur warna, maka ukuran teks tetap mengikuti internal CSS (20px).


### 4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya! ```( <p id="paragraf-1" class="text-paragraf"> )```

<img width="1564" height="883" alt="Screenshot 2025-10-02 204843" src="https://github.com/user-attachments/assets/52fe3e19-69a2-4916-be6e-fc0f6076e70d" />

Output: 

<img width="1919" height="607" alt="Screenshot 2025-10-02 204927" src="https://github.com/user-attachments/assets/c6f8230b-9a67-4aa9-a07d-a6eb70c99545" />

Penjelasan:

- Selector Class (```.text-paragraf```) → Ditandai dengan tanda titik (```.```). Bisa digunakan oleh banyak elemen. Pada kode di atas, class ```.text-paragraf``` memberikan warna merah dan ukuran teks 18px.

- Selector ID (```#paragraf-1```) → Ditandai dengan tanda pagar (```#```). Bersifat unik, hanya boleh digunakan satu kali dalam satu halaman HTML. Pada kode di atas, ID ```#paragraf-1``` memberikan warna biru dan teks menjadi bold.

- Ketika Elemen Memiliki ID dan Class Sekaligus → Class ```.text-paragraf``` memberi aturan warna merah, sedangkan ID ```#paragraf-1``` memberi aturan warna biru. Karena ID memiliki prioritas lebih tinggi dibanding Class, maka warna yang tampil adalah biru.





























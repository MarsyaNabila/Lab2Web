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





















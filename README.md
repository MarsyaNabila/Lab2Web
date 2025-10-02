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














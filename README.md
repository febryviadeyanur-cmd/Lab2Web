# Lab2Web - Praktikum 2: HTML Lanjutan

**Mata Kuliah:** Pemrograman Web

**Nama:** Febryvia Deya Nur Havidtar Murti Aqsa

**NIM:** 312510194

**Kelas:** I251B

**Program Studi:** Teknik Informatika

## Deskripsi

Repository ini berisi hasil Praktikum 2 (HTML Lanjutan) yang meliputi tabel, form dan berbagai jenis input, semantic HTML, multimedia, dan validasi form dasar.

## Struktur Folder

```
Lab2Web/
├── index.html      
├── biodata.html    
├── media/
│   ├── audio.mp3
│   └── video.mp4
└── README.md
```

## Langkah-langkah Praktikum

### 1. Membuat Tabel Data Mahasiswa
Membuat tabel dengan `<table>`, `<tr>`, `<th>`, `<td>` berisi NIM, Nama, dan Program Studi (minimal tiga data).

![alt text](tabel.png)

### 2. Tabel dengan thead, tbody, dan tfoot
Menambahkan `<caption>`, `<thead>`, `<tbody>`, `<tfoot>`, serta `colspan="2"` pada baris rata-rata.

![alt text](<tabel 2.png>)

### 3. Form Registrasi Mahasiswa
Membuat form dengan input `text`, `email`, `password`, `date`, tombol `submit` dan `reset`, semuanya dihubungkan dengan `<label for="...">`.

![alt text](form.png)

### 4. Radio Button dan Checkbox
Radio button untuk jenis kelamin (satu pilihan, `name` sama) dan checkbox untuk keahlian (boleh lebih dari satu).

![alt text](radio.png)

### 5. Select dan Textarea
Membuat dropdown program studi dengan `<select>` dan kolom alamat dengan `<textarea>`.

![alt text](select.png)

### 6. Validasi Form Dasar
Menggunakan atribut `required`, `minlength`, `min`, `max`, `pattern`, dan `type`. Saat tombol Kirim ditekan tanpa mengisi data, browser menampilkan pesan validasi.

![alt text](validasi.png)

### 7. Halaman Semantic HTML
Menyusun halaman dengan `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, dan `<footer>`.

![alt text](semantic.png)

### 8. Menambahkan Multimedia
Menambahkan `<audio controls>` dan `<video controls>` dengan file dari folder `media/`.

![alt text](mutimedia.png)

### 9. Proyek Mini - Form Biodata Mahasiswa
File `biodata.html` menggabungkan semantic structure, tabel data, form, validasi dasar, dan elemen video.

![alt text](<biodata mini.png>)
![alt text](<biodata mini 2.png>)
![alt text](<biodata mini 3.png>)

### Jawaban Pertanyaan

**1. Apa fungsi `<table>`, `<tr>`, `<th>`, dan `<td>`?**
**Jawaban:** `<table>` digunakan untuk membuat tabel, `<tr>` untuk membuat baris, `<th>` untuk membuat sel header atau judul kolom, dan `<td>` untuk membuat sel data. Tabel juga dapat dibagi menggunakan `<thead>`, `<tbody>`, dan `<tfoot>`, serta dapat diberi judul menggunakan `<caption>`.

**2. Apa perbedaan `<th>` dan `<td>`?**
**Jawaban:** `<th>` digunakan sebagai sel header atau judul kolom/baris, sedangkan `<td>` digunakan untuk menampilkan data pada tabel.

**3. Apa fungsi `colspan` pada tabel?**
**Jawaban:** `colspan` digunakan untuk menggabungkan beberapa kolom menjadi satu sel. Contohnya `colspan="2"` berarti sel tersebut membentang sepanjang dua kolom, seperti pada bagian rata-rata di `<tfoot>`.

**4. Apa fungsi `<form>` dalam HTML?**
**Jawaban:** `<form>` digunakan sebagai wadah untuk menerima data dari pengguna melalui berbagai elemen input, seperti teks, email, password, tanggal, radio button, checkbox, dan lainnya.

**5. Apa perbedaan radio button dan checkbox?**
**Jawaban:** Radio button digunakan untuk memilih satu pilihan dari beberapa pilihan, sedangkan checkbox dapat digunakan untuk memilih satu atau beberapa pilihan. Pada praktikum ini, radio button digunakan untuk jenis kelamin, sedangkan checkbox digunakan untuk memilih keahlian seperti HTML, CSS, dan JavaScript.

**6. Mengapa `<label>` sebaiknya terhubung dengan `id` input melalui atribut `for`?**
**Jawaban:** Agar label terhubung dengan input yang sesuai. Dengan begitu, pengguna dapat mengklik label untuk memilih atau memfokuskan input tersebut, terutama pada radio button dan checkbox.

**7. Apa perbedaan `<textarea>` dengan input type text?**
**Jawaban:** `<input type="text">` digunakan untuk memasukkan teks dalam satu baris, sedangkan `<textarea>` digunakan untuk memasukkan teks yang lebih panjang dan dapat terdiri dari beberapa baris. Ukuran `<textarea>` dapat diatur menggunakan `rows` dan `cols`.

**8. Apa fungsi semantic HTML seperti `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, dan `<footer>`?**
**Jawaban:** Elemen semantic digunakan untuk memberikan makna pada bagian-bagian halaman HTML. `<header>` untuk bagian kepala, `<nav>` untuk navigasi, `<main>` untuk konten utama, `<section>` untuk bagian konten, `<article>` untuk konten mandiri, `<aside>` untuk informasi tambahan, dan `<footer>` untuk bagian kaki halaman.

**9. Apa fungsi `required`, `min`, `max`, `minlength`, `maxlength`, dan `pattern`?**
**Jawaban:** `required` digunakan agar input wajib diisi. `min` dan `max` digunakan untuk menentukan nilai minimum dan maksimum. `minlength` dan `maxlength` digunakan untuk menentukan jumlah karakter minimum dan maksimum. `pattern` digunakan untuk menentukan pola tertentu pada input, misalnya `pattern="[0-9]{8}"` untuk membatasi NIM menjadi 8 digit angka.

**10. Apa perbedaan elemen `<audio>` dan `<video>`?**
**Jawaban:** `<audio>` digunakan untuk memutar suara, sedangkan `<video>` digunakan untuk menampilkan video. Keduanya dapat menggunakan atribut `controls` agar tombol kontrol ditampilkan dan `<source>` untuk menentukan file yang digunakan.

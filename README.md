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

**Jawaban Pertanyaan**

**1. Apa fungsi <table>, <tr>, <th>, dan <td>?**
Jawaban: <table> membuat struktur tabel, <tr> membuat baris, <th> membuat sel header (judul kolom/baris), dan <td> membuat sel data. Tabel juga bisa dikelompokkan dengan <thead> (bagian kepala), <tbody> (bagian isi), dan <tfoot> (bagian kaki), serta diberi judul dengan <caption>.

**2. Apa perbedaan <th> dan <td>?**
Jawaban: <th> adalah sel header yang secara default tampil tebal dan rata tengah serta bermakna sebagai judul kolom/baris. <td> adalah sel data biasa yang berisi isi tabel.

**3. Apa fungsi colspan pada tabel?**
Jawaban: colspan menggabungkan beberapa kolom menjadi satu sel. Contoh colspan="2" membuat sel membentang selebar dua kolom, seperti pada baris "Rata-rata" di <tfoot> praktikum ini. Pasangannya adalah rowspan, yang menggabungkan beberapa baris menjadi satu sel.

**4. Apa fungsi <form> dalam HTML?**
Jawaban: <form> adalah wadah untuk elemen input yang menerima data dari pengguna dan mengirimkannya ke server (atau ke proses lain) saat tombol submit ditekan. Atribut pentingnya adalah action (tujuan pengiriman data) dan method (GET atau POST). Data hanya ikut terkirim jika input memiliki atribut name.

**5. Apa perbedaan radio button dan checkbox?**
Jawaban: Radio button memungkinkan satu pilihan dari satu grup (atribut name sama), sedangkan checkbox memungkinkan memilih satu, beberapa, atau tidak sama sekali. Pada praktikum ini radio button dipakai untuk jenis kelamin, sedangkan checkbox dipakai untuk keahlian (HTML, CSS, JavaScript).

**6. Mengapa <label> sebaiknya terhubung dengan id input melalui atribut for?**
Jawaban: Agar label terkait dengan input-nya: mengklik label langsung memfokuskan input (atau mencentang checkbox/radio), area klik jadi lebih luas, dan pembaca layar (screen reader) bisa membacakan label yang tepat sehingga lebih aksesibel.

**7. Apa perbedaan <textarea> dengan input type text?**
Jawaban: <input type="text"> untuk teks satu baris pendek, sedangkan <textarea> untuk teks panjang multi-baris dengan ukuran diatur lewat rows dan cols. <textarea> punya tag penutup, sedangkan <input> tidak.

**8. Apa fungsi semantic HTML seperti <header>, <nav>, <main>, <section>, <article>, <aside>, dan <footer>?**
Jawaban: Elemen-elemen ini memberi makna pada struktur halaman: <header> kepala halaman/bagian, <nav> navigasi, <main> konten utama, <section> kelompok konten, <article> konten mandiri, <aside> konten pelengkap, dan <footer> kaki halaman. Berbeda dengan <div> dan <span> yang tidak memiliki makna, elemen semantic menjelaskan peran tiap bagian halaman. Manfaatnya: kode lebih mudah dibaca, lebih baik untuk SEO dan aksesibilitas, serta lebih mudah dipelihara.

**9. Apa fungsi required, min, max, minlength, maxlength, dan pattern?**
Jawaban: required mewajibkan input diisi. min dan max menentukan nilai minimum dan maksimum (untuk input angka atau tanggal). minlength dan maxlength menentukan jumlah karakter minimum dan maksimum pada input teks. pattern membatasi isian dengan aturan tertentu (regular expression), misalnya pattern="[0-9]{8}" agar NIM hanya berisi 8 digit angka.

**10. Apa perbedaan elemen <audio> dan <video>?**
Jawaban: <audio> menampilkan pemutar suara saja (tanpa gambar), sedangkan <video> menampilkan gambar bergerak beserta suara, dan ukurannya bisa diatur (width, height). Keduanya memakai atribut controls untuk menampilkan tombol putar dan <source> untuk menentukan file beserta formatnya, serta menyediakan teks cadangan jika browser tidak mendukung. Khusus <video>, ada atribut poster untuk gambar sampul. Atribut autoplay dan loop juga bisa dipakai pada keduanya.

# Praktikum 1: HTML Dasar

Repository ini dibuat untuk memenuhi tugas **Praktikum 1 - HTML Dasar** pada mata kuliah Pemrograman Web.

**Identitas Mahasiswa:**
- **Nama:** Nabila Lutfia Sari
- **NIM:** 312510040
- **Kelas:** I253A
- **Program Studi:** Teknik Informatika
- **Dosen Pengampu:** Agung Nugroho, S.Kom., M.Kom.
- **Kampus:** Universitas Pelita Bangsa

---

## Panduan Screenshot Tugas

Simpan semua file tangkapan layar (screenshot) di dalam folder `screenshots/` dengan format nama angka (`1.png` sampai `8.png`) sesuai tabel berikut:

| No File | Aplikasi / Lokasi | Yang Harus Di-Screenshot |
|---|---|---|
| **`1.png`** | VS Code (Editor) | Kode struktur dasar HTML5 pada `index.html` (`<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`). |
| **`2.png`** | Browser | Tampilan heading `<h1>`, `<h2>`, dan teks paragraf `<p>` di browser. |
| **`3.png`** | Browser | Tampilan hasil pemformatan teks (`<b>`, `<i>`, `<mark>`, `<sub>`, `<sup>`, `<del>`, `<ins>`). |
| **`4.png`** | Browser | Tampilan gambar foto profil mahasiswa (`images/profil.jpg`) dengan lebar 200px. |
| **`5.png`** | Browser | Tampilan file `halaman2.html` yang menunjukkan navigasi link dan anchor link. |
| **`6.png`** | Browser | Tampilan Unordered List (`<ul>` keahlian) dan Ordered List (`<ol>` target belajar). |
| **`7.png`** | Browser | Tampilan utuh satu halaman Profil Mahasiswa (`index.html`) dari atas sampai bawah. |
| **`8.png`** | Browser ([validator.w3.org](http://validator.w3.org)) | Hasil validasi W3C yang menunjukkan halaman bebas error (hijau). |

---

## Struktur Folder

```text
Lab1Web/
├── index.html
├── halaman2.html
├── images/
│   └── profil.jpg
├── screenshots/
│   ├── 1.png
│   ├── 2.png
│   ├── 3.png
│   ├── 4.png
│   ├── 5.png
│   ├── 6.png
│   ├── 7.png
│   └── 8.png
└── README.md
```

---

## Langkah Pengerjaan Praktikum

### 1. Struktur Dasar HTML5
Membuat file `index.html` dengan kerangka dokumen HTML5: deklarasi `<!DOCTYPE html>`, tag `<html>`, `<head>` untuk judul tab browser, dan `<body>` untuk tempat konten diletakkan.

```html
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <title>Praktikum HTML Dasar</title>
</head>
<body>
</body>
</html>
```

**Screenshot Hasil:**  
<img width="788" height="459" alt="Screenshot 2026-09-26 190100" src="https://github.com/user-attachments/assets/29429e89-f528-434e-b4ab-4628cbfbdc2a" />

---

### 2. Menambahkan Heading dan Paragraf
Menambahkan judul utama dengan `<h1>`, subjudul dengan `<h2>`, serta teks paragraf menggunakan tag `<p>`.

```html
<!-- Judul utama dan subjudul -->
<h1>Belajar Dasar HTML</h1>
<h2>Paragraf pada HTML</h2>

<!-- Paragraf -->
<p>
    Kami sedang belajar HTML dasar pada mata kuliah Pemrograman Web.
    Praktikum ini digunakan untuk mengenal tag-tag dasar HTML.
</p>
<p>
    HTML digunakan untuk menyusun struktur dan konten halaman web.
    Browser akan menampilkan hasil interpretasi dari dokumen HTML.
</p>
```

**Screenshot Hasil:**  


---

### 3. Pemformatan Teks
Mencoba berbagai tag pemformatan teks di HTML, seperti cetak tebal (`<b>`, `<strong>`), miring (`<i>`, `<em>`), tanda sorot (`<mark>`), teks kecil (`<small>`), teks coret (`<del>`), teks sisipan (`<ins>`), serta tulisan indeks bawah (`<sub>`) dan pangkat (`<sup>`).

```html
<p>Belajar <b>HTML dasar</b> pada mata kuliah <i>Pemrograman Web</i>.</p>
<p>HTML adalah <strong>bahasa markup</strong> untuk membuat halaman web.</p>
<p>Status: <mark>Mahasiswa Aktif</mark> | Catatan: <small>Semester Gasal</small></p>
<p>Target: <del>Malas-malasan</del> <ins>Rajin Ngoding</ins></p>
<p>Contoh rumus: H<sub>2</sub>O dan rumus kuadrat x<sup>2</sup> + y<sup>2</sup> = r<sup>2</sup></p>
```

**Screenshot Hasil:**  

---

### 4 & 5. Menyisipkan dan Mengatur Ukuran Gambar
Menyimpan file foto di folder `images/profil.jpg`, kemudian menampilkannya menggunakan tag `<img>` dengan atribut `src`, `alt`, `title`, serta mengatur ukuran lebarnya melalui atribut `width`.

```html
<h3>Foto Profil</h3>
<img src="images/profil.jpg" width="200" height="200" alt="Foto profil mahasiswa" title="Foto Profil Mahasiswa">
```

**Screenshot Hasil:**  


---

### 6. Hyperlink dan Halaman Baru (halaman2.html)
Membuat file baru bernama `halaman2.html` untuk mempraktikkan navigasi:
- **Link Internal:** Berpindah antar file (`index.html` dan `halaman2.html`).
- **Link Eksternal:** Mengarahkan ke situs luar seperti Google (`https://www.google.com`).
- **Anchor Link:** Melompat ke bagian tertentu di halaman yang sama menggunakan `#id`.

Potongan kode navigasi:
```html
<nav>
    <a href="index.html">Dasar HTML / Profil Mahasiswa</a> |
    <a href="halaman2.html">Halaman 2</a> |
    <a href="https://www.google.com" target="_blank">Website Eksternal</a>
</nav>
<hr>

<!-- Contoh Anchor Link -->
<h2 id="materi">Materi Tambahan</h2>
<p><a href="#materi">Klik untuk loncat ke judul materi ini</a></p>
```

**Screenshot Hasil:**  


---

### 7. Menambahkan List (Daftar)
Mengelompokkan data menggunakan list:
- `<ul>` (Unordered List): Daftar menggunakan bullet/poin tanpa nomor urut (contoh: daftar keahlian).
- `<ol>` (Ordered List): Daftar berurutan dengan nomor 1, 2, 3 (contoh: target belajar).

```html
<h2>Keahlian</h2>
<ul>
    <li>HTML Dasar</li>
    <li>CSS</li>
    <li>JavaScript</li>
</ul>

<h2>Target Belajar</h2>
<ol>
    <li>Mempelajari struktur HTML</li>
    <li>Mempelajari tag dan atribut</li>
    <li>Membuat halaman HTML</li>
    <li>Menguji halaman pada browser</li>
</ol>
```

**Screenshot Hasil:**  


---

### 8. Menambahkan Komentar
Menambahkan komentar HTML menggunakan format `<!-- isi komentar -->` sebagai penanda bagian kode agar dokumen rapi dan mudah dibaca saat diedit kembali.

```html
<!-- Bagian Profil Mahasiswa -->
<h2>Profil Mahasiswa</h2>

<!-- Bagian Keahlian -->
<ul>
    <li>HTML</li>
    <li>CSS</li>
</ul>
```

---

### 9. Halaman Profil Mahasiswa (Gabungan Semua Elemen)
Menggabungkan semua elemen yang sudah dipelajari menjadi satu halaman `index.html` yang utuh.

Isi lengkap `index.html`:
```html
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profil Mahasiswa</title>
</head>
<body>

    <!-- Navigasi Halaman -->
    <nav>
        <a href="index.html">Beranda</a> |
        <a href="halaman2.html">Halaman 2</a> |
        <a href="https://www.google.com" target="_blank">Website Eksternal (Google)</a>
    </nav>
    <hr>

    <!-- Langkah 2: Judul & Paragraf Dasar -->
    <h1>Belajar Dasar HTML</h1>
    <h2>Paragraf pada HTML</h2>
    <p>
        Kami sedang belajar HTML dasar pada mata kuliah Pemrograman Web.
        Praktikum ini digunakan untuk mengenal tag-tag dasar HTML.
    </p>
    <p>
        HTML digunakan untuk menyusun struktur dan konten halaman web.
        Browser akan menampilkan hasil interpretasi dari dokumen HTML.
    </p>
    <hr>

    <!-- Judul dan Foto -->
    <h1>Profil Mahasiswa</h1>
    <img src="images/profil.jpg" width="200" height="200" alt="Foto profil mahasiswa" title="Foto Profil Mahasiswa">

    <!-- Data Diri -->
    <h2>Data Diri</h2>
    <p>Nama: <b>Nabila Lutfia Sari</b></p>
    <p>NIM: <b>312510040</b></p>
    <p>Kelas: <b>I253A</b></p>
    <p>Program Studi: <i>Teknik Informatika</i></p>
    <p>
        Saya sedang mempelajari dasar-dasar pengembangan aplikasi web menggunakan <strong>HTML</strong>.
        Praktikum ini melatih pemahaman mengenai struktur dokumen web standar, tag, atribut, teks formatting, hyperlink, gambar, dan list.
    </p>

    <!-- Pemformatan Teks Tambahan -->
    <h2>Eksperimen Pemformatan Teks</h2>
    <p>Status: <mark>Aktif</mark></p>
    <p><small>* Terdaftar resmi di pangkalan data kampus.</small></p>
    <p>Rencana: <del>Menunda tugas</del> <ins>Fokus belajar Pemrograman Web</ins></p>
    <p>Contoh penulisan ilmiah: H<sub>2</sub>O dan x<sup>2</sup> + y<sup>2</sup> = r<sup>2</sup></p>
    <p>Belajar HTML dasar sangat <em>penting</em> sebagai fondasi web developer.</p>

    <!-- Keahlian & Target -->
    <h2>Keahlian</h2>
    <ul>
        <li>HTML Dasar</li>
        <li>CSS</li>
        <li>JavaScript</li>
    </ul>

    <h2>Target Belajar</h2>
    <ol>
        <li>Mempelajari struktur HTML dan DTD HTML5</li>
        <li>Mempelajari tag, elemen, dan atribut dasar</li>
        <li>Membuat halaman web terstruktur dan semantik</li>
        <li>Menguasai navigasi hyperlink internal dan eksternal</li>
        <li>Menguji tampilan halaman di web browser dan validasi W3C</li>
    </ol>

    <hr>
    <p><small>&copy; 2026 Praktikum Pemrograman Web - Lab1Web</small></p>

</body>
</html>
```

**Screenshot Halaman Profil Mahasiswa:**  


---

## Pengujian dan Validasi

### Pengujian Browser
File `index.html` dan `halaman2.html` dibuka melalui browser untuk memastikan:
- Teks heading, paragraf, gambar, dan daftar tampil dengan rapi.
- Link internal antar halaman (`index.html` ke `halaman2.html` dan sebaliknya) berfungsi normal.
- Link eksternal terbuka di tab baru.
- Anchor link melompat tepat ke elemen yang dituju.

### Validasi W3C
Kode dicek melalui layanan resmi [W3C Markup Validation](http://validator.w3.org) untuk memastikan struktur dokumen sudah sesuai standar HTML5 dan tidak memiliki error sintaks.

**Screenshot Validasi W3C:**  


---

## Jawaban Pertanyaan Evaluasi

MENJAWAB PERTANYAAN EVALUASI
**1. Apa fungsi deklarasi `<!DOCTYPE html>` pada dokumen HTML?**
Deklarasi `<!DOCTYPE html>` berfungsi untuk memberitahu web browser tentang versi HTML yang digunakan (yaitu HTML5). Hal ini memastikan browser dapat merender dan menampilkan halaman web sesuai standar HTML5 secara konsisten.

**2. Apa perbedaan antara tag, elemen, dan atribut pada HTML?**
Tag: Penanda atau sintaks HTML yang diawali `<` dan diakhiri `>` (misalnya: `<p>` sebagai tag pembuka dan `</p>` sebagai tag penutup).
Elemen: Keseluruhan komponen yang terdiri dari tag pembuka, isi/konten teks di dalamnya, hingga tag penutup (contoh: `<p>Ini paragraf</p>`).
Atribut: Informasi atau properti tambahan yang disisipkan di dalam tag pembuka untuk mengubah/mengatur perilaku elemen (contoh: `src="..."` atau `width="200"` pada tag `<img>`).

**3. Apa perbedaan `<p>` dengan `<br>`? Jelaskan penggunaannya.**
`<p>` (Paragraph): Digunakan untuk mendefinisikan sebuah paragraf baru. Tag ini memiliki tag penutup `</p>` dan secara otomatis memberikan jarak (margin/spasi) di atas dan di bawah teks.
`<br>` (Line Break): Digunakan untuk membuat baris baru tanpa membuat paragraf baru (seperti menekan tombol *Enter* pada teks editor). Tag ini merupakan empty tag (tidak memerlukan tag penutup).

**4. Apa fungsi atribut `href` pada tag `<a>`?**
Atribut `href` (Hypertext Reference) berfungsi untuk menentukan alamat tujuan (URL atau path file) dari link/hyperlink saat teks atau elemen yang dibungkus tag `<a>` diklik.

**5. Apa perbedaan hyperlink ke halaman internal dengan hyperlink ke website eksternal?**
Hyperlink Internal: Menghubungkan halaman web ke halaman/file lain yang masih berada dalam satu folder atau proyek website yang sama (contoh: `<a href="halaman2.html">`).
Hyperlink Eksternal: Menghubungkan halaman web ke situs web atau domain lain di internet melalui alamat URL lengkap (contoh: `<a href="[https://www.google.com](https://www.google.com)">`).

**6. Apa fungsi atribut `src` dan `alt` pada tag `<img>`?**
`src` (Source): Berfungsi untuk menentukan jalur (*path*) atau lokasi file gambar yang ingin ditampilkan.
`alt` (Alternate Text): Berfungsi menyediakan teks alternatif yang akan ditampilkan jika gambar gagal dimuat, serta membantu membaca layar (*screen reader*) untuk pembaca berkebutuhan khusus.

**7. Apa perbedaan penggunaan `<ul>` dan `<ol>`?**
`<ul>` (Unordered List): Digunakan untuk membuat daftar item yang tidak berurutan, biasanya ditampilkan menggunakan simbol bullet (bulatan/kotak).
`<ol>` (Ordered List): Digunakan untuk membuat daftar item terurut secara kronologis atau berjenjang, ditampilkan menggunakan penomoran (angka, huruf, atau angka romawi).

**8. Apa yang terjadi jika path gambar pada atribut `src` salah?**
Gambar tidak akan bisa ditampilkan oleh browser dan akan muncul ikon broken image (gambar rusak). Sebagai gantinya, browser akan menampilkan teks alternatif yang telah kamu tulis di dalam atribut `alt`.

**9. Mengapa struktur heading `<h1>` sampai `<h6>` perlu digunakan secara terstruktur?**
Penggunaan heading secara terstruktur mempermudah pembaca memahami hirarki topik informasi pada halaman web. Selain itu, struktur yang runtut sangat penting untuk *Search Engine Optimization* (SEO) agar mesin pencari (seperti Google) dapat membaca topik utama halaman web dengan lebih baik.

**10. Apa fungsi komentar `<!-- ... -->` dalam kode HTML?**
Komentar berfungsi untuk memberikan catatan, penanda, atau penjelasan pada baris kode HTML untuk mempermudah developer dalam membaca atau merawat kode. Kode di dalam tag komentar tidak akan dieksekusi atau ditampilkan oleh browser.

---

## Checklist Sebelum Dikumpulkan

Berdasarkan checklist pada modul:
- [v] Struktur HTML sudah lengkap.
- [v] Heading dan paragraf sudah digunakan.
- [v] Pemformatan teks sudah dicoba.
- [v] Gambar tampil dengan benar.
- [v] Hyperlink internal dan eksternal dapat digunakan.
- [v] Unordered list dan ordered list sudah dibuat.
- [v] Komentar HTML sudah dicoba.
- [v] Screenshot setiap tahap sudah tersedia (file `1.png` sampai `8.png` di folder `screenshots/`).
- [v] README.md sudah menjelaskan proses praktikum.
- [v] Repository sudah dibuat dan siap dikumpulkan.

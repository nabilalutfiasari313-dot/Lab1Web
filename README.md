# PRAKTIKUM PEMROGRAMAN WEB
> **Modul 1: Dasar-Dasar HTML (HyperText Markup Language)**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

---

##  Informasi Mahasiswa

| Kategori | Detail |
| :--- | :--- |
| **Nama** | Nabila Lutfia Sari |
| **Program Studi** | Teknik Informatika |
| **Universitas** | Universitas Pelita Bangsa |
| **Mata Kuliah** | Pemrograman Web |
| **Tugas** | Praktikum 1 - HTML Dasar |

---

##  Tujuan Praktikum

1. Memahami konsep dasar dan struktur dokumen **HTML5**.
2. Mengimplementasikan berbagai tag dasar HTML seperti elemen teks, hyperlink, gambar, dan daftar (*list*).
3. Mampu mengorganisasi dan mengelola berkas proyek web serta mengunggahnya ke **GitHub**.

---

##  Struktur Direktori Proyek

```text
Lab1Web/
├──  index.html          # Halaman utama (Beranda & Profil)
├──  halaman2.html       # Halaman navigasi internal
├──  images/
│   └──  profil.jpg      # Foto profil mahasiswa
└──  README.md           # Laporan dan dokumentasi praktikum

MENJAWAB PERTANYAAN EVALUASI
1. Apa fungsi deklarasi `<!DOCTYPE html>` pada dokumen HTML?
Deklarasi `<!DOCTYPE html>` berfungsi untuk memberitahu web browser tentang versi HTML yang digunakan (yaitu HTML5). Hal ini memastikan browser dapat merender dan menampilkan halaman web sesuai standar HTML5 secara konsisten.

2. Apa perbedaan antara tag, elemen, dan atribut pada HTML?
Tag: Penanda atau sintaks HTML yang diawali `<` dan diakhiri `>` (misalnya: `<p>` sebagai tag pembuka dan `</p>` sebagai tag penutup).
Elemen: Keseluruhan komponen yang terdiri dari tag pembuka, isi/konten teks di dalamnya, hingga tag penutup (contoh: `<p>Ini paragraf</p>`).
Atribut: Informasi atau properti tambahan yang disisipkan di dalam tag pembuka untuk mengubah/mengatur perilaku elemen (contoh: `src="..."` atau `width="200"` pada tag `<img>`).

3. Apa perbedaan `<p>` dengan `<br>`? Jelaskan penggunaannya.
`<p>` (Paragraph): Digunakan untuk mendefinisikan sebuah paragraf baru. Tag ini memiliki tag penutup `</p>` dan secara otomatis memberikan jarak (margin/spasi) di atas dan di bawah teks.
`<br>` (Line Break): Digunakan untuk membuat baris baru tanpa membuat paragraf baru (seperti menekan tombol *Enter* pada teks editor). Tag ini merupakan empty tag (tidak memerlukan tag penutup).

4. Apa fungsi atribut `href` pada tag `<a>`?
Atribut `href` (Hypertext Reference) berfungsi untuk menentukan alamat tujuan (URL atau path file) dari link/hyperlink saat teks atau elemen yang dibungkus tag `<a>` diklik.

5. Apa perbedaan hyperlink ke halaman internal dengan hyperlink ke website eksternal?
Hyperlink Internal: Menghubungkan halaman web ke halaman/file lain yang masih berada dalam satu folder atau proyek website yang sama (contoh: `<a href="halaman2.html">`).
Hyperlink Eksternal: Menghubungkan halaman web ke situs web atau domain lain di internet melalui alamat URL lengkap (contoh: `<a href="[https://www.google.com](https://www.google.com)">`).

6. Apa fungsi atribut `src` dan `alt` pada tag `<img>`?
`src` (Source): Berfungsi untuk menentukan jalur (*path*) atau lokasi file gambar yang ingin ditampilkan.
`alt` (Alternate Text): Berfungsi menyediakan teks alternatif yang akan ditampilkan jika gambar gagal dimuat, serta membantu membaca layar (*screen reader*) untuk pembaca berkebutuhan khusus.

7. Apa perbedaan penggunaan `<ul>` dan `<ol>`?
`<ul>` (Unordered List): Digunakan untuk membuat daftar item yang tidak berurutan, biasanya ditampilkan menggunakan simbol bullet (bulatan/kotak).
`<ol>` (Ordered List): Digunakan untuk membuat daftar item terurut secara kronologis atau berjenjang, ditampilkan menggunakan penomoran (angka, huruf, atau angka romawi).

8. Apa yang terjadi jika path gambar pada atribut `src` salah?
Gambar tidak akan bisa ditampilkan oleh browser dan akan muncul ikon broken image (gambar rusak). Sebagai gantinya, browser akan menampilkan teks alternatif yang telah kamu tulis di dalam atribut `alt`.

9. Mengapa struktur heading `<h1>` sampai `<h6>` perlu digunakan secara terstruktur?
Penggunaan heading secara terstruktur mempermudah pembaca memahami hirarki topik informasi pada halaman web. Selain itu, struktur yang runtut sangat penting untuk *Search Engine Optimization* (SEO) agar mesin pencari (seperti Google) dapat membaca topik utama halaman web dengan lebih baik.

10. Apa fungsi komentar `<!-- ... -->` dalam kode HTML?
Komentar berfungsi untuk memberikan catatan, penanda, atau penjelasan pada baris kode HTML untuk mempermudah developer dalam membaca atau merawat kode. Kode di dalam tag komentar tidak akan dieksekusi atau ditampilkan oleh browser.

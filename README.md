# LAPORAN PRAKTIKUM PEMROGRAMAN WEB
## MODUL 1: DASAR-DASAR HTML

---

### IDENTITAS MAHASISWA
* Nama: Nabila Lutfia Sari
* Program Studi: Teknik Informatika
* Perguruan Tinggi: Universitas Pelita Bangsa

---

## I. TUJUAN PRAKTIKUM
1. Mahasiswa mampu memahami struktur dasar dokumen HTML.
2. Mahasiswa mampu memahami dan mengimplementasikan tag-tag dasar HTML.
3. Mahasiswa mampu membuat dokumen HTML sederhana secara terstruktur.

---

## II. SARANA DAN PRASARANA
1. Perangkat Keras: Laptop / Komputer.
2. Perangkat Lunak:
   - Text Editor: Visual Studio Code
   - Web Browser: Mozilla Firefox / Google Chrome / Microsoft Edge
   - Validator: W3C Markup Validation Service

---

## III. STRUKTUR DIREKTORI PROYEK

Lab1Web/
- index.html
- halaman2.html
- images/
  - profil.jpg
- README.md

---

## IV. JAWABAN PERTANYAAN EVALUASI

1. Apa fungsi deklarasi `<!DOCTYPE html>` pada dokumen HTML?
Jawab: Deklarasi `<!DOCTYPE html>` berfungsi untuk memberitahu web browser tentang versi HTML yang digunakan (yaitu HTML5). Hal ini memastikan browser dapat merender dan menampilkan halaman web sesuai standar HTML5 secara konsisten.

2. Apa perbedaan antara tag, elemen, dan atribut pada HTML?
Jawab: Tag: Penanda atau sintaks HTML yang diawali `<` dan diakhiri `>` (misalnya: `<p>` sebagai tag pembuka dan `</p>` sebagai tag penutup).
Elemen: Keseluruhan komponen yang terdiri dari tag pembuka, isi/konten teks di dalamnya, hingga tag penutup (contoh: `<p>Ini paragraf</p>`).
Atribut: Informasi atau properti tambahan yang disisipkan di dalam tag pembuka untuk mengubah/mengatur perilaku elemen (contoh: `src="..."` atau `width="200"` pada tag `<img>`).

3. Apa perbedaan `<p>` dengan `<br>`? Jelaskan penggunaannya.
Jawab: `<p>` (Paragraph): Digunakan untuk mendefinisikan sebuah paragraf baru. Tag ini memiliki tag penutup `</p>` dan secara otomatis memberikan jarak (margin/spasi) di atas dan di bawah teks.
`<br>` (Line Break): Digunakan untuk membuat baris baru tanpa membuat paragraf baru (seperti menekan tombol *Enter* pada teks editor). Tag ini merupakan empty tag (tidak memerlukan tag penutup).

4. Apa fungsi atribut `href` pada tag `<a>`?
Jawab: Atribut `href` (Hypertext Reference) berfungsi untuk menentukan alamat tujuan (URL atau path file) dari link/hyperlink saat teks atau elemen yang dibungkus tag `<a>` diklik.

5. Apa perbedaan hyperlink ke halaman internal dengan hyperlink ke website eksternal?
Jawab: Hyperlink Internal: Menghubungkan halaman web ke halaman/file lain yang masih berada dalam satu folder atau proyek website yang sama (contoh: `<a href="halaman2.html">`).
Hyperlink Eksternal: Menghubungkan halaman web ke situs web atau domain lain di internet melalui alamat URL lengkap (contoh: `<a href="[https://www.google.com](https://www.google.com)">`).

6. Apa fungsi atribut `src` dan `alt` pada tag `<img>`?
Jawab: `src` (Source): Berfungsi untuk menentukan jalur (*path*) atau lokasi file gambar yang ingin ditampilkan.
`alt` (Alternate Text): Berfungsi menyediakan teks alternatif yang akan ditampilkan jika gambar gagal dimuat, serta membantu membaca layar (*screen reader*) untuk pembaca berkebutuhan khusus.

7. Apa perbedaan penggunaan `<ul>` dan `<ol>`?
Jawab: `<ul>` (Unordered List): Digunakan untuk membuat daftar item yang tidak berurutan, biasanya ditampilkan menggunakan simbol bullet (bulatan/kotak).
`<ol>` (Ordered List): Digunakan untuk membuat daftar item terurut secara kronologis atau berjenjang, ditampilkan menggunakan penomoran (angka, huruf, atau angka romawi).

8. Apa yang terjadi jika path gambar pada atribut `src` salah?
Jawab: Gambar tidak akan bisa ditampilkan oleh browser dan akan muncul ikon broken image (gambar rusak). Sebagai gantinya, browser akan menampilkan teks alternatif yang telah kamu tulis di dalam atribut `alt`.

9. Mengapa struktur heading `<h1>` sampai `<h6>` perlu digunakan secara terstruktur?
Jawab: Penggunaan heading secara terstruktur mempermudah pembaca memahami hirarki topik informasi pada halaman web. Selain itu, struktur yang runtut sangat penting untuk *Search Engine Optimization* (SEO) agar mesin pencari (seperti Google) dapat membaca topik utama halaman web dengan lebih baik.

10. Apa fungsi komentar `<!-- ... -->` dalam kode HTML?
Jawab: Komentar berfungsi untuk memberikan catatan, penanda, atau penjelasan pada baris kode HTML untuk mempermudah developer dalam membaca atau merawat kode. Kode di dalam tag komentar tidak akan dieksekusi atau ditampilkan oleh browser.
---

## V. KESIMPULAN
Pada praktikum ini, mahasiswa telah berhasil mempelajari dan mengimplementasikan konsep dasar HTML, meliputi struktur dokumen, pengorganisasian konten dengan heading dan paragraf, pemformatan teks, penggunaan elemen gambar dan hyperlink, serta penyusunan daftar (list). Pemahaman ini menjadi fondasi penting untuk pengembangan antarmuka web tingkat lanjut.

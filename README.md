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

1. Apa fungsi deklarasi <!DOCTYPE html> pada dokumen HTML?
Jawab:
Deklarasi <!DOCTYPE html> berfungsi untuk memberi tahu web browser tentang versi standar HTML yang digunakan dokumen tersebut (dalam hal ini HTML5). Hal ini memastikan browser merender konten halaman web sesuai aturan standar yang berlaku.

2. Apa perbedaan antara tag, elemen, dan atribut pada HTML?
Jawab:
- Tag: Penanda khusus berupa nama elemen di dalam kurung siku, contoh: <p> (tag pembuka) dan </p> (tag penutup).
- Elemen: Keseluruhan komponen yang terdiri dari tag pembuka, isi/konten teks, hingga tag penutup. Contoh: <p>Ini paragraf</p>.
- Atribut: Informasi atau properti tambahan yang dituliskan di dalam tag pembuka untuk mengatur perilaku atau karakteristik elemen. Contoh: src="..." atau href="..."..

3. Apa perbedaan <p> dengan <br>? Jelaskan penggunaannya.
Jawab:
Tag <p> (paragraph) digunakan untuk mengelompokkan satu blok teks paragraf dan secara otomatis memberi spasi/margin vertikal sebelum dan sesudah blok teks. Sedangkan tag <br> (break line) digunakan hanya untuk memaksa perpindahan ke baris baru di dalam blok teks tanpa menambahkan margin paragraf.

4. Apa fungsi atribut href pada tag <a>?
Jawab:
Atribut href (Hypertext Reference) menentukan lokasi alamat URL atau jalur file penunjuk (destination target) saat elemen tautan/hyperlink diklik.

5. Apa perbedaan hyperlink ke halaman internal dengan hyperlink ke website eksternal?
Jawab:
Hyperlink internal mengarah ke file atau dokumen lain di dalam direktori proyek lokal yang sama (contoh: halaman2.html). Sementara hyperlink eksternal mengarah ke halaman web di luar domain lokal dengan menyertakan alamat protokol lengkap (contoh: https://www.google.com).

6. Apa fungsi atribut src dan alt pada tag <img>?
Jawab:
Atribut src (source) menentukan jalur/lokasi berkas gambar yang disisipkan. Atribut alt (alternate text) menyimpan teks deskripsi alternatif yang ditampilkan apabila gambar gagal dimuat, serta membantu peranti pemindai layar (screen reader) bagi penyandang disabilitas visual.

7. Apa perbedaan penggunaan <ul> dan <ol>?
Jawab:
Tag <ul> (Unordered List) digunakan untuk menampilkan daftar yang tidak memerlukan urutan/prioritas, secara bawaan ditampilkan berupa simbol buletin. Tag <ol> (Ordered List) digunakan untuk daftar yang berurutan, ditampilkan dengan urutan angka atau huruf secara terstruktur.

8. Apa yang terjadi jika path gambar pada atribut src salah?
Jawab:
Browser tidak dapat menemukan berkas gambar sehingga gambar tidak muncul di halaman web (menampilkan simbol broken image). Sebagai gantinya, browser akan menampilkan teks deskripsi dari atribut alt.

9. Mengapa struktur heading <h1> sampai <h6> perlu digunakan secara terstruktur?
Jawab:
Penggunaan heading hirarkis memperjelas susunan tingkat kepentingan judul dan subjudul bagi pengguna. Selain itu, struktur heading yang runtut sangat penting untuk Search Engine Optimization (SEO) serta membantu pembaca layar menentukan struktur navigasi dokumen.

10. Apa fungsi komentar <!-- ... --> dalam kode HTML?
Jawab:
Komentar digunakan untuk menyisipkan catatan, penjelasan kode, atau menonaktifkan kode HTML sementara. Teks di dalam tag komentar tidak dirender dan tidak terlihat oleh pengguna di web browser.

---

## V. KESIMPULAN
Pada praktikum ini, mahasiswa telah berhasil mempelajari dan mengimplementasikan konsep dasar HTML, meliputi struktur dokumen, pengorganisasian konten dengan heading dan paragraf, pemformatan teks, penggunaan elemen gambar dan hyperlink, serta penyusunan daftar (list). Pemahaman ini menjadi fondasi penting untuk pengembangan antarmuka web tingkat lanjut.

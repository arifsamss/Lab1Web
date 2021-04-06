# Pemrograman Web
```
Nama  : Arif Samsudin
NIM   : 311910255
Kelas : TI.19.C1

```
## Langkah 1
Buka VSCode buat file baru dengan nama lab1_tag_dasar.html, Buat struktur dasar dari dokumen HTML.
```
<!DOCTYPE html>
<html>
<head>
    <title>Tag HTML Dasar </title>
</head>
<body>
</body>
</html>
```
![1](https://user-images.githubusercontent.com/81839328/113710158-9085f800-970d-11eb-8b2d-bd89a13c47a4.JPG)
![5](https://user-images.githubusercontent.com/81839328/113710205-9da2e700-970d-11eb-8675-acb75f28cbc5.JPG)

## Langkah 2
Selanjutnya buatlah beberapa paragraf sederhana sebagai berikut.
```
  <!-- Ini adalah paragraf pertama -->
  <p>Kami sedang belajar HTML dasar, pada matakuliah Pemrograman Web di Prodi 
  Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama yang kami dapat 
  adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar 
  HTML.</p>

  <!-- Ini adalah paragraf kedua -->
  <p>Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang saling 
  mendukung sehingga menjadi satu kesatuan. Paragraf dibuat dengan menggunakan 
  tag dasar html.</p>
```
![2](https://user-images.githubusercontent.com/81839328/113710911-8284a700-970e-11eb-8470-1da91127bdc8.JPG)
![6](https://user-images.githubusercontent.com/81839328/113710916-84e70100-970e-11eb-90f2-3f49f2f70791.JPG)

## Langkah 3
Selanjutnya silakan ubah-ubah nilai atributnya (align => justify, left, right, dan center) untuk melihat perbedaan lainnya.
```
    <!-- Ini adalah paragraf pertama -->
    <p align="center">Kami sedang belajar HTML dasar, pada matakuliah Pemrograman 
    Web di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama 
    yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal 
    tag-tag dasar HTML.</p>

    <!-- Ini adalah paragraf kedua -->
    <p align="left">Ini merupakan sebuah paragraf yang terdiri dari beberapa 
    kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat 
    dengan menggunakan tag dasar html.</p>
```
![3](https://user-images.githubusercontent.com/81839328/113711387-15bddc80-970f-11eb-8e24-5c775e03153a.JPG)
![7](https://user-images.githubusercontent.com/81839328/113711397-1787a000-970f-11eb-8a5b-9841b55c3dc4.JPG)

Kemudian tambahkan judul h1 sebelum paragraf pertama dan tambahkan sub judul h2 sebelum paragraf kedua.
```
    <!-- judul paragraf pertama -->
    <h1>Belajar Dasar HTML</h1>
    <!-- judul paragraf kedua -->
    <h2>Paragraf pada HTML</h2>
```
![4](https://user-images.githubusercontent.com/81839328/113711940-b9a78800-970f-11eb-8ecf-681be2d6a699.JPG)
![7](https://user-images.githubusercontent.com/81839328/113711947-bc09e200-970f-11eb-9e3e-c59d7605cfe5.JPG)

## LANGKAH 4
Lakukan pemformatan teks yang ada pada paragraf yang sudah ada sebelumnya, mengacu kepada penjelasan materi pemformatan teks, sehingga tampilannya seperti berikut.
```
    <p align="center">Kami sedang belajar HTML dasar, pada matakuliah <b>Pemrograman 
    Web</b> di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama 
    yang kami dapat adalah <u>membuat tampilan web sederhana dalam rangka mengenal 
    tag-tag dasar HTML.</u></p>
 ```
![12](https://user-images.githubusercontent.com/81839328/113712178-01c6aa80-9710-11eb-8964-e712378078e5.JPG)
![8](https://user-images.githubusercontent.com/81839328/113712186-04290480-9710-11eb-8491-59fb6934f763.JPG)

## LANGKAH 5
Untuk menyisipkan gambar, siapkan gambar yang akan disisipkan pada halaman web, kemudian simpan file gambar tersebut satu folder dengan file dokumen html.

![13](https://user-images.githubusercontent.com/81839328/113712609-89acb480-9710-11eb-846e-c854d01a1371.JPG)

Kemudian tambahkan tag img setelah paragraf yang kedua, dengan menambahkan heading 3 sebelumnya.
```
    <!-- sub judul paragraf -->
    <h3>Menambahkan Gambar</h3>
    <!-- menambahkan gambar pada dokumen -->
    <img src="Logo_UPB.jpeg" width="200" title="Logo Univeritas Pelita Bangsa">
```
![14](https://user-images.githubusercontent.com/81839328/113713015-0a6bb080-9711-11eb-9abd-52cf9418aa86.JPG)
![9](https://user-images.githubusercontent.com/81839328/113713024-0cce0a80-9711-11eb-82cf-3345f7686a18.JPG)

## LANGKAH 6
Tambahkan hyperlink pada dokumen sebelum heading 1 seperti berikut.
```
    <!-- menambahkan link navigasi -->
    <nav>
    <a href="lab1_tag_dasar.html">Dasar HTML</a>
    <a href="lab1_halaman2.html" target="_top">Halaman 2</a>
    <a href="http://www.google.com">Halaman Web Eksternal Google</a>
    </nav>
    <hr> 
```
![15](https://user-images.githubusercontent.com/81839328/113713310-5fa7c200-9711-11eb-8295-4291e883206a.JPG)
![10](https://user-images.githubusercontent.com/81839328/113713316-620a1c00-9711-11eb-808a-4f7da82de626.JPG)

##LANGKAH 7
Membuat halaman ke 2 yg akan terhubung dengan halaman pertama menggunakan Hyperlink.
```
<!DOCTYPE html>
<html>
<head>
    <title>Halaman 2</title>
</head>
<body>
    <!-- menambahkan link navigasi -->
    <nav>
    <a href="lab1_tag_dasar.html">Dasar HTML</a>
    <a href="lab1_halaman2.html">Halaman 2</a>
    <a href="http://www.google.com">Halaman Web Eksternal Google</a>
    </nav>
    <hr>
    <!-- judul paragraf pertama -->
    <h1>Halaman 2</h1>

</body>
</html>
<body>
    
</body>
</html>
```
![16](https://user-images.githubusercontent.com/81839328/113713620-c1682c00-9711-11eb-8be6-806c1db4d4d1.JPG)
![11](https://user-images.githubusercontent.com/81839328/113713624-c331ef80-9711-11eb-95dd-ed6ae68ef6b2.JPG)

## JAWAB PERTANYAAN

1.	Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah error ketika terjadi kesalahan penulisan tag? 
Tidak ada error, hanya saja jika kita salah menuliskan tag, perubahan tidak akan menjadi seperti yang kita inginkan. 

2.	Apa perbedaan dari tag <p> dengan tag <br> berikan penjelasannya! 
Tag <p> adalah tag untuk membuat paragraf (ada space antar baris) sedangkan tag <br> adalah tag untuk membuat break line (tidak ada space dengan baris baru).

3.	Apa perbedaan atribut title dan alt pada tag <img> , berikan penjelasannya! 
Atribut title memungkinkan kita untuk membuat balon teks pada gambar yang kita tunjuk dengan kursor sedangkan atribut alt atau alternatif text tidak dapat menampilkan balon teks hanya memberi nama gambar.

4.	Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya! 
Tergantung kebutuhan, jika yang ingin kita sesuaikan hanya lebar cukup dengan atribut width saja karena atribut height akan langsung menyesuaikan ukuran width. Akan tetapi jika kita ingin merubah ukuran lebar dan panjangnya maka kedua atribut harus diatur ukurannya.

5.	Pada link tambahkan atribut target dengan nilai atribut bervariasi ( _blank, _self, _top, _parent ), apa yang terjadi pada masing-masing nilai antribut tersebut?
•	_blank membuat link terbuka di new tab.
•	_self membuat link terbuka di current tab.
•	_top untuk membuka link di frame paling atas (paling luar).
•	_parent untuk membuka link di frame yang satu tingkat di atas frame link tersebut berada


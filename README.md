# Lab2Web

<strong>Repository ini dibuat untuk memenuhi tugas Pemrograman Web</strong>
| <strong>Nama</strong>      | <strong>Riris Naomi Gurning</strong>  |
| ----------- | ----------- |
| <strong>NIM</strong>     | <strong>312010190</strong>       |
| <strong>Kelas</strong>   | <strong>TI.20.A.1</strong>        |


# <strong><hr><mark>LANGKAH - LANGKAH PRATIKUM 2 'CSS DASAR'</mark></hr></strong>

# 1. <strong>Membuat dokumen HTML</strong>
   <strong>Buatlah dokumen HTML seperti berikut ini di VSCode:</strong>
    ![](Foto/foto1.png)
   <strong><hr>Selanjutnya buka pada brwoser untuk melihat hasilnya.</hr></strong>
    ![](Foto/foto2.png)

# 2. <strong>Mendeklarasikan CSS Internal></strong>
   <strong>Kemudian tambahkan deklarasi CSS internal seperti berikut pada bagian head dokumen.</strong>
    ![](Foto/foto3.png)
   <strong><hr>Selanjutnya simpan perubahan yang ada, dan lakukan refresh pada browser untuk melihat
   hasilnya..</hr></strong>
    ![](Foto/foto4.png)

# 3. <strong>Menambahkan Inline CSS</strong>
   <strong>Kemudian tambahkan deklarasi inline CSS pada tag '< p >' seperti berikut:</strong>
    ![](Foto/foto5.png)
   <strong><hr>Simpan kembali dan refresh kembali browser untuk melihat perubahannya dan ini hasilnya: </hr></strong>
    ![](Foto/foto6.png)


# 4. <strong>Membuat CSS Eksternal</strong>
   <strong>Buatlah file baru dengan nama style_eksternal.css kemudian buatlah deklarasi CSS seperti berikut.</strong>
    ![](Foto/foto7.png)
   <strong><hr>Kemudian tambahkan tag '< link >' untuk merujuk file css yang sudah dibuat pada bagian '< head >'</hr></strong>
    ![](Foto/foto8.png)
    <strong><hr>Simpan kembali dan refresh kembali browser untuk melihat perubahannya dan ini hasilnya: </hr></strong>
    ![](Foto/foto9.png)

# 5. <strong>Menambahkan CSS Selector</strong>
   <strong>Selanjutnya menambahkan CSS Selector menggunakan ID dan Class Selector. Pada file
   style_eksternal.css, tambahkan kode berikut.</strong>
    ![](Foto/foto10.png)
   <strong><hr>Simpan kembali dan refresh kembali browser untuk melihat perubahannya dan ini hasilnya: </hr></strong>
    ![](Foto/foto11.png)

# 6. <strong>Memembuat dokumen HTML dengan judul lab2_css_eksternal.html</strong>
   <strong>Buatlah dokumen HTML seperti berikut ini di VSCode :</strong>
    <!doctype html>
<html>
<head>
    <!-- menyisipkan css eksternal -->
    <link rel="stylesheet" href="style_eksternal.css" type="text/css">
    <title>CSS eksternal html</title>
    <style>
        body {
            font-family:'Open Sans', sans-serif;
        }
        header {
            min-height: 80px;
            border-bottom:1px solid #77CCEF;
        }
        h1 {
            font-size: 24px;
            color: #FF0000;
            text-align: center;
            padding: 20px 10px;
        }
        h1 i {
            color:#00CED1;
        }
        }
        h2 {
            font-size: 5px;
            color: #00CED1;
            text-align: center;
            padding: 10px 10px;
        }
        h2 i {
            color:#FA8072; 
        }

        </style>
    <link rel="stylesheet" type="text/css" href="styleku.css" />
</head>
<body>
    <header>
        <h1>CSS Internal dan <i>Inline CSS</i></h1>
        <h2>Praktikum 2: <i>CSS Dasar</i></h2>
    </header>
    <nav>
        <a href="lab2_css_dasar.html">CSS Dasar</a>
        <a href="lab2_css_eksternal.html">CSS Eksternal</a>
        <a href="lab1_tag_dasar.html">HTML Dasar</a>
    </nav>
    <!-- CSS ID Selector -->
    <div id="intro">
    <h1>Hello Guys</h1>
    <p style="text-align: center; color: #ccd8e4;">Perkenalkan nama saya Riris Naomi Gurning Kelas TI.20.A1. Saya sedang belajar HTML dan CSS dasar, pada mata kuliah <b>Pemrograman
    Web</b> di <i>Universitas Pelita Bangsa</i>. Pelajaran pertama yang kami dapat
    adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML
    dan CSS.</p>

</body>
</html>
   <strong><hr>Selanjutnya buka pada brwoser untuk melihat hasilnya.</hr></strong>
    ![](Foto/foto2.png)

# Pertanyaan dan Tugas
1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS
dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan
penjelasannya!
3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada
elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan
penjelasan dan contohnya!
4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut
terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser?
Berikan penjelasan dan contohnya! ( <p id="paragraf-1" class="text-paragraf"> )

# Jawaban 
1. 

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
    ![](Foto/foto12.png)
    ![](Foto/foto14.png)
   <strong><hr>Selanjutnya buka pada brwoser untuk melihat hasilnya.</hr></strong>
    ![](Foto/foto13.png)

# Pertanyaan dan Tugas
   ![](Foto/foto21.png)

# Jawaban 
1. Saya akan mengubah dan menambah properti dan nilai pada kode CSS, dimulai dari membuat kerangka html nya
   ![](Foto/foto15.png)

   Kemudian membuat CSS nya dengan menambah properti dan nilai pada kode
   ![](Foto/foto16.png)
   ![](Foto/foto17.png)

   Hasilnya seperti dibawah ini:
   ![](Foto/foto18.png)

   Selanjutnya saya menambahkan css id selector
   ![](Foto/foto19.png)
   Hasilnya seperti ini:
   ![](Foto/foto20.png)

2. h1{} Untuk memberikan style pada semua element h1

   #intro h1{} Awalan simbol hash (#) memungkinkan kita untuk memberi style pada id. selector id bersifat kaku dan tidak bisa digunakan kembali pada element yang lainnya. Menurut saya lebih baik gunakan selektor class untuk mendefinisikan element yang ingin diberi nilai.

3. Setelah dilakukan pengujian, deklarasi CSS Inline lebih dahulu tampil di browser, itu dikarenakan      permintaan HTTP yang sangat kecil memungkinkan untuk ditampilkan dahulu

   Berikut merupakan hasil pengujian deklarasi CSS

   CSS Inline blue

   CSS Internal red

   CSS Eksternal yellow
   ![](Foto/foto22.png)

4. Deklarasi id="paragraf-1" akan ditampilkan pada browser, karena selektor id lebih spesifik dari class atau bahkan element P itu sendiri, kecuali jika kita menambahkan property pada inline element P maka selektor id tersebut akan tertimpa, karena inline lebih spesifik daripada id, class, dan element


# Tugas Lab2 CSS Dasar HTML<br><br>

| Nova Tegar Adiyansyah | 312010145  |
|----------------- |----------- |
|  TI.20.A.1          | PROGRAM WEB|

# Langkah-langkah Praktikum<br>

Disini saya akan membuat langkah-langkah praktikum CSS dasar HTML menggunakan VScode :<br>

![Lab2Web](gambar/ss1.png)
<br>
<br>

## 1. Membuat dokumen HTML <br>

Buatlah dokumen HTML seperti berikut :<br>

![Lab2Web](gambar/dok1.png) <br><br>


Selanjutnya buka pada browser<b> Google Chrome</b> untuk melihat hasilnya <br>

![Law2Web](gambar/dok2.png)


## 2. Mendeklarasikan CSS Internal <br>

Kemudian tambahkan deklarasi CSS internal seperti berikut pada bagian head dokumen <br>

![Lab2Web](gambar/deklarasi1.png) <br>

Selanjutnya simpan perubahan yang ada, dan lakukan refresh pada browser untuk melihat 
hasilnya <br>

![Lab2Web](gambar/deklarasi2.png)<br>


## 3. Menambahkan Inline CSS <br>

Kemudian tambahkan deklarasi inline CSS pada tag < p > seperti berikut : <br>

(<p style="text-align: center; color: #ccd8e4;" ) 


![Lab2Web](gambar/menambahkan1.png)<br>

Simpan kembali dan refresh kembali browser untuk melihat perubahannya <br>

![Lab2Web](gambar/menambahkan2.png) <br>


## 4. Membuat CSS Eksternal<br>

Buatlah file baru dengan nama style_eksternal.css kemudian buatlah deklarasi CSS seperti berikut :

![Lab2Web](gambar/membuatcss1.png)<br>

Kemudian tambahkan tag < link > untuk merujuk file css yang sudah dibuat pada bagian < head > <br>

![Lab2Web](gambar/membuatcss2.png) <br>

Selanjutnya refresh kembali browser untuk melihat hasilnya <br>

![Lab2Web](gambar/membuatcss3.png)


## 5. Menambahkan CSS Selector<br>

Selanjutnya menambahkan CSS Selector menggunakan ID dan Class Selector. Pada file 
style_eksternal.css, tambahkan kode berikut.

![Lab2Web](gambar/menambahkanstyelcss1.png)<br>


Kemudian simpan kembali dan refresh browser untuk melihat perubahannya<br>


![Lab2Web](gambar/menambahcss3.png)
<BR>
<BR>


## ========== TERIMAKASIH ========== ##

<br>
<hr>
<br>

## Pertanyaan <br>

1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS 
dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.

2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan 
penjelasannya!

3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada 
elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan 
penjelasan dan contohnya!

4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut 
terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? 
Berikan penjelasan dan contohnya! ( < p id="paragraf-1" class="text-paragraf" > )

## Jawaban <br>


1. Saya akan mengubah dan menambah properti dan nilai pada kode CSS, dimulai dari membuat kerangka htmlnya. Seperti gambar berikut : Kemudian membuat CSSnya dengan menambahkan nilai dan properti pada kode diatas Disini Saya menambahkan 4 pemilih kedalam CSS, diantaranya body, h2, .avatar, .header-profile. Masing-masing memiliki fungsi untuk mengatur tampilan pada HTML<br>

![Lab2Web](gambar/jwb1.png)<br>

2. Jadi jika mendeklarasikan h1 nya saja itu akan mengubah semua elemen {h1}, sedangkan jika mendeklarasikan {#intro h1} itu hanya mengubah elemen {h1} pada {#intro} saja. <br>

3. Jika mendeklarasikan Internal, Eksternal dan Inline secara bersamaan yang akan ditampilkan pada Browser adalah Inline, Karena Inline Memiliki prioritas dibanding Eksternal atau pun Internal. Saya akan membuat dokumen baru HTML, kemudian saya buat Elemen {h2}, kemudian saya deklarasikan di CSS Internal Eksternal dan juga Inline, dengan menggunakan properti {color} yang berbeda, jika Internal {color: yellow} sementara Eksternal {color: brown;} dan Inline {color: blue;} yang terpanggil dibrowser adalah Inline karena memiliki prioritas. Berikut contohnya :<br>

![Lab2Web](gambar/jwb2.png)<br>

4. Yang ditampilkan dibrowser adalah ID, ID bersifat unik berbeda dengan Class, Class bisa digunakan banyak, sementara ID hanya tertentu saja, oleh karena itu ID yang ditampilkan dibrowser.<br>

![Lab2Web](gambar/jwb4.png)

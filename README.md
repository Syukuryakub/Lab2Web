# Lab2Web

Nama   : Syukur Yakub

Kelas  : TI.19.C1

Nim    : 311910696


Langkah-langkah Praktikum 
1.	Membuat dokumen HTML 

![aa](https://user-images.githubusercontent.com/56242226/114253933-c90c2700-99d6-11eb-8189-29e09b5a3539.PNG)

Selanjutnya buka pada browser untuk melihat hasilnya.

![a](https://user-images.githubusercontent.com/56242226/114253980-125c7680-99d7-11eb-98ae-736bd32ea48f.PNG)

2.	Mendeklarasikan CSS Internal
 
Kemudian tambahkan deklarasi CSS internal seperti berikut pada bagian head dokumen

![bb](https://user-images.githubusercontent.com/56242226/114254040-55b6e500-99d7-11eb-8018-8693cf3fbcf9.PNG)

3.	Menambahkan Inline CSS 
Kemudian tambahkan deklarasi inline CSS pada tag seperti berikut.

![c1](https://user-images.githubusercontent.com/56242226/114254137-e1307600-99d7-11eb-9e05-7a64be5be919.PNG)

Simpan kembali dan refresh kembali browser untuk melihat perubahannya.

![c](https://user-images.githubusercontent.com/56242226/114254161-fe654480-99d7-11eb-9daa-520c90f73865.PNG)

4.	Membuat CSS Eksternal
 Buat file baru dengan nama style_eksternal.css kemudian buatlah deklarasi CSS seperti berikut.

![d](https://user-images.githubusercontent.com/56242226/114254227-513efc00-99d8-11eb-9652-5936b1498ed7.PNG)

Kemudian tambahkan tag < link > untuk merujuk file css yang sudah dibuat pada bagian < head >

![e2](https://user-images.githubusercontent.com/56242226/114254248-716ebb00-99d8-11eb-8310-33937ff2abb7.PNG)

Selanjutnya refresh kembali browser untuk melihat perubahannya.

![d1](https://user-images.githubusercontent.com/56242226/114254276-92cfa700-99d8-11eb-806b-6c05177a3c09.PNG)

5.	Menambahkan CSS Selector 
Selanjutnya menambahkan CSS Selector menggunakan ID dan Class Selector. Pada file style_eksternal.css, tambahkan kode berikut.

![e](https://user-images.githubusercontent.com/56242226/114254362-17bac080-99d9-11eb-930d-74ce7d27f95c.PNG)

Kemudian simpan kembali dan refresh browser untuk melihat perubahannya.

![e1](https://user-images.githubusercontent.com/56242226/114254377-315c0800-99d9-11eb-80c4-f3c2bfb2044a.PNG)

Pertanyaan dan Tugas
1.	Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini. 
jawab : 
Jadi dalam eksperimen saya .. saya menambah <body bgcolor="#ff9966"> ini untuk supaya background dapat berwarna semua hingga memenuhi layar computer dan seperti inilah hasil gambarnya : 

![soal no 1](https://user-images.githubusercontent.com/56242226/114254482-c959f180-99d9-11eb-959e-4bf6c269f859.PNG)

2.	Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan penjelasannya! 

jawab : 

Elemen h1 {...} yang dideklarasikan pada CSS mengacu pada style atau gaya teks saja yang ada di halaman awal web (sebagai header) atau memberi style CSS pada elemen HTML yang diingikan. Elemen h1 {...} mengacu pada Internal CSS yaitu menyisipkan CSS pada file HTML. sedangkan lemen #intro h1 {...} memiliki id maka penggunaan pada css dengan pagar (#) dan di dalam file index.html dalam pemanggilannya menggunakan id=" ". Elemen tersebut mengacu pada tampilan selector yang terdiri dari ID dan Class dimana ID selector ditandai dengan tanda pagar (#) di depannya.

3.	Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya! 


Jawab : 

Jadi yang akan muncul di browser itu adalah CSS internal karena Kode CSS internal diletakkan di dalam bagian pada halaman HTML. Class dan ID bisa digunakan untuk merujuk pada kode CSS, namun hanya akan aktif pada halaman tersebut (hanya 1 halaman). CSS internal diletakkan di dalam tag <style></style>.

dan berikut adalah hasil gambarnya : 

![no4](https://user-images.githubusercontent.com/56242226/114254651-d0353400-99da-11eb-8092-83a408bba4f2.PNG)

4.	Keduanya akan ditampilkan, karena Class merubah beberapa objek dengan settingan yang sama sehingga tidak merubah id. Lalu Cara mendefinisikan style untuk id tertentu adalah dengan menjadikannya sebagai selector menggunakan tanda pagar atau hash (#) diikuti dengan nama atau nilai dari atribut id.Cara mendefinisikan style untuk class tertentu adalah dengan menjadikannya sebagai selector menggunakan tanda titik atau dot (.) diikuti dengan nama atau nilai dari atribut class.

Source codenya :

![5A](https://user-images.githubusercontent.com/56242226/114258482-eea62a00-99f0-11eb-8e46-bbc2115f4c34.PNG)


Berikut tampilan di browsernya 

![no 5](https://user-images.githubusercontent.com/56242226/114257906-42af0f80-99ed-11eb-949e-27bc6c70724d.PNG)



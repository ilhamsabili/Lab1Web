# Lab1Web
NAMA : Ilham Sabili

KELAS : TI.22.A.1

Langkah-langkah Praktikum

Persiapan membuka VSCode dan Browser.

![Gambar WhatsApp 2023-09-29 pukul 20 05 35](https://github.com/ilhamsabili/Lab1Web/assets/115677697/4d000325-e3f4-40c9-9331-8cc3a97c712e)

Kemudian buat file baru dengan nama lab1_tag_dasar.html dan tambahkan tag dasar dokumen HTML.

![image](https://github.com/ilhamsabili/Lab1Web/assets/115677697/277920d0-cb6a-44e5-b5d1-db1e80ed01b5)

1. Membuat Paragraf

   ![Gambar WhatsApp 2023-09-29 pukul 20 13 45](https://github.com/ilhamsabili/Lab1Web/assets/115677697/5f9aa691-92d0-4bdf-9420-2afa491c4345)


2. Menambahkan Judul
<!--judul paragraf pertama-->
    <h1>Belajar Dasar HTML</h1>
 <!--judul paragraf kedua-->
        <h2>Paragraf Pada HTML</h2>
![Gambar WhatsApp 2023-09-29 pukul 20 18 31](https://github.com/ilhamsabili/Lab1Web/assets/115677697/a6247739-bc75-4701-b9c4-90cd67028457)



3. Memformat teks
Lakukan pemformatan teks yang ada pada paragraf yang sudah ada sebelumnya, mengacu kepada penjelasan materi pemformatan teks, sehingga tampilannya seperti berikut.

![Gambar WhatsApp 2023-09-29 pukul 20 17 18](https://github.com/ilhamsabili/Lab1Web/assets/115677697/ad941b37-f855-4e9c-b155-60d27bd10f48)


4. Menyisipkan Gambar
Untuk menyisipkan gmbar, siapkan gambar yang akan disisipkan pada halaman web, kemudian simpan file gambar tersebut satu folder dengan file dokumen html. Atau bisa juga menyisipkan gambar dari website external.

  <!-- sub judul paragraf -->
      <h3>Menambahkan Gambar</h3>
  <!-- menambahkan gambar pada dokumen -->
      <img src="Logo_UPB.png" title="Logo Univeritas Pelita Bangsa">
Simpan perubahannya, kemudian refresh browser.

![Gambar WhatsApp 2023-09-29 pukul 20 17 19](https://github.com/ilhamsabili/Lab1Web/assets/115677697/4378d5a8-bc5e-4f2d-88f0-2a0db23e1180)


5. Menambahkan Hyperlink
Tambahkan hyperlink pada dokumen sebelum heading 1 seperti berikut.

    <!-- menambahkan link navigasi -->
    <nav>!
    <a href="lab1_tag_dasar.html">Dasar HTML</a>
    <a href="lab1_halaman2.html">Halaman 2</a>
    <a href="http://www.google.com">Halaman Web Eksternal Google</a>
    </nav>
    <hr>
![Gambar WhatsApp 2023-09-29 pukul 20 17 19](https://github.com/ilhamsabili/Lab1Web/assets/115677697/b9c3350c-57c8-4dee-a5da-8ffda0d1a9d5)


Pertanyaan
1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah error ketika terjadi kesalahan penulisan tag?
~ Ya, kesalahan penulisan tag dalam kode HTML dapat menyebabkan error atau masalah dalam halaman web. Kesalahan tersebut dapat mencakup tag yang tidak ditutup dengan benar, tag yang tidak valid, atau atribut yang salah

2. Apa perbedaan dari tag <p> dengan tag <br>, berikan penjelasannya!
~ Tag HTML <p> dan <br> memiliki perbedaan dalam penggunaan dan efek yang mereka miliki dalam tata letak halaman web:

<p> (Paragraph):
<p> digunakan untuk mengelompokkan teks menjadi paragraf atau blok teks.
Ini akan menambahkan jarak paragraf di atas dan di bawah teks yang ada, menciptakan ruang vertikal yang signifikan.
Contoh penggunaan: <p>Ini adalah paragraf pertama.</p> <p>Ini adalah paragraf kedua      </p>
<br> (Line Break):
<br> digunakan untuk membuat jeda baris tunggal dalam teks, yang berarti teks akan berlanjut di baris berikutnya tanpa membuat paragraf baru.
Ini hanya menciptakan jeda baris dan tidak menambahkan spasi vertikal tambahan.
Contoh penggunaan: Ini adalah baris pertama.<br>Ini adalah baris kedua. Jadi, intinya adalah 
digunakan untuk mengelompokkan teks menjadi paragraf dengan jarak vertikal, sementara
` hanya digunakan untuk membuat jeda baris dalam teks tanpa menambahkan jarak vertikal tambahan.

3. Apa perbedaan atribut title dan alt pada tag , berikan penjelasannya!
~ Atribut title dan alt dalam tag HTML <img> memiliki perbedaan dalam tujuan dan penggunaan mereka:

Atribut alt (Alternative Text):
Atribut alt digunakan untuk memberikan teks alternatif atau deskripsi gambar.
Ini memiliki peran penting dalam aksesibilitas web, karena digunakan oleh pembaca layar untuk membantu pengguna yang memiliki masalah penglihatan memahami konten gambar.
Jika gambar tidak dapat ditampilkan (misalnya, jika berkas gambar tidak dapat dimuat), teks alt akan muncul sebagai teks pengganti.
Contoh penggunaan: <img src="gambar.jpg" alt="Sebuah gambar bukit yang indah">
Atribut title:
Atribut title digunakan untuk memberikan informasi tambahan atau tooltip ketika pengguna mengarahkan kursor mouse ke gambar.

Ini tidak memiliki dampak pada aksesibilitas web, tetapi dapat memberikan informasi tambahan kepada pengguna tentang gambar tersebut.

Contoh penggunaan: <img src="gambar.jpg" alt="Sebuah gambar bukit yang indah" title="Pemandangan  bukit di musim panas">

Jadi, perbedaan utama adalah bahwa alt digunakan untuk memberikan teks alternatif untuk gambar dan penting untuk aksesibilitas, sementara title digunakan untuk memberikan informasi tambahan yang muncul sebagai tooltip saat pengguna mengarahkan kursor mouse ke gambar.

4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!
~ Untuk mengatur ukuran gambar dalam HTML, dapat menggunakan atribut width (lebar) dan height (tinggi). Agar tampilan gambar tetap proporsional, sebaiknya mengisi hanya salah satu dari kedua atribut tersebut, biasanya width atau height, sementara yang lainnya akan dihitung secara otomatis oleh browser. Ini dilakukan karena gambar memiliki rasio aspek (aspect ratio), yang merupakan perbandingan antara lebar dan tingginya. Jika mengisi baik width maupun height, tanpa memperhatikan rasio aspek gambar, gambar tersebut dapat terlihat terdistorsi atau tidak proporsional.

5. Pada link tambahkan atribut target dengan nilai atribut bervariasi ( _blank, _self, _top, _parent ), apa yang terjadi pada masing-masing nilai antribut tersebut?
~ 1. _blank:

Ketika target="_blank" digunakan, tautan akan membuka halaman yang ditautkan dalam tab atau jendela browser baru, terpisah dari halaman asal. Ini berguna ketika Anda ingin menjaga pengguna tetap di halaman asal dan membuka tautan eksternal atau tautan yang tidak ingin menggantikan halaman asal.
_self:
Ini adalah nilai default untuk atribut target. Ketika target="_self" digunakan, tautan akan membuka halaman yang ditautkan di jendela atau tab yang sama di mana halaman asal berada. Ini berarti halaman asal akan digantikan dengan halaman yang baru.
_top:
Ketika target="_top" digunakan, tautan akan membuka halaman yang ditautkan di jendela atau tab paling atas atau paling tinggi dalam tumpukan jendela browser. Jadi, jika halaman asal ada dalam bingkai (frame), tautan akan membuka halaman baru di luar bingkai tersebut.
_parent:
target="_parent" digunakan ketika halaman web memiliki bingkai (frame) yang saling terkait. Ini akan membuka tautan di jendela atau tab yang menggantikan bingkai "induk" yang berisi tautan tersebut.

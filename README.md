

# PRAKTIKUM PEMROGRAMAN WEB 4

## Praktikum

Praktikum membuat box & layout menggunakan html & css. Praktikum dilakukan dengan mengikuti petunjuk pada modul yang sudah disediakan.

## 1. Box Element

### Float

Box element di bawah ini dapat digunakan untuk membuat layout pada sebuah website. 

![enter image description here](https://github.com/antonmartinus72/Lab4Web/raw/main/assets/1_ss.jpg)

Tag html utama yang digunakan adalah `<div>` yang disusun pada satu baris dengan properti`float` pada css. Deklarasi yang digunakan adalah `float:left;` yang berarti box akan disusun ke kiri.

![enter image description here](https://github.com/antonmartinus72/Lab4Web/raw/main/assets/1_code.jpg)

## 2. Clearfix Element

Box dengan  tag `<div>` dengan atribut `class="div4"` di bawah ini menggunakan properti `clear` dengan value `left` pada internal css untuk membersihkan elemen yang sebelumnya menggunakan properti `float`.

![enter image description here](https://github.com/antonmartinus72/Lab4Web/raw/main/assets/2_ss.jpg)

Dapat dilihat bahwa box **div 4** berwarna biru diatas tidak terpengaruh oleh css diatasnya yang menggunakan selector `div`.

![enter image description here](https://github.com/antonmartinus72/Lab4Web/raw/main/assets/2_code.jpg)

### Menggunakan deklarasi css `clear:both;`

![enter image description here](https://github.com/antonmartinus72/Lab4Web/raw/main/assets/2a_ss.jpg)

### Menggunakan deklarasi css`clear:right;`

![enter image description here](https://github.com/antonmartinus72/Lab4Web/raw/main/assets/2b_ss.jpg)

## 3. Layout

Layout dasar dengan hanya menggunakan html.

![enter image description here](https://github.com/antonmartinus72/Lab4Web/raw/main/assets/3_ss.jpg)

Kode html yang digunakan untuk membentuk kerangka layout di atas.

![enter image description here](https://github.com/antonmartinus72/Lab4Web/raw/main/assets/3_code.jpg)

Properti CSS pada dasarnya mempunyai value default. Value default ini memberikan nilai awal contohnya seperti pada properti `margin`. CSS dibawah ini digunakan untuk mereset value css default untuk memudahkan dalam mengatur layout.

![enter image description here](https://github.com/antonmartinus72/Lab4Web/raw/main/assets/3_css.jpg)

## 4.  Navigasi

Navigasi adalah salah satu bentuk layout yang berisi opsi dan link pada website yang digunakan untuk berpindah halaman. 

![enter image description here](https://github.com/antonmartinus72/Lab4Web/raw/main/assets/4_ss.jpg)

Navigasi ini dibentuk berurutan menggunakan deklarasi css `display: block;` pada selector `nav` dan `display: inline-block;`  pada selector `nav a`.

![enter image description here](https://github.com/antonmartinus72/Lab4Web/raw/main/assets/4_css.jpg)

Setiap opsi navigasi juga menggunakan properti pseudo `active` dan `hover` untuk merubah warna background saat dalam keadaan tertentu.

## 5.  Hero Layout

**Tampilan hero layout sebelum menggunakan css.**

![enter image description here](https://github.com/antonmartinus72/Lab4Web/raw/main/assets/5_ss.jpg)

Kode html.

![enter image description here](https://github.com/antonmartinus72/Lab4Web/raw/main/assets/5_code.jpg)

<hr>

**Tampilan hero layout menggunakan css.**

Dibawah ini adalah layout hero yang sudah menggunakan css. Layout hero dibawah ini mengisi seluruh lembar kerja secara vertikal.

![enter image description here](https://github.com/antonmartinus72/Lab4Web/raw/main/assets/6_ss.jpg)

Properti CSS yang digunakan adalah `padding`, `margin`, `background-color` dan properti untuk mengatur teks.

![enter image description here](https://github.com/antonmartinus72/Lab4Web/raw/main/assets/6_css.jpg)


## 6. Layout Main

Layout dibawah ini merupakan bagian utama dari website yang berisi konten utama yang disajikan pada halaman. Layout dibawah ini belum menggunakan css.

![enter image description here](https://github.com/antonmartinus72/Lab4Web/raw/main/assets/7_ss.jpg)

Layout main diletakan di sebelah kiri halaman dengan menggunakan deklarasi `float: left;`. Untuk bagian sebelah kanan halaman akan di isi dengan layout sidebar.

![enter image description here](https://github.com/antonmartinus72/Lab4Web/raw/main/assets/7_css.jpg)

## 7. Sidebar Widget

Sidebar dibawah ini diletakan pada samping halaman dan bersebelahan dengan layout main yang berisi informasi tambahan atau link untuk ke halaman lainnya.

![enter image description here](https://github.com/antonmartinus72/Lab4Web/raw/main/assets/8_ss.jpg)

Kode html tambahan didalam sidebar.

![enter image description here](https://github.com/antonmartinus72/Lab4Web/raw/main/assets/8_code.jpg)

Layout sidebar ini mengikuti layout yang ditulis diatasnya pada kode html yaitu **"main"** yang menggunakan deklarasi css `float: left;`, sehingga layout sidebar akan otomatis  berada pada posisi kanan halaman.

![enter image description here](https://github.com/antonmartinus72/Lab4Web/raw/main/assets/8_css.jpg)

## 8. Footer

Footer pada halaman website diletakan di akhir halaman seperti berikut :

![enter image description here](https://github.com/antonmartinus72/Lab4Web/raw/main/assets/9_ss.jpg)

Deklarasi `clear: both;` di bawah ini digunakan agar footer tidak terpengaruh implementasi properti `float` di atasnya.

![enter image description here](https://github.com/antonmartinus72/Lab4Web/raw/main/assets/9_css.jpg)

## 9. Content

Layout main yang sudah dibuat masih kosong dan perlu di isi. Salah satunya diisi dengan konten yang dikehendaki pemilik website. Konten dibawah ini belum menggunakan css.

![enter image description here](https://github.com/antonmartinus72/Lab4Web/raw/main/assets/10_ss.jpg)

Layout konten di atas menggunakan css seperti dibawah ini. Masing-masing kotak menggunakan deklarasi `float: left;` untuk membuat kotak menjadi satu baris vertikal.  Bentuk kotak juga menggunakan deklarasi `border-radius: 50%;` yang membuat kotak menjadi berbentuk bulat.

![enter image description here](https://github.com/antonmartinus72/Lab4Web/raw/main/assets/11_css.jpg)

Dengan css diatas maka tampilan akan menjadi seperti di bawah ini ;

![enter image description here](https://github.com/antonmartinus72/Lab4Web/raw/main/assets/11_ss.jpg)

## 10.  Article

Artikel dalam website biasanya berisi bacaan deskripsi, narasi dan lain-lain. Artikel dibawah ini belum menggunakan css.

![enter image description here](https://github.com/antonmartinus72/Lab4Web/raw/main/assets/12_ss.jpg)

Kode html yang digunakan pada artikel di atas :

![enter image description here](https://github.com/antonmartinus72/Lab4Web/raw/main/assets/12_code.jpg)

Artikel yang sudah menggunakan css akan terlihat seperti berikut :

![enter image description here](https://github.com/antonmartinus72/Lab4Web/raw/main/assets/13_ss.jpg)

Gambar pada bagian kiri dan kanan layout di atas menggunakan properti `float` untuk menentukan posisi gambar tersebut.
Selebihnya gambar ditambahkan properti `border-radius` untuk membuat sudut tumpul pada gambar serta margin untuk memberikan jarak antara gambar dan text.

![enter image description here](https://github.com/antonmartinus72/Lab4Web/raw/main/assets/13_css.jpg)

## 11. Layout Halaman About

Halaman ini dibuat untuk mengisi halaman about yang terdapat pada navigasi. Pada halaman ini pemilik dapat menambahkan informasi tentang website tersebut maupun tentang pemilik. 

![enter image description here](https://github.com/antonmartinus72/Lab4Web/raw/main/assets/14_ss.jpg)

Tampilan keseluruhan di atas dibuat dengan memodifikasi layout yang sudah ada. Khususnya pada bagian **main** yang di isi dengan informasi dan gambar tentang website tersebut.

Properti yang sebagian besar digunakan adalah `margin` dan `padding`. Untuk gambar menggunakan `border-radius` untuk membuat sudut tumpul pada gambar dan menggunakan class `center` yang sudah didefinisikan untuk membuat gambar dan text di bawahnya berada di tengah. 

![enter image description here](https://github.com/antonmartinus72/Lab4Web/raw/main/assets/14_css.jpg)

## 12. Layout Halaman Kontak

Navigasi kontak diisi dengan halaman yang memberikan informasi kepada pengunjung untuk dapat menghubungi pemilik website.

![enter image description here](https://github.com/antonmartinus72/Lab4Web/raw/main/assets/15_ss.jpg)

Untuk pengisian data seperti nama dan email menggunakan tag form pada html dengan atribut `action` sebagai alamat tujuan langsung ke alamat email pemilik website.

![enter image description here](https://github.com/antonmartinus72/Lab4Web/raw/main/assets/15_code.jpg)

CSS yang digunakan pada form di atas tidak terlalu banyak, hanya menggunakan beberapa properti untuk mengubah posisi input ke sebelah kanan dan membuat tombol submit berwarna biru.

![enter image description here](https://github.com/antonmartinus72/Lab4Web/raw/main/assets/15_css.jpg)

## Sekian & Terimakasih.
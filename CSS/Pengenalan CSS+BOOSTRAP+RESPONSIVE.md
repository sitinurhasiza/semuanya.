# Anatomi CSS

## Kode Program

```css
P {
Color: red;
}
```

## Penjelasan
- Tag `<p>` adalah selector yang ingin di modifikasi.
- property adalah `color` pada komponen textnya
- property values adalah `red` kita mau modifikasi seperti apa warnanya

## Kesimpulan
warna teks (text color) dari elemen HTML yang memiliki tag P akan diubah menjadi merah (red).
  

# Percobaan Pertama

## Kode Program

```html

<!DOCTYPE html>

<html>

    <head>

        <title>Belajar CSS 1</title>

        <style>

            p {

                color: red;

            }

        </style>

    </head>

    <body>

        <p>Welcome CSS</p>

    </body>

</html>

```

## Hasil
  ![](asetCSS/1.png)

## Penjelasan

1. <!DOCTYPE html>: Mendefinisikan jenis dokumen HTML yang digunakan, dalam hal ini HTML5.

2. `<html>`: Elemen utama yang memuat seluruh konten dokumen.

3. `<head>`: Bagian yang berisi informasi tambahan tentang dokumen, seperti judul dan link ke stylesheet eksternal.

4. `<title>`: Menentukan judul halaman web yang akan ditampilkan di tab browser.

5. `<style>`: Bagian di mana Anda dapat menambahkan aturan CSS untuk mengubah tampilan elemen HTML di halaman.

6. `p { color: red; }`: Aturan CSS yang mengubah warna teks pada semua elemen `<p>` menjadi merah.

7. `<body>`: Bagian yang berisi konten aktual halaman web, seperti teks, gambar, atau elemen lainnya.

8. `<p>Welcome CSS</p>` : Elemen paragraf dengan teks "Welcome CSS", yang akan ditampilkan dengan warna merah karena aturan CSS yang telah ditentukan sebelumnya.

# Percobaan Kedua
## Border-Radius
### Kode 
```css

button{
        border-radius: 20px;
        width:150px;
        height:50px;
      }
      ```
>[!note] Penjelasan: 
>Border-radius adalah properti CSS yang digunakan untuk mengatur radius sudut dari elemen kotak seperti div, span, atau elemen lainnya. Dengan menggunakan border-radius, Anda dapat membuat sudut-sudut elemen menjadi melengkung dengan menggambar lengkungan di setiap sudutnya. Properti ini memberikan fleksibilitas dalam menciptakan tampilan yang lebih menarik dan estetis pada elemen-elemen kotak. Anda dapat mengatur radius sudut dengan menggunakan nilai piksel, persentase, atau kombinasi dari keduanya.
### Before
![](asetCSS/2.jpeg)
>[!faq]- Tidak memakai `border-radius`:
 -Tanpa menggunakan `border-radius`, elemen kotak akan memiliki sudut-sudut yang tajam dan persegi.
-Tampilan elemen dapat terlihat lebih sederhana dan minimalis.
 -Jika tidak diperlukan penampilan dengan sudut melengkung, penggunaan `border-radius` tidak diperlukan, sehingga memudahkan dalam pengaturan gaya dan tata letak elemen lainnya.

### After
![](asetCSS/3.jpeg)
>[!faq]- Memakai `border-radius`:
 -Menggunakan `border-radius` dapat memberikan elemen kotak tampilan yang lebih menarik dengan sudut-sudut yang melengkung.
-Lengkungan sudut dapat membuat elemen terlihat lebih lembut, ramah, dan estetis.
 -Anda dapat mengatur radius sudut dengan nilai piksel atau persentase, serta mengkombinasikan nilai untuk setiap sudut secara terpisah.



  

## Padding-Left
### Kode
```css

button{
   width:150px;
   height:50px;
   padding-left:20px;
}
```
>[!note] Penjelasan: 
>Padding-left adalah properti CSS yang digunakan untuk mengatur ruang kosong (padding) di sebelah kiri elemen. Nilai padding-left menentukan jarak antara tepi kiri elemen (content box) dengan konten yang ada di dalamnya atau dengan tepi elemen yang berada di sebelah kiri (misalnya, border atau margin elemen tetangga di sebelah kiri). Properti ini memungkinkan pengaturan ruang kosong di sebelah kiri elemen untuk mencapai tata letak yang diinginkan atau memberikan ruang tambahan antara elemen tetangga di sebelah kiri. Nilai padding-left dapat dinyatakan dalam piksel, persentase, atau unit lainnya.
### Before

![](asetCSS/2.jpeg)
>[!faq]- Tidak memakai `padding-left`:

-Tanpa menggunakan `padding-left`, elemen akan tidak memiliki ruang kosong di sebelah kiri.
-Hal ini dapat membuat elemen terlihat lebih rapat dengan elemen tetangga atau konten di dalamnya.
-Jika tidak diperlukan ruang tambahan di sebelah kiri elemen, penggunaan `padding-left` tidak diperlukan, sehingga memudahkan dalam pengaturan tata letak elemen lainnya.
### After

![](asetCSS/4.jpeg)
>[!faq]- Memakai `padding-left`:
 -Dengan menggunakan `padding-left`, Anda dapat memberikan ruang kosong di sebelah kiri elemen.
-Properti ini memungkinkan Anda untuk mengatur jarak antara tepi kiri elemen dengan konten di dalamnya atau dengan elemen tetangga di sebelah kiri.
-Penggunaan `padding-left` berguna untuk mencapai tata letak yang diinginkan atau memberikan ruang tambahan di sebelah kiri elemen.
>[!note] Penjelasan:


## Font-Size

### Kode
```css
button{
   width:150px;
   height:50px;
   font-size:20px;
}
```
>[!note] Penjelasan: 
>Font-size adalah properti CSS yang digunakan untuk mengatur ukuran teks pada elemen. Properti ini menentukan ukuran relatif atau absolut dari teks yang ditampilkan. Nilai font-size dapat dinyatakan dalam berbagai unit, seperti piksel (px), em (em), persen (%), atau unit lainnya. Dengan menggunakan font-size, Anda dapat mengatur teks menjadi lebih kecil atau lebih besar untuk mencapai tampilan yang diinginkan. Ukuran teks yang tepat dapat membantu meningkatkan keterbacaan dan mempengaruhi tata letak keseluruhan elemen di dalam dokumen web.
### Before

![](asetCSS/2.jpeg)
>[!faq]- Tidak memakai `font-size`:
-Tanpa menggunakan `font-size`, ukuran teks akan mengikuti nilai default yang ditetapkan oleh browser.
-Hal ini dapat mengakibatkan ukuran teks yang tidak sesuai dengan kebutuhan atau preferensi yang diinginkan.
-Jika tidak ada kebutuhan khusus untuk mengatur ukuran teks, penggunaan `font-size` tidak diperlukan.
  
### After

![](asetCSS/5.jpeg)
>[!faq]- Memakai `font-size`:
-Dengan menggunakan `font-size`, Anda dapat mengatur ukuran teks pada elemen sesuai dengan kebutuhan.
-Properti ini memungkinkan Anda untuk mengontrol ukuran relatif atau absolut dari teks yang ditampilkan.
-Dengan menentukan nilai font-size yang tepat, Anda dapat mencapai tampilan teks yang sesuai dengan desain atau preferensi Anda.

# Text
## Text Align 

### Penjelasan
- `p` adalah sebuah selektor CSS yang menargetkan elemen HTML `<p>` (paragraf).
- `text-align: center;` adalah sebuah properti CSS yang menentukan penataan teks di dalam elemen yang dipilih. Nilai `center` menyebabkan teks di dalam elemen paragraf tersebut terpusat secara horizontal.

### Kode Program
```css
p{

   text-align: center;

}
```
### Hasil

![](asetCSS/textalign.png)
### Kesimpulan

Kesimpulannya, program CSS tersebut secara khusus menargetkan elemen paragraf `<p>` pada halaman web dan mengatur penataan teks di dalamnya agar terpusat secara horizontal. Dengan demikian, semua teks yang berada di dalam elemen paragraf akan ditampilkan dengan penataan terpusat secara horizontal.
## Text Decoration

### Penjelasan
- `p` adalah selektor CSS yang menargetkan elemen paragraf `<p>`.
- `text-decoration: underline;` adalah properti CSS yang menetapkan dekorasi garis bawah pada teks di dalam elemen yang dipilih. Dengan nilai `underline`, teks di dalam elemen paragraf akan memiliki garis bawah.
### Kode Program
```css
p{

   text-decoration: underline;

}
```
### Hasil

![](asetCSS/textdecoration.png)
### Kesimpulan
Kesimpulannya, program CSS tersebut mengubah tampilan teks pada elemen paragraf `<p>` dengan menambahkan dekorasi garis bawah pada teks di dalamnya. Sehingga, semua teks yang berada di dalam elemen paragraf akan ditampilkan dengan garis bawah.

## Text Transform

### Penjelasan
- `p` adalah selektor CSS yang menargetkan elemen paragraf `<p>`.
- `text-transform: uppercase;` adalah properti CSS yang mengubah teks di dalam elemen yang dipilih menjadi huruf kapital (uppercase).
### Kode Program
```css
p{

   text-transform: uppercase;

}
```
### Hasil

![](asetCSS/texttransform.png)
### Kesimpulan
Dengan menggunakan kode CSS `p { text-transform: uppercase; }`, setiap teks yang terdapat di dalam elemen paragraf `<p>` pada halaman web akan diubah menjadi huruf kapital (uppercase). Ini berarti semua teks tersebut akan ditampilkan dalam format huruf besar tanpa memperhatikan huruf aslinya.


# Cara pemanggilan CSS

## In-line

In-line merupakan salah satu cara untuk memanggil css yaitu dengan cara memanggilnya kedalam baris yang sama dengan tag yang ingin di modifikasi contoh
### Kode Program

```html

<p style="color: red;">Welcome CSS</p>

```

<p style="color: red;">Welcome CSS</p>

  
### Hasil

![](asetCSS/merah.png)
  
### Penjelasan

> [!NOTE] Penjelasan
> *In-line CSS*: Dalam metode ini, CSS ditulis langsung di dalam tag HTML menggunakan atribut style. Ini berguna ketika Anda ingin menerapkan gaya yang spesifik hanya untuk satu elemen.

## Internal

### Kode Program

```HTML

<html>

    <head>

        <title>Belajar CSS 1</title>

        <style>

            p {

                color: red;

            }

        </style>

    </head>

    <body>

        <p>Welcome CSS</p>

    </body>

</html>

```

  

<html>

    <head>

        <title>Belajar CSS 1</title>

        <style>

            p {

                color: red;

            }

        </style>

    </head>

    <body>

        <p>Welcome CSS</p>

    </body>

</html>

### Hasil

  ![](asetCSS/1.png)

### Penjelasan

  

> [!NOTE] Penjelasan

> *Internal CSS*: Dalam metode ini, CSS ditulis di dalam tag `<style>` di dalam elemen `<head>` dokumen HTML. Ini berguna ketika Anda memiliki beberapa halaman yang memerlukan gaya yang sama. Dengan menggunakan internal CSS, Anda dapat menetapkan gaya sekali dan akan berlaku untuk seluruh halaman tersebut.

  

## External

### Kode Program

Kode Program HTML yang dimana ini adalah tempat css di panggil dengan menggunakan metode external

```html

<html>

    <head>

        <title>Belajar CSS2</title>

        <link rel="stylesheet" href="belajar css1.css">

    </head>

    <body>

        <p>Welcome CSS</p>

    </body>

</html>

```

tampilan

<html>

    <head>

        <title>Belajar CSS2</title>

        <link rel="stylesheet" href="belajar css1.css">

    </head>

    <body>

        <p>Welcome CSS</p>

    </body>

</html>

  

```css

Kode Program CSS

p{

    font-family: 'Courier New', Courier, monospace;

    }
```
### Hasil

![](asetCSS/merah1.png)
### Penjelasan

> [!NOTE] Penjelasan
> *External CSS*: Dalam metode ini, CSS ditulis dalam file terpisah dengan ekstensi .css, dan kemudian dihubungkan dengan dokumen HTML menggunakan tag <link>. Hal ini memisahkan struktur konten (HTML) dari presentasi (CSS), membuatnya lebih mudah untuk memelihara dan memperbarui gaya di seluruh situs web Anda

  

# ID SELECTOR

## Penjelasan

- `<!DOCTYPE html>` : Mendefinisikan tipe dokumen sebagai HTML versi 5.

- `<html`: Menandakan awala dan akhir dari dokumen HTML.

- `<head>`: Berisi informasi tambahan tentang dokumen HTML.

- `<title>CSS</title>`: Menentukan judul dokumen yang akan di tampilkan di web browser.

- `<link rel="stylesheet" href="style.css>`: Menautkan dokumen HTML dengan file CSS eksternal bernama `style.css`, sehingga dokumen HTML dapat menerapkan gaya ynag di definisikan dalam file CSS tersebut.

- `<body>`: Berisi konten yang akan di tampilkan di website.

- Elemen `<p id="hijau"> ini warna hijau</p>` memiliki atribut `id` yang menentukan identitas uniknya dalam dokumen HTML. Dengan demikian, fungsi dari atribut `id` ini adalah untuk memberikan cara yang unik untuk merujuk atau menargetkan elemen tersebut dalam CSS, dan memberikan warna hijau pada teks sesuai perintah pada CSS.

  

## Kode Progam

```HTML

<!DOCTYPE html>

<html>

<head>

    <title>Document</title>

    <link rel="stylesheet" href="style.css">

</head>

<body>

    <p style="font-size: 48px;">Welcome CSS</p>

    <h1>Hallo RPL</h1>

    <p id="hijau"> Ini Warna Hijau</p>

</body>

</html>

```

```css

#hijau {

    color:green;

}

```

  

## Hasil

![](asetCSS/hijau1.png)
## Kesimpulan

Jadi nama ID selector harus unik di dalam dokumen HTML. Artinya, hanya boleh ada satu elemen dengan ID tertentu dalam satu halaman web. Jika ada beberapa elemen dengan ID yang sama, hal itu tidak valid dan dapat menyebabkan masalah dalam tata letak serta perilaku halaman web. Sebagai rekomendasi, sebaiknya gunakan ID selector dengan bijak dan pastikan setiap ID unik di halaman web yang di buat..

  

# TEXT

## Text-decoration

### Overline


#### Penjelasan

text-decoration overline merupakan properti CSS yang digunakan untuk memberi garis di atas  teks.

#### Kode program

```css

<head>

    <title>Text</title>

    <style>

        .over {

    text-decoration: overline;

    }

    </style>

</head>

<body>

    <p class="over">HASIZA</p>

</body>

```

#### Hasil

![](asetCSS/t.png)
#### Kesimpulan

overline merupakan salah satu jenis garis pada teks dekorasi yang berguna untuk memberi garis atas pada teks.

### Underline

  

#### Penjelasan

Text-decoration underline merupakan properti CSS yang memberi garis bawah pada teks.

#### Kode program

```css

<head>

    <title>Text</title>

    <style>

        .under {

    text-decoration: underline;

    }

    </style>

</head>

<body>

    <p class="under">Hasiza</p>

</body>

```

#### Hasil

![](asetCSS/textdecoration.png)

#### Kesimpulan

underline merupakan salah satu jenis garis yang memberikan garis bawah pada teks.

### Line-through

  

#### Penjelasan

text-decoration line-through merupakan dekorasi garis di tengah atau teks tercoret.

#### Kode program

```css

<head>

    <title>Text</title>

    <style>

        .through {

    text-decoration: line-through;

    }

    </style>

</head>

<body>

    <p class="through">HASIZA</p>

</body>

```

#### Hasil

![](asetCSS/s.png)

#### Kesimpulan

line-through adalah salah satu jenis garis di CSS yang memberi kesan tercoret pada teks atau garis tengah pada teks.

# BACKGROUND

## Background-color

### Penjelasan

background-color merupakan properti css yang mengatur warna latar belakang halaman.

### Kode program

```css

<head>

<style>

body {

    background-color: lightblue;

}

</style>

</head>

<body>

<p>Hello World!</p>

</body>

```

### Hasil

![](asetCSS/r.png)

  

### Kesimpulan

merupakan properti CSS yang memberikan warna pada latar belakang web.

## Background-image

### Penjelasan

Background-image dalam CSS adalah properti yang digunakan untuk menentukan gambar yang akan digunakan sebagai latar belakang dari suatu elemen.

### Kode program

```css

<head>

<style>

body {

    background-image: url("acica.jpeg");

}

</style>

</head>

<body>

<p>Hello World!</p>

</body>

```

  

### Hasil

![](asetCSS/q.png)

  

### Kesimpulan

merupakan properti CSS yang dapat mengatur gambar pada latar belakang web.

## Background-repeat

### Penjelasan

Background-repeat adalah properti yang digunakan untuk mengatur gambar latar belakang yang digunakan apakah ingin di ulang atau tidak.

### Kode program

```css

<head>

<style>

body {

    background-image: url("acica.jpeg");

    background-repeat: no-repeat;

}

</style>

</head>

<body>

<p>Hello World!</p>

</body>

```

### Hasil

![](asetCSS/p.png)

  
  

### Kesimpulan

Background-repeat adalah properti yang digunakan untuk mengulang gambar latar belakang atau tidak.


## Background-attachament
### Penjelasan

Properti `background-attachment` digunakan untuk mengontrol apakah gambar latar belakang akan tetap diam (`fixed`) atau akan bergulir bersamaan dengan konten (`scroll`) saat pengguna menggulir halaman. Dalam contoh ini, gambar latar belakang tetap diam bahkan saat halaman digulir.

### Kode program

```css
<!DOCTYPE html>

  

<html>

    <head>

  

        <style>

        body {

     background-image: url("acica.jpeg");

     background-repeat: no-repeat;

     background-attachment: local;

        }

        </style>

        </head>

        <body>

        <p>Hello World!</p>

        </body>
```

### Hasil

![](asetCSS/o.png)


### Kesimpulan
background tersebut digunakan untuk menambahkan gambar tetapi halaman tersebut tdk dapat digulir ke halaman berikutnya

# FONT

## Font-Size
### Penjelasan
font-size merupakan properti css yang digunakan untuk mengatur ukuran font.
### Kode program

[](https://github.com/nayah14/MateriCSS/blob/main/CSS/Pengenalan%20CSS.md#kode-program-8)

```css
<head>
    <title>font</title>
    <style>
        .size {
    font-size: 100px;
    }  
    </style>
</head>
<body>    
    <p class="size">HASIZA</p>
</body>
```

### Hasil

![](asetCSS/a.png)
### Kesimpulan
font-size merupakan properti yang digunakan untuk mengatur seberapa besar atau kecil ukuran font yang di inginkan.

## font-weight
Penjelasan font-weight adalah properti CSS yang dapat mengubah ketebalan sebuah teks.
### Kode program

```css
<head>
    <title>font</title>
    <style>
        .weight {
    font-weight:bolder;
    }
    </style>
</head>
<body>    
    <p class="weight">HASIZA</p>
</body>
```

### Hasil

![](asetCSS/n.png)

### Kesimpulan
font-weight adalah properti yang digunakan untuk mengatur ketebalan teks sesuai keinginan.
## font-style

### Penjelasan
font-style merupakan properti CSS yang mengatur gaya dari teks, seperti kemiringan.
### Kode program

```css
<head>
    <title>font</title>
    <style>
        .style {
    font-style:italic;
    }
    </style>
</head>
<body>    
    <p class="style">HASIZA</p>
</body>
```

### Hasil

![](asetCSS/m.png)
### Kesimpulan
font-style digunakan untuk mengatur gaya dari sebuah teks
## font-family

### Penjelasan
font-family adalah property CSS yang dapat mengubah jenis font suatu text.
### Kode Program

```css
.family {
font-family: 'Courier New' , Courier, monospace
}
```

### Hasil

![](asetCSS/l.png)
### Kesimpulan
Font-family adalah property CSSS yg digunakan untuk mengatur jenis text.Font-family juga dapat menampung beberapa nama font sesuai selera,jika font pertama tidak terbaca maka font selanjutnya akan dijalankan,Nama font harus dipisah dengan tanda koma

# Box-Model
## border
### penjelasan
Border (batas) dalam CSS adalah garis yang mengelilingi suatu elemen HTML. Border dapat digunakan untuk memberikan tampilan visual yang jelas dan terpisah antara elemen-elemen di dalam halaman web. Ada tiga properti utama yang dapat digunakan untuk mengatur border suatu elemen:

1. `border-width`: Mengatur lebar border.
2. `border-style`: Mengatur jenis atau gaya border, seperti solid, dashed, dotted, double, dsb.
3. `border-color`: Mengatur warna border.
4. `boder-radius`: membuat sudut elemen HTML menjadi melengkung daripada tajam.

### kode program
```css
Button {
border-color: red;
}
```

### Hasil

![](asetCSS/k.png)

### kesimpulan
kesimpulan kode tersebut `div { border-color: red; }` adalah bahwa semua elemen `<div>` pada halaman web akan memiliki border dengan warna merah. Dengan kode tersebut, setiap elemen `<div>` akan memiliki border dengan lebar default (biasanya 1 piksel), gaya default (biasanya solid), namun warna bordernya akan diatur menjadi merah. Ini berarti elemen `<div>` akan memiliki garis pinggiran berwarna merah mengelilingi seluruh elemennya.

## Margin
### penjelasan
Margin dalam CSS adalah ruang kosong di sekeliling elemen HTML yang digunakan untuk mengatur jarak antara elemen dengan elemen lainnya atau dengan batas-batas luar halaman web. Ada empat properti margin yang dapat digunakan:

1. `margin-top`: Mengatur jarak atas elemen.
2. `margin-right`: Mengatur jarak kanan elemen.
3. `margin-bottom`: Mengatur jarak bawah elemen.
4. `margin-left`: Mengatur jarak kiri elemen.

### kode program
```css
img{
    
    margin-left: 600px;
    }
```

### Hasil

![](asetCSS/c.png)
### kesimpulan
Kesimpulan dari kode CSS `div { margin-left: 600px; }` adalah bahwa semua elemen `<img>` pada halaman web akan memiliki margin sebesar 600 piksel di sisi kanan. Dengan kode tersebut, setiap elemen `<img>` akan memiliki ruang kosong (margin) sebesar 600 piksel di sisi kiri, yang berarti elemen-elemen tersebut akan terpisah dengan elemen lain di sebelah kanannya sejauh 600 piksel. Ini akan memengaruhi tata letak (layout) dari elemen-elemen `<img>` tersebut dalam halaman web.

## Padding
### penjelasan

`padding` digunakan dalam CSS untuk menentukan ruang kosong di sekeliling konten suatu elemen HTML. Properti `padding` dapat diatur secara terpisah untuk setiap sisi elemen, yaitu atas (top), kanan (right), bawah (bottom), dan kiri (left). Properti `padding` digunakan dalam CSS untuk menentukan ruang kosong di sekeliling konten suatu elemen HTML. Properti `padding` dapat diatur secara terpisah untuk setiap sisi elemen, yaitu atas (top), kanan (right), bawah (bottom), dan kiri (left). Ini berarti elemen yang diatur akan memiliki padding sebagai berikut:

- `padding-left: 10px;` : Padding sebesar 10 piksel di sisi kiri elemen.
- `padding-bottom: 10px;` : Padding sebesar 10 piksel di sisi bawah elemen.
- `padding-right: 10px;` : Padding sebesar 10 piksel di sisi kanan elemen.
- `padding-top: 10px;` : Padding sebesar 10 piksel di sisi atas elemen.

### kode program

```css
Img {

    padding-left: 200px;

    }
```

### Hasil

![](asetCSS/b.png)
### kesimpulan
Kesimpulan dari kode CSS `div { padding-left: 100px; }` adalah bahwa semua elemen `<img>` pada halaman web akan memiliki padding sebesar 100 piksel di sisi kiri. Dengan kode tersebut, setiap elemen `<img>` akan memiliki ruang kosong 100 piksel di sisi kiri, yang berarti konten di dalam elemen tersebut akan tergeser ke kiri sejauh 10p piksel dari batas kiri elemen. Jadi, setiap elemen `<img>` akan memiliki padding sebesar 100 piksel di sisi kiri elemen.

# Tantangann Box model

## Kode Program

```html
<!DOCTYPE html>

<html lang="en">

    <head>

        <title>CSS</title>

        <link rel="stylesheet" href="web.css">

    </head>

    <body bgcolor="purple">

        <span> <img src="acica.jpeg" width="270px" height=270px" align="right">

        <p>Selamat Datang<br>

        <b>di web Alwi Assegaf</p></b>

        </span>

        <button>Klik!</button>

    </body>

    </html>
```

```css
p{

   font-size:50px ;

   font-style:italic ;

   margin-top: 100px;

   margin-left: 50px;

   color: white;

}

img{

    margin-right: 130px;

    margin-top:-1px;

    border: 5px solid white;

    border-radius: 1500% 1500%;

}

button{

    background-color: purple;

    width:150px;

    height:60px;

    border-width: 2px;

    border-style:solid 50px;

    border-color: orangered;

    color: orangered;

    margin-bottom:20px ;

    margin-left: 300px;

}
```

## Hasil

![](asetCSS/d.png)

## Kesimpulan
Paragraf :

- `Teks besar dan miring` : Ukuran font 75px dan gaya font `italic` membuat teks paragraf menonjol dan terlihat formal.
- `Font klasik` : Penggunaan font `'times new roman'` memberikan kesan klasik dan elegan.
- `Margin besar` : Margin atas 150px, bawah 100px, kiri 50px, dan kanan 100px memberikan jarak yang besar antara paragraf dan elemen lainnya.
- `Warna biru pastel` : Warna `aliceblue` memberikan kesan lembut dan dingin pada teks.

image :

- `Margin kanan besar`: Margin kanan 200px memberikan spasi yang lebar antara gambar dan elemen lain di sebelah kanan.
- `Margin atas negatif`: Margin atas -50px kemungkinan digunakan untuk menaikkan posisi gambar agar sejajar dengan bagian atas paragraf.
- `Garis tepi tebal`: Border 10px membuat garis tepi gambar tebal dan terlihat jelas.
- `Sudut membulat ekstrem`: Border radius 1500px membuat sudut gambar membulat hampir menjadi lingkaran penuh.

button :

- `Warna ungu`: Background color `purple` memberikan kesan profesional dan modern pada tombol.
- `Ukuran sedang`: Lebar 100px dan tinggi 50px membuat tombol berukuran sedang dan mudah diklik.
- `Garis tepi oranye`: Border width 2px dan color `orangered` membuat garis tepi tombol berwarna oranye dan terlihat jelas.


# Transition
## Transition-property
### Penjelasan
adalah atribut yang digunakan untuk transisi yang apabila kursor didekatkan maka transisi akan berfungsi.
### Kode Program
```css
<html>

<head>

<style>

div {

  width: 100px;

  height: 100px;

  background: red;

  transition-property: width;

  transition-duration: 2s;

}

  

div:hover {

  width: 300px;

}

</style>

</head>

<body>

<div></div>

</body>

</html>
```

### Hasil

![](asetCSS/j.png)

## Transition-duration
### Penjelasan
Properti ini `transition-duration`menentukan berapa detik (s) atau milidetik (ms) yang diperlukan untuk menyelesaikan efek transisi.
### Kode Program
```css
<html>

<head>

<style>

div {

  width: 100px;

  height: 100px;

  background: red;

  transition-property: width;

  transition-duration: 5s;

}

  

div:hover {

  width: 300px;

}

</style>

</head>

<body>

<div></div>

</body>

</html>
```

### Hasil

![](asetCSS/j.png)

## Transition-timing function
### Penjelasan
Properti `transition-timing-function`menentukan kurva kecepatan efek transisi. Properti ini memungkinkan efek transisi untuk mengubah kecepatan sepanjang durasinya
### Kode program
```css
<!DOCTYPE html>

<html>

<head>

<style>

div {

  width: 100px;

  height: 100px;

  background: blueviolet;

  transition: width 2s;

  transition-timing-function: linear;

}

  

div:hover {

  width: 300px;

}

</style>

</head>

<body>

<div></div>

</body>

</html>
```

### Hasil

![[i.png]]
# Tantangan Transition

## Penjelasan
1. `body`:
    - `background-color: rgb(248, 210, 163);`: Menetapkan warna latar belakang body menjadi warna oranye (dinyatakan dalam format RGB).
    - `width: 100%;`: Membuat body mengisi lebar penuh layar.
2. `.container`:
    - `display: contents;`: Membuat kontainer tersebut memiliki perilaku seperti tidak ada kontainer. Artinya, anak-anak langsung dari kontainer akan ditata sesuai dengan tata letak induknya.
    - `align-items: flex-end;`: Menetapkan item dalam kontainer untuk diatur di bagian bawah kontainer.
    - `flex-direction: row;`: Menjadikan anak-anak kontainer diatur dalam satu baris horizontal.
    - `justify-content: space-around;`: Membuat ruang sekitar item dalam kontainer secara merata.
3. `.box-2`:
    - `font-size: 75px;`: Menetapkan ukuran font sebesar 75 piksel.
    - `font-family: 'arial';`: Menggunakan jenis font Arial.
    - `margin-top: 150px; margin-bottom: 100px; margin-left: 50px; margin-right: 100px;`: Menetapkan jarak antara box dan elemen lain di sekitarnya.
    - `color: rgb(104, 104, 104);`: Menetapkan warna teks menjadi abu-abu tua.
4. `.box-1`:
    - `margin-right: 200px; margin-top: -30px;`: Menetapkan jarak dari sisi kanan dan atas box-1.
    - `border: 10px solid white; border-radius: 1500px 1500px;`: Menambahkan border putih dengan ketebalan 10 piksel dan radius sudut sebesar 1500 piksel.
5. `button`:
    - `background-color: lightblue; width: 150px; height: 50px;`: Menetapkan warna latar belakang, lebar, dan tinggi tombol.
    - `border-width: 2px; color: rgb(138, 138, 229); border-color: rgba(73, 134, 240, 0.29);`: Menetapkan ketebalan border, warna teks, dan warna border (dalam format RGBA) tombol.
    - `margin-bottom: 20px; margin-left: 400px;`: Menetapkan jarak bawah dan kiri tombol.
6. `button:hover`:
    - `background-color: lightcyan; font-weight: bolder; transition: all 0.3s ease-in;`: Menetapkan efek saat tombol dihover, seperti perubahan warna latar belakang dan penambahan ketebalan font. Ini menggunakan transisi selama 0.3 detik untuk menciptakan perubahan yang mulus.

## Kode Program

```html
<!DOCTYPE html>

<html>

<head>

    <title>tantangan transition</title>

    <link rel="stylesheet" href="acica.css">

</head>

<body>

    <div class="container">

        <div>

            <img class="box-1" src="unduhan.jpg" width="350px" height="350px" align="right">

            <p class="box-2"> Selamat Datang <br><b>

            di web Hasiza !</b>

            <p>

        </div>

        <button> klik saya </button>

    </div>

</body>

</html>
```

```css
body {

    background-color: rgb(248, 210, 163);

    width: 100%;

  }

  .container {

    display: contents;

    align-items: flex-end;

    flex-direction: row;

    justify-content: space-around;

  }

  .box-2 {

    font-size: 75px;

    font-family: 'arial';

    margin-top: 150px;

    margin-bottom: 100px;

    margin-left: 50px;

    margin-right: 100px;  

    color: rgb(104, 104, 104);

  }

  .box-1 {

    margin-right: 200px;

    margin-top: -30px;  

    border: 10px solid white;

    border-radius: 1500px 1500px;

  }

  button {

    background-color: lightblue;

    width: 150px;

    height: 50px;

    border-width: 2px;

    color: rgb(138, 138, 229);

    border-color: rgba(73, 134, 240, 0.29);

    margin-bottom: 20px;

    margin-left: 400px;

  }

  button:hover {

    background-color: lightcyan;

    font-weight: bolder;

    transition: all 0.3s ease-in;

  }
```

## Hasil

![](asetCSS/e.png)
## Kesimpulan

Latar belakang body akan memiliki warna `RGB (248, 210, 163)` yang merupakan kombinasi dari merah, hijau, dan biru. Lebar body akan setara dengan 100% lebar viewport (area tampilan browser). Elemen dengan kelas `"container"` akan memiliki tata letak kontennya yang diatur secara fleksibel, dengan elemen-elemen yang diatur dalam baris. Konten dalam elemen dengan kelas `"container"` akan diatur agar berada di bagian bawah `(align-items: flex-end)` dan memiliki ruang kosong merata di sekitarnya `(justify-content: space-around).` Elemen dengan kelas "box-2" akan memiliki ukuran `font 75 piksel`, menggunakan jenis `font Arial`, dan memiliki `margin atas, bawah, kiri, dan kanan` yang masing-masing telah ditentukan. Elemen dengan kelas "box-1" akan memiliki `margin kanan 200 piksel`, `margin atas -30 piksel` (mendorong elemen ke atas), border dengan `ketebalan 10 piksel`, dan radius lengkungan `border sebesar 1500 piksel` pada sudut-sudutnya. Tombol akan memiliki latar belakang warna `lightblue`, `lebar 150 piksel`, `tinggi 50 piksel`, `ketebalan border 2 piksel`, `warna teks RGB (138, 138, 229)`, `warna border RGBA (73, 134, 240, 0.29)`, dan `margin bawah dan kiri` yang telah ditentukan. Saat tombol dihover, latar belakangnya akan berubah menjadi lightcyan, teksnya akan menjadi lebih tebal, dan akan ada efek transisi selama `0.3 detik` dengan fungsi `timing ease-in`.

# Transform

### Penjelasan
`Transform` adalah untuk mengubah tampilan elemen HTML, seperti menggeser, memutar, atau mengubah ukurannya ketika di klik. Ini adalah cara untuk membuat animasi sederhana atau mengatur posisi elemen dengan lebih fleksibel, atau lebih singkatnya mengubah gaya pada suatu elemen HTML ketika diklik.

### Kode Program
```css
<html>
    <head>
        <title>Home</title>
        <link rel="stylesheet" href="acica.css">
    </head>
    </head>
    <body>
          <p>Klik untuk merubah dirimu menjadi lebih baik</p>
          <button class="tombol">KLIK!!!</button>
       </div>
    </body>
</html>

```

```css
.tombol {

    background-color: blue;

    color: white;

    border: none;

    width: 180px;

    height: 40px;

    font-size: 15px;

    border: 30px;

}

.tombol:hover {

    background-color: yellow;

    color: black;

    border: none;

    width: 160px;

    height: 40px;

    font-size: 20px;

    font-family: 'Segoe UI';

    font-weight: bold;

    border-radius: 30px;

    transition: all 0.3s ease-in;

  

}

.tombol:active {

    transform: scale(0.15);

}
```

### Hasil

![](asetCSS/h.png)


# Flexbox

## FLEX-CONTAINER
### Penjelasan
Flex container adalah elemen induk yang mengatur tata letak flex item-nya. flexbox yaitu memberikan container kemampuan untuk mengatur panjang, lebar, dan posisi item-item yang berada di dalamnya agar memaksimalkan ruang yang ada. Pengaturan ini sangat penting bagi seorang frontend developer untuk membuat sebuah website yang nyaman dilihat di berbagai device dengan berbagai macam resolus.

1. flex-direction :Menentukkan arah (direction) yang akan diberlakukan untuk item-item yang ada pada container flexbox.
2. flex-wrap :Digunakan untuk mendefinisikan bahwa elemen item di dalam container flexbox tidak harus disejajarkan dalam satu baris.
3. justify-content :Digunakan untuk mensejajarkan item-item diantara flexbox agar container dari flexbox tersebut bisa mendistribusikan ruang kosong yang tersisa ketika item flex dalam satu baris tersebut tidak flexsibel atau meskipun flexsibel tapi sudah mencapai batas ukuran maksimum.
4. align-items :Mendefinisikan bagaimana item-item pada container flex tersebut diletakkan sepanjang garis tegak lurus pada sumbu utama (cross-axis).
5. align-content :Digunakan untuk mensejajarkan garis flex container ketika ada ruang kosong secara garis tegak lurus pada sumbu utama (cross-axis).

### Kode Program
```css
.contrainer {

     display: flex;

     height: 100vh;

     justify-content: space-around ;

     align-items: center  ;

     background-color: blanchedalmond;

    }
```

### Hasil

![](asetCSS/8.png)

## FLEX-ITEM

### Penjelasan

 Dalam konteks Flexbox, elemen-elemen dianggap sebagai flex items (item fleksibel), dan mereka diatur dalam satu dimensi (baris atau kolom) menggunakan properti-properti Flexbox.  1. flex-grow: Properti ini menentukan sejauh mana flex item akan memperluas ruang tersedia dalam flex container.  2. flex-shrink: Properti ini menentukan sejauh mana flex item akan menyusut jika ruang tidak cukup dalam flex container.  3. flex-basis: Properti ini menentukan ukuran awal (basis) flex item sebelum fleks container membagi ruang yang tersedia.  4. flex: Properti singkat flex digunakan untuk menggabungkan flex-grow, flex-shrink, dan flex-basis dalam satu deklarasi.

### Kode Program

```css
.item {
    width: 100px;
    margin-right: 10px;
    margin-bottom: 10px;
    height: 100px;
    background-color: red;
    display: flex;
}
```

### Hasil
![](asetCSS/8.png)
### Kesimpulan

Kesimpulannya, dalam CSS Flexbox, elemen-elemen dianggap sebagai flex items (item fleksibel) dan dapat diatur menggunakan properti-properti Flexbox.

# Tantangan Flexbox

## Penjelasan

1. : Ini adalah deklarasi tipe dokumen HTML yang menunjukkan bahwa dokumen ini adalah dokumen HTML5.
2. `<html lang="en">:` Ini adalah elemen root (akar) dari dokumen HTML. lang="en" menunjukkan bahwa bahasa yang digunakan dalam dokumen adalah bahasa Inggris.
3. `<head>:` Elemen `<head>` digunakan untuk menyediakan informasi tentang dokumen, seperti judul (title) dan referensi ke file eksternal seperti stylesheet (CSS).
4. `<title>:` Elemen `<title>` digunakan untuk menentukan judul dokumen yang akan ditampilkan di bilah judul browser.
5. `<link rel="stylesheet" href="tugasflex.css">:` Elemen `<link>` digunakan untuk menghubungkan dokumen HTML dengan file eksternal CSS. Dalam contoh ini, file CSS yang disebut "tugasflex.css" akan digunakan untuk mengatur tampilan halaman.
6. `<body bgcolor="purple">:` Elemen `<body>` digunakan untuk mengelilingi konten utama halaman web. `bgcolor="purple"` adalah atribut yang digunakan untuk mengatur warna latar belakang body menjadi ungu (purple).
7. `<div class="main-container">:` Elemen `<div>` adalah elemen blok yang digunakan untuk mengelompokkan dan mengatur konten. class="main-container" adalah atribut kelas yang memberikan nama kelas "main-container" pada elemen ini. Kelas ini nantinya dapat digunakan dalam CSS untuk mengatur tampilan elemen ini.
8. `<div class="hero-container">:` Elemen `<div>` dengan kelas "hero-container" digunakan untuk mengelompokkan konten yang terkait dengan bagian hero atau bagian utama halaman.
9. `<div class="item p">:` Elemen `<div>` dengan kelas `"item p"` digunakan untuk mengelompokkan konten dan memberikan atribut kelas "p".
10. `<p>:` Elemen `<p>` digunakan untuk menampilkan paragraf teks. Di dalam elemen ini, terdapat teks "Selamat Datang" dan "di Web Adel" yang ditampilkan dalam beberapa baris yang dipisahkan oleh tag `<br>`. Teks "Web Adel" ditampilkan dengan teks tebal menggunakan tag `<b>`.
11. `<button>:` Elemen `<button>` digunakan untuk membuat tombol. Di sini, tombol ditampilkan dengan teks "klik saya".
12. `<span class="img">:` Elemen `<span>` digunakan untuk mengelompokkan dan memanipulasi bagian teks atau elemen lainnya dalam dokumen. Di sini, elemen span memiliki atribut kelas "img".
13. `<img src="abrar.JPG" width="350px" height="350px" align="right">:` Elemen `<img>` digunakan untuk menampilkan gambar dalam halaman. Atribut src menentukan sumber gambar (dalam hal ini, "abrar.JPG"), sedangkan atribut width dan height mengatur lebar dan tinggi gambar. Atribut align="right" mengatur posisi gambar ke sebelah kanan.

## Kode Program

```css
<!DOCTYPE html>

<html lang="en">

<head>

    <title>Document</title>

    <link rel="stylesheet" href="acica.css">

</head>

<body bgcolor="purple">

    <div class="main-container">

    <div class="hero-container">

        <div class="item p">

           <p> Selamat Datang <br>

            di<b>Web Hasiza</b> </P>

            <button> klik!! </button>

        </div>

        <div>

            <span class="img">

                <img src="cica.jpeg" width="350px" height="350px" align="right">

            </span>

    </div>

    </div>

</div>

</body>

</html>
```

```css
.main-container {

    display:flex;

    height: 100vh;

    justify-content: space-around ;

    align-items: center  ;

    background-color: purple;

}

.hero-container {

    display:flex;

    height: 100vh;

    justify-content: space-between;

    align-items: center  ;

    background-color: purple;

}

.item {

    width: 500px;

    height: 250px;

    background-color: none;

}

  

.p {

    font-size: 65px;

    font-family: 'arial';

    margin-top: 40px;

    margin-bottom: 100px;

    margin-left: 50px;

    margin-right: 100px;  

    color: aliceblue;

}

img {

    margin-right: 100px;

    margin-top: -10px;  

    border: 10px solid white;

    border-radius: 1500px 1500px;

}

button {

    background-color: purple;

    width: 150px;

    height: 50px;

    border-width: 2px;

    color: orange;

    border-color: orange;

    margin-bottom: 20px;

    margin-left: 290px;  

    box-shadow: 20px;

}

button:hover {

    background-color: orange;

    color: white;

    width: 150px;

    transition: all 0.3s esse-in;

    cursor: pointer;

}

button:active {

    transform:scale(0.5);

}
```

## Hasil

![](asetCSS/f.png)

# Position

## Position relative

### Penjelasan

`position: relative` adalah properti CSS yang digunakan untuk menetapkan posisi elemen pada halaman web relatif terhadap posisinya sendiri.

### Kode program

```css
.box { position: relative; top: 10px; left: 10px; width: 100px; height: 100px; background-color: red; }
```

### Hasil


![](asetCSS/10.png)

### Kesimpulan

memungkinkan pengguna untuk mengatur posisi elemen dengan properti top, right, bottom, atau left

## Position absolute

### Penjelasan

`position: absolute` akan dikeluarkan dari normal flow, yang berarti elemen tersebut tidak akan memengaruhi posisi elemen lain di halaman.

### Kode program

```css
.box { position: absolute; top: 10px; left: 10px; width: 100px; height: 100px; background-color: red; }
```

### Hasil

![](asetCSS/9.png)

### Kesimpulan
hanya berpengaruh pada elemen yang diatur, tidak akan berpengaruh pada posisi elemen lain.

## Position fixed
### Penjelasan
`position: fixed` adalah properti CSS yang digunakan untuk menetapkan posisi elemen pada halaman web tetap dalam posisi tertentu di layar

### Kode program
```css
.box {
  position: fixed;
  width: 100px;
  height: 100px;
  background-color: red;
}
```

### Hasil

![](asetCSS/7.png)

### Kesimpulan
Untuk menetapkan posisi suatu elemen

## Position sticky

### Penjelasan

Posisi sticky adalah cara efektif untuk mengubah posisi elemen dengan kecil atau sedikit, seperti menyesuaikan posisi elemen dengan kursor atau mengubah posisi elemen dalam layout.

### Kode program

```css
.box {
  position: sticky;
  top: 10px;
  width: 100px;
  height: 100px;
  background-color: red;
}
```

### Hasil

![](asetCSS/6.png)

### Kesimpulan

`position: sticky` akan bergulir seperti normal hingga mencapai titik tertentu

# Tantangan Position
## Penjelasan

- `position: static;`: Kontainer tersebut memiliki posisi statis.
- `display: flex;`: Anak-anak dari kontainer akan diatur dalam satu baris, berdasarkan sumbu utama yang secara default akan menjadi horizontal.
- `flex-direction: column;`: Anak-anak dari kontainer akan diatur dalam satu kolom.
- `width: 100%;`: Kontainer akan mengisi lebar penuh dari elemen induknya.
- `height: 580px;`: Tinggi kontainer ditetapkan pada 580 piksel.
- `background-color: rgba(122, 122, 247, 0.628);`: Warna latar belakang kontainer diatur sebagai nilai RGBA.
- `width: 250px;`: Lebar box ditetapkan pada 250 piksel.
- `height: 350px;`: Tinggi box ditetapkan pada 350 piksel.
- `background-color: white;`: Warna latar belakang box diatur sebagai putih.
- `align-items: center;`: Anak-anak dari box akan dipusatkan secara horizontal.
- `align-content: center;`: Konten di dalam box akan dipusatkan secara vertikal.
- `border-radius: 10px;`: Sudut box akan dibulatkan sebesar 10 piksel.
- `align-self: center;`: Box akan dipusatkan di dalam kontainer secara horizontal.
- `margin-top: 150px;`: Jarak antara bagian atas kontainer dan bagian atas box ditetapkan pada 150 piksel.
- `margin-bottom: 200px;`: Jarak antara bagian bawah kontainer dan bagian bawah box ditetapkan pada 200 piksel.

## Kode Program

```html
<!DOCTYPE html>

<html>

<head>

    <title>POSITION</title>

    <link rel= "stylesheet" href="acica.css">

</head>

<body>

    <div class="container">

        <div class="box">

            <img class="item box-1" src="saya.jpeg" alt="Gambar">

            <p> <img class="icon" src="jempol.jpeg"></p>

            <p class="item box-2">Saturday, April 27, 2024</p>

            <h1 class="item box-3">The standard chunk of <br>Lorem Ipsum</h1>

            <p class="item box-4">Sed posuere consectetur est at lobortis.<br>Aeneen eu leo quam</p>

            <p class="box-5"><b>Read more </b> <img class="item-1" src="panah.jpeg"></p>

        </div>

    </div>

</body>

</html>
```

```css
.container {

    position: static;

    display: flex;

    flex-direction: column;

    width: 100%;

    height: 580px;

    background-color: rgba(122, 122, 247, 0.628);

}

.box {

    width: 250px;

    height: 350px;

    background-color: white;

    align-items: center;

    align-content: center;

    border-radius: 10px;

    align-self: center;

    margin-top: 150px;

    margin-bottom: 200px;

}

  

.item {

    width: 100%;

    color: black;

}

  

.box-1 {

    height: 225px;

    width: 100%;

    border-radius: 10px 10px 0px 0px;

}

  

.box-2 {

    font-size: 10px;

    margin-left: 10px;

    margin-top: 10px;

    padding-top: 10px;

    font-family: Arial, Helvetica, sans-serif;

}

  

.box-3 {

    font-size: 18px;

    margin-left: 10px;

    margin-top: 10px;

    padding-top: 10px;

    font-family: Arial, Helvetica, sans-serif;

}

  

.box-4 {

    font-size: 11px;

    font-family: Arial, Helvetica, sans-serif;

    margin-left: 10px;

}

  

.box-5 {

    background-color: rgb(193, 193, 193);

    padding-left: 20px;

    padding-bottom: 10px;

    padding-top: 10px;

    margin-bottom: 90px ;

    font-family: Arial, Helvetica, sans-serif;

    border-radius: 0px 0px 10px 10px;

    font-size: small;

}

  

.item-1 {

    width: 10px;

    padding-left: 130px;

}

  

.icon {

   background-color: skyblue;

   position: relative;

   left: 200px;

   bottom: 35px;

   width: 30px;

   height: 30px;

   border-radius: 1500px;

}
```

## Hasil

![](asetCSS/g.png)

## Kesimpulan

- Kontainer tersebut memiliki posisi statis dan akan mengisi lebar penuh dari elemen induknya.
- Tinggi kontainer ditetapkan pada 580 piksel, dengan latar belakang berwarna RGBA (122, 122, 247, 0.628).
- Anak-anak dari kontainer akan diatur dalam satu kolom, sehingga properti `flex-direction: column;` diterapkan.
- Lebar box ditetapkan pada 250 piksel dan tinggi pada 350 piksel, dengan latar belakang berwarna putih.
- Isi dari box akan dipusatkan secara horizontal dan vertikal dengan properti `align-items: center;` dan `align-content: center;`.
- Sudut box dibulatkan sebesar 10 piksel dan box itu sendiri akan dipusatkan di dalam kontainer secara horizontal dengan menggunakan `align-self: center;`.
- Terdapat juga penyesuaian margin, di mana jarak antara bagian atas kontainer dan bagian atas box ditetapkan pada 150 piksel,  dan jarak antara bagian bawah kontainer dan bagian bawah box ditetapkan pada 200 piksel.

# Pengenalan Bootstrap

## Apa Itu Bootstrap?

Bootstrap adalah salah satu dari banyak framework front-end yang ada di web development. Framework-front end menyediakan serangkaian alat dan gaya bawaan untuk mempercepat proses pengembangan web dengan menyediakan komponen-komponen UI siap pakai dan sistem grid yang responsif. Bootstrap khususnya, terkenal dengan kemampuannya dalam menciptakan tata letak yang responsif dan komponen-komponen UI yang seragam.

# Instalasi Bootstrap

## Cara instalasi Bootstrap secara online / CDN.

sekarang kita akan menjelaskan bagaimana cara menginstall bootstrap secara online. Berikut langkah-langkahnya:

  

1. Masuklah ke website resmi Bootstrap dengan mengunjungi situs web resmi di https://getbootstrap.com/.

2. Di laman utama web Bootstrap, cari dan klik menu "Introduction" yang terletak pada sisi sebelah kiri website.

3. Pada bagian "Starter Template" di halaman Introduction, kita akan melihat kode yang dapat kita gunakan untuk menghubungkan website kita yang mau diterapkan Bootstrap.

4. Klik tombol "Copy" untuk menyalin seluruh kode tersebut.

5. Buatlah file baru dengan nama index.html atau nama yang kita inginkan menggunakan teks editor atau editor HTML yang kita biasa pakai.

6. Tempelkan(paste) kode yang telah kita salin dari langkah sebelumnya ke dalam file html yang baru kita buat. dengan menempelkan kode tersebut maka bootstrap kita sudah terhubung namun harus secara online.

7. kita dapat mulai memberikan gaya pada tag-tag atau elemen dalam file HTML tersebut dengan menggunakan kelas-kelas Bootstrap. kita dapat melihatnya pada website resmi Bootstrap untuk mempelajari lebih lanjut tentang kelas-kelas yang tersedia dan cara penggunaannya.

8. Untuk melihat hasilnya, buka file html tadi menggunakan web browser kita.

9. Halaman web yang ditampilkan akan menggunakan Bootstrap untuk gaya dan fungsionalitasnya

  

## Mengunduh dan menginstal Bootstrap secara lokal.

Untuk menginstal Bootstrap secara offline, kita perlu mengunduh file Bootstrap dan menyimpannya di folder proyek kita. Berikut adalah langkah-langkah untuk menginstal Bootstrap secara offline:

1. **Unduh File Bootstrap:** Kunjungi situs web resmi Bootstrap di https://getbootstrap.com/ dan cari tautan unduhan untuk versi Bootstrap yang diinginkan. Klik atau ikuti instruksi untuk mengunduh file ZIP Bootstrap.

2. **Ekstrak File Bootstrap:** Setelah mengunduh file ZIP Bootstrap, temukan file tersebut di komputer kita dan ekstrak isi file ZIP ke folder proyek kita. kita dapat menggunakan aplikasi pengarsipan file atau ekstraksi bawaan (Archiver, 7zip, dll) pada sistem operasi kita untuk mengekstrak file ZIP . Setelah diekstrak, kita akan memiliki folder Bootstrap yang berisi berkas-berkas Bootstrap yang diperlukan.

3. **Hubungkan Berkas Bootstrap pada Halaman HTML:** Buka file HTML proyek kita menggunakan teks editor atau editor HTML yang biasa kita gunakan. Di dalam tag pada halaman HTML , tambahkan tautan ke berkas CSS Bootstrap dan skrip JavaScript Bootstrap. Gunakan tag link di dalam tag head untuk tautan CSS dan tag script di dalam tag body untuk javascript. Berikut contoh tautan yang umum di bootstrap:

```html

<link href="path/to/bootstrap.min.css" rel="stylesheet">

// tautan bootstrap CSS

<script src="path/to/bootstrap.bundle.min.js"></script>

// tautan bootstrap Javascript

```

dengan menuliskan script diatas, maka kita telah menghubungkan antara file html kita dengan bootstrap yang kita unduh tadi.

4. **Gunakan Kelas Bootstrap:** Setelah tautan Bootstrap ditambahkan, Kita dapat menggunakan kelas-kelas Bootstrap dalam elemen HTML proyek Kita untuk menerapkan gaya dan fungsionalitas yang disediakan oleh bootstrap kita. Kita dapat masuk ke web resmi Bootstrap untuk mempelajari lebih lanjut tentang kelaskelas yang tersedia dan cara penggunaannya.

5. **Jalankan File HTML:** Setelah Kita selesai menghbungkan tautan dan menggunakan kelas Bootstrap, Kita dapat menjalankan halaman HTML kita di web browser Kita untuk melihat hasilnya. Buka file HTML menggunakan web browser Kita dan lihat hasilnya

# Komponen-Komponen Bootstrap

Bootstrap menyediakan berbagai komponen yang siap pakai untuk membangun tampilan website yang responsif dan menarik. Berikut adalah beberapa komponen utama yang disediakan oleh Bootstrap:

## Grid System

Grid system Bootstrap adalah sistem layout yang responsif dan fleksibel. kita dapat membagi halaman menjadi baris(rows) dan kolom(columns) yang membentuk grid. Grid terdiri dari 12 kolom, yang dapat kita susun sesuai kebutuhan. Dengan menggunakan kelas CSS yang disediakan oleh Bootstrap, kita dapat dengan mudah menentukan berapa banyak kolom yang akan digunakan oleh setiap elemen di halaman web kita. Grid system ini sangat berguna dalam menciptakan tata letak yang responsif dan dapat menyesuaikan diri dengan berbagai ukuran layar

## Typography

Komponen typography Bootstrap menyediakan gaya dan kelas CSS yang konsisten untuk tipografi di halaman web kita. kita dapat dengan mudah mengatur ukuran teks, gaya huruf, dan pengaturan lainnya menggunakan kelas-kelas yang telah ditentukan. Ini memastikan bahwa teks di halaman web kita memiliki tampilan yang konsisten dan mudah dibaca di berbagai perangkat.

## Button

Komponen tombol Bootstrap memungkinkan kita dengan mudah membuat tombol dengan tampilan yang menarik dan responsif. kita dapat menggunakan kelas-kelas Bootstrap untuk mengatur berbagai gaya tombol, termasuk ukuran (large, small), warna (default, primary, secondary, dll.), dan variasi lainnya. Tombol-tombol ini dapat digunakan untuk tindakan seperti mengirim formulir, memuat ulang halaman, atau memicu tindakan lainnya di aplikasi web kita.

## Forms

Bootstrap menyediakan komponen form yang mudah digunakan untuk membuat form input. Ini termasuk input teks, area teks, kotak centang (checkbox), tombol radio, dropdown, dan lain-lain. Komponen form Bootstrap telah dirancang dengan tampilan yang responsif dan mudah dikustomisasi. kita dapat dengan mudah menambahkan validasi form dan mengatur tampilan form kita dengan menggunakan kelas-kelas Bootstrap yang telah ditentukan.

## Navbar

Komponen navbar Bootstrap memungkinkan kita membuat navigasi yang responsif dan mudah dikustomisasi di halaman web. kita dapat menambahkan logo, menu, tombol, dan komponen lainnya ke navbar dengan mudah. Navbar Bootstrap juga menyediakan fitur seperti menu dropdown, navigasi yang terlipat untuk perangkat mobile, dan tata letak yang fleksibel.

## Cards

Cards adalah komponen yang digunakan untuk menampilkan informasi dalam format yang terstruktur. Komponen kartu Bootstrap memungkinkan kita untuk membuat kolom dengan gambar, teks, tombol, dan komponen lainnya. cards ini dapat digunakan untuk menampilkan artikel, produk, profil pengguna, atau konten lainnya dengan tampilan yang menarik.

## Modal

Komponen modal Bootstrap digunakan untuk menampilkan jendela pop-up yang tumpang tindih dengan konten utama halaman. Modal ini berfungsi untuk menyoroti konten tambahan, pesan, atau form yang membutuhkan fokus pengguna. kita dapat menyesuaikan tampilan modal, mengatur ukuran, menambahkan judul, dan mengatur perilaku saat modal ditampilkan atau ditutup.

## Carousel

Carousel adalah komponen Bootstrap yang digunakan untuk membuat tampilan slide gambar atau konten lainnya. kita dapat menambahkan gambar, teks, tombol navigasi, dan indikator slide untuk membuat tampilan yang menarik dan interaktif. Carousel Bootstrap mendukung navigasi otomatis, kontrol manual, dan animasi transisi yang halus.

## Icons

Bootstrap sendiri menggunakan ikon dari Font Awesome, yang merupakan kumpulan ikon vektor yang sangat populer dan kaya akan fitur. kita dapat dengan mudah menambahkan ikon ke elemen seperti tombol, tautan, dan elemen lainnya menggunakan class-class ikon Bootstrap. Ini berfungsi untuk memperindah halaman web kita.

## Jumbotron

Jumbotron adalah komponen Bootstrap yang digunakan untuk menyoroti konten utama di halaman web. Biasanya ditempatkan di bagian atas halaman dengan judul besar danTerima kasih atas klarifikasinya.Komponen carousel Bootstrap digunakan untuk membuat tampilan slide yang interaktif. kita dapat menambahkan gambar, teks, dan tombol navigasi ke dalam carousel. Carousel Bootstrap mendukung navigasi otomatis, kontrol manual, dan animasi transisi.

  

kita dapat menemukan daftar komponen lengkap dan dokumentasi resmi di situs web Bootstrap (https://getbootstrap.com/docs/).

# Contoh Penerapan Komponen Bootstrap

## Typography

1. Buka situs resmi Bootstrap di [getboostrap.com](getbootstrap.com)

    ![](asetCSS/btc-1.png)

2. Klik "Read the docs". Maka kita akan diarahkan pada halaman web yang berisi berbagai macam Typografi (class Bootstrap).

    ![](asetCSS/btc-2.png)

3. Misalnya kita akan membuat sebuah teks quotes seperti di bawah ini:

    ![](asetCSS/btc-3.png)

4. Ketikan "Typography" di kolom search lalu enter. Maka kita akan masuk ke halaman berikut:

    ![](asetCSS/btc-4.png)

5. Carilah Subbab "Alignment":

    ![](asetCSS/btc-5.png)

6. Salinlah kode yang tertera, lalu tempelkan di tag body pada halaman html yang telah kita hubungkan dengan Bootstrap kita

```html

<figure class="text-center">

<blockquote class="blockquote">

<p>A well-known quote, contained in a blockquote element.</p>

</blockquote>

<figcaption class="blockquote-footer">

Someone famous in

<cite title="Source Title">Source Title </cite>

</figcaption>

</figure>

```

![](asetCSS/btc-6.png)

7. Hasilnya akan terlihat seperti berikut:

   ![](asetCSS/btc-7.png)

8. Kita bisa mengganti kata kata nya dengan cara mengganti teks yang ada di dalam tag p dan untuk teks kecil bagian bawah kita ganti pada bagian dalam tag figcaption

```html

<figure class="text-center">

  <blockquote class="blockquote">

    <p>Sebenarnya otak kita sama aja, yang <br>

    membedakan hanya siapa yang <br>

    mulai belajar duluan dan siapa yang <br>

    belajar terus menerus </p>

  </blockquote>

  <figcaption class="blockquote-footer">

    Dea Afrizal Doroboka<cite title="Source Title">Doroboka</cite>

  </figcaption>

</figure>

```

Hasilnya adalah sebagai berikut:

![](asetCSS/btc-8.png)

*Keterangan :*

1. ==`text-center`== pada ==`<figure>`==: Kelas ini diterapkan pada elemen ==`<figure>`== , yang mengakibatkan kontennya, termasuk elemen ==`<blockquote>`== dan ==`<figcaption>`== , akan diatur menjadi ketengah halaman maupun kontainer.

2. blockquote pada ==`<blockquote>`== : Kelas ini memberikan gaya khusus pada elemen ==`<blockquote>`== . Elemen ini digunakan untuk merinci sebuah kutipan atau teks yang dianggap signifikan. Penggunaan kelas ini dari Bootstrap mungkin memberikan tampilan tertentu, seperti memodifikasi gaya margin atau padding, untuk memberikan estetika yang lebih baik.

3. blockquote-footer pada ==`<figcaption>`== : Kelas ini memberikan gaya khusus pada elemen ==`<figcaption>`== yang berada di dalam ==`<figure>`== . Elemen ini kemungkinan berisi informasi tambahan atau keterangan terkait elemen-elemen lain dalam ==`<figure>`==.

    - **`Dea Afrizal Doroboka`**: Ini adalah teks yang berada di dalam elemen ==`<figcaption>`==, memberikan informasi tambahan atau keterangan terkait dengan kutipan atau elemen-elemen lain dalam ==`<figure>`==.

    -  **`<cite title="Source Title">Doroboka / cite>`**: Ini adalah elemen ==`<cite>`== yang memberikan judul sumber ("Source Title"). Penggunaan kelas `blockquote-footer` dari Bootstrap mungkin menyusun elemen ini dengan tata letak dan gaya tertentu, seperti menetapkannya sebagai teks kaki atau memberikan gaya yang konsisten dengan elemen lain dalam kelompok ==`<figure>`==.

*Keterangan*:

Untuk bagian "Dea Afrizal" adalah nama seseorang yang mengatakan quotes tersebut dan "Doroboka" adalah sumber dimana orang tersebut mengatakn kata-kata itu. Kata- kata yang dituliskan yaitu berada dalam tag ==`p`== .

## Navbar

1. Bukalah Kembali [getbootstrap.com](getbootstrap.com) lalu ketik "navbar" dikolom "search" dan klik enter

   ![](asetCSS/btc-15.png)

2. Carilah jenis navbar yang diinginkan.

   ![](asetCSS/btc-16.png)

3. Jika misalnya kita telah menemukan jenis navbar yang kita inginkan, maka, salinlah kode program yang ada dibawah gambar contoh navbar tersebut

    ![[btc-17.png]]

```html

<nav class="navbar navbar-expand-lg bg-body-tertiary">

    <div class="container-fluid">

        <a class="navbar-brand" href="#">Navbar</a>

        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">

            <span class="navbar-toggler-icon"></span>

        </button>

        <div class="collapse navbar-collapse" id="navbarNavDropdown">

            <ul class="navbar-nav">

                <li class="nav-item">

                    <a class="nav-link active" aria-current="page" href="#">Home</a>

                </li>

                <li class="nav-item">

                    <a class="nav-link" href="#">Features</a>

                </li>

                <li class="nav-item">

                    <a class="nav-link" href="#">Pricing</a>

                </li>

                <li class="nav-item dropdown">

                    <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">

                        Dropdown link

                    </a>

                    <ul class="dropdown-menu">

                        <li><a class="dropdown-item" href="#">Action</a></li>

                        <li><a class="dropdown-item" href="#">Another action</a></li>

                        <li><a class="dropdown-item" href="#">Something else here</a></li>

                    </ul>

                </li>

            </ul>

        </div>

    </div>

</nav>

  

```

4. Tempelkanlah kode program yang terlah kita salin ke dalam tag body di file html kita. Jangan lupa untuk menautkan file html kita dengan bootstrap seperti pada langkah-langkah sebelumnya

   ![](asetCSS/btc-18.png)

5. Jalankanlah file html yang sudah ditempeli kode program bootstrap tadi melalui web browser. Maka lihatlah hasilnya

   ![](asetCSS/btc-19.png)

6. Misalnya kita ingin memberikan warna hijau pada background navbar kita. Pertama ketiklah "background" di kolom search

   ![](asetCSS/btc-20.png)

7. Carilah Warna yang kita inginkan. Misalnya dalam praktek ini adalah warna hijau

   ![](asetCSS/btc-21.png)

    ![](asetCSS/btc-22.png)

    Terdapat banyak jenis warna dalam bootstrap.

8. Karena kita ingin mengkostumisasi warna background kita menjadi hijau maka kita akan memakai bg-succes . ketikkan bg-succes pada class tag pembuka seperti di bawah ini

   ![](asetCSS/btc-23.png)

    *Keterangan*:

    Karena kita akan memberikan warna background pada navbar maka untuk menerapkannya, langsung terapkan class tag yang membungkus semua eleme-elemen yang ada pada tag tersebut.

9. Jika sudah maka hasilnya akan seperti ini:

   ![](asetCSS/btc-24.png)

10. Sekarang kita akan mengubah warna font yang ada pada navbar. Langkah pertama klik "Colors" pada bagian Utilities

![](asetCSS/btc-25.png)

11. Maka kita akan diarahkan pada halaman yang memuat berbagai macam warna font

    ![](asetCSS/btc-26.png)

12. Carilah warna font yang kita inginkan. Misalnya pada kostumisasi navbar ini. Kita akan menggunakan warna font putih

   ![](asetCSS/btc-27.png)

13. Karena kita ingin menggunakan warna font putih maka perintah yang digunakan adalah "text-white"

14. Masuklah kembali ke dalam file html kita

15. pada bagian class sebuah tag yang membungkus text yang akan kita ganti warna, ketiklah text-white . Contohny ada pada gambar berikut:

   ![](asetCSS/btc-28.png)

16. Hasilnya akan terlihat seperti di gambar ini:

   ![](asetCSS/btc-29.png)

17. Terapkanlah Text-White diseluruh class pada tag yang membungkus text-text itu seperti halnya pada text navbar tadi

   ![](asetCSS/btc-30.png)

18. Jika file html dijalankan, hasilnya adalah sebagai berikut

    ![](asetCSS/btc-31.png)

19. Sekarang kita akan mengganti text yang ada di navbar tersebut. Caranya sangat mudah, yaitu cukup kita ganti text-text tadi dengan kata kata yang kita inginkan. Misalnya adalah sebagai berikut:

   ![](asetCSS/btc-32.png)

20. Maka hasilnya adalah sebagai berikut:

   ![](asetCSS/btc-33.png)

21. Sekarang kita akan menambahkan kolom search pada navbar kita. pada bagian navbar di [getbootstrap.com](getbootstrap.com) Scroll ke bawah hingga menemukan seperti pada gambar

	 ![](asetCSS/btc-34.png)

22. Salin kodenya lalu tempelkan di bagian bawah kode navbar kita tadi. Jadi jangan disatukan ke dalam kode navbar tadi.

```html

<nav class="navbar bg-body-tertiary">

    <div class="container-fluid">

        <form class="d-flex" role="search">

            <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">

            <button class="btn btn-outline-success" type="submit">Search</button>

        </form>

    </div>

</nav>

```

![](asetCSS/btc-35.png)

  

*Keterangan*:

1. ==`navbar`== : Kelas ini menunjukkan bahwa elemen ==`<nav>`== adalah bagian dari komponen navbar. Navbar adalah bagian dari Bootstrap yang menyediakan navigasi di bagian atas halaman web. Dengan memberikan kelas navbar , kita memberitahu Bootstrap untuk menerapkan gaya dan tata letak khusus yang terkait dengan navigasi.

2. ==`bg-body-tertiary`== : Kelas ini memberikan warna latar belakang pada navbar. Dalam hal ini, warna latar belakangnya diberi warna sesuai dengan warna "hijau" Warna latar belakang ini dapat disesuaikan sesuai kebutuhan desain.

3. ==`container-fluid`== : Kelas ini diterapkan pada elemen ==`<div>`== yang membungkus elemen-elemen dalam navbar. Kelas ini memberikan padding yang sesuai dan membuat elemen-elemen di dalamnya menjaga lebar penuh dari layar (menggunakan grid system Bootstrap). Dengan kata lain, kontennya akan merespons secara baik pada berbagai lebar perangkat.

4. ==`d-flex`== : Kelas ini mengubah elemen ==`<form>`== menjadi kontainer flex. Flexbox adalah teknik tata letak yang kuat di CSS yang memudahkan pengaturan dan penataan elemen dalam satu atau dua dimensi. Dengan memberikan kelas d-flex , elemen form dan anak-anaknya dapat disusun secara fleksibel.

5. ==`form-control`== : Kelas ini diterapkan pada elemen ==`<input>`== untuk memberikan gaya yang konsisten pada elemen formulir. Di sini, elemen input diberi gaya Bootstrap standar untuk mengubahnya menjadi kontrol formulir yang responsif dan berada dalam baris yang sesuai.

6. ==`me-2`== : Ini adalah kelas Bootstrap yang memberikan margin kanan sebesar 2 pada elemen yang memilikinya. Dalam codingan ini, kelas ini diterapkan pada elemen input untuk memberikan jarak margin kanan.

7. ==`btn`== dan ==`btn-outline-success`== : Kelas ini memberikan gaya pada elemen ==`<button>`== . Kelas btn mengindikasikan bahwa ini adalah elemen tombol Bootstrap, sedangkan btn-outline-success memberikan gaya tombol dengan warna tepi hijau ("success" dalam Bootstrap).

8. ==`type="submit"`== pada tombol: Ini menentukan bahwa tombol tersebut bertindak sebagai tombol submit dalam formulir. Ketika ditekan, formulir akan dikirim.

9. Maka hasilnya adalah seperti berikut:

    ![](asetCSS/btc-36.png)

10. Untuk membuat agar navbar tersebut terlihat menyatu, berikan background-color yang sama pada navbar diatasnya, yaitu menggunakan kode bg-succes . Letakkan di class tag yang membungkus seluruh elemen search tadi.

    ![](asetCSS/btc-37.png)

11. Maka hasil yang muncul akan seperti ini

    ![](asetCSS/btc-38.png)

## Buttons

Pada praktek sebelumnya kita sudah mengatur navbar dan juga menambahkan kolom search. Namun ada masalah dengan tombolnya. Karena tombolnya memiliki warna yang sama dengan warna background yang digunakan yaitu hijau, Maka tombol tersebut tidak terlihat akibat warnanya menyatu. Pada bagian kali kita akan membahas cara mengatur sebuah tombol di bootstrap. Berikut caranya:

  

1. Permasalahan tadi ialah background color tombolnya yang menyatu dengan warna backgriund navbarnya. Untuk mengatur warna tombol, pertama di situs getbootstrap.com, carilah bagian "buttons" di Components

    ![](asetCSS/btc-39.png)

2. Jika sudah menemukan klik bagian tersebut, maka kita akan diarahkan pada bagian buttons seperti pada gambar

   ![](asetCSS/btc-40.png)

3. Scroll lah ke bawah hingga menemukan bagian "Outlines Buttons"

   ![](asetCSS/btc-41.png)

4. Saat ini kita akan menggunakan jenis warna putih agar tidak lagi menyatu dengan warna background navabrnya. Pada outline buttons yang berwarna putih, tertulis "Light". Oleh karena itu salinlah kode program yang ada tulisan "Light".

```html

<button type="button" class="btn btn-outline-light">Light</button>

```

5. Blok lah terlebih dahulu kode program yang mengatur tombol pada bagian search tadi

    ![](asetCSS/btc-42.png)

6. Tempelkanlah kode program outline light, untuk menggantikan kode program button yang lama

    ![](asetCSS/btc-43.png)

7. Maka hasilnya akan bagus seperti pada gambar dibawah ini:

   ![](asetCSS/btc-44.png)

8. Ubahlah Text "Light" menjadi "Search"

    ![](asetCSS/btc-45.png)

9. Maka hasilnya akan seperti ini:

    ![](asetCSS/btc-46.png)

## Cards dan Form

Sekarang kita akan membuat sebuah form, dimana form tersebut kita asumsikan sebagai login page dari web kita tadi. Dalam pembuatan form login ini, kita akan menggunakan cards sebagai layout/tata letak yang akan mengatur form login tadi. Berikut langkah-langkahnya:

  

1. Yang pertama kita tentunya harus menentukan layout cards nya terlebih dahulu. Hal ini bertujuan agar jika tata letak card sudah ada, maka kita tinggal mengatur form nya di dalam card tadi. Masuk ke situs bootstrap tadi lalu pilih cards

    ![](asetCSS/btc-47.png)

2. Scrol ke bawah hingga menemukan layout yang kita inginkan, misalnya seperti pada gambar:

   ![](asetCSS/btc-48.png)

3. Pada bagian bawah contoh, terdapat kode program. Salinlah kode program tersebut

```html

<div class="card">

    <div class="card-header">

        Featured

    </div>

    <div class="card-body">

        <h5 class="card-title">Special title treatment</h5>

        <p class="card-text">With supporting text below as a natural lead-in to additional content.</p>

        <a href="#" class="btn btn-primary">Go somewhere</a>

    </div>

</div>

```

4. Tempelkanlah kode program itu pada halaman html terkait. Tentu saja dengan bootstrap yang sudah ditautkan, baik offline, maupun online.

5. Maka hasil awalnya adalah sebagai berikut:

    ![](asetCSS/btc-49.png)

6. karena jarak atas antara card dengan batas website terlalu dekat maka pada class card tambahkan mt-2 .

```html

<div class="card mt-2">

    <div class="card-header">

        Featured

    </div>

    <div class="card-body">

        <h5 class="card-title">Special title treatment</h5>

        <p class="card-text">With supporting text below as a natural lead-in to additional content.</p>

        <a href="#" class="btn btn-primary">Go somewhere</a>

    </div>

</div>

```

7. Maka hasilnya adalah seperti ini:

    ![](asetCSS/btc-50.png)

8. Sekarang kita ingin membuatnya terlihat ke tengah. Maka buatlah sebuah div dengan class yaitu "container", lalu salin masuklah kode program card tadi. Dengan kata lain, bungkuslah kode program card dengan sebuah div dengan class="container".

```html

<div class="container">

    <div class="card mt-2">

        <div class="card-header">

            Featured

        </div>

        <div class="card-body">

            <h5 class="card-title">Special title treatment</h5>

            <p class="card-text">With supporting text below as a natural lead-in to additional content.</p>

            <a href="#" class="btn btn-primary">Go somewhere</a>

        </div>

    </div>

</div>

```

9. Berikut hasil dari di bungkusnya cards tadi.

   ![](asetCSS/btc-51.png)

10. Sekarang kita akan membuat form nya. Pertama-tama, kita perlu membuat judul form. Caranya adalah ganti tulisan "Featured" di html kita dengan kata yang kita inginkan. misalnya pada program ini kita akan mengganti tulisan menjadi "Form Login".

    ![](asetCSS/btc-10.png)

```html

<div class="container">

    <div class="card mt-2">

        <div class="card-header">

            <h5>Form Login</h5>

        </div>

        <div class="card-body">

            <h5 class="card-title">Special title treatment</h5>

            <p class="card-text">With supporting text below as a natural lead-in to additional content.</p>

            <a href="#" class="btn btn-primary">Go somewhere</a>

        </div>

    </div>

</div>

```

*Keterangan*:

    1. ==`container`== pada ==`<div class="container">`== : Kelas ini memberikan tata letak yang terkandung pada lebar tertentu (dalam pixel) dan ditengahkan di tengah halaman atau elemen yang memuatnya. Ini membantu dalam mengatur konten agar sesuai dengan standar desain Bootstrap.

    2. ==`card`== pada ==`<div class="card mt-2">`== : Kelas ini memberikan gaya dan tata letak khusus untuk elemen ==`<div>`== yang merupakan kartu (card). Kartu adalah elemen Bootstrap yang sering digunakan untuk menampilkan konten atau informasi dalam satu unit terpisah dengan gaya yang konsisten.

        - `mt-2` : Kelas ini memberikan margin atas (margin-top) sebesar 2 unit. Ini membantu memberikan ruang di bagian atas kartu dan memisahkannya dari elemen-elemen sekitarnya.

    3. ==`card-header`== pada ==`<div class="card-header">`== : Kelas ini memberikan gaya khusus untuk elemen ==`<div>`== yang berfungsi sebagai header kartu. Header kartu biasanya berisi judul atau informasi lain yang menandai atau menjelaskan konten kartu.

        - ==`<h5>Form Login / h5>`== : Ini adalah elemen judul level 5 (h5) di dalam header kartu yang memberikan judul "Form Login" pada kartu.

    4. ==`card-body`== pada ==`<div class="card-body">`== : Kelas ini memberikan gaya khusus untuk elemen ==`<div>`== yang berisi tubuh atau konten utama kartu. Ini membantu memisahkan dan memvisualisasikan konten utama kartu.

        - ==`<h5 class="card-title">Special title treatment / h5>`== : Ini adalah elemen judul level 5 (h5) di dalam tubuh kartu yang memberikan judul khusus.

        - ==`<p class="card-text">With supporting text below as a natural lead-in to additional content. / p>`== : Ini adalah elemen paragraf di dalam tubuh kartu yang memberikan teks pendukung atau keterangan untuk konten utama kartu.

        - ==`<a href="#" class="btn btn-primary">Go somewhere / a>`== : Ini adalah elemen anchor (tautan) yang merupakan tombol dengan kelas Bootstrap "btn" dan "btn-primary", memberikan tampilan dan warna tertentu sesuai dengan desain Bootstrap.

    **Perbedaan Container dengan Container-fluid**:

    **container**:

    - ==`container`== memberikan tata letak yang terpusat dan memiliki lebar yang tetap (fixed-width).

    - Lebar ==`container`== diatur dalam satuan piksel dan tetap konstan terlepas dari ukuran layar pengguna.

    - Digunakan untuk membuat tata letak yang terkonsentrasi di tengah halaman dan memberikan batasan pada lebar kontennya.

    **container-fluid**:

        - ==`container-fluid`== memberikan tata letak yang penuh lebar, mengisi seluruh lebar layar.

        - Lebar ==`container-fluid`== disesuaikan dengan lebar layar pengguna, sehingga konten dapat memanfaatkan seluruh lebar tampilan tanpa batasan piksel tertentu.

        - Digunakan ketika Anda ingin membuat tata letak yang menyesuaikan diri dengan lebar layar dan memberikan tampilan responsif.

11. Hasilnya adalah sebagai berikut

    ![](asetCSS/btc-9.png)

12. Sekarang pada bagian dalam div card-body hapus semua elemen yang ada didalamnya kecuali button:

```html

<div class="container">

    <div class="card mt-2">

        <div class="card-header">

            <h5>Form Login</h5>

        </div>

        <div class="card-body">

            <a href="#" class="btn btn-primary">Go somewhere</a>

        </div>

    </div>

</div>

```

13. Hasilnya akan seperti ini

   ![](asetCSS/btc-11.png)

14. Langkah selanjutnya adalah menambahkan elemen-elemen form ke dalam card-body untuk membuat formulir login. Anda dapat menggunakan elemen-elemen HTML seperti form , input , dan button untuk ini. bukalah kembali getbootstrap.com dan pilihlah form yang kita inginkan:

   ![](asetCSS/btc-12.png)

15. Salinlah kode program dibawah contoh forms tadi:

```html

<form>

    <div class="mb-3">

        <label for="exampleInputEmail1" class="form-label">Email address</label>

        <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">

        <div id="emailHelp" class="form-text">We'll never share your email with anyone else.</div>

    </div>

    <div class="mb-3">

        <label for="exampleInputPassword1" class="form-label">Password</label>

        <input type="password" class="form-control" id="exampleInputPassword1">

    </div>

    <div class="mb-3 form-check">

        <input type="checkbox" class="form-check-input" id="exampleCheck1">

        <label class="form-check-label" for="exampleCheck1">Check me out</label>

    </div>

    <button type="submit" class="btn btn-primary">Submit</button>

</form>

```

16. Tempelkanlah didalam cards-body tadi

   ![](asetCSS/btc-13.png)

17. Maka hasilnya adalah sepert ini:

   ![](asetCSS/btc-14.png)

Dengan demikian kita sudah berhasil membuat layoutcards dimana form login sebagai kontennya

# Grid For Responsive Web/Layouting

Bootstrap memiliki sistem tata letak yang kuat yang bernama grid. Grid berguna untuk membuat tata letak yang responsif di halaman web kita. Sistem grid Bootstrap berdasarkan konsep kolom yang dapat diatur dalam baris. Berikut adalah beberapa hal penting yang perlu kita ketahui tentang grid dan layouting di Bootstrap:

  

1. **KONTAINER (Container)**

    Grid Bootstrap harus ditempatkan dalam elemen kontainer. Terdapat dua jenis kontainer yang tersedia, yaitu .container dan .container-fluid. .container memiliki lebar terbatas dan akan disesuaikan dengan lebar layar. .container ini digunakan ketika kita ingin membuat tata letak yang terpusat dan terbatas pada lebar tertentu. .container-fluid memiliki lebar penuh dan akan mengisi seluruh lebar layar. Kontainer ini digunakan ketika kita ingin membuat tata letak yang menyesuaikan dengan lebar layar penuh.

2. **BARIS (Row)**

    Baris digunakan untuk mengelompokkan kolom-kolom dalam tata letak. kita dapat menambahkan class .row pada elemen yang berfungsi sebagai wadah kolom. Baris ini akan memastikan bahwa kolom-kolom di dalamnya akan diatur secara horizontal.

3. **KOLOM (Column):**

    Kolom adalah bagian dasar dari sistem grid Bootstrap. Kolom- kolom ditempatkan di dalam baris dan digunakan untuk membagi horizontal ruang dalam grid. Setiap baris dipecah menjadi 12 kolom, yang dapat kita bagi sesuai kebutuhan.

  

    **Catatan**: kita dapat menggunakan kelas seperti .col- , .col-sm- , .col-md- , .col-lg- , atau .col-xl- untuk menentukan bagaimana kolom akan berperilaku di berbagai ukuran perangkat. Misalnya, .col-sm-6 akan membuat kolom tersebut memiliki lebar setengah dari baris pada ukuran layar kecil. kita dapat menggabungkan kelas kolom untuk ukuran layar yang berbeda untuk menciptakan tata letak yang responsif. Misalnya, .col-md-6 .col-lg-4 akan membuat kolom tersebut memiliki lebar setengah dari baris pada ukuran layar medium, dan memiliki lebar sepertiga dari baris pada ukuran layar besar.

4. **OFFSET**

    Kita dapat menggunakan kelas offset untuk memindahkan kolom ke samping. Misalnya, .offset-md-2 akan memindahkan kolom 2 satuan ke kanan pada layar dengan ukuran medium. Offset digunakan ketika Kita ingin membuat ruang kosong di antara kolom-kolom.

5. **Perilaku pada Ukuran Layar yang Berbeda**

    Kita dapat menggunakan kelas-kelas grid Bootstrap yang berbeda untuk mengontrol tampilan kolom pada ukuran layar yang berbeda. Misalnya, Kita dapat menggunakan .colsm- untuk ukuran layar kecil, .col-md- untuk ukuran layar medium, dan sebagainya. Dengan cara ini, Kita dapat membuat tata letak yang responsif untuk berbagai perangkat.

6. **NESTING**

    Nesting memungkinkan Kita menempatkan baris dan kolom di dalam kolom lainnya. Dengan cara ini, Kita dapat membuat tata letak yang lebih kompleks dengan komponen-komponen yang terkait. Misalnya, Kita dapat menempatkan sebuah baris di dalam kolom yang ada di dalam baris lainnya

7. **ORDER**

    Kita dapat menggunakan kelas .order- untuk mengubah urutan kolom pada ukuran layar tertentu. Misalnya, .order-first akan memindahkan kolom ke posisi pertama, dan .orderlast akan memindahkan kolom ke posisi terakhir. Dengan menggunakan kelas ini, Kita dapat mengatur ulang urutan kolom untuk mencapai tata letak yang diinginkan pada berbagai ukuran layar.

  

Itu adalah beberapa konsep penting dalam sistem grid Bootstrap. Dengan menggunakan sistem grid ini, kita dapat membuat tata letak yang responsif dan menyesuaikan tampilan elemen-elemen pada berbagai ukuran layar dengan mudah.

## Contoh Penggunaan dan Penjelasannya

Sekarang kita akan mencoba penggunaan grid yang dengan bantuan Bootstrap. Berikut langkah-langkahnya:

  

1. Masuklah kembali ke web getbootstrap.com.

    ![](asetCSS/btc-52.png)

2. carilah "Grid" di Kolom search lalu klik enter. Maka kita akan diarahkan pada halaman web yang berisi tentang grid.

    ![](asetCSS/btc-53.png)

3. Carilah layout atau tata letak grid yang kita inginkan. Misalnya pada praktek kali ini, kita akan menggunakan layout "Row columns".

    ![](asetCSS/btc-54.png)

4. Salinlah kode program yang terletak di kode bawah contohnya.

```html

<div class="container text-center">

    <div class="row row-cols-2">

        <div class="col">Column</div>

        <div class="col">Column</div>

        <div class="col">Column</div>

        <div class="col">Column</div>

    </div>

</div>

```

5. Tempelah pada file html yang tentunya telah dihubungkan dengan tautan bootstrap, baik secara offline maupun online.

    ![](asetCSS/btc-55.png)

6. Maka hasilnya akan seperti berikut:

   ![](asetCSS/btc-56.png)

    *Keterangan:*

    Jadi tulisan "Column" adalah isi konten yang sudah teratur dalam grid ini. kita bisa mengganti "konten" ini dengan konten yang kita inginkan

7. Untuk mengganti kontennya hapuslah tulisan "Column" lalu gantilah dengan kontent yang kita inginkan.

```html

<div class="container text-center">

    <div class="row row-cols-2">

        <div class="col">

            <div>

                <img width="50px" height="50px" src="img/HTML5_badge.png" alt="logo html" class="mt-5">

                <h3>HTML</h3>

                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. <br>Nobis totam assumenda unde quod et vitae minus beatae, <br> quibusdam impedit laboriosam earum, <br> possimus consequatur quisquam dolore ex ipsa eaque cupiditate neque.</p>

            </div>

        </div>

        <div class="col">

            <div>

                <img width="50px" height="60px" src="img/css-3-logo.png" alt="logo html" class="mt-4">

                <h3>CSS</h3>

                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. <br>Nobis totam assumenda unde quod et vitae minus beatae, <br> quibusdam impedit laboriosam earum, <br> possimus consequatur quisquam dolore ex ipsa eaque cupiditate neque.</p>

            </div>

        </div>

        <div class="col">

            <div>

                <img width="50px" height="50px" src="img/OIP.jpeg" alt="logo html" class="mt-2">

                <h3>JavaScript</h3>

                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. <br>Nobis totam assumenda unde quod et vitae minus beatae, <br> quibusdam impedit laboriosam earum, <br> possimus consequatur quisquam dolore ex ipsa eaque cupiditate neque.</p>

            </div>

        </div>

        <div class="col">

            <div>

                <img width="50px" height="50px" src="img/R.png" alt="logo html" class="mt-2">

                <h3>JQuery</h3>

                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. <br> Nobis totam assumenda unde quod et vitae minus beatae, <br> quibusdam impedit laboriosam earum, <br> possimus consequatur quisquam dolore ex ipsa eaque cupiditate neque.</p>

            </div>

        </div>

    </div>

</div>

```

8. Hasil nya akan menjadi seperti berikut:

   ![](asetCSS/btc-57.png)

    *Keterangan:*

    Jadi Grid tadi mengatur Row dan Column dimana terdapat 2 baris berisi 4 kolom sebagai kontennya. Kontennya tadi kita ganti dengan konten yang kita inginkan

9. Apabila layar yang kita kecilkan, maka grid akan menyesuaikan ukurannya seperti pada gambar ini

    ![](asetCSS/btc-58.png)

    *Keterangan:*

    Jadi grid ini sudah mengatur mengenai penyesuaian ukuran layar kita, sehingga, dapat menyesuaikan di segala ukuran monitor.

10. Apabila kita melihatnya di perangkat, maka akan terlihat seperti ini:

   ![](asetCSS/btc-59.png)

    *Keterangan:*

    Jadi karena grid yang disediakan oleh bootstrap telah mendukung fitur responsive, maka ketika user melihat tampilan web kita di ponsel, maka tata letak akan mengikutinya sesuai dengan ukuran ponsel, seperti yang terlihat pada gambar di atas

## Contoh Penggunaan `col-md`, `col-lg` dan `col-sm`

Kelas ==`col-md`== , ==`col-lg`== , dan ==`col-sm`== adalah kelas-kelas kolom dalam Bootstrap yang digunakan untuk meresponsifkan tata letak halaman web sesuai dengan ukuran layar perangkat. Bootstrap menggunakan sistem grid yang terdiri dari 12 kolom, dan kelas-kelas ini memungkinkan Anda mengontrol sejauh mana elemen-elemen tersebut harus meluas pada layar yang berbeda.

  

- ==`col-sm`== : Digunakan untuk layar kecil (small), seperti pada perangkat mobile atau tablet dalam orientasi potret. Kolom ini akan berlaku untuk layar dengan lebar 576px atau lebih.

- ==`col-md`== : Digunakan untuk layar sedang (medium), yang mencakup perangkat seperti tablet dalam orientasi landscape. Kolom ini akan berlaku untuk layar dengan lebar 768px atau lebih.

- ==`col-lg`== : Digunakan untuk layar besar (large), yang mencakup desktop. Kolom ini akan berlaku untuk layar dengan lebar 992px atau lebih.

  

**Contoh**:

Sekarang kita akan coba untuk membuat sebuah tampilan dengan menggunakan class diatas tadi. Berikut contohnya:

1. Bukalah kembali web getbootsrap lalu di kolom pencarian carilah "grid".

   ![](asetCSS/btc-60.png)

2. Cari dan copylah kembali codingan grid yang kita gunakan pada praktek sebelumnya.

   ![](asetCSS/btc-61.png)

```html

<div class="container text-center">

    <div class="row row-cols-2">

        <div class="col">Column</div>

        <div class="col">Column</div>

        <div class="col">Column</div>

        <div class="col">Column</div>

    </div>

</div>

```

3. Tempelkanlah codingan tadi di visual studio kode pada file tempat kita mempraktekkan grid pada praktikum sebelumnya, agar kita bisa menggunakan satu file saja untuk praktek.

   ![](asetCSS/btc-62.png)

4. Maka akan terlihat seperti gambar di bawah ini:

    ![](asetCSS/btc-63.png)

    *Keterangan*:

    Perhatikanlah di bawah kolom JavaScript dan JQuery, terdapat tulisan column sebanyak 4 dan bersusun hal ini dikarenakan pada kodingan tadi, teks yang dipakai sebagai template di bootstrap adalah "Column", nanti pada tahap selanjutnya kita akan mengganti "Column" itu dengan text atau item yang kita inginkan.

5. Sekarang, pada codingan yang kita ambil dari web bootstrap tadi pada bagian ==`<div class="col">`== yang pertama, tambahkanlah -md sehingga menjadi ==`<div class="col-md>"`== . Kemudian pada ==`<div class="col">`== yang kedua, tambahkanlah - lg sehingga menjadi ==`<div class="col-lg">`== , dan terakhir pada ==`<div class="col">`== yang ketiga, tambahkanlah -sm sehingga menjadi ==`<div class="col-sm">`== , sementara pada ==`<div class="col">`== yang terakhir kita biarkan saja seperti bawaan.

```html

<div class="container text-center">

    <div class="row row-cols-2">

        <div class="col-md">Column</div>

        <div class="col-lg">Column</div>

        <div class="col-sm">Column</div>

        <div class="col">Column</div>

    </div>

</div>

```

![](asetCSS/btc-65.png)

6. Maka hasilnya akan menjadi seperti ini:

    **Sebelum:**

    ![](asetCSS/btc-66.png)

    **Sesudah:**

   ![](asetCSS/btc-67.png)

  

*Keterangan:*

- ==`col-md`== :Dengan menambahkan -md pada codingan tadi akan membuat kolom tersebut mengambil sebagian besar lebar tersedia (12 kolom) pada layar dengan lebar medium (768px atau lebih).

- ==`col-lg`== : Sama seperti col-md , tetapi ditujukan untuk layar lebar (large, 992px atau lebih). col-sm : Sama seperti col-md , tetapi ditujukan untuk layar kecil (small, 576px atau lebih).

7. Tambahkanlah teks ataupun item dari yang kita inginkan dengan cara hapuslah teks "Column" tadi, dan ditempat teks "Column" yang sudah dihapus, tempelkan lah item atau teks yang kita inginkan

```html

<div class="container text-center">

    <div class="row row-cols-2">

        <div class="col-md">

            <div>

                <img width="50px" height="50px" src="img/HTML5_badge.png" alt="logo html" class="mt-5">

                <h3>HTML</h3>

                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. <br>

                    Nobis totam assumenda unde quod et vitae minus beatae, <br> quibusdam impedit laboriosam earum, <br>

                    possimus consequatur quisquam dolore ex ipsa eaque cupiditate neque.</p>

            </div>

        </div>

        <div class="col-lg">

            <div>

                <img width="50px" height="60px" src="img/css-3-logo.png" alt="logo html" class="mt-4">

                <h3>CSS</h3>

                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. <br>

                    Nobis totam assumenda unde quod et vitae minus beatae, <br> quibusdam impedit laboriosam earum, <br>

                    possimus consequatur quisquam dolore ex ipsa eaque cupiditate neque.</p>

            </div>

        </div>

        <div class="col-sm">

            <div>

                <img width="50px" height="50px" src="img/OIP.jpeg" alt="logo html" class="mt-2">

                <h3>JavaScript</h3>

                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. <br>

                    Nobis totam assumenda unde quod et vitae minus beatae, <br> quibusdam impedit laboriosam earum, <br>

                    possimus consequatur quisquam dolore ex ipsa eaque cupiditate neque.</p>

            </div>

        </div>

        <div class="col">

            <div>

                <img width="50px" height="50px" src="img/R.png" alt="logo html" class="mt-2">

                <h3>JQuery</h3>

                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. <br>

                    Nobis totam assumenda unde quod et vitae minus beatae, <br> quibusdam impedit laboriosam earum, <br>

                    possimus consequatur quisquam dolore ex ipsa eaque cupiditate neque.</p>

            </div>

        </div>

    </div>

</div>

```

![](asetCSS/btc-100.png)

8. Maka hasilnya akan seperti ini:

   ![](asetCSS/btc-68.png)

    *Keterangan:*

    Jadi pada praktek sebelumnya tanpa adanya tambahan pada class bootstrap tadi maka elemen akan menyesuaikan lebar pada pembungkus menjadi full, sedangkan untuk praktek yang saat ini kita tampilkan, item dan teks nya menyesuaikan ukurannya sesuai dengan tambahannnya. Untuk penjelasan ukurannya **Penjelasannya telah kami sediakan di langkah ke-6**.

# Penggunaan Tema

Dalam Bootstrap, tema dasarnya terdiri dari sejumlah variabel CSS yang mengontrol aspek-aspek seperti warna, ukuran teks, jarak, dan banyak lagi. Untuk melakukan kostumisasi tema, kita dapat mengganti nilai-nilai variabel ini sesuai dengan preferensi kita.

  

Berikut adalah langkah-langkah umum untuk melakukan kostumisasi tema Bootstrap:

1. **Menentukan gaya desain**: Pertama, tentukan gaya desain yang ingin kita terapkan pada situs web kita. Apakah kita ingin tampilan yang lebih minimalis, warna yang cerah, atau mungkin tampilan yang lebih kustom dengan elemen desain yang unik? Menentukan gaya desain akan membantu kita memutuskan bagaimana mengubah tema Bootstrap.

2. **Menggunakan Sass atau CSS**: Bootstrap menyediakan versi Sass (Syntactically Awesome Style Sheets) dari file sumbernya. Sass adalah bahasa pemrograman yang memungkinkan kita menulis CSS dengan sintaks yang lebih kuat dan fleksibel. Jika kita memiliki pengetahuan tentang Sass, kita dapat mengunduh versi Sass Bootstrap dan mengedit variabel-variabelnya. Jika kita tidak familiar dengan Sass , kita masih dapat mengedit file CSS Bootstrap langsung.

3. **Membuat file kustom**: Buat file kustom yang akan berisi kostumisasi tema kita. Dalam file ini, kita dapat menetapkan nilai-nilai variabel yang ingin kita ubah. Misalnya, kita dapat mengubah warna primer, warna latar belakang, ukuran huruf, dan lain sebagainya.

4. **Mengganti variabel**: Temukan variabel yang relevan dalam file sumber Bootstrap dan ubah nilainya sesuai dengan preferensi kita. Misalnya, jika kita ingin mengubah warna primer, cari variabel ==`$primary-color`== atau sejenisnya dalam file sumber dan ubah nilainya menjadi warna yang diinginkan.

5. **Mengompilasi tema kustom**: Setelah kita selesai mengedit file kustom, kita perlu mengompilasinya ke dalam file CSS yang dapat digunakan pada situs web kita. Jika kita menggunakan Sass, kita perlu mengompilasi file Sass menjadi CSS . Jika kita mengedit file CSS langsung, kita dapat menggunakan file tersebut langsung.

6. **Menerapkan tema kustom**: Setelah kita memiliki file CSS tema kustom, kita perlu menggantikan file Bootstrap default dengan file tema kustom kita pada situs web kita. Pastikan untuk menghubungkan file CSS tema kustom kita setelah file Bootstrap default sehingga kostumisasi kita akan ditimpa pada tema default. Kita dapat membuat tema kostuminasi Bootstrap yang sesuai dengan kebutuhan dan gaya desain kita. Penting untuk diingat bahwa jika kita menggunakan versi Bootstrap yang lebih baru, beberapa variabel atau struktur file mungkin telah berubah.

  

Kita dapat membuat tema kostuminasi Bootstrap yang sesuai dengan kebutuhan dan gaya desain kita. Penting untuk diingat bahwa jika kita menggunakan versi Bootstrap yang lebih baru, beberapa variabel atau struktur file mungkin telah berubah.

# Contoh Penggunaan Tema dalam Bootstrap

1. Jadi misalnya kita ingin memberikan tema pada website yang telah kita buat sebelumnya

    ![](asetCSS/btc-70.png)

2. Bukalah website bootswacth.com dimana website ini menyediakan tema tema yang dapat digunakan untuk web bootstrap kia.

    ![](asetCSS/btc-71.png)

3. Scroll lah ke bawah hingga kita menemukan kumpulan tema tema yang telah disediakaan oleh website ini

    ![](asetCSS/btc-72.png)

4. Misalnya kita akan memilih tema "Darkly", oleh karena itu, klik download pada bagian bawah contoh tema tersebut.

    !![](asetCSS/btc-73.png)

5. Jika sudah mendownloadnya maka kita telah mendapatkan file css untuk tema tersebut

    ![](asetCSS/btc-74.png)

6. Pindahkanlah file css tersebut ke dalam folder yang berisi file html yang akan kita berikan tema

    ![](asetCSS/btc-75.png)

7. Sekarang, masuklah ke dalam file html yang akan kita berikan tema bootstrap, lalu panggillah secara eksternal file css tema tadi ke dalam file html tersebut

   ![](asetCSS/btc-76.png)

8. Maka hasilnya adalah sebagai berikut dengan demikian kita sudah berhasil memberikan tema gelap pada tampilan html kita menggunakan tema dark pada bootstrap

    ![](asetCSS/btc-77.png)

    dengan demikian kita sudah berhasil memberikan tema gelap pada tampilan html kita menggunakan tema dark pada bootstrap

# Modifikasi Template Bootstrap

Kostumasisasi dalam bootstrap adalah menggunakan template bootstrap kemudian kita akan memodifikasi template tersebut sesuai dengan keinginan kita.

  

Template dalam Bootstrap adalah struktur dasar atau kerangka kerja yang telah dirancang sebelumnya dan dapat digunakan sebagai dasar untuk membangun halaman web. Bootstrap adalah sebuah framework front-end yang populer digunakan untuk pengembangan web responsif. Dalam konteks Bootstrap, template menyediakan struktur HTML dan gaya CSS dasar yang dapat digunakan sebagai dasar untuk membangun halaman web yang responsif dan mudah diatur.

  

Dengan menggunakan template Bootstrap, kita dapat menghemat waktu dan usaha dalam merancang tata letak dan gaya dasar dari suatu proyek web. Template ini biasanya sudah mencakup elemen￾elemen umum seperti navigasi, grid system, tombol, formulir, dan banyak lagi. Dengan cara ini, kita dapat fokus pada konten dan fitur unik dari situs web kita tanpa harus memulai dari awal.

  

Template dalam Bootstrap juga mendukung konsep responsivitas, yang berarti halaman web atau aplikasi yang dibangun dengan menggunakan template ini dapat menyesuaikan diri dengan berbagai ukuran layar, mulai dari perangkat seluler hingga desktop, tanpa perlu penyesuaian tambahan. Ini membuat pengembangan web lebih efisien dan memastikan pengalaman pengguna yang konsisten di berbagai perangkat.

  

Berikut cara mengkostumisasi template bootstrap:

  

1. Pertama adalah kita akan membuka sebuah website yang menyediakan template bootstrap. Kali ini web akan kita gunakan adalah themewagon.com

   ![](asetCSS/btc-78.png)

2. Masuklah ke dalam website tersebut

    ![](asetCSS/btc-79.png)

3. Carilah template yang ingin kita sesuaikan dengan cara mensearch ataupun menscroll hingga menemukan tema yang sesuai

    ![](asetCSS/btc-80.png)

4. Jika sudah menemukan template yang kita inginkan, masuk ke template tersebut lalu klik download pada bagian kanan sebelah, contoh gambar dibawah ini.

   ![](asetCSS/btc-81.png)

5. Jika sudah mendownloadnya maka kita telah mendapatkan file template bootsrap kita dalam bentuk zip. File ini berisi asset gambar, style css, index tml, maupun javascript yang menyusun komponen template ini

    ![](asetCSS/btc-82.png)

6. Ekstraklah file tersebut hingga berbentuk seperti file biasa dengan cara klik kanan pada file zip tadi lalu pilih "Extract All".

   ![](asetCSS/btc-83.png)

7. Jika proses ekstrak sudah selesai maka kita tela mendapatkan folder template tersebut dalam bentuk folder biasa

    ![](asetCSS/btc-84.png)

8. Masuklah ke dalam folder template yang telah diekstrak tadi

   ![](asetCSS/btc-85.png)

9. Masuklah ke dalam folder index.html. didalam sana terdapat tampilan template kita

   ![](asetCSS/btc-86.png)

10. Sekarang kita akan mengkostumasisasi tampilan web template ini. Caranya adalah buka file template nya di visual studio code

   ![](asetCSS/btc-87.png)

11. Mulailah mengganti konten-konten seperti teks, gambarm dan lainnya seperti yang kita inginkan. Misalnya saya akan mengganti teks yang ada di gambar ini

   ![](asetCSS/btc-.png)

12. Buka kembali visual studio dan masuk ke file index.html tersebut lalu carilah penyusun konten itu

   ![](asetCSS/btc-88.png)

13. Gantilah kalimat dan tujuan email dan nomor telp itu dengan yang kita inginkan

```html

<a class="navbar-sm-brand text-light text-decoration-none" href="mailto:powershop179@gmail.com">powershop179@gmail.com</a>

<i class="fa fa-phone mx-2"></i>

<a class="navbar-sm-brand text-light text-decoration-none" href="tel:082133273167">082133273167</a>

```

Maka hasilnya akan terlihat seperti dibawah ini:

   ![](asetCSS/btc-89.png)

14. Mulailah mengganti elemen-elemen lainnya sesuai keinginan kita. Misalnya kita ingin juga mengganti logo yang ada di website ini

    ![](asetCSS/btc-90.png)

```html

<a class="navbar-brand text-success logo h1 align-self-center" href="index.html">

    Powershop179

</a>

```

15. Hasil setelah diganti adalah seperti ini

   ![](asetCSS/btc-91.png)

16. Sekarang kita akan mengganti Nama web kita yang ada di slide carousel

    ![](asetCSS/btc-92.png)

```html

<div class="col-lg-6 mb-0 d-flex align-items-center">

    <div class="text-align-left align-self-center">

        <h1 class="h1 text-success"><b>PowerShop179</b> eCommerce</h1>

        <h3 class="h2">Tiny and Perfect eCommerce Template</h3>

        <p>

            PowerShop179 is an eCommerce HTML5 CSS template with the latest version of Bootstrap 5 (beta 1).

            This template is 100% free provided by <a rel="sponsored" class="text-success" href="https://templatemo.com" target="_blank">TemplateMo</a> website. Image credits go to

            <a rel="sponsored" class="text-success" href="https://stories.freepik.com/" target="_blank">Freepik Stories</a>,

            <a rel="sponsored" class="text-success" href="https://unsplash.com/" target="_blank">Unsplash</a> and

            <a rel="sponsored" class="text-success" href="https://icons8.com/" target="_blank">Icons 8</a>.

        </p>

    </div>

</div>

  

```

Hasilnya akan menjadi seperti ini:

   ![](asetCSS/btc-93.png)

17. bagaimana jika kita ingin mengganti gambar? Misalnya kita akan mengganti gambar yang ada di card ini

    ![](asetCSS/btc-94.png)

18. Masuklah ke visual studio code dan ke index.html tadi lalu carilah kode penyusun untuk gambar ini, kemudian gantilah di bagian src gambar yang sudah ada dengan gambar yang kita inginkan

```html

<a href="shop-single.html">

<img src="./assets/img/feature_prod_01.jpg" class="card-img-top" alt="..." />

</a>

```

Maka haslinya akan menjadi seperti ini:

  ![](asetCSS/btc-95.png)

Demikianlah kostumisasi template bootstrap ini. Kesimpulanya kita dapat mengganti text, gambar, link tujuan, atau menambahkan elemen tertentu sesuai dengan kebutuhan kita. Ini tentunya sangat menghemat waktu dan tenaga, dimana kita hanya fokus pada konten yang kita sajikan dibanding harus menyusun grid, responsif, dan lainnya dari awal

# Studi Kasus Pengaplikasian Bootstrap dalam Desain Web

**Contoh Desain Web Yang Akan di Implementasikan**:

  ![](asetCSS/bf-1.jpg)

1. dalam desain web tersebut terdapat beberapa komponen, yaitu

   - Navbar, Hero Section, Button dll

2. Pertama-tama kita perlu Inisialisasikan class ==`container`== agar dapat memberikan tata letak konten yang sesuai dengan desainnya.

```html

<div class="container">

</div>

```

*Keterangan*:

- pada ==`<div class="container">`== : Kelas ini memberikan tata letak yang terkandung pada lebar tertentu (dalam pixel) dan ditengahkan di tengah halaman atau elemen yang memuatnya. Ini membantu dalam mengatur konten agar sesuai dengan standar desain Bootstrap.

  

3. Selanjutnya kita akan implementasikan navbarnya, bukalah kembali web getbootsrap lalu di kolom pencarian carilah "navbar".

      ![](asetCSS/bf-2.png)

4. Cari dan copylah codingan komponen navbar yang mungkin sesuai dengan desainnya.

      ![](asetCSS/bf-3.png)

```html

<nav class="navbar navbar-expand-lg bg-body-tertiary"> <div class="container-fluid"> <a class="navbar-brand" href="#">Navbar</a> <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation"> <span class="navbar-toggler-icon"></span> </button> <div class="collapse navbar-collapse" id="navbarSupportedContent"> <ul class="navbar-nav me-auto mb-2 mb-lg-0"> <li class="nav-item"> <a class="nav-link active" aria-current="page" href="#">Home</a> </li> <li class="nav-item"> <a class="nav-link" href="#">Link</a> </li> <li class="nav-item dropdown"> <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false"> Dropdown </a> <ul class="dropdown-menu"> <li><a class="dropdown-item" href="#">Action</a></li> <li><a class="dropdown-item" href="#">Another action</a></li> <li> <hr class="dropdown-divider"> </li> <li><a class="dropdown-item" href="#">Something else here</a></li> </ul> </li> <li class="nav-item"> <a class="nav-link disabled" aria-disabled="true">Disabled</a> </li> </ul> <form class="d-flex" role="search"> <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search"> <button class="btn btn-outline-success" type="submit">Search</button> </form> </div> </div> </nav>

```

*Keterangan*:

    1. ==`navbar`== : Kelas ini menunjukkan bahwa elemen ==`<nav>`== adalah bagian dari komponen navbar. Navbar adalah bagian dari Bootstrap yang menyediakan navigasi di bagian atas halaman web. Dengan memberikan kelas navbar , kita memberitahu Bootstrap untuk menerapkan gaya dan tata letak khusus yang terkait dengan navigasi.

    2. ==`bg-body-tertiary`== : Kelas ini memberikan warna latar belakang pada navbar. Dalam hal ini, warna latar belakangnya diberi warna sesuai dengan warna "hijau" Warna latar belakang ini dapat disesuaikan sesuai kebutuhan desain.

    3. ==`container-fluid`== : Kelas ini diterapkan pada elemen ==`<div>`== yang membungkus elemen-elemen dalam navbar. Kelas ini memberikan padding yang sesuai dan membuat elemen-elemen di dalamnya menjaga lebar penuh dari layar (menggunakan grid system Bootstrap). Dengan kata lain, kontennya akan merespons secara baik pada berbagai lebar perangkat.

    4. ==`d-flex`== : Kelas ini mengubah elemen ==`<form>`== menjadi kontainer flex. Flexbox adalah teknik tata letak yang kuat di CSS yang memudahkan pengaturan dan penataan elemen dalam satu atau dua dimensi. Dengan memberikan kelas d-flex , elemen form dan anak-anaknya dapat disusun secara fleksibel.

    5. ==`me-2`== : Ini adalah kelas Bootstrap yang memberikan margin kanan sebesar 2 pada elemen yang memilikinya. Dalam codingan ini, kelas ini diterapkan pada elemen input untuk memberikan jarak margin kanan.

  

5. Tempelkanlah kode program itu didalam class ==`container`== sebelumnya pada halaman html terkait. Tentu saja dengan bootstrap yang sudah ditautkan, baik offline, maupun online.

6. Maka hasilnya akan seperti ini:

      ![](asetCSS/bf-4.png)

7. Sekarang pada bagian dalam div `navbar-collapse` hapus elemen form:

```html

<form class="d-flex" role="search"> <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search" /> <button class="btn btn-outline-success" type="submit">Search</button> </form>

```

  ![](asetCSS/bf-r1.png)

8. Hasilnya akan seperti ini:

   ![](asetCSS/bf-5.png)

9. Langkah Selanjutnya kita perlu mengganti list list serta nama logo pada navbarnya

```html

<ul class="navbar-nav me-auto mb-2 mb-lg-0"> <li class="nav-item"> <a class="nav-link active fw-bold" aria-current="page" href="#">Home</a> </li> <li class="nav-item"> <a class="nav-link text-muted" href="#">Discover</a> </li> <li class="nav-item"> <a class="nav-link text-muted" href="#">Post a Job</a> </li> <li class="nav-item"> <a class="nav-link text-muted" href="#">Contact Us</a> </li> </ul>

```

*Keterangan*:

    1. Disini kita mengganti text list item, dari sebelumnya default dari bootstrap ke desain yang akan diimplementasikan seperti: home,discover,post a job dan contact us

    2. ==`fw-bold`== dalam Bootstrap digunakan untuk memberikan tebal pada teks. Kelas ini merupakan bagian dari utilitas ==`font-weight`== yang disediakan oleh Bootstrap, yang memungkinkan Anda untuk dengan cepat mengubah berat font teks dengan kelas `.fw-*`. Kelas ==`fw-bold`== setara dengan berat font 700

    3. ==`text-muted`== digunakan untuk memberi gaya pada teks dengan warna yang redup. Kelas ini merupakan bagian dari utilitas ==`text-color`== yang disediakan oleh Bootstrap, yang memungkinkan Anda untuk dengan mudah mengubah warna teks dengan kelas ==`.text-*`.== Kelas ==`text-muted`== setara dengan warna ==`$gray-600`==, yang merupakan warna abu-abu yang redup.

  

  ![](asetCSS/bf-6.png)

10. Kemudian tambah tombol `sign-up`  di sebelah kanan, sama seperti form namun kita berikan tag anchor

```html

<a href="/sign-up" class="btn btn-outline-dark rounded-0 fw-bold"> Sign Up </a>

```

*Keterangan*:

    1. class ==`btn`==  digunakan untuk mengatur tampilan tombol. Class ini menambahkan beberapa stil ke tampilan tombol, seperti padding, margin, dan warna latar belakang.

    2. ==`btn-outline-dark`== digunakan untuk mengatur tampilan tombol dengan latar belakang transparan dan warna tekstu yang hitam.

    3. ==`rounded-0`==  digunakan untuk mengatur bentuk tombol dengan sudut yang tidak ada (0).

    4. ==`fw-bold`==  digunakan untuk mengatur font teks dengan berat font yang tebal.

    5.  ==`text-muted`==  digunakan untuk mengatur warna teks dengan warna yang redup.

  

  ![](asetCSS/bf-7.png)

11. Selanjutnya ganti background navbarnya dari `bg-body-tertiary` menjadi transparan dengan menggunakan class `bg-trasnparent`

  ![](asetCSS/bf-r2.png)

  ![](asetCSS/bf-8.png)

12. Sekarang kita akan menengahkan list navbarnya dengan menggunakan class `m-auto`

  

sebelum

  ![](asetCSS/bf-9.png)

sesudah

  ![](asetCSS/bf-10.png)

13. Hasilnya akan seperti ini:

     ![](asetCSS/bf-11.png)

14. Sekarang kita akan implementasikan komponen hero section, tuliskan kode berikut.

```html

<section id="hero"></section>

```

15. dapat kita lihat pada komponen hero terdapat text dan tombol posisinya ditengah, nah disini kita bisa menggunakan grid system bootstrap agar dapat mengatur posisinya.

```html

<div class="row h-100 justify-content-center align-items-center text-center"> <div class="col-12"> <h1 class="fw-bold">Get Connected to the Best Remote <br />Jobs in Your Field </h1> <p class="text-muted">Discover a wide range of remote opportunities on our platform and<br />take control of your career</p> </div> </div>

```

*Keterangan*:

    1.  ==`row`== digunakan untuk mengatur tata letak konten dalam satu baris. Class ini menambahkan beberapa stil ke tata letak konten, seperti mengatur margin dan padding untuk konten yang berada di sisi.

    2.  ==`h-100`== adalah class Bootstrap yang digunakan untuk mengatur tinggi konten dalam sebuah halaman web. Class ini menambahkan stil yang memastikan konten berada pada tinggi penuh dari bagian atas ke bawah.d

    3.  ==`justify-content-center`== adalah class Bootstrap yang digunakan untuk mengatur posisinya konten di tengah bagian horizontal.

    4. class ==`align-items-center`== adalah class Bootstrap yang digunakan untuk mengatur posisinya konten di tengah bagian vertikal.

    5. class ==`text-center`== adalah class Bootstrap yang digunakan untuk mengatur posisi teks di tengah bagian konten.

    6. class ==`col-12`== adalah class Bootstrap yang digunakan untuk mengatur lebar konten. Class ini menambahkan stil yang memastikan konten berada pada lebar penuh dari bagian atas ke bawah.

  

16. Hasilnya akan seperti ini:

     ![](asetCSS/bf-12.png)

17. Disini text nya hanya ke tengah secara horizontal, agar dapat ke tengah secara vertikal perlu kita atur tinggi pada hero sectionnya dengan external style

```html

<style> #hero { height: 85vh; } </style>

```

![[bf-r3.png]]

*Keterangan*:

     ini mengatur tinggi dari elemen yang memiliki ID `hero` menjadi 85% dari tinggi viewport (viewport height).

  

18. Hasilnya akan seperti ini:

     ![](asetCSS/bf-13.png)

19. Sekarang kita akan implementasikan komponen button nya, dapat kita lihat pada desainnya terdapat dua button sejajar secara horizontal, maka kita perlu memakai flexbox yang disediakan oleh bootstrap.

```html

<div class="d-flex gap-4 justify-content-center align-items-center"> <a href="#" class="">Explore Remote Jobs</a> <a href="#" class="">How it works?</a> </div>

```

*Keterangan*:

    1. ==`d-flex`==  digunakan untuk mengatur tata letak konten dalam satu baris. Class ini menambahkan stil yang memastikan konten berada pada satu baris dan tidak berpindah ke baris baru.

    2. ==`gap-4`==  digunakan untuk mengatur jarak antara konten dalam satu baris. Class ini menambahkan stil yang membuat jarak antara konten berada 4 unit.

    3. ==`justify-content-center`== digunakan untuk mengatur posisinya konten di tengah bagian horizontal.

    4. ==`align-items-center`== digunakan untuk mengatur posisinya konten di tengah bagian vertikal.

  

  ![](asetCSS/bf-14.png)

20. Selanjutnya kita perlu beri space dari setiap buttonnya, dan beri warna pada button sebelah kiri

```html

<div class="d-flex gap-4 justify-content-center align-items-center"> <a href="#" class="p-2 px-3 text-decoration-none bg-primary rounded-5 text-white shadow-sm ">Explore Remote Jobs</a> <a href="#" class="p-2 px-3 text-primary rounded-5 fw-semibold">How it works?</a> </div>

```

*Keterangan*:

    1.  ==`p-2`== digunakan untuk mengatur padding pada tautan. Class ini menambahkan stil yang membuat padding pada tautan berada 0.5 unit pada sisi atas dan bawah, serta 0.75 unit pada sisi kiri dan kanan.

    2. ==`px-3`== digunakan untuk mengatur padding pada tautan. Class ini menambahkan stil yang membuat padding pada tautan berada 0.75 unit pada sisi kiri dan kanan.

    3. ==`text-decoration-none`== digunakan untuk mengatur dekorasi teks pada tautan. Class ini menghilangkan dekorasi garis bawah yang biasanya muncul pada tautan.

    4. ==`bg-primary`== digunakan untuk mengatur warna latar belakang pada tautan. Class ini menambahkan stil yang membuat latar belakang tautan berwarna hitam.

    5.  ==`rounded-5`== digunakan untuk mengatur bentuk tautan. Class ini menambahkan stil yang membuat bentuk tautan berbentuk lingkaran dengan jari-jari 5 unit.

    6. ==`text-white`== digunakan untuk mengatur warna teks pada tautan. Class ini menambahkan stil yang membuat warna teks tautan berwarna putih.

    7. ==`shadow-sm`== digunakan untuk mengatur gaya bagian atas tautan. Class ini menambahkan stil yang membuat bagian atas tautan berwarna abu-abu dengan efek shadow.

    8. ==`fw-semibold`== digunakan untuk mengatur font teks dengan berat font yang semibold.

    9. ==`text-primary`== digunakan untuk mengatur warna teks pada tautan. Class ini menambahkan stil yang membuat warna teks tautan berwarna hitam.

  

  ![](asetCSS/bf-15.png)

21. Sekarang kita akan mengganti background body nya

```html

<style> body { background-color: #F6FAFF; background-image: linear-gradient(90deg, #0500FF 0%, #F8FB76 35%, #4EFF75 64%, #00FFD1 100%); background-blend-mode: overlay; } </style>

```

![[bf-r4.png]]

22. Hasilnya akan seperti ini:

   ![](asetCSS/bf-16.png)

# Best Practices dan Tips

## Gunakan Grid Sistem:

Manfaatkan grid sistem Bootstrap untuk mengatur tata letak (layout) situs Anda dengan baik. Gunakan kelas-kelas seperti `container`, `row`, dan `col` untuk membagi konten Anda menjadi bagian-bagian yang sesuai.

## Gunakan Komponen Bootstrap:

Manfaatkan komponen-komponen yang disediakan oleh Bootstrap seperti navbar, card, form, dll. Komponen-komponen ini sudah dirancang dan diuji untuk memastikan konsistensi dan fungsionalitas yang baik.

## Uji pada Berbagai Browser:

Pastikan situs Anda berfungsi dengan baik di berbagai browser, termasuk versi lama dan baru, dengan melakukan pengujian silang browser.

# Pengenalan Responsive Web Design

Responsive web design atau desain web responsif adalah sebuah teknik atau metode bagi web designer untuk membuat suatu layout website yang dapat menyesuaikan diri sesuai dengan ukuran layar pengguna. Baik dari ukuran huruf, user interface, gambar dan tata letak akan menyesuaikan dengan lebar layar dan resolusi device yang digunakan.

Selain dapat memengaruhi apa yang ditampilkan pada perangkat tertentu, ini juga untuk meningkatkan kenyamanan pengguna dalam mengunjungi suatu website.
![[responsive-1.png]]
# Mengapa perlu CSS Responsive?

Pernahkah Anda mengunjungi situs web di smartphone Anda dan halaman webnya berantakan atau teksnya terlalu kecil untuk dibaca? Ini artinya situs web tersebut belum responsif. Dengan memakai css responsif maka web kita memungkinkan tampil optimal di berbagai perangkat, mulai dari desktop, laptop, tablet, hingga smartphone. Berikut alasan beberapa alasan mengapa css responsif penting:

- **Tampilan yang Bagus di Semua Perangkat**

  CSS responsif memungkinkan tampilan situs web beradaptasi dengan baik terhadap berbagai perangkat dan ukuran layar, sehingga pengguna akan memiliki pengalaman yang konsisten dan optimal, baik mereka mengakses situs melalui desktop, tablet, atau ponsel.

- **Mudah Diakses**

  Situs yang responsif bisa diakses dengan mudah oleh lebih banyak orang, termasuk yang menggunakan ponsel untuk browsing.

- **Interaksi yang Lebih Baik**

  Situs yang responsif cenderung membuat orang merasa lebih nyaman dan lebih mudah berinteraksi. Ini bisa meningkatkan kemungkinan orang melakukan hal-hal seperti membeli produk atau menghubungi Anda.

# Teknik Dasar CSS Responsif

## Konsep Dasar

- **Grid System**: Menggunakan grid system dalam CSS untuk mempermudah penataan elemen pada halaman web.

- **Flexbox**: Memahami penggunaan flexbox untuk menata elemen secara responsif.

## Media Query

Media query adalah fitur CSS yang memungkinkan Anda menargetkan perangkat dan ukuran layar yang berbeda dengan aturan CSS yang spesifik. Hal ini sangat penting untuk membuat website yang responsif, yaitu website yang dapat menyesuaikan tata letak dan desainnya secara otomatis agar terlihat optimal di semua perangkat, mulai dari desktop, laptop, tablet, hingga smartphone.

### Cara Kerja Media Query

Media query menggunakan aturan `@media` untuk menargetkan perangkat dan ukuran layar yang berbeda. Aturan ini terdiri dari dua bagian:

- **Media type:** Menentukan jenis perangkat yang ingin Anda targetkan, seperti `screen` (untuk desktop, laptop, tablet, dan smartphone) atau `print` (untuk printer).

- **Media feature:** Menentukan karakteristik perangkat yang ingin Anda targetkan, seperti `max-width` (lebar layar maksimum), `min-width` (lebar layar minimum), `device-width` (lebar perangkat), dan `orientation` (orientasi perangkat).

### Breakpoints

Breakpoints adalah titik-titik di mana tata letak halaman web akan berubah. Breakpoints biasanya ditentukan berdasarkan lebar layar perangkat.

  

- **320px:** Lebar minimum untuk smartphone.

- **768px:** Lebar minimum untuk tablet.

- **1024px:** Lebar minimum untuk laptop.

- **1200px:** Lebar minimum untuk desktop.

  

```css

@media screen and (max-width: 768px) {

  /* Aturan CSS untuk perangkat mobile */

  body {

    font-size: 16px;

  }

  .container {

    width: 100%;

  }

}

```

## Unit Relatif

Unit relatif adalah unit yang digunakan dalam CSS untuk menentukan ukuran elemen secara proporsional. Berbeda dengan unit absolut seperti piksel dan sentimeter, unit relatif tidak memiliki nilai tetap dan dapat berubah tergantung pada konteksnya.

### Keuntungan

- **Fleksibilitas:** Unit relatif memungkinkan Anda membuat website yang responsif dan dapat menyesuaikan dengan berbagai ukuran layar dan perangkat.

- **Kemudahan Penggunaan:** Unit relatif lebih mudah digunakan untuk menentukan ukuran elemen yang proporsional dan konsisten di seluruh website.

- **Pemeliharaan:** Website yang menggunakan unit relatif lebih mudah dipelihara dan diubah karena ukuran elemen akan menyesuaikan secara otomatis.

### Jenis-jenis Unit Relatif:

- **em:** Ukuran font elemen induk

- **rem:** Ukuran font elemen root (biasanya elemen `<html>`)

- **vw:** Lebar viewport (layar perangkat pengguna)

- **vh:** Tinggi viewport (layar perangkat pengguna)

- **vmin:** Nilai terkecil antara vw dan vh

- **vmax:** Nilai terbesar antara vw dan vh

## Viewport Meta Tag

Viewport meta tag adalah sebuah elemen HTML yang memberitahu browser web bagaimana cara menampilkan website Anda pada perangkat pengguna. Tag ini sangat penting untuk website responsif, yaitu website yang dapat menyesuaikan tata letak dan desainnya secara otomatis agar terlihat optimal di semua perangkat, mulai dari desktop, laptop, tablet, hingga smartphone.

  

```html

<meta name="viewport" content="width=device-width, initial-scale=1.0">

```

  

- **width=device-width:** Menentukan lebar awal website agar sama dengan lebar perangkat pengguna.

- **initial-scale=1.0:** Mengatur skala awal website menjadi 100%.

# Best Practices

## Gunakan Mobile-First

Saat mendesain website, mulailah dengan mempertimbangkan tampilan website pada perangkat mobile. Hal ini akan membantu Anda membuat website yang lebih ringkas dan mudah digunakan di semua perangkat.

  

# Implementasi CSS Responsif

## Sebelum Responsif
![[res-2.png]]

## Sesudah Responsif
![[res-3.png]]

## Kode

### HTML

```html

<!DOCTYPE html>

<html>

  <head>

    <link rel="stylesheet" href="style.css" />

    <meta name="viewport" content="width=device-width, initial-scale=1" />

    <title>CSS Responsif</title>

  </head>

  <body>

    <header></header>

    <section class="container">

      <div class="list">

        <div class="item"></div>

        <div class="item"></div>

        <div class="item"></div>

        <div class="item"></div>

      </div>

      <aside></aside>

    </section>

    <footer></footer>

  </body>

</html>

```

### CSS

```css

body {

  background-color: #222831;

  color: white;

}

  

header {

  width: 100%;

  height: 77px;

  background-color: #EEEEEE;

}

  

.container {

  display: flex;

  justify-content: space-between;

}

.item {

  width: 250px;

  height: 70px;

  background-color: teal;

  margin: 1em 0;

}

  

aside {

  width: 300px;

  height: 70vh;

  background-color: salmon;

}

  

footer {

  width: 100%;

  height: 100px;

  background-color: yellow;

}

  

@media screen and (max-width: 768px) {

  .container {

    padding: 1rem;

    flex-direction: column;

  }

  .item {

    width: 100%;

  }

  aside {

    width: 100%;

  }

}

```

### Penjelasan Singkat

```css

body {

  background-color: #222831;

  color: white;

}

```

- `body`: Ini adalah elemen HTML yang menandakan seluruh konten halaman web.

- `background-color: #222831`: Ini mengatur warna latar belakang dari elemen "body" menjadi warna gelap dengan kode warna #222831 (hampir hitam).

- `color: white`: Ini mengatur warna teks di dalam elemen "body" menjadi putih.

  

```css

header {

  width: 100%;

  height: 77px;

  background-color: #EEEEEE;

}

```

- `header`:  elemen HTML yang menandakan bagian atas halaman web.

- `width: 100%`: membuat lebar elemen "header" sejajar dengan lebar area yang mengandungnya, yang mungkin adalah lebar jendela browser atau lebar elemen induk lainnya. Dengan memberikan nilai 100%, elemen "header" akan merentang ke seluruh lebar area tersebut.

- `height: 77px`: menetapkan tinggi elemen "header" menjadi 77 piksel. Jadi, meskipun lebarnya mengikuti lebar area induknya (100%), tingginya tetap diberikan secara spesifik dengan 77 piksel. Ini bertujuan untuk memastikan bahwa tinggi header tetap konsisten meskipun konten di dalamnya berubah.

- `background-color: #EEEEEE` : Ini mengatur warna latar belakang dari elemen "header" menjadi abu-abu muda dengan kode warna # EEEEEE.

  

```css

.container {

  display: flex;

  justify-content: space-between;

}

```

- `.container`: Ini adalah kelas CSS yang digunakan untuk menargetkan elemen HTML dengan kelas "container".

- `display: flex`: membuat elemen dengan kelas "container" menggunakan model tata letak flexbox.

- `justify-content: space-between`: Ini mengatur jarak antara elemen-elemen di dalam flexbox container agar rata di sepanjang sumbu utama (biasanya sumbu horizontal), dengan menjaga jarak yang sama antara elemen-elemen dan meletakkan mereka pada posisi ujung container.

  

```css

.item {

  width: 250px;

  height: 70px;

  background-color: teal;

  margin: 1em 0;

}

```

- `.item`: Ini adalah sebuah selektor CSS yang memilih elemen dengan kelas "item".

- `width: 250px`: Ini mengatur lebar elemen menjadi 250 piksel.

- `height: 70px;`: Ini mengatur tinggi elemen menjadi 70 piksel.

- `background-color: teal;`: Ini mengatur warna latar belakang elemen menjadi warna teal.

- `margin: 1em 0;`: Ini mengatur jarak antara elemen dengan elemen lainnya, dengan 1 em (ukuran relatif terhadap font-size) pada bagian atas dan bawah, dan 0 pada bagian kanan dan kiri.

  

```css

aside {

  width: 300px;

  height: 70vh;

  background-color: salmon;

}

```

- `aside`: Ini adalah sebuah elemen HTML yang biasanya digunakan untuk menunjukkan konten tambahan di samping konten utama.

- `width: 300px;`: Ini mengatur lebar elemen "aside" menjadi 300 piksel.

- `height: 70vh;`: Ini mengatur tinggi elemen "aside" menjadi 70% dari tinggi viewport.

- `background-color: salmon;`: Ini mengatur warna latar belakang elemen "aside" menjadi warna salmon.

  

```css

footer {

  width: 100%;

  height: 100px;

  background-color: yellow;

}

```

- `footer`: Ini adalah sebuah elemen HTML yang biasanya digunakan untuk menampilkan informasi tambahan di bagian bawah halaman web.

- `width: 100%;`: Ini mengatur lebar elemen "footer" agar mengisi seluruh lebar dari parent element (biasanya body atau container lainnya).

- `height: 100px;`: Ini mengatur tinggi elemen "footer" menjadi 100 piksel.

- `background-color: yellow;`: Ini mengatur warna latar belakang elemen "footer" menjadi warna kuning.

  

```css

@media screen and (max-width: 768px) {

  .container {

    padding: 1rem;

    flex-direction: column;

  }

  .item {

    width: 100%;

  }

  aside {

    width: 100%;

  }

}

```

- `@media screen and (max-width: 768px)`: Ini adalah aturan media query yang diterapkan ketika lebar layar kurang dari atau sama dengan 768 piksel.

- `.container`: Mengatur tampilan untuk elemen dengan kelas "container" ketika media query aktif.

    - `padding: 1rem;`: Memberikan padding sebesar 1 rem di sekitar elemen "container".

    - `flex-direction: column;`: Mengubah arah penataan elemen menjadi vertikal (kolom), sehingga elemen akan ditata dari atas ke bawah.

- `.item`: Mengatur tampilan untuk elemen dengan kelas "item" ketika media query aktif.

    - `width: 100%;`: Memberikan lebar sebesar 100% dari parent element, sehingga elemen akan mengisi lebar penuh.

- `aside`: Mengatur tampilan untuk elemen "aside" ketika media query aktif.

    - `width: 100%;`: Memberikan lebar sebesar 100% dari parent element, sehingga elemen "aside" akan mengisi lebar penuh.


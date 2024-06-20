# Apa Itu Dinamis?
Web dinamis adalah jenis situs web yang menggunakan sisi server untuk menghasilkan konten yang berubah secara dinamis sesuai dengan permintaan pengguna. Ini berarti bahwa konten yang ditampilkan kepada pengguna dapat berubah berdasarkan interaksi mereka atau data yang diterima oleh server.

# Apa Itu PHP?
PHP (Hypertext Preprocessor) adalah bahasa pemrograman yang umum digunakan untuk pengembangan web dinamis. PHP bekerja di sisi server, yang berarti kode PHP dijalankan di server web dan hasilnya dikirimkan ke browser pengguna dalam bentuk HTML. Dengan PHP, Anda dapat membuat halaman web yang menanggapi input pengguna, berinteraksi dengan basis data, menghasilkan konten dinamis, dan melakukan banyak tugas lainnya yang diperlukan untuk mengembangkan aplikasi web yang dinamis dan interaktif.
# Program pertama PHP
## Cara 
1. Buka XAMPP, kemudian klik tombol start pada `apache`
2. Open file manager 
3. Open di Drive D
4. Kemudian Open folder XAMPP
5. Lalu open folder htdocs
6. Buat folder baru di dalam htdocs 
7. Lalu open folder yang sudah anda buat 
8. Open VSCode
9. Open folder yang sudah anda buat di VSCode
10. Buat file baru di VSCode dengan ekstensi `.php` di folder yang sudah anda buka
Berikut adalah beberapa konsep dasar dalam PHP:
# Echo
## Kutip satu
kutip satu hanya bisa membaca teks atau STRING, variabel dan string
dipisahkan dengan tanda titik
## Kutip dua
kutip dua bisa membaca nilai dari variabel
# Komentar
## Single line
php
//ini komentar 1 baris menggunakan dua slice

## Multiple line
php
/*
ini
komentar
multibaris
menggunakan satu slice dan bintang
*/

# Variabel & Konstanta

# Apa itu web dinamis dan PHP?

>[!WEB DINAMIS]
>Web dinamis adalah jenis situs web yang dapat menghasilkan konten yang berubah atau disesuaikan secara dinamis berdasarkan permintaan pengguna. Konten dinamis dapat dihasilkan melalui interaksi dengan pengguna, pengambilan data dari basis data, integrasi dengan layanan eksternal, dan pemrosesan logika bisnis. Web dinamis menggunakan bahasa pemrograman server-side untuk menghasilkan dan mengelola konten dinamis ini.

>[!PHP]
>PHP (PHP: Hypertext Preprocessor) adalah salah satu bahasa pemrograman yang sering digunakan untuk mengembangkan web dinamis. PHP adalah bahasa pemrograman sisi server yang dirancang khusus untuk pengembangan web. Itu dapat diintegrasikan dengan HTML untuk menghasilkan konten dinamis. PHP berjalan di sisi server, yang berarti kode PHP dieksekusi di server web sebelum hasilnya dikirim ke browser pengguna.
# Program pertama PHP
## Cara 
1. Buka XAMPP, kemudian klik tombol start pada 'apache'
2. Open file manager
3. Open di Drive D
4. Kemudian Open folder XAMPP
5. Lalu open folder htdocs
6. Buat folder baru di dalam htdocs 
7. Lalu open folder yang sudah Anda buat
8. Open VSCode
9. Open folder yang sudah Anda buat di VSCode
10. Buat file baru di VSCode dengan ekstensi .php di folder yang sudah Anda buka

# Echo & commentar
## Echo
1. Penggunaan Dasar:
   - echo adalah perintah dasar dalam PHP yang digunakan untuk menampilkan teks atau nilai pada halaman web.
   - Anda dapat menggunakan echo untuk menampilkan teks statis atau untuk menampilkan nilai dari variabel atau ekspresi.
   - echo dapat menerima satu atau lebih argumen yang dipisahkan oleh tanda titik (.) untuk menggabungkan teks dan variabel.

2. Menampilkan Teks:
   - Anda dapat menggunakan echo untuk langsung menampilkan teks statis dalam tanda kutip ganda ("") atau tanda kutip tunggal ('').
   - Contoh: echo "Halo, dunia!";

3. Menampilkan Nilai Variabel:
   - Anda dapat menggunakan echo untuk menampilkan nilai dari variabel dalam teks yang ditampilkan.
   - Gunakan operator konkatenasi (tanda titik) untuk menggabungkan teks dan variabel.
   - Contoh: 
     php
     $nama = "John Doe";
     echo "Halo, nama saya " . $nama . ".";
     

4. Menampilkan HTML:
   - Selain teks, Anda juga dapat menggunakan echo untuk menampilkan kode HTML di dalam skrip PHP.
   - Uji coba berikut menunjukkan penggunaan echo untuk menampilkan elemen HTML:
     php
     echo "<h1>Selamat Datang!</h1>";
     echo "<p>Ini adalah halaman web PHP.</p>";
     

5. Penggunaan Kutipan:
   - Anda dapat menggunakan tanda kutip ganda ("") atau tanda kutip tunggal ('') untuk mengelilingi teks dalam echo.
   - Misalnya, echo "Halo, nama saya 'John'.";

6. Menggunakan Pemisah:
   - Saat menggunakan echo dengan beberapa argumen, Anda dapat menggunakan koma (,) sebagai pemisah antara argumen.
   - Contoh: echo "Halo,", " nama saya ", $nama, ".";

Materi echo pada PHP memungkinkan Anda untuk menampilkan teks, nilai variabel, dan bahkan kode HTML di dalam skrip PHP. Hal ini berguna dalam menghasilkan tampilan dinamis pada halaman web yang sedang Anda bangun.

## Struktur dasar echo
1. <?php dan ?>: Adalah penanda awal dan akhir dari blok kode PHP. Semua kode PHP harus berada di antara penanda ini agar dapat dieksekusi dengan benar.
2. echo: Adalah perintah dalam PHP yang digunakan untuk menampilkan teks atau nilai ke dalam halaman web.
3. teks atau nilai yang ingin ditampilkan: Adalah bagian di mana Anda memasukkan teks statis, nilai variabel, atau ekspresi matematika yang ingin ditampilkan di halaman web.

Jadi, ketika kode tersebut dieksekusi, teks atau nilai yang ditentukan akan ditampilkan di halaman web sebagai hasil dari perintah echo.
Kode program
php
<?php
    echo "Halo, dunia!";
?>


Hasil:

Halo, dunia!

## Commentar
Dalam PHP, komentar digunakan untuk memberikan penjelasan, catatan, atau dokumentasi di dalam kode program. Komentar tidak akan dieksekusi oleh interpreter PHP, sehingga komentar tidak akan mempengaruhi hasil program.
Berikut adalah beberapa hal yang perlu diketahui tentang komentar dalam PHP:
1. Komentar Satu Baris:
   - Komentar satu baris dimulai dengan tanda // atau #.
   - Semua teks setelah tanda tersebut hingga akhir baris diabaikan oleh interpreter PHP.
   - Contoh:
     php
     // Ini adalah komentar satu baris
     $nama = "John Doe"; // Ini adalah komentar di samping kode
     
2. Komentar Multibaris:
   - Komentar multibaris dimulai dengan /* dan diakhiri dengan */.
   - Semua teks di antara tanda tersebut diabaikan oleh interpreter PHP.
   - Komentar multibaris dapat mencakup beberapa baris kode.
   - Contoh:
     php
     /*
         Ini adalah komentar multibaris.
         Ini dapat mencakup beberapa baris kode.
     */
     $umur = 25;
     
3. Komentar Dokumentasi:
   - Komentar dokumen atau DocBlock digunakan untuk memberikan dokumentasi formal pada fungsi, kelas, atau metode.
   - Komentar dokumen dimulai dengan /** dan diakhiri dengan */.
   - Komentar ini sering digunakan dengan format khusus seperti PHPDoc untuk menghasilkan dokumentasi otomatis.
   - Contoh:
php
     /**
      * Fungsi ini menghitung jumlah dua angka.
      *
      * @param int $a Angka pertama
      * @param int $b Angka kedua
      * @return int Hasil penjumlahan
      */
     function tambah($a, $b) {
         return $a + $b;
     }
     
4. Tujuan Penggunaan Komentar:
   - Memberikan penjelasan tentang tujuan dan fungsionalitas kode.
   - Membantu dalam pemeliharaan dan pemahaman kode untuk pengembang dan anggota tim lainnya.
   - Menyembunyikan atau menonaktifkan sebagian kode untuk uji coba atau sementara.
   - Meninggalkan catatan atau pesan kepada diri sendiri atau pengembang lain tentang kode tertentu.
Penggunaan komentar yang baik sangat penting dalam pemrograman untuk menjaga kejelasan dan keberlanjutan kode. Dengan menggunakan komentar yang tepat, Anda dapat meningkatkan kemudahan pemeliharaan dan kolaborasi dalam pengembangan perangkat lunak.
# Variable, const, operator
## Variable
Variabel pada PHP merupakan suatu wadah atau tempat untuk menyimpan data. Variabel digunakan untuk menyimpan nilai-nilai yang akan digunakan dalam program PHP. Anda dapat memberikan nama pada variabel untuk mengidentifikasinya, dan kemudian menggunakan nama tersebut untuk mengakses nilai yang disimpan di dalamnya.

Dalam PHP, variabel bersifat dinamis, yang berarti Anda tidak perlu mendeklarasikan tipe data variabel sebelum menggunakannya. PHP akan secara otomatis menentukan tipe data variabel berdasarkan nilai yang Anda berikan.

Simbol $ pada PHP digunakan untuk menandakan sebuah variabel. Dalam PHP, setiap kali Anda ingin membuat, mengakses, atau memanipulasi nilai variabel, Anda perlu menggunakan simbol `$`diikuti dengan nama variabelnya.

Contoh penggunaan variabel pada PHP:
php
$nama = "John Doe"; // Variabel $nama dengan nilai "John Doe"
$umur = 25; // Variabel $umur dengan nilai 25
$gaji = 2500.50; // Variabel $gaji dengan nilai 2500.50
$isActive = true; // Variabel $isActive dengan nilai true


## Const
Dalam PHP, const adalah kata kunci yang digunakan untuk mendefinisikan konstanta. Konstanta adalah nilai yang tidak dapat diubah selama eksekusi program. Setelah konstanta didefinisikan, nilainya tidak dapat diubah atau dilakukan penugasan ulang.
-  Konstanta didefinisikan menggunakan kata kunci const diikuti dengan nama konstanta dan nilainya.
- Nama konstanta biasanya ditulis dalam huruf besar (uppercase) untuk membedakan dengan variabel biasa.
- Nilai konstanta dapat berupa bilangan, string, boolean, atau ekspresi konstan lainnya.
Contoh:
php
	const PI = 3.14;
    const NAMA_SITUS = "Website ABC";
    const STATUS_AKTIF = true;

## Operator
Operator dalam PHP adalah simbol atau tanda yang digunakan untuk melakukan operasi atau manipulasi pada nilai atau variabel. Operator memungkinkan Anda untuk melakukan perhitungan matematika, perbandingan, penggabungan teks, dan operasi logika dalam program PHP. 
Berikut ini beberapa jenis operator yang tersedia dalam PHP:
1. Operator Aritmatika:
   - Operator aritmatika digunakan untuk melakukan operasi matematika seperti penjumlahan, pengurangan, perkalian, pembagian, modulus, dan sebagainya.
   - Contoh:
     php
     $a = 10;
     $b = 5;
     $c = $a + $b; // Penjumlahan
     $d = $a - $b; // Pengurangan
     $e = $a * $b; // Perkalian
     $f = $a / $b; // Pembagian
     $g = $a % $b; // Modulus (sisa pembagian)
     
2. Operator Penugasan:
   - Operator penugasan digunakan untuk memberikan nilai ke variabel.
   - Contoh:
     php
     $a = 10; // Penugasan nilai 10 ke variabel $a
     $b += 5; // Penugasan nilai $b + 5 ke variabel $b (sama dengan $b = $b + 5)
     
3. Operator Perbandingan:
   - Operator pembanding digunakan untuk membandingkan dua nilai dan menghasilkan nilai kebenaran (true atau false).
   - Contoh:
     php
     $a = 10;
     $b = 5;
     $c = $a == $b; // Sama dengan
     $d = $a != $b; // Tidak sama dengan
     $e = $a > $b; // Lebih besar dari
     $f = $a < $b; // Lebih kecil dari
     $g = $a >= $b; // Lebih besar dari atau sama dengan
     $h = $a <= $b; // Lebih kecil dari atau sama dengan
     
4. Operator Logika:
   - Operator logika digunakan untuk menggabungkan atau memanipulasi nilai kebenaran (true atau false).
   - Contoh:
     php
     $a = true;
     $b = false;
     $c = $a && $b; // Logika AND
     $d = $a || $b; // Logika OR
     $e = !$a; // Logika NOT
     
5. Operator String:
   - Operator string digunakan untuk menggabungkan atau memanipulasi teks.
   - Contoh:
     php
     $a = "Hello, ";
     $b = "World!";
     $c = $a . $b; // Penggabungan teks
     
6. Operator Lainnya:
   - Selain operator-operator di atas, PHP juga memiliki operator lain seperti operator increment (++) dan decrement (--), operator ternary (?:), operator array, dan lain-lain.

Operator dalam PHP memungkinkan Anda untuk melakukan berbagai operasi dan manipulasi pada data, dan memungkinkan logika dan fungsionalitas yang lebih kompleks dalam program Anda. Dalam pengembangan PHP, pemahaman tentang operator sangat penting untuk membuat kode yang efisien dan efektif.
```php
<?php

//komentar 1 baris menggunakan dua slice
/*
ini
komentar
multibaris
menggunakan satu slice dan bintang
*/

//variabel
$meja = 30;
$tk_kelas = "XI";
$ketua_kelas = "Juli";
$wali_kelas = "Saleh";
$ketua_gank = "bombom";
$ketua_gank = "Rahmat"; //pengubahan nilai variabel

//konstanta
const KepSek = "Herwelis";
define('kelas', 'RPL 1');

//echo berfungsi untuk menampilkan
/*kutip satu hanya bisa membaca teks atau STRING, variabel dan string
dipisahkan dengan tanda titik
*/
echo 'jumlah meja di kelas : ' . $meja . ' buah';
echo "<br>";

//kutip dua bisa membaca nilai dari variabel 
echo "Sholat gess, nabilang Pak $wali_kelas dan $ketua_kelas";
echo "<br>";


//kutip satu pada kata diracca', dibaca string disini
echo "Klo tidak, diracca' sama ketua gank $ketua_gank";
echo "<br>";
echo 'KepSeknya Pak ' . KepSek;
echo "<br>";
echo 'Kelasnya ' . $tk_kelas . ' ' . kelas;
?>
```
### Hasil
![](asetPHP/16.png)
# Coditional Statement

## IF
Pernyataan if digunakan untuk mengevaluasi sebuah kondisi dan menjalankan blok kode jika kondisi tersebut benar. Jika kondisi yang dievaluasi adalah salah, maka blok kode tersebut tidak akan dijalankan.
### Program
```php
<?php
$umur = 17;
if ($umur >= 20) {
    echo "Anda sudah dewasa";
}
?>

```

### Hasil
![](asetPHP/32.png)
### Penjelasan
Program ini mengevaluasi variabel $umur dan mencetak pesan "Anda sudah dewasa" jika umur lebih besar atau sama dengan 20.
### Analisis
Karena nilai variabel $umur adalah 17, kondisi if tidak terpenuhi, sehingga pesan tidak dicetak.
## IF-ELSE
### Program

```php
<?php
$umur = 17;
if ($umur >= 20) {
    echo "Anda sudah dewasa";
} else {
    echo "Anda masih di bawah umur";
}
?>
```

### Hasil

![](asetPHP/32.png)
### Penjelasan
Program ini mengevaluasi variabel $umur dan mencetak pesan "Anda sudah dewasa" jika umur lebih besar atau sama dengan 20. Jika umur kurang dari 20, pesan "Anda masih di bawah umur" akan dicetak.
### Analisis
Karena nilai variabel $umur adalah 17, maka blok kode di dalam else yang mencetak "Anda masih di bawah umur" akan dieksekusi.
## IF-ELSE IF-ELSE
### Program
```php
<?php
$nilai = 85;
if ($nilai >= 90) {
    echo "Nilai Anda A";
} elseif ($nilai >= 80) {
    echo "Nilai Anda B";
} elseif ($nilai >= 70) {
    echo "Nilai Anda C";
} else {
    echo "Nilai Anda D";
}
?>
```

### Hasil
![](asetPHP/31.png)
### Penjelasan
Program ini mengevaluasi variabel $nilai dan mencetak grade berdasarkan rentang nilai. Misalnya, jika nilai lebih dari atau sama dengan 90, maka grade A dicetak.

### Analisis
Karena nilai variabel $nilai adalah 85, maka blok kode yang dicetak adalah "Nilai Anda B", karena nilai tersebut memenuhi kondisi kedua.
## SWITCH-CASE
### Program
```php
<?php
$warna = "merah";
switch ($warna) {
    case "merah":
        echo "Warna favorit Anda adalah merah";
        break;
    case "biru":
        echo "Warna favorit Anda adalah biru";
        break;
    default:
        echo "Warna favorit Anda bukan merah atau biru";
}
?>
```

### Hasil

![](asetPHP/33.png)
### Penjelasan
Program ini mengevaluasi variabel $warna dan mencetak pesan berdasarkan nilai $warna. Dalam kasus ini, karena nilai $warna adalah "biru", maka pesan "Warna favorit Anda adalah biru" akan dicetak.

### Analisis
Karena nilai variabel $warna adalah "biru", maka blok kode yang dicetak adalah "Warna favorit Anda adalah biru".
# Array

## Array 1 Dinamis
### Program
```php
<?php
$buah = array("Alpukat", "Durian", "Apel");
foreach ($buah as $item) {
    echo $item . "<br>";
}
?>

```

### Hasil

![](asetPHP/30.png)
### Penjelasan
Program ini membuat sebuah array dinamis dengan isi "apel", "pisang", dan "jeruk". Kemudian menggunakan loop foreach untuk menampilkan setiap nilai dalam array.
## Array Asosiatif
```php
<?php
$umur = array("Hasiza" => 17, "Dilla" => 16 , "Doe" => 35);
echo "Umur Hasiza: " . $umur['Hasiza'];
?>
```

### Hasil

![](asetPHP/29.png)
### Penjelasan
Program ini membuat sebuah array asosiatif dengan nama sebagai kunci dan umur sebagai nilainya. Kemudian mencetak umur John dengan menggunakan kunci 'John'.
## Array Multidimensi
### Program
```php
<?php
$Siswa = array(
    array("Hasiza", 17, "RPL"),
    array("Dilla", 16, "Perkantoran"),
    array("Specky",15, "RPL")
);
echo "Nama: " . $Siswa[0][0] . ", Umur: " . $Siswa[0][1] . ", Jurusan: " . $Siswa[0][2];
?>
```

### Hasil

![](asetPHP/28.png)
### Penjelasan
Program ini membuat sebuah array multidimensi yang menampung data mahasiswa. Setiap elemen dalam array adalah array sendiri yang berisi nama, umur, dan jurusan mahasiswa. Kemudian mencetak detail mahasiswa pertama.
# Var-Dump
## Penjelasan 
```php
<?php
$variabel = "Siti Nur Hasiza.A";
var_dump($variabel);
?>
```
## Struktur 
```php
<?php
$variabel = "contoh";
var_dump($variabel);
?>

```
## Program 
```php
<?php
$umur = 17;
$nama = "Hasiza";
$nilai = array(80, 85, 90);
var_dump($umur, $nama, $nilai);
?>
```
## Hasil

![](asetPHP/27.png)
## Analisis
Fungsi var_dump sangat berguna dalam debugging karena memberikan informasi rinci tentang variabel. Dengan melihat hasilnya, kita dapat memahami tipe data dan nilai variabel dengan lebih baik.
## Kesimpulan Program 
Dengan menggunakan var_dump, pengembang dapat mengeksplorasi struktur data dalam variabel dan mengidentifikasi masalah atau kesalahan dalam kode dengan lebih efektif.
# Looping(Perulangan)
## FOR
### Program
```php
<?php
for ($i = 0; $i < 5; $i++) {
    echo $i . "<br>";
}
?>
```

### Hasil

![](asetPHP/26.png)
### Penjelasan
Program ini menggunakan loop for untuk mencetak angka dari 0 hingga 4.
### Analisis
Loop for adalah cara yang efisien untuk melakukan iterasi berulang dengan jumlah iterasi yang sudah diketahui sebelumnya.
### Kesimpulan
Loop for sangat berguna dalam situasi di mana kita perlu melakukan iterasi sejumlah tertentu.
## While
### Program
```php
<?php
$i = 0;
while ($i < 5) {
    echo $i . "<br>";
    $i++;
}
?>
```

### Hasil

![](asetPHP/25.png)
### Penjelasan
Program ini menggunakan loop while untuk mencetak angka dari 0 hingga 4.
### Analisis
Loop while berguna ketika kita perlu melakukan iterasi berdasarkan kondisi tertentu.
### Kesimpulan
Loop while dapat digunakan untuk melakukan iterasi selama kondisi tertentu terpenuhi.
## Do-While
### Program
```php
<?php
$i = 0;
do {
    echo $i . "<br>";
    $i++;
} while ($i < 5);
?>
```

### Hasil

![](asetPHP/25.png)
### Penjelasan
Program ini menggunakan loop do-while untuk mencetak angka dari 0 hingga 4.
### Analisis
Loop do-while berguna ketika kita ingin menjalankan blok kode setidaknya sekali sebelum mengevaluasi kondisi.
### Kesimpulan
Loop do-while berguna dalam situasi di mana kita perlu menjalankan blok kode minimal satu kali.
## Foreach
### Program
```php
<?php
$buah = array("Alpukat", "Durian", "Apel");
foreach ($buah as $item) {
    echo $item . "<br>";
}
?>

```

### Hasil

![](asetPHP/30.png)
### Penjelasan
Program ini menggunakan loop foreach untuk mencetak setiap nilai dalam array buah.
### Analisis
Loop foreach sangat berguna ketika kita perlu melakukan iterasi melalui setiap elemen dalam array atau objek.
### Kesimpulan
Loop foreach memudahkan kita dalam melakukan iterasi melalui array atau objek tanpa perlu mengkhawatirkan indeks atau kunci.
# FUNCTION

## Penjelasan

Fungsi di PHP adalah blok kode yang dapat digunakan kembali untuk melakukan tugas-tugas tertentu. Fungsi dapat menerima parameter (input) dan dapat mengembalikan nilai (output).

## Struktur

```php

function namaFungsi($parameter1, $parameter2, ...) {

    // Blok kode yang akan dieksekusi

    // Dapat berisi berbagai jenis pernyataan (statement)

    return nilai_yang_dikembalikan;

}

```

### Program

```php

<?php

  

function tambah($a, $b) {

  

    $hasil = $a + $b;

  

    return $hasil;

  

}

  

  

$angka1 = 5;

  

$angka2 = 3;

  

$hasil_penjumlahan = tambah($angka1, $angka2);

  

  

echo "Hasil penjumlahan: " . $hasil_penjumlahan;

  

  

?>

```

## Hasil

![](asetPHP/c.png)

## Analisis

1. Program ini mendefinisikan sebuah fungsi bernama `tambah()` yang menerima dua parameter `$a` dan `$b`.

2. Dalam fungsi `tambah()`, variabel `$hasil` akan menyimpan hasil penjumlahan antara `$a` dan `$b`.

3. Fungsi `tambah()` mengembalikan nilai yang disimpan dalam `$hasil`.

4. Di luar fungsi `tambah()`, program mendeklarasikan dua variabel `$angka1` dan `$angka2` dengan nilai 5 dan 3.

5. Program memanggil fungsi `tambah()` dengan argumen `$angka1` dan `$angka2`, dan menyimpan hasilnya dalam variabel `$hasil_penjumlahan`.

6. Akhirnya, program mencetak pesan "Hasil penjumlahan: " diikuti dengan nilai yang tersimpan dalam `$hasil_penjumlahan`.

## Kesimpulan

1. Program ini mengdemonstrasikan penggunaan fungsi dalam PHP untuk melakukan operasi penjumlahan.

2. Fungsi `tambah()` bertindak sebagai sebuah modul yang dapat digunakan kembali untuk melakukan penjumlahan antara dua angka.

3. Penggunaan fungsi memungkinkan program menjadi lebih modular, reusable, dan mudah dibaca dan dipelihara.

4. Pemanggilan fungsi `tambah()` dengan argumen `$angka1` dan `$angka2` menunjukkan fleksibilitas fungsi, di mana Anda dapat memanggil fungsi dengan nilai yang berbeda setiap kali.

5. Secara keseluruhan, program ini mendemonstrasikan pemahaman dasar tentang fungsi dalam pemrograman PHP, yang merupakan konsep penting bagi pelajar kelas 11 SMK jurusan RPL.

# PHP Form

## GET Method

#### Penjelasan

Metode GET adalah salah satu cara untuk mengirimkan data dari sisi klien (browser) ke sisi server (PHP) melalui URL. Data yang dikirimkan melalui metode GET akan terlihat dalam URL.

### Program

FORM

```PHP

<!DOCTYPE html>

  

<html lang="en">

  

  

<head>

  

    <title>Document</title>

  

</head>

  

  

<body>

  

    <!-- Pada atribut action, kalian tuliskan nama file php yang bertugas untuk mengelola atau menangkap data dari form tersebut. -->

  

    <form action="proses_get.php" method="GET">

  

        <input type="text" name="nama_lengkap" placeholder="Masukkan nama">

  

        <input type="number" name="umur" placeholder="Masukkan umur"> <br>

  

        <button type="submit">Kirim</button>

  

    </form>

  

</body>

  

  

</html>

```

PROSES

```PHP

<?php

  

// Key dari array-nya, sesuai dengan nama dari atribut name di setiap input-nya

  

$nama = $_GET["nama_lengkap"];

  

$umur = $_GET["umur"];

  

?>

  

  

<!DOCTYPE html>

  

<html lang="en">

  

  

<head>

  

    <meta charset="UTF-8">

  

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

  

    <title>XI RPL 1 - GET</title>

  

</head>

  

  

<body>

  

    <p>Nama anda

  

        <!-- Ini adalah versi singkatnya dari php echo,

  

             yang fungsinya untuk menampilkan data -->

  

        <?= $nama ?>

  

    </p>

  

    <p>Umur anda <?= $umur ?> tahun</p>

  

</body>

  

  

</html>

```

### Hasil
![](asetPHP/14.png)

![](asetPHP/13.png)

## POST Method

### Penjelasan

Metode POST adalah salah satu cara untuk mengirimkan data dari sisi klien (browser) ke sisi server (PHP) melalui body request HTTP. Data yang dikirimkan melalui metode POST tidak akan terlihat dalam URL.

#### Program

FORM

```PHP

<!DOCTYPE html>

  

<html lang="en">

  

  

<head>

  

    <title>Document</title>

  

</head>

  

  

<body>

  

    <!-- Pada atribut action, kalian tuliskan nama file php yang bertugas untuk mengelola atau menangkap data dari form tersebut. -->

  

    <form action="proses_post.php" method="POST">

  

        <input type="text" name="nama_lengkap" placeholder="Masukkan nama">

  

        <input type="number" name="umur" placeholder="Masukkan umur">

  

        <input type="password" name="password" placeholder="Masukkan password"><br>

  

        <button type="submit">Kirim</button>

  

    </form>

  

</body>

  

  

</html>

```

PROSES

```PHP

<?php

  

// Key dari array-nya, sesuai dengan nama dari atribut name di setiap input-nya

  

//$nama = $_GET["nama"];

  

$umur = $_POST["umur"];

  

  

var_dump($_POST);

  

  

?>

  

  

<!DOCTYPE html>

  

<html lang="en">

  

  

<head>

  

    <title> XI RPL 1 - POST</title>

  

</head>

  

  

<body>

  

    <p>Nama anda <?= $_POST["nama_lengkap"] ?></p>

  

    <p>Umur anda <?= $umur ?> tahun</p>

  

    <p>Password anda aman!</p>

  

</body>

  

  

</html>

```

### Hasil

![](asetPHP/12.png)

![](asetPHP/11.png)

# Koneksi Database
## Program
```php
<?php

//koneksi ke database

$koneksi = mysqli_connect('localhost', 'root', '', 'rental_hasiza');

if ($koneksi) {

    echo "<br> koneksi aman <br>";

} else {

    echo "error, tidak bisa koneksi ke database";

}

?>
```
## Hasil

![](asetPHP/20.png)
## Analisis

1. Kode ini melakukan koneksi ke database menggunakan fungsi `mysqli_connect()`.
2. Fungsi `mysqli_connect()` membutuhkan empat parameter: hostname, username, password, dan nama database.
3. Jika koneksi berhasil, variabel `$koneksi` akan menyimpan objek koneksi.
4. Setelah koneksi, kode melakukan pengecekan apakah koneksi berhasil atau tidak.
5. Jika koneksi berhasil, kode akan menampilkan pesan "koneksi aman".
6. Jika terjadi error saat koneksi, kode akan menampilkan pesan "error, tidak bisa koneksi ke database".
## Kesimpulan
Kode di atas merupakan dasar untuk melakukan koneksi ke database menggunakan PHP. Hal ini sangat penting dalam pengembangan aplikasi berbasis web, karena aplikasi biasanya membutuhkan akses ke database untuk menyimpan dan mengambil data.

# Tampilkan Data
## Program

```php

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>index tabel</title>
</head>
<body>
    <h2>Data Siswa XI RPL 1</h2>
    <table border="5">
    <tr>
        <th>id_siswa</th>
        <th>Gambar</th>
        <th>nama</th>
        <th>email</th>
        <th>jenis_kelamin</th>
        <th>alamat</th>
        <th>Aksi</th>
    </tr>
<?php
    include "koneksi.php";
    $i = 1;
    $query = mysqli_query($koneksi, "SELECT * FROM siswa");
    while ($data = mysqli_fetch_array($query)) {
    ?>
    <tr>
        <td><?php echo $i; ?></td>
        <td>
            <img src="img/<?= $data['gambar'] ?>" alt="gambar" width="100px">
        </td>
        <td><?php echo $data['nama']; ?></td>
        <td><?php echo $data['email']; ?></td>
        <td><?php echo $data['jenis_kelamin']; ?></td>
        <td><?php echo $data['alamat']; ?></td>
        <td>
            <a href="ubah.php?id=<?= $data['id_siswa']; ?>">Ubah</a> |
            <a href="hapus.php?id=<?= $data['id_siswa']; ?>">Hapus</a> |
        </td>
    </tr>
<?php
    $i++;
    }
?>
    </table>
</body>
</html>
```

## Hasil

![](asetPHP/a3.jpeg)

## Analisis

1. Kode program ini adalah sebuah halaman web HTML yang menampilkan data siswa dari sebuah database.

2. Halaman ini memiliki judul "Data Siswa XI RPL 1".

3. Tabel yang ditampilkan memiliki 7 kolom: id_siswa, Gambar, nama, email, jenis_kelamin, alamat, dan Aksi.

4. Kode PHP di bagian bawah digunakan untuk mengambil data dari database dan menampilkannya dalam tabel.

5. Proses koneksi ke database dilakukan melalui file "koneksi.php" yang di-include.

6. Setiap baris data siswa ditampilkan dalam satu baris tabel, dengan masing-masing kolom menampilkan data terkait.

7. Pada kolom "Aksi", terdapat dua link: "Ubah" dan "Hapus" yang mengarah ke halaman lain.

## Kesimpulan

1. Kode program ini merupakan sebuah halaman web yang menampilkan data siswa dari database dalam bentuk tabel.

2. Halaman ini dapat digunakan untuk melihat, mengubah, dan menghapus data siswa.

3. Kode ini menggunakan PHP untuk mengambil data dari database dan menampilkannya dalam tabel HTML.

4. Fitur "Ubah" dan "Hapus" memberikan kemampuan untuk melakukan operasi CRUD (Create, Read, Update, Delete) pada data siswa.

  

# Tambahkan Data

## Program

```php

<!DOCTYPE html>
<html lang="en">
<head>
    <title>Document</title>
</head>
<body>
    <h2>Tambah Data</h2>
    
<?php
    
    include "koneksi.php";
    function upload(): string
{

    $nameImage = $_FILES['gambar']['name'];
    $directoryFile = $_FILES['gambar']['tmp_name'];
    $errorImage = intval($_FILES['gambar']['error']);
    $sizeFile = $_FILES['gambar']['size'];
    
    // cek apakah gambar ada
    if ($errorImage === 4) {
        echo "<script>alert('Anda Belum Upload Gambar')</script>";
        return false;
    }
    
    // mengambil ekstensi file
    
    $validType = ['svg', 'jpg', 'png', 'jpeg', 'webp'];
    $extensionFile = explode(".", $nameImage);
    $extensionValid = strtolower(end($extensionFile));
    
    // cek apakah yang diupload gambar atau bukan
    
    if (!in_array($extensionValid, $validType)) {
        echo "<script>alert('yang anda Upload bukan gambar')</script>";
        return false;
    }
    
    // cek size file
    
    if ($sizeFile > 3_000_000) {
        echo "<script>alert('Ukuran File Terlalu Besar!!(Maks 3MB)')</script>";
        return false;
    }
    
    // upload file
    
    $nameImage = uniqid() . "." . $extensionValid;
    move_uploaded_file($directoryFile, "img/{$nameImage}");
    // mengembalikan namafile yg sudah divalidasi
    
    return $nameImage;
}

    if (isset($_POST['simpan'])) {
        $nama = $_POST['nama'];
        $email = $_POST['email'];
        $jenis_kelamin = $_POST['jenis_kelamin'];
        $alamat = $_POST['alamat'];
        $gambar = upload();
        if (!$gambar) {
            return false;
        }
        
        // * true / false
        
        $query = mysqli_query($koneksi, "INSERT into
        siswa(nama,email,jenis_kelamin,alamat,gambar)
        values ('$nama','$email','$jenis_kelamin','$alamat','$gambar')");
        if ($query == true) {
            echo "<script>
            alert('Tambah data Berhasil')
            window.location.href='table.php'
            </script>";
        } else {
            echo '<script>alert("Tambah data gagal")</script>';
        }
    }
    ?>
    <form method="post" enctype="multipart/form-data">
        <table>
            <tr>
                <td>Nama</td>
                <td><input type="text" name="nama"></td>
            </tr>
            <tr>
                <td>Email</td>
                <td><input type="text" name="email"></td>
            </tr>
            <tr>
                <td>Jenis Kelamin</td>
                <td>>
                    <select name="jenis_kelamin">
                        <option>Laki-laki</option>
                        <option>Perempuan</option>
                    </select>
                </td>
            </tr>
            <tr>
                <td>Alamat</td>
                <td><input type="text" name="alamat"></td>
            </tr>
            <tr>
                <td>Gambar</td>
                <td><input type="file" name="gambar"></td>
            </tr>
            <tr>
                <td></td>
                <td>
                    <button name="simpan" type="submit">Simpan</button>
                    <button type="reset">Reset</button>
                    <a href="table.php">Kembali</a>
                </td>
            </tr>
        </table>
    </form>
</body>
</html>

```

## Hasil

![](asetPHP/php3.png)

![](asetPHP/a2.jpeg)

  

## Analisis

- Kode program ini adalah sebuah halaman web yang digunakan untuk menambah data siswa ke dalam database.

- Halaman ini terdiri dari sebuah form yang meminta input dari pengguna, seperti nama, email, jenis kelamin, alamat, dan gambar.

- Saat pengguna mengisi form dan menekan tombol "Simpan", kode PHP akan melakukan beberapa langkah:

    - Memeriksa apakah ada file gambar yang diupload.

    - Melakukan validasi terhadap file gambar, seperti tipe file yang diizinkan dan ukuran file.

    - Jika validasi berhasil, file gambar akan disimpan ke dalam direktori "img/" dengan nama file yang unik.

    - Data yang diisi oleh pengguna, termasuk nama file gambar, akan disimpan ke dalam tabel "siswa" di database.

- Jika proses penyimpanan data berhasil, akan muncul pesan "Tambah data Berhasil" dan pengguna akan dialihkan ke halaman "table.php".

- Jika terjadi kesalahan, akan muncul pesan "Tambah data gagal".

## Kesimpulan

- Kode program ini berfungsi untuk menyediakan antarmuka bagi pengguna (dalam hal ini siswa) untuk menambahkan data diri mereka ke dalam database.

- Kode program ini juga melakukan validasi terhadap file gambar yang diupload, untuk memastikan file yang diupload sesuai dengan persyaratan yang ditentukan.

- Secara keseluruhan, kode program ini berjalan dengan baik dan sesuai dengan tujuannya, yaitu menambahkan data siswa ke dalam database.

# Ubah Data

## Program

  

```php

<!DOCTYPE html>
<html lang="en">
<head>
    <title>Document</title>
</head>
<body>
    <h2>Ubah Data</h2>
  
<?php
    include "koneksi.php";
    $id = $_GET['id'];
    if (isset($_POST['simpan'])) {
        $nama = $_POST['nama'];
        $email = $_POST['email'];
        $jenis_kelamin = $_POST['jenis_kelamin']; 
        $alamat = $_POST['alamat'];
        $query = mysqli_query($koneksi, "UPDATE siswa SET
                                        nama='$nama',
                                        email='$email',
                                        jenis_kelamin='$jenis_kelamin',
                                        alamat='$alamat'
                                        WHERE id_siswa=$id");
        if ($query) {
            echo "<script>
            alert('ubah data Berhasil')
            window.location.href='table.php'
            </script>";
        } else {
            echo '<script>alert("ubah data gagal")</script>';
        }

    }


    $query = mysqli_query($koneksi, "SELECT * FROM siswa where id_siswa=$id");
    $data = mysqli_fetch_array($query);

    if ($data == "") {
        die('Data tidak ada');
    }
    ?>
    <form method="post">
        <table>
            <tr>
                <td>Nama</td>
                <td><input type="text" value="<?= $data['nama'] ?>" name="nama"></td>
            </tr>
            <tr>
                <td>Email</td>
                <td><input type="text" value="<?= $data['email'] ?>" name="email"></td>
                
            </tr>
            <tr>
                <td>Jenis Kelamin</td>
                <td>>
                    <select name="jenis_kelamin">
                        <option <?php if ($data['jenis_kelamin'] == "laki-laki")
                            echo 'selected'; ?>>Laki-laki</option>
                        <option <?php if ($data['jenis_kelamin'] == "perempuan")
                            echo 'selected'; ?>>Perempuan</option>
                    </select>
                </td>
            </tr>
            <tr>
                <td>Alamat</td>
                <td><input type="text" value="<?= $data['alamat'] ?>" name="alamat"></td>

            </tr>
            <tr>
                <td></td>
                <td>
                    <button name="simpan" type="submit">Ubah</button>
                    <button type="reset">Reset</button>
                    <a href="table.php">Kembali</a>
                </td>
            </tr>
        </table>
    </form>
</body>
</html>

```

## Hasil

![](asetPHP/a4.jpeg)

![](asetPHP/a1.jpeg)

  

## Analisis

1. Kode program ini merupakan halaman untuk mengubah data siswa yang disimpan dalam database.

2. Pada bagian awal, kode melakukan koneksi ke database menggunakan file "koneksi.php".

3. Variabel `$id` diambil dari parameter `GET` pada URL, yang menunjukkan ID siswa yang akan diubah.

4. Jika tombol "Ubah" (`name="simpan"`) ditekan, maka data baru yang dimasukkan ke dalam form akan digunakan untuk memperbarui data siswa di database dengan query `UPDATE`.

5. Jika proses pembaruan berhasil, maka akan muncul pesan "ubah data Berhasil" dan pengguna akan diarahkan ke halaman "table.php".

6. Jika proses pembaruan gagal, maka akan muncul pesan "ubah data gagal".

7. Pada akhir kode, data siswa yang akan diubah diambil dari database dan ditampilkan dalam form.

## Kesimpulan

Kode program ini merupakan halaman untuk mengubah data siswa yang disimpan dalam database. Pengguna dapat mengisi form dengan data baru dan menyimpannya ke dalam database. Jika proses pembaruan berhasil, maka pengguna akan diarahkan ke halaman "table.php". Jika proses pembaruan gagal, maka akan muncul pesan kesalahan.

  

# Hapus Data

## Program

```php

<?php

include('koneksi.php');
if(isset($_GET['id'])){

    $id = $_GET['id'];
    $query = mysqli_query($koneksi, "DELETE FROM siswa WHERE id_siswa = $id");


   if($query) {
            echo "<script>
            alert('Hapus data Berhasil')
            window.location.href='table.php'
            </script>";
        }else {
            echo '<script>alert("Hapus data gagal")</script>';

        }
}

?>

```

## Hasil

![](asetPHP/php7.png)

## Analisis

1. Kode program ini merupakan halaman untuk menghapus data siswa yang disimpan dalam database.

2. Pada bagian awal, kode melakukan koneksi ke database menggunakan file "koneksi.php".

3. Variabel `$id` diambil dari parameter `GET` pada URL, yang menunjukkan ID siswa yang akan dihapus.

4. Jika variabel `$id` ada, maka akan dilakukan proses penghapusan data siswa di database dengan query `DELETE FROM`.

5. Jika proses penghapusan berhasil, maka akan muncul pesan "Hapus data Berhasil" dan pengguna akan diarahkan ke halaman "table.php".

6. Jika proses penghapusan gagal, maka akan muncul pesan "Hapus data gagal".

## Kesimpulan

Kode program ini merupakan halaman untuk menghapus data siswa yang disimpan dalam database. Pengguna dapat menghapus data siswa berdasarkan ID yang diberikan melalui parameter `GET`. Jika proses penghapusan berhasil, maka pengguna akan diarahkan ke halaman "table.php". Jika proses penghapusan gagal, maka akan muncul pesan kesalahan.

# Session/Login

## Program

```PHP

<?php

session_start();
if (isset($_POST['submit'])) {
    $username = $_POST['username'];
    $password = $_POST['password'];
    $koneksi = mysqli_connect('localhost', 'root', '', 'pemilu_test') or die('error koneksi');

    $result = mysqli_query($koneksi, "SELECT * FROM user
    WHERE username = '$username' AND password = '$password'");
    $data = mysqli_fetch_assoc($result);
    if (isset($data)) {
        $_SESSION['username'] = $data['username'];
        $_SESSION['nama'] = $data['nama'];
        $_SESSION['status'] = 'login';
        header('Location: user.php');
    } else {
        echo "Username dan Password Salah";
    }
}
?>
<!DOCTYPE html>
<html>
<head>
    <title>Login Session</title>
</head>
<body>
    <form method="post">

        <label>Username</label>
        <input type="text" name="username">

        <br>
        <label>Password</label>
        <input type="text" name="password">

        <br>
        <button type="submit" name="submit">Login</button>
    </form>
</body>
</html>

```

  

```PHP

<?php

session_start();

if ($_SESSION['status'] == 'login' && $_SESSION['username'] == 'admin') {
    header("Location: admin.php");
}

if ($_SESSION['status'] != 'login') {
    header('Location: login.php');
}
  
?>

<!DOCTYPE html>
<html lang="en">
<head>
    <title>Document</title>

</head>
<body>
    <h1>Halaman User</h1>
    
    <h1>Halo, <?= $_SESSION['nama'] ?></h1>
    <a href="logout.php">Logout</a>
</body>
</html>

```

  

```PHP

<?php

if ($_SESSION['status'] == 'login' && $_SESSION['username'] != 'admin') {
    header("Location: user.php");
    exit();
} else if ($_SESSION['status'] == 'login' && $_SESSION['username'] == 'admin') {
    header("Location: admin.php");
}else{
    header("Location: session.php");

}

```

  

```php

<?php

session_start();

if ($_SESSION['status'] == 'login' && $_SESSION['username'] != 'admin') {
    header("Location: user.php");
}

if ($_SESSION['status'] != 'login') {
    header('Location: login.php');
}
?>

<!DOCTYPE html>
<html lang="en">
<head>
    <title>Document</title>
</head>
<body>
    <h1>Halaman Admin</h1>

    <h1>Halo, <?= $_SESSION['nama'] ?></h1>
    <a href="logout.php">Logout</a>
</body>
</html>

```

## Hasil

![](asetPHP/1.png)

  

![](asetPHP/2.png)

## Analisis

 Pada bagian PHP:

- Program memulai session dengan menggunakan fungsi session_start(). Hal ini penting untuk memulai dan mengelola session di PHP.

- Jika terdapat data yang dikirimkan melalui metode POST dengan nama "submit" (diperiksa menggunakan isset($_POST['submit'])), maka program akan melakukan proses login.

- Data username dan password yang dikirimkan melalui form diambil menggunakan $_POST['username'] dan $_POST['password'].

- Dilakukan koneksi ke database MySQL menggunakan mysqli_connect() dengan parameter host, username, password, dan nama database.

- Dilakukan query SQL untuk mencocokkan data username dan password yang diberikan dengan data di tabel "user" menggunakan perintah mysqli_query().

- Hasil query diambil menggunakan mysqli_fetch_assoc() dan disimpan dalam variabel $data.

- Hasil dari $data ditampilkan menggunakan var_dump() untuk tujuan debugging.

- Jika $data memiliki nilai (artinya username dan password cocok), maka session akan diset dengan variabel-variabel dari data tersebut, dan pengguna akan diarahkan ke halaman "user.php" menggunakan header('Location: user.php').

- Jika tidak ada data yang cocok, maka akan ditampilkan pesan "Username dan Password Salah".

  

Pada bagian HTML:

- Terdapat sebuah form dengan metode POST.

- Form tersebut memiliki input field untuk username dan password.

- Terdapat tombol "Login" yang akan mengirimkan data form saat ditekan.

## Kesimpulan

File session.php adalah program PHP yang melakukan proses login menggunakan session. Program ini memeriksa apakah data username dan password yang diberikan cocok dengan data yang ada di database. Jika cocok, session akan diset dengan variabel-variabel dari data tersebut dan pengguna akan diarahkan ke halaman "user.php". Jika tidak cocok, pesan kesalahan akan ditampilkan. Namun, perlu diperhatikan bahwa file ini belum mengimplementasikan fitur keamanan seperti sanitasi input dan penggunaan prepared statement untuk mencegah serangan SQL Injection.

# Upload & Download

## Upload

### Program

```php

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
  
    <title>index tabel</title>

</head>
<body>

    <h2>Data Siswa Berprestasi</h2>
    
    <a href="tambah.php">+Tambah Data Baru</a><br><br>
    <p>
        <a href="export.php">Export ke Excel</a>
    </p>
    <table border="5">
    <tr>
        <th>id_siswa</th>
        <th>Gambar</th>
        <th>nama</th>
        <th>email</th>
        <th>jenis_kelamin</th>
        <th>alamat</th>
        <th>Aksi</th>
    </tr>
    
    <?php

    include "koneksi.php";
    
    $i = 1;

    $query = mysqli_query($koneksi, "SELECT * FROM siswa");
    while ($data = mysqli_fetch_array($query)) {

    ?>
    
    <tr>
        <td><?php echo $i; ?></td>
        <td>
            <img src="img/<?= $data['gambar'] ?>" alt="gambar" width="100px">
       </td>
  
        <td><?php echo $data['nama']; ?></td>
        <td><?php echo $data['email']; ?></td>
        <td><?php echo $data['jenis_kelamin']; ?></td>
        <td><?php echo $data['alamat']; ?></td>
        <td>
            <a href="ubah.php?id=<?= $data['id_siswa']; ?>">Ubah</a> |
            <a href="hapus.php?id=<?= $data['id_siswa']; ?>">Hapus</a> 
        </td>
    </tr>
    <?php

    $i++;
    }
    
?>

    </table>
</body>
</html>

```

### Hasil

![](asetPHP/php3.png)

  

![](asetPHP/php2.png)

### Analisis

1. Kode program ini merupakan halaman utama (index) untuk menampilkan data siswa berprestasi yang disimpan dalam database.

2. Halaman ini terdiri dari beberapa elemen, yaitu:

    - Judul "Data Siswa Berprestasi"

    - Link "Tambah Data Baru" yang mengarah ke halaman "tambah.php"

    - Link "Export ke Excel" yang mengarah ke halaman "export.php"

    - Tabel yang menampilkan data siswa, meliputi: id_siswa, gambar, nama, email, jenis kelamin, dan alamat.

    - Tabel juga menampilkan aksi yang dapat dilakukan, yaitu "Ubah" dan "Hapus".

3. Data siswa ditampilkan dengan menggunakan perulangan `while` yang mengambil data dari tabel "siswa" di database.

4. Pada setiap baris data siswa, terdapat gambar, nama, email, jenis kelamin, dan alamat yang diambil dari tabel "siswa".

5. Tombol "Ubah" dan "Hapus" pada setiap baris data siswa akan mengarahkan pengguna ke halaman "ubah.php" dan "hapus.php" dengan membawa parameter ID siswa.
### Kesimpulan

Kode program ini merupakan halaman utama (index) untuk menampilkan data siswa berprestasi yang disimpan dalam database. Halaman ini memiliki fitur untuk menambah data baru, mengekspor data ke Excel, dan melakukan aksi ubah atau hapus data siswa. Keseluruhan fungsi pada halaman ini berjalan dengan baik dan dapat digunakan untuk manajemen data siswa.

## Download

### Program

```php

<?php

include "koneksi.php";

$query = mysqli_query($koneksi, 'SELECT * FROM siswa');
  
$data = [];
$data[] = ["ID", "Nama", "Email", "Jenis Kelamin", "Alamat"];

while ($row = mysqli_fetch_assoc($query)) {

    $data[] = [
    
        $row['id_siswa'],
        $row['nama'],
        $row['email'],
        $row['jenis_kelamin'],
        $row['alamat']
    ];
      
}

$namafile = "excel_data.xls";

header("Content-Type: application/vnd.ms-excel");
header("Content-Disposition: attachment;filename=\"$namafile\"");
header("Cache-Control: max-age=0");

$output = fopen("php://output", "w");
foreach ($data as $row) {
    fputcsv($output, $row, "\t");
}

fclose($output);

exit;

```

### Hasil

![](asetPHP/php10.png)

### Analisis

1. Kode program ini merupakan halaman untuk mengekspor data siswa ke dalam format file Excel (.xls).

2. Pertama, program menyertakan file "koneksi.php" yang diduga berisi konfigurasi untuk koneksi ke database.

3. Program kemudian mengambil semua data dari tabel "siswa" menggunakan perintah `mysqli_query()`.

4. Data yang diambil disimpan dalam sebuah array `$data`, di mana baris pertama berisi nama-nama kolom (ID, Nama, Email, Jenis Kelamin, Alamat).

5. Program selanjutnya mengatur header HTTP untuk memaksa browser mengunduh file Excel, dengan nama file "excel_data.xls".

6. Selanjutnya, program membuka output stream untuk menulis data ke file Excel menggunakan `fopen()` dan `fputcsv()`.

7. Setiap baris data dari array `$data` ditulis ke output stream menggunakan `fputcsv()`, dengan karakter tab sebagai pemisah antar kolom.

8. Setelah semua data ditulis, program menutup output stream dan keluar.
### Kesimpulan

Kode program ini berfungsi untuk mengekspor data siswa dari database ke dalam format file Excel (.xls). Hal ini dapat memudahkan pengguna untuk mengakses dan mengolah data siswa dalam bentuk spreadsheet. Sebagai seorang siswa SMK jurusan RPL, Anda dapat mempelajari bagaimana membuat fitur ekspor data ke Excel dengan menggunakan PHP dan MySQL. Selain itu, Anda juga dapat mempelajari tentang pengaturan header HTTP dan penggunaan fungsi-fungsi PHP untuk bekerja dengan file Excel.
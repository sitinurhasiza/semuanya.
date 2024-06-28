# Rangkuman materi PHP

PHP adalah bahasa pemrograman yang sering digunakan untuk pengembangan aplikasi web dinamis. Berikut adalah rangkuman beberapa topik penting dalam PHP beserta contoh program dan penjelasan singkatnya:

## 1. Pengantar PHP
PHP (Hypertext Preprocessor) digunakan terutama untuk membuat halaman web yang dinamis dan interaktif.

## 2. Contoh Penggunaan Array
```php
<?php
// Contoh penggunaan array
// Array satu dimensi
$buah = array("Alpukat", "Durian", "Apel");

// Array multi-dimensi
$mahasiswa = array(
    array("Nama" => "Hasiza", "Jurusan" => "RPL", "Umur" => 17),
    array("Nama" => "Dilla", "Jurusan" => "Perkantoran", "Umur" => 16)
);

// Array asosiatif
$pegawai = array(
    "nama" => "Hasiza",
    "jabatan" => "Manager",
    "gaji" => 5000000
);
?>
```
- **Penjelasan**:
  - **Array satu dimensi**: Kumpulan nilai dengan indeks numerik.
  - **Array multi-dimensi**: Kumpulan array di dalam array untuk menyimpan data yang lebih kompleks.
  - **Array asosiatif**: Kumpulan pasangan kunci-nilai untuk mengakses nilai dengan menggunakan kunci tertentu.

## 3. Penggunaan Pengendali Aliran
```php
<?php
// Contoh penggunaan pengendali aliran
$nilai = 75;

if ($nilai >= 60) {
    echo "Lulus";
} else {
    echo "Tidak Lulus";
}
?>
```
- **Penjelasan**:
  - **if-else statement**: Mengatur alur eksekusi berdasarkan kondisi tertentu.
  - Contoh di atas mengecek apakah nilai lebih besar atau sama dengan 60, dan mencetak "Lulus" jika benar, dan "Tidak Lulus" jika salah.

## 4. Penggunaan Perulangan
```php
<?php
// Contoh penggunaan perulangan
// Perulangan for
for ($i = 1; $i <= 5; $i++) {
    echo "Nomor: $i <br>";
}

// Perulangan foreach
$warna = array("Biru", "Hitam", "Pink");
foreach ($warna as $nilai) {
    echo "Warna: $nilai <br>";
}
?>
```
- **Penjelasan**:
  - **Perulangan for**: Melakukan iterasi berulang berdasarkan kondisi dan menginkremen variabel.
  - **Perulangan foreach**: Digunakan untuk mengulang elemen dalam array atau objek.

## 5. Penggunaan Fungsi
```php
<?php
// Contoh penggunaan fungsi
function hitungLuasSegitiga($alas, $tinggi) {
    $luas = 0.5 * $alas * $tinggi;
    return $luas;
}

$alas = 10;
$tinggi = 5;
echo "Luas Segitiga: " . hitungLuasSegitiga($alas, $tinggi);
?>
```
- **Penjelasan**:
  - **Function declaration**: Membuat fungsi untuk menghitung luas segitiga berdasarkan alas dan tinggi yang diberikan.
  - **Function call**: Memanggil fungsi `hitungLuasSegitiga()` dengan parameter tertentu dan mencetak hasilnya.

## 6. Penggunaan Superglobals
```php
<?php
// Contoh penggunaan superglobals
echo "Nama pengguna: " . $_SERVER['PHP_SELF'] . "<br>";
echo "Alamat IP: " . $_SERVER['REMOTE_ADDR'] . "<br>";
echo "Metode: " . $_SERVER['REQUEST_METHOD'];
?>
```
- **Penjelasan**:
  - **Superglobals**: Variabel bawaan PHP yang dapat diakses dari mana saja dalam skrip PHP.
  - Contoh di atas menggunakan `$_SERVER` untuk mendapatkan informasi seperti nama skrip, alamat IP pengguna, dan metode permintaan HTTP.

### Kesimpulan
PHP adalah bahasa pemrograman yang kuat untuk pengembangan web dinamis. Dengan memahami konsep dasar seperti array, pengendali aliran, perulangan, fungsi, dan superglobals, Anda dapat membangun aplikasi web yang kompleks dan interaktif dengan lebih efisien menggunakan PHP.
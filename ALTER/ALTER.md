Berikut Struktur Awal
# Menambahkan Kolom

## Struktur Query

```mysql

ALTER TABLE (nama_tabel) ADD (nama_kolom_baru) (tipe_data) (`opsional` = AFTER (nama_kolom));

```

## Contoh Query

```mysql

 ALTER TABLE tugasss ADD batas_peminjam varchar(25) AFTER peminjam;

```

## Hasil

BEFORE

![](asetALTER/2aset.jpg)

AFTER

![](asetALTER/1aset.jpg)

  

## Analisis

- `ALTER TABLE`: Ini adalah perintah SQL yang digunakan untuk memodifikasi struktur tabel yang ada.

- `tugasss`: merupakan nama tabel yang diubah.

- `ADD`: Kata kunci ini menunjukkan bahwa sebuah kolom baru ditambahkan ke dalam tabel.

- `batas_peminjam`: Ini adalah nama kolom baru yang ditambahkan.

- `varchar(10)`: Ini menentukan tipe data dari kolom baru. `varchar` adalah string karakter berpanjang variabel, dan `(10)` menunjukkan bahwa itu dapat menampung hingga 10 karakter.

- `AFTER peminjam`: Ini menentukan posisi di mana kolom baru akan ditambahkan. Dalam hal ini, itu akan ditambahkan setelah kolom `peminjam`.

## Kesimpulan

Jadi, kesimpulan program ini adalah bahwa ia menambahkan kolom `batas_peminjam` ke tabel `tugasss`, di mana kolom baru tersebut merupakan `string` teks dengan panjang maksimal 10 karakter, dan kolom ini akan ditempatkan setelah kolom `peminjam dalam struktur tabel.

## Tambahan

### Query

```mysql

UPDATE tugasss SET batas_peminjaman='2024-04-24' WHERE peminjam IS NOT NULL;

```

### Hasil

![](asetALTER/3aset.jpg)

# Mengubah Nama Kolom

## Struktur Query

```mysql

ALTER TABLE (nama_tabel) CHANGE (nama_kolom_yg_dignti) (nama_kolom_baru) (tipedata);

```

## Contoh Query

```mysql
ALTER TABLE tugasss CHANGE batas_peminjaman deadline varchar(10);
```

## Hasil

![](asetALTER/4aset.jpg)

  

## Analisis

- `ALTER TABLE`: Ini adalah perintah SQL yang digunakan untuk memodifikasi struktur tabel yang sudah ada.

- `tugasss`: Ini adalah nama tabel yang akan diubah.

- `CHANGE batas_peminjaman deadline varchar(10)`: Ini adalah perintah untuk mengubah nama dan tipe data kolom. Kolom yang sebelumnya bernama `batas_peminjaman` akan diubah menjadi `deadline`. Selain itu, tipe data kolom ini diubah menjadi `varchar(10)`, yang berarti itu adalah string teks dengan panjang maksimal 10 karakter.

  

## Kesimpulan

Kesimpulan perintah ini melakukan dua perubahan pada tabel `tugasss`: mengubah nama kolom dari `batas_peminjaman` menjadi `deadline`, dan mengubah tipe data kolom tersebut menjadi `varchar(10)`.

  

# Mengubah Tipe Data Kolom

## Struktur Query

```MYSQL

ALTER TABLE (nama_tabel) MODIFY (nama_kolom) (nama_tipedata);

```

## Contoh Query

```MYSQL

ALTER TABLE tugasss MODIFY deadline DATE;

```

## Hasil

![](asetALTER/5aset.jpg)

  

## Analisis

- `ALTER TABLE` adalah perintah SQL yang digunakan untuk mengubah struktur tabel yang sudah ada.

- `tugasss` adalah nama tabel yang akan diubah.

- `MODIFY deadline DATE` adalah klausa yang menentukan kolom `deadline` yang akan diubah dan tipe datanya menjadi `DATE`.

## Kesimpulan

Kesimpulannya, program `ALTER TABLE tugasss MODIFY deadline DATE;` digunakan untuk mengubah tipe data kolom `deadline` dalam tabel `tugasss` menjadi `DATE`. Perubahan ini memungkinkan kolom `deadline` untuk hanya menyimpan nilai tanggal, dan memungkinkan operasi dan pemrosesan yang lebih tepat terhadap data tanggal yang terkait.

# Menambahkan constraint

## Struktur Query

```MYSQL

ALTER TABLE (nama_tabel)

    -> ALTER (nama_kolom) SET DEFAULT (nilai_default );

```

## Contoh Query

```MYSQL

ALTER TABLE tugasss
    -> ALTER deadline SET DEFAULT 'Ready';

```

## Hasil

![](asetALTER/6aset.jpg)

  

## Analisis

- `ALTER TABLE`adalah SQL

- `tugasss`adalah sebuah nama tabel

- `ALTER deadline`adalah sebuah klausa`deadline`dalam`desc_mobil`

- `SET DEFAULT 'Ready'`adalah`deadline`kolom

## Kesimpulan

Program `ALTER TABLE tugasss ALTER deadline SET DEFAULT 'Ready';` mengubah nilai default kolom `deadline` dalam tabel `tugasss` menjadi `'Ready'`. Ini berarti bahwa jika tidak ada nilai yang diberikan secara eksplisit saat melakukan operasi `INSERT` pada tabel `tugasss`, maka kolom `deadline` akan memiliki nilai default `'Ready'`.

## Tambahan

### Query

```mysql

INSERT INTO tugasss
    -> (id_mobil,no_plat,no_mesin,warna,pemilik,peminjam,harga_rental)
    -> VALUES (6,"DD2224LC","H4856CH","Merah","AI","ECA",2300000000000);
```

### Hasil

![](asetALTER/7aset.jpg)

  

## Referensi tambahan

https://revou.co/panduan-teknis/sql-constraint

# Menghapus constraint

## Struktur Query

```MYSQL

 ALTER TABLE (nama_tabel)

    -> ALTER (nama_kolom) DROP DEFAULT;

```

## Contoh Query

```MYSQL

 ALTER TABLE tugasss
    -> ALTER deadline DROP DEFAULT;

```

## Hasil

![](asetALTER/8aset.jpg)

  

## Analisis

- `ALTER TABLE` adalah perintah SQL yang digunakan untuk mengubah struktur tabel yang sudah ada.

- `tugasss` adalah nama tabel yang akan diubah.

- `ALTER deadline` adalah klausa yang menentukan kolom `deadline` yang akan diubah.

- `DROP DEFAULT` adalah klausa yang digunakan untuk menghapus nilai default dari kolom.

## Kesimpulan

Program `ALTER TABLE tugasss ALTER deadline DROP DEFAULT;` menghapus nilai default dari kolom `deadline` dalam tabel `tugasss`. Setelah menjalankan program ini, kolom `deadline` tidak akan memiliki nilai default, dan jika tidak ada nilai yang diberikan secara eksplisit saat melakukan operasi `INSERT`, kolom `deadline` akan memiliki nilai `NULL`.

## Referensi tambahan

https://www.geeksforgeeks.org/sql-drop-constraint

# Menghapus kolom

## Struktur Query

```mysql

ALTER TABLE mobil DROP COLUMN deadline;

```

## Contoh Query

```mysql

ALTER TABLE tugasss DROP COLUMN deadline;
```

## Hasil

![](asetALTER/9aset.jpg)

  

## Analisis

- `ALTER TABLE`adalah perintah SQL yang digunakan untuk mengubah struktur tabel yang ada.

- `tugasss`adalah nama tabel yang sedang diubah.

- `DROP COLUMN`adalah klausa yang digunakan untuk menghapus kolom tertentu dari tabel.

- `deadline`adalah nama kolom yang dihilangkan dari `tugasss`tabel.

## Kesimpulan

Singkatnya, program ini menginstruksikan sistem manajemen basis data untuk menghapus `deadline`kolom dari `tugasss`tabel. Setelah menjalankan program ini, `deadline` kolom tersebut tidak akan ada lagi di struktur tabel, dan data apa pun yang disimpan di kolom tersebut akan dihapus secara permanen.

# Mengganti nama tabel

## Struktur Query

```mysql

 ALTER TABLE mobil RENAME TO daftar_mobil;

```

## Contoh Query

```mysql

 ALTER TABLE tugasss RENAME TO daftar_mobil;

```

## Hasil

![](asetALTER/10aset.jpg)

  

## Analisis

- `ALTER TABLE` adalah perintah SQL yang digunakan untuk mengubah struktur tabel yang sudah ada.

- `tugasss` adalah nama tabel yang akan diubah.

- `RENAME TO` adalah klausa yang digunakan untuk mengubah nama tabel.

- `daftar_mobil` adalah nama baru yang diberikan kepada tabel.

## Kesimpulan

Program `ALTER TABLE tugasss RENAME TO daftar_mobil;` mengubah nama tabel `tugasss` menjadi `daftar_mobil`. Setelah menjalankan program ini, tabel yang sebelumnya bernama `tugasss` akan berganti nama menjadi `daftar_mobil`.
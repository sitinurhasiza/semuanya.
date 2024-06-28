# Rangkuman materi HTML
### 1. Pengenalan HTML

HTML (HyperText Markup Language) adalah bahasa standar untuk membuat dan merancang halaman web. HTML menggunakan elemen-elemen yang diwakili oleh tag untuk membentuk struktur dan konten dari sebuah halaman web.

### 2. Struktur Dasar HTML

```HTML
<!DOCTYPE html>
<html>
<head>
    <title>Judul Halaman</title>
</head>
<body>
    <h1>Selamat Datang di HTML</h1>
    <p>Ini adalah paragraf pertama saya.</p>
</body>
</html>

```

- **Penjelasan**:
    - `<!DOCTYPE html>`: Mendeklarasikan tipe dokumen dan versi HTML.
    - `<html>`: Elemen root yang mencakup seluruh konten halaman.
    - `<head>`: Bagian dokumen yang berisi informasi meta-data.
    - `<title>`: Menentukan judul dokumen yang muncul di tab browser.
    - `<body>`: Berisi konten utama yang ditampilkan di halaman web.

### 3. **Tag Form**

```HTML
<form action="/submit" method="post">
    <label for="nama">Nama:</label>
    <input type="text" id="nama" name="nama"><br><br>
    <label for="email">Email:</label>
    <input type="email" id="email" name="email"><br><br>
    <input type="submit" value="Submit">
</form>

```

- **Penjelasan**:
    - `<form>`: Elemen untuk membuat form.
    - `action`: URL tujuan saat form dikirim.
    - `method`: Metode pengiriman (GET atau POST).
    - `<label>`: Menandai elemen input untuk meningkatkan aksesibilitas.
    - `<input>`: Elemen input untuk berbagai jenis data (teks, email, dll.).
    - `type`: Menentukan jenis input.
    - `name`: Nama yang digunakan untuk mengidentifikasi data input.
    - `<input type="submit">`: Tombol untuk mengirim form.

### 4. **Tag dan Elemen Dasar**

- **Heading**: `<h1>` hingga `<h6>` untuk judul, dari yang paling besar (`<h1>`) hingga yang paling kecil (`<h6>`).
- **Paragraf**: `<p>` untuk teks paragraf.
- **Link**: `<a href="url">Teks Link</a>` untuk membuat hyperlink.
- **Gambar**: `<img src="url" alt="deskripsi">` untuk menampilkan gambar.
- **Daftar**:
    - Tidak berurut: `<ul>` dengan item `<li>`.
    - Berurut: `<ol>` dengan item `<li>`.

### 5. **Contoh Analisis Materi**

#### Contoh Tag Form

```HTML
<form action="/submit" method="post">
    <label for="nama">Nama:</label>
    <input type="text" id="nama" name="nama"><br><br>
    <label for="email">Email:</label>
    <input type="email" id="email" name="email"><br><br>
    <input type="submit" value="Submit">
</form>

```

- **Penjelasan**:
    - Form adalah salah satu elemen penting dalam HTML yang digunakan untuk mengumpulkan data dari pengguna.
    - Setiap elemen input dalam form harus memiliki atribut `name` untuk mengidentifikasi data saat form dikirim.
    - Penggunaan label (`<label>`) sangat penting untuk aksesibilitas, karena memungkinkan pengguna yang menggunakan pembaca layar untuk memahami elemen input yang terkait.

### 6. **Kesimpulan**

HTML adalah bahasa dasar untuk membuat struktur halaman web. Pemahaman tentang tag-tag dasar seperti form, heading, paragraf, link, dan gambar sangat penting untuk membangun halaman web yang efektif dan user-friendly. Analisis singkat setiap materi membantu memahami fungsi dan penggunaan masing-masing elemen dalam konteks yang lebih luas.
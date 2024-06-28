# Rangkuman materi CSS

## 1. Pengenalan CSS
CSS (Cascading Style Sheets) digunakan untuk mengatur tampilan dan format halaman web yang dibuat dengan HTML. CSS memungkinkan kontrol yang lebih detail terhadap tata letak, warna, dan gaya elemen-elemen HTML.

## 2. Contoh Penggunaan Property Font
```css
/* Penggunaan property font */
.example {
    font-family: Arial, sans-serif;
    font-size: 16px;
    font-weight: bold;
    line-height: 1.5;
    text-align: center;
}
```
- **Penjelasan**:
  - `font-family`: Menentukan jenis font untuk teks, dengan pilihan cadangan jika font utama tidak tersedia.
  - `font-size`: Menentukan ukuran font dalam piksel atau unit lain.
  - `font-weight`: Menentukan ketebalan font (normal, bold, lighter, atau bolder).
  - `line-height`: Menentukan jarak antara baris teks.
  - `text-align`: Menentukan penataan teks (left, center, right).

## 3. Property Background
```css
/* Penggunaan property background */
.example {
    background-color: #f0f0f0;
    background-image: url('background.jpg');
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
}
```
- **Penjelasan**:
  - `background-color`: Menentukan warna latar belakang elemen.
  - `background-image`: Menentukan gambar latar belakang.
  - `background-size`: Menentukan ukuran gambar latar belakang (cover, contain, atau nilai tertentu).
  - `background-position`: Menentukan posisi gambar latar belakang.
  - `background-repeat`: Menentukan apakah gambar latar belakang diulang atau tidak.

## 4. Property Box Model
```css
/* Penggunaan property box model */
.example {
    width: 300px;
    height: 200px;
    padding: 20px;
    border: 1px solid #ccc;
    margin: 10px;
}
```
- **Penjelasan**:
  - `width`: Menentukan lebar elemen.
  - `height`: Menentukan tinggi elemen.
  - `padding`: Menentukan ruang di antara konten dan batas elemen.
  - `border`: Menentukan garis batas elemen (ukuran, jenis, warna).
  - `margin`: Menentukan ruang di luar batas elemen.

## 5. Property Positioning
```css
/* Penggunaan property positioning */
.example {
    position: relative;
    top: 20px;
    left: 30px;
}
```
- **Penjelasan**:
  - `position`: Menentukan jenis posisi elemen (static, relative, absolute, fixed).
  - `top`, `bottom`, `left`, `right`: Menentukan posisi elemen relatif terhadap posisi normalnya.

## 6. Media Queries
```css
/* Penggunaan media queries */
@media screen and (max-width: 768px) {
    .example {
        font-size: 14px;
    }
}
```
- **Penjelasan**:
  - Media queries digunakan untuk menyesuaikan tampilan halaman web berdasarkan ukuran layar atau perangkat pengguna.
  - Contoh di atas mengubah ukuran font menjadi 14px ketika lebar layar kurang dari atau sama dengan 768px.

## 7. Pseudo-classes dan Pseudo-elements
```css
/* Penggunaan pseudo-classes dan pseudo-elements */
.example:hover {
    color: red;
}

.example::before {
    content: '• ';
    color: blue;
}
```
- **Penjelasan**:
  - Pseudo-classes (`:hover`, `:focus`, `:nth-child()`) digunakan untuk mengubah gaya elemen berdasarkan status atau posisi tertentu.
  - Pseudo-elements (`::before`, `::after`) digunakan untuk menambahkan isi atau gaya ke bagian spesifik dari elemen.

### Kesimpulan
CSS adalah bahasa yang kuat untuk mengontrol tampilan halaman web. Dengan memahami property dasar seperti font, background, box model, positioning, media queries, serta pseudo-classes dan pseudo-elements, Anda dapat meningkatkan tampilan dan interaktivitas halaman web dengan lebih efektif.
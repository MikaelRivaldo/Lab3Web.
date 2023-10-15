# Lab3Web

# Langkah pertama membuat dokumen HTML dengan nama file lab3_list.html
`Untuk Sourcodenya bisa menggunakan di bawah ini:`

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Lanjutan</title>
</head>
<body>
  <header>
    <h1>Membuat List</h1>
  </header>
</body>
</html>

```

`Selanjutnya tambahkan Ordered List`

Kemudian tambahkan kode untuk membuat Ordered List seperti berikut:

```html
<section id="order-list">
  <h2>Ordered List</h2>
  <ol>
    <li>Pemrograman Web</li>
    <li>Sistem Informasi</li>
    <li>Basis Data 2</li>
  </ol>
</section>
```

`Untuk hasilnya akan seperti ini:`

![tampilan ordered list](https://github.com/MikaelRivaldo/Lab3Web./assets/115770247/b614c4a0-576d-4fbd-8d6a-bf76108c3955)

`Selanjutnya tambahkan Unorderd List`

Kemudian tambakan kode untuk membuat Unordered List, setelah deklarasi ordered list pada
section unordered-list, seperti berikut.

```html
<section id="unorder-list">
  <h2>Unordered List</h2>
  <ul type="square">
    <li>Jaringan Komputer</li>
    <li>Struktur Data</li>
    <li>Algoritma &amp; Pemrograman</li>
  </ul>
</section>
```
`Untuk hasilnya akan seperti ini:`

![tampilan Unorderd list](https://github.com/MikaelRivaldo/Lab3Web./assets/115770247/e606db44-524f-472c-a358-1d17450a1dc7)

`Selajutnya membuat Description List`

Kemudian tambahkan kode untuk membuat description list setelah deklarasi unorderd-list.

```html
<section id="unorder-list">
  <h2>Description List</h2>
  <dl>
    <dt>Fakultas Teknik</dt>
    <dd>Teknik Industri</dd>
    <dd>Teknik Informatika</dd>
    <dd>Teknik Lingkungan</dd>
    <dt>Fakultas Ekonomi dan Bisnis</dt>
    <dd>Akuntansi</dd>
    <dd>Manajemen</dd>
    <dd>Bisnis Digital</dd>
  </dl>
</section>
```
`Untuk hasilnya akan seperti ini:`

![tampilan deskripsi list](https://github.com/MikaelRivaldo/Lab3Web./assets/115770247/43c4c434-10f5-4e1a-bc41-11d479da8800)

`Selanjutnya membuat Table`

Buat file baru dengan nama lab3_tabel.html seperti berikut

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>HTML Lanjutan</title>
</head>
<body>
  <header>
      <h1>Membuat Table</h1>
  </header>
</body>
</html>
```

Kemudian selanjutnya tambahkan kode untuk membuat tabel sederhana seperti berikut:

```html
<table border="1" cellpadding="4" cellspacing="0">
  <thead>
  <tr>
    <th>No.</th>
    <th>Fakultas</th>
    <th>Program Studi</th>
  </tr>
  </thead>
<tbody>
  <tr>
    <td>1.</td>
    <td>Teknik</td>
    <td>Teknik Informatika</td>
  </tr>
  <tr>
    <td>2.</td>
    <td>Teknik</td>
    <td>Teknik Industri</td>
  </tr>
  <tr>
    <td>3.</td>
    <td>Teknik</td>
    <td>Teknik Lingkungan</td>
  </tr>
</tbody>
</table>
```
`Untuk hasilnya akan seperti ini:`

![tampilan table](https://github.com/MikaelRivaldo/Lab3Web./assets/115770247/cfb60757-5584-4f7c-9f54-ea3e44502fdd)

`Selanjutnya Menggabungkan Sel Data`

Untuk menggabungkan sel data, gunakan atribut rowspan dan colspan. Atribut rowspan untuk
menggabungkan baris (secara vertikal) dan colspan untuk menggabungkan kolom (secara
horizontal).

`Untuk sourcodenya bisa menggunakan seperti ini:`

```html
<table border="1" cellpadding="6" cellspacing="0">
    <thead>
      <tr>
        <th>No.</th>
        <th>Fakultas</th>
        <th>Program Studi</th>
      </tr>
</thead>
<tbody>
      <tr>
        <td>1.</td>
        <td rowspan="3">Teknik</td>
        <td>Teknik Informatika</td>
      </tr>
      <tr>
        <td>2.</td>
        <td>Teknik Industri</td>
      </tr>
      <tr>
        <td>3.</td>
        <td>Teknik Lingkungan</td>
      </tr>
</tbody>
</table>
```
`Untuk hasilnya akan seperti ini:`

![tampilan menggabungkan sel data](https://github.com/MikaelRivaldo/Lab3Web./assets/115770247/8ea41792-22ad-42f1-9ecc-5605314788eb)

`Selanjutnya membuat form`

Buat file baru dengan nama lab3_form.html seperti berikut.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Lanjutan</title>
</head>
<body>
    <header>
        <h1>Membuat Form</h1>
    </header>
</body>
</html>
```
Kemudian selanjutnya tambahkan kode untuk membuat tabel sederhana seperti berikut:

```html
<form action="proses.php" method="post">
    <fieldset>
      <legend>Data Pelanggan</legend>
    <p>
      <label for="nama">Nama</label>
      <input type="text" id="nama" name="nama">
    </p>
    <p>
      <label for="alamat">Alamat</label>
      <textarea id="alamat" name="alamat" cols="20" rows="3"></textarea>
    </p>
    <p>
      <label>Jenis Kelamin</label>
      <input id="jk_l" type="radio" name="kelamin" value="L" /><label
for="jk_l">Laki-laki</label>
      <input id="jk_p" type="radio" name="kelamin" value="P" /><label
```
Kemudian tambahkan kode unntuk membuat `SUBMIT`

```html
for="jk_p">Perempuan</label>
    </p>
    <p><input type="submit" value="Login"></p>
</fieldset>
</form>
```

`Untuk hasilnnya akan seperti ini:`

![tampilan form](https://github.com/MikaelRivaldo/Lab3Web./assets/115770247/24b8f8e0-1229-4009-a09e-1e22bb5d0f15)

`Selanjutnya Menabahkan Style pada Form`

Agar tampilan form lebih menarik, bisa ditambahkan CSS seperti berikut.

```html
<style>
    form p > label {
      display: inline-block;
      width: 100px;
}
    form input[type="text"], form textarea {
      border: 1px solid #197a43;
}
    form input[type="submit"] {
      border: 1px solid #197a43;
      background-color: #197a43;
      color: #ffffff;
      font-weight: bold;
      padding: 5px 15px;
}
</style>
```
`Untuk hasilnya akan seperti ini:`

![tampilan style form](https://github.com/MikaelRivaldo/Lab3Web./assets/115770247/1d9fde7f-d75f-490d-9b42-6cdb056800eb)

# :rocket: Latihan PHP Dasar

Made With :

- Nama : Hizbullah Ridwan
- NIM : 312110055
- Kelas : TI.21.B.1
- Mata Kuliah : Pemrograman Web

## Install XAMPP

Sebelum mulai latihan PHP, pertama adalah mendownload dan install [XAMPP](https://www.apachefriends.org/) terlebih dahulu sebagai aplikasi bundle web servernya. Download langsung pada websitenya yaitu `https://www.apachefriends.org/download.html` atau [klik disini](https://www.apachefriends.org/download.html).

## Run Web Server

Setelah berhasil download dan install, [XAMPP](https://www.apachefriends.org/) bisa langsung di run. Start apache module kemudian pergi ke localhost dengan mengakses `http://127.0.0.1` atau `http://localhost`.

![Gambar 1](Screenshoots/Capture1.PNG)

![Gambar 2](Screenshoots/Capture2.PNG)

## Create Folder and File

Pada document root, buat folder baru dengan nama `lab7_php_dasar` dan buat file `php_dasar.php` didalamnya. Secara default, document root letaknya ada di `C:\xampp\htdocs`.

## Hello World

Untuk membuat hello world pada PHP seperti ini :

```bash
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>PHP Dasar</title>
  </head>
  <body>
    <h1>Belajar PHP Dasar</h1>
    <?php
      echo "Hello World";?>
  </body>
</html>
```

![Gambar 3](Screenshoots/Capture3.PNG)

## Variable

Untuk membuat variable pada PHP, harus menyertakan tanda `$` didepannya seperti ini :

```bash
<?php
    $nim = "0411500400";
    $nama = 'Abdullah';
    echo "NIM : " . $nim . "<br>"; echo "Nama : $nama";
?>
```

![Gambar 4](Screenshoots/Capture4.PNG)

## Predefine Variable GET

Untuk membuat predefine variable dengan get adalah seperti ini :

```bash
<?php
    echo 'Selamat Datang ' . $_GET['name'];
?>
```

Dan untuk mengaksesnya, yaitu dengan menambahkan `?name=nama_saya` dibelakang URL nya.

![Gambar 5](Screenshoots/Capture5.PNG)

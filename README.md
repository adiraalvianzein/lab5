# lab5

# Belajar JavaScript
Untuk Awalan Buat File Folder Dengan Nama Lab5
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <title>Mengenal JavaScript</title>
</head>
<body>
  <h1>Pengenalan JavaScript</h1>
  <h3>Contoh document.write dan console.log</h3>
  <script>
    document.write("Hello World");
    console.log("Hello World");
  </script>
</body>
</html>
```
## Untuk Hasilnya
![Screenshot 2024-10-31 192220](https://github.com/user-attachments/assets/75686334-319d-4076-bb15-f677f9fd3c9e)

# JavaScript Dasar
Pemakaian Alert Sebagai Property Window
```js
<html>
<head>
<title>alert box</title>
</head>
<body>
<script language = "javascript">
<!--
window.alert("ini merupakan pesan untuk anda");
//-->
</script>
</body>
</html>
```
Pemakaian Method Dalam objek
```js
<html>
<head>
<title>skrip javascript</title>
</head>
<body>
percobaan memakai javascript:<br>
<script language = "javascript">
<!--
document.write("selamat mencoba javascript<br>"); document.write("semoga sukses!");
//-->
-</script>
</body> 
</html>
```
Pemakaian Prompt
```js
<html>
<head>
<title>pemasukan data</title>
</head>
<body>
<script language = "javascript">
<!--
var nama prompt("siapa nama anda?", "masukkan nama anda"); document.write("hai, nama);
//-->
</script>
</body>
</html>
```
Untuk Cara Pemanggilannya
```js
<html>
<head>
  <title>contoh program javascript</title>
  <script language="javascript">
  function pesan() {
    alert("memanggil javascript lewat body onload")
    }
  </script>
</head>
<body onload=pesan()>
</body>
</html>
```

# Dasar Pemograman Di JavaScript
Operasi Dasar Aritmatika
```js
<html>
<head>
  <title>contoh program javascript</title>

  <script language="javascript">
  function test (vall, val2)
{
      document.write("<br>"+"perkalian vali val2 "+"<br>")
      document.write(vall*val2)
      document.write("<br>"+"pembagian: vall/val2 "+"<br>")
      document.write(val1/val2)
      document.write("<br>"+"penjumlahan vall+val2 "+"<br>")
      document.write(vall+val2)
      document.write("<br>"+"pengurangan vall-val2 "+"<br>")
      document.write(vall-val2)
      document.write("<br>"+"modulus valival2 "+"<br>")
      document.write(vall val2)
  }
  </script>
</head>
<body>
<input type="button" name="button" value="arithmetic" onclick=test(9,4)>
</body>
</html>
```
Seleksi Kondisi (if..else)
```js
<html>
<head>
  <title>contoh if-else</title>
</head>
<body>
  <script language = "javascript">
  <!--
  var nilai prompt("nilai (0-100): ", 0);
  var hasil = "";
  if (nilai >= 60)
  hasil = "lulus";
  else
  hasil "tidak lulus";
  document.write("hasil: "+ hasil);
  //-->
  </script>
</body>
</html>
```
Penggunaan operator swicth untuk seleksi kondisi
```js
<html>
<head><
  <title>contoh program javascript</title>

  <script language="javascript">
  function test ()
  {
    vall window.prompt("input nilai (1-5):")
    switch (vall)
    {
      case "1":
        document.write("bilangan satu")
        break
      case "2":
        document.write("bilangan dua")
        break
      case "3":
        document.write("bilangan tiga")
        break
      case "4":
        document.write("bilangan empat")
        break
      case "5":
        document.write("bilangan lima")
        break
      default:
        document.write("bilangan lainnya")
    }
  }
  </script>
</head>
<body>
  <input type="button" name="button" value="switch" onclick=test()>
</body>
</html>
```

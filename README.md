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
## Pembuatan Form
Form Input
```js
<html>
<head>
  <script language="javascript">
  function test () {
    var vall=document.kirim.Tl.value
    if (val1%2==0)
      document.kirim.T2.value="bilangan genap"
    else
      document.kirim.T2.value="bilangan ganjil"
  }
  </script>
</head>
<body>
  <form method="POST" name="kirim">
    <p>BIL <input type="text" name="T1" size="20">
    MERUPAKAN BIL <input type="text" name="12" size="20"></p>
    <p><input type="button" value="TEBAK" name="B1" onclick=test()></p>
  </form>
</body>
</html>
```
Form Button
```js
<html>
<head>
  <title>objek document</title>
</head>
<body>
  <script language="javascript"
  <!--
  function ubahwarnaLB (warna) {
  document.bgColor warna;
  }
  function ubahwarnaLD(warna) {
  document.fgColor = warna;
  }
  //-->
  </script>
  
  <h1>tes</h1>
  <form>
    <input type="button" value="Latar Belakang Hijau" onclick="ubahlarnaLB('GREEN')">
    <input type="button" value="Latar Belakang Putih" onClick="ubahalarnaLB('WHITE')"> 
    <input type="button" value="Teks Kuning" onclick="ubahwarnaLDI 'YELLOW')">
    <input type="button" value="Teks Biru" onClick="ubahwarnaLD('BLUE')">

  </form>
  <script language="javascript">
  <!--
  document.write("Dinodifikasi terakhir pada" + 
  document. lastModified);
  //-->
  </script>

</body> 
</html>
```
# HTML DOM
Pilihan Menggunakan ChaeckBox Dengan Perhitungan Otomatis
```js
<!--
file daftar menu
//-->
<html>
<head>
  <title>Daftar Menu</title>
  <script>
    function hitung(ele) (
      var total document.getElementById(total).value;
        total (total? parseInt(total): 0);
      var harga 0;

      if (ele.checked) {
        harga ele.value;
        total += parseInt(harga);
    } else {
        harga ele.value;
        if (total > 0)
          total -= parseInt(harga);
      }

      document.getElementById('total').value = total;
    }
  </script>
</head>
<body>
  <h1>Daftar Menu Makanan</hi>
  <label><input type="checkbox" value z ^ -5000^ + id =^ menul" onclick="hitung(this);" /> Ayam Goreng Rp. 5.000</label><br />
  <label><input type="checkbox" value =^ prime prime 500 ^ prime prime id = menu" onclick="hitung(this);" /> Tempe Goreng Rp. 500</label><br /> <label>  <input type="checkbox" value =^ prime prime 2500 deg id = menu" onclick="hitung(this);" /> Telur Dadar Rp. 2.500</label><hr />
  <strong>Total Bayar: Rp. <input id="total" type="text" /></strong>
</body>
</html>
```

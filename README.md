## LANGKAH - LANGKAH PRAKTIKUM 5

```
Galang Rintang Widya Pratama
312010299
TI.20.B.2
Universitas Pelita Bangsa
```

# A. Javascript dasar
### Seperti biasa langkah awal adalah buka Aplikasi text editor yang biasa kalian pakai, disini saya menggunakan text Editor VsCode.

### 1. Mengenal Java Script
jika sudah dibuka, langsung membuat folder bernama lab5_javascript. setelah itu buat file dengan nama "Mengenal Javascript".

lalu ketik code seperti berikut :
```
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
Maka hasilnya akan seperti berikut :

![image](https://user-images.githubusercontent.com/101440705/162960289-7006b477-0e2d-43e4-9d90-f681ddec2188.png)
Klik tombol f12 pada komputer anda, agar bisa melihat console.log.

### 2. Alert Box
Selanjutnya kita akan menampilkan Alert box dengan Javascript. Masukan Kode seperti di bawah ini :
```
<html lang="en"> 
    <head> 
        <title>alert box</title> 
    </head> 
    <body> 
        <script language = "javascript"> 
        // window.alert("ini merupakan pesan untuk anda");
        window.alert("Test 1 2 3");
        </script> 
    </body> 
</html>
```
Maka Hasilnya akan seperti ini :

![image](https://user-images.githubusercontent.com/101440705/162966275-f3038972-6a94-4b45-bc5a-04d156a83f0b.png)

### 3. Method dalam objek
Disini kita akan mencoba memakasi javascript sebagai objek. Masukkan kode berikut :
```
<html lang="en"> 
    <head> 
        <title>Skrip Javascript</title> 
    </head> 
    <body> 
        Percobaan memakai javascript:<br>
        <script language = "javascript"> 
        document.write("Selamat mencoba javascript<br>");
        document.write("semoga sukses!");
        </script> 
    </body> 
</html>
```
Lalu buka di web browser, dan lihat hasilnya. 

![image](https://user-images.githubusercontent.com/101440705/162967158-2684e8a2-4071-41fc-8a55-283e3519c2e0.png)

### 4. Prompt
Prompt digunakan untuk memasukkan data, bentuknya sama seperti alert box.
masukkan kode berikut :
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pemasukan Data</title>
</head>
<body>
  <script lang="javascript">
    var nama=prompt("siapa nama Anda?","Masukkan nama anda");
    document.write("hai, "+ nama );
  </script>
</body>
</html>
```
Maka hasilnya akan seperti di bawah ini :

![image](https://user-images.githubusercontent.com/101440705/162968585-8b9d890f-7d47-4fde-a86c-4a4d84ed60bc.png)

jika kita ketik sebuah nama, maka akan muncul kalimat 'hai, (nama)'. kemudian klik ok agar muncul tulisan seperti di gambar bawah ini.

![image](https://user-images.githubusercontent.com/101440705/162968691-201a8a28-62f9-4753-9d44-738a7011cfbe.png)

### 5. On load
sama seperti alert box, masukkan kode berikut :
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Contoh program javascript</title>
    <script lang="javascript">
      function pesan() {
        alert ("memanggil javascript lewat body onload")
      }
    </script>
  </head>
  <body onload="pesan()">
  </body>
</html>
```
Maka Hasil akan muncul seperti ini : 

![image](https://user-images.githubusercontent.com/101440705/162971760-adc3d37e-64a6-4a8e-8246-881dd7cf76d2.png)

### 6. Operasi Aritmatika
Kali ini kita akan membuat sebuah program aritmatika menggunakan JavaScript. Perhatikan dan ketiklah kode berikut :
```
<html lang="en"> 
    <head> 
        <title>Contoh Program Javascript</title>

        <script language = "javascript"> 
        function test (val1, val2) 
        {
            document.write("<br>"+"perkalian : val1*val2"+"<br>")
            document.write(val1*val2)
            document.write("<br>"+"pembagian : val1/val2"+"<br>")
            document.write(val1/val2)
            document.write("<br>"+"penjumlahan : val1+val2"+"<br>")
            document.write(val1+val2)
            document.write("<br>"+"pengurangan : val1-val2"+"<br>")
            document.write(val1-val2)
            document.write("<br>"+"modulus : val1%val2"+"<br>")
            document.write(val1%val2)
        }
        </script> 
    </head> 
    <body>
        <input type="button" name="button1" value="arithmethic" onclick="test(9,4)">
    </body> 
</html>
```

Jika sudah, langsung buka di browser dan lihat hasilnya. 

Tampilan awal, kita langsung di perlihatkan tombol dengan nama 'arithmethic',

![image](https://user-images.githubusercontent.com/101440705/162973044-8caed44d-b578-4cc3-b3fe-e69b0c1c2367.png)

Jika kita klik tombol tersebut, maka akan muncul aritmatikanya
![image](https://user-images.githubusercontent.com/101440705/162973105-9d40a53b-79f0-4245-8963-46cd79790198.png)

### 7. If - Else
sekarang kita akan membuat program if else, if else berguna sesuai dengan kondisi yang kita atur. pada Praktikum ini, Program yang dibuat adalah nilai rendah dan tinggi. jika kita masukan nilai diatas 60, maka program akan menampilkan hasil 'lulus', Sebaliknya jika kita masukan nilai di bawah 60 maka program akan menampilkan hasil 'tidak lulus'.
berikut kodenya :
```
<html lang="en"> 
    <head> 
        <title>Contoh if-else</title> 
    </head> 
    <body> 
        <script language = "javascript"> 
        var nilai = prompt("nilai (0-100): ", 0);
        var hasil = "";
        if (nilai >= 60) 
        hasil = "Lulus";
        else
        hasil = "Tidak Lulus";
        document.write("hasil: " + hasil);
        </script> 
    </body> 
</html>
```
Kita lihat Hasilnya di web browser :

![image](https://user-images.githubusercontent.com/101440705/162975917-8fea9cc2-ce4b-4e90-857f-712cfe5650f3.png)

![image](https://user-images.githubusercontent.com/101440705/162975971-e65f8d55-fbfb-4752-876c-1d7534398a63.png)

### 8. Operator Switch
Operator Switch akan menampilkan hasil dengan program yang kita perintah, Ketik kode berikut :
```
<html lang="en">
<head>
    <title>Contoh program javascript</title>

    <script lang="javascript">
    function test ()
    {
        val1=window.prompt("input nilai (1-5):")
        switch (val1)

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
            default :
                document.write("bilangan lainnya")
        }
    }
  </script>
</head>
<body>
    <input type="button" name="button1" value="switch" onclick="test()">
</body>
</html>
```
Maka Hasilnya akan menunjukan bilangan yang kita pilih, yaitu angka 0-5. jika yang kita masukan adalah bilangan yang lebih dari 5, maka akan menampikan hasil 'bilangan lainnya'

![image](https://user-images.githubusercontent.com/101440705/162976764-5a11e446-1ecb-403d-85cd-d149f03e177b.png)

### 9. Form Input
Ketik Kode seperti berikut :
```
<html lang="en">
<head>
    <title>form input</title>
    <script lang="javascript">
    function test (){
        var val1=document.kirim.T1.value
        if (val1%2==0)
            document.kirim.T2.value="bilangan genap"
        else 
            document.kirim.T2.value="bilangan ganjil"
    }
    </script>
</head>
<body>
    <form method="post" name="kirim">
        <p>BIL <input type="text" name="T1" size="20"> MERUPAKAN BIL <input type="text" name="T2" size="20"></p>
        <p><input type="button" value="tebak" name="B1" onclick="test()"></p>
    </form>
</body>
</html>
```
Maka hasilnya akan menampilkan seperti ini :

![image](https://user-images.githubusercontent.com/101440705/162977653-5e023ac3-2b32-48a5-9da4-92ce55274547.png)

### 10. Form Button
Pada Praktikum ini, akan di tunjukkan bagaimana cara merubah warna background dan warna font hanya dengan mengklik tombol. 

ketik kode berikut :
```
<html lang="en">
<head>
    <title>Objek Document</title>
    </head>
    <body>
    <script lang="javascript">
        function ubahWarnaLB(warna) {
            document.bgColor = warna;
        }
        function ubahWarnaLD(warna) {
            document.fgColor = warna;
        }
    </script>

    <h1>Test</h1>
    <form>
        <input type="button" value="Latar Belakang Hijau" onclick="ubahWarnaLB('green')">
        <input type="button" value="Latar Belakang Putih" onclick="ubahWarnaLB('white')">
        <input type="button" value="teks kuning" onclick="ubahWarnaLD('yellow')">
        <input type="button" value="teks biru" onclick="ubahWarnaLD('blue')">
    </form>
    <script lang="javascript">
        document.write("dimodifikasi terakhir pada " + document.lastModified);
    </script>
</body>
</html>
```
Lihat hasilnya di browser :

![image](https://user-images.githubusercontent.com/101440705/162978216-6e032fe0-1753-42a7-95ad-2eefab5e335e.png)

### 11. HTML DOM
Kali ini kita akan memuat program yang menghasilkan jumlah, masukan kode berikut :
```
<html lang="en">
<head>
    <title>Daftar menu</title>
    <script>
        function hitung(ele) {
        var total = document.getElementById('total').value;
            total = (total ? parseInt(total) : 0);
        var harga = 0;

        if (ele.checked) {
            harga = ele.value;
            total += parseInt(harga);
        } 
        else {
            harga = ele.value;
            if (total > 0)
            total -= parseInt(harga);
        }
        document.getElementById('total').value = total;
        }
    </script>
</head>
<body>
    <h1>Daftar Menu Makanan</h1>
    <label><input type="checkbox" value="5000" id="menu1" onclick="hitung(this);" />Ayam Goreng Rp. 5000</label><br>
    <label><input type="checkbox" value="500" id="menu2" onclick="hitung(this);" />Tempe Goreng Rp. 500</label><br>
    <label><input type="checkbox" value="2500" id="menu3" onclick="hitung(this);" />Telur Dadar Rp. 2.500</label><br>
    <strong>Total Bayar: Rp. <input id="total" type="text"/></strong>
</body>
</html>
```
dan hasilnya akan seperti berikut :

![image](https://user-images.githubusercontent.com/101440705/162978747-fe99679f-14e4-45fe-acb6-9079faaa2411.png)

=====================================================================
## B. TUGAS
Diperintahkan untuk membuat script untuk melakukan validasi pada sebuah form.
saya membuat form tersebut dengan kode seperti berikut :
```
<html>
<head>
	<title>Validasi Form</title>
	<link rel="stylesheet" type="text/css" href="style.css">

	<script type="text/javascript">
	function validasiForm() {
		var nama = document.getElementById("nama").value;
        var nim = document.getElementById("nim").value;
		var kelas = document.getElementById("kelas").value;
		var password = document.getElementById("password").value;
		if (nama != "" && nim !="" && email !="" && password !="") {
			return true;
		}else{
			alert('HARAP ISI DATA ANDA!');
		}
	}
</script>

</head>
<body>
    <div class="container">
		<center><h1>DAFTAR ABSENSI MAHASISWA TI.20.B2</h1></center>

		<form action="#" method="POST" onSubmit="validasiForm()">
			<fieldset > 
			<p>
				<label for="nama">USERNAME : </label>
				<input type="text" id="nama" name="nama" placeholder="Enter your username">
			</p>
			<p>
				<label for="nim">NIM : </label></b>
				<input type="text" id="nim" name="nim" placeholder="Enter your nim">
			</p>
			<p>
				<label for="kelas">Kelas: </label></b>
				<input type="text" id="kelas" name="kelas" placeholder="Enter your class">
			</p>
				<p>
				<label for="password">PASSWORD : </label>
				<input type="password" id="password" name="password" placeholder="Enter your password">
			</p>
		
			<p style="display: flex; justify-content: center;"><input type="submit" value="SIGN IN"></p>
		</form>
		</fieldset>
	</div>	
</body>
</html>
```
Disini agar tampilan form menarik, saya tambahkan juga CSS. Seperti berikut :
```
body {
    font-family:'Open Sans', sans-serif;
	background-image:url("Logo_upb.png");
    background-position: center;
    background-size: 1050px;
    background-repeat: no-repeat;
}
.container {
	width: 18em;
	margin: 0 auto;
	box-shadow: 0 0 10em #cccccc;
	padding: 1em;
    margin: 2em auto;
    background: #fff;
    border-radius: 10px;
	}
form p > label {
	display: inline-block;
	width: 200px;
}
form input[type="text"], input[type="password"], form textarea {
		width: 224px;
		border: 1px solid #098938;
		padding: 5px 15px;
		padding-left: 20px;
		border-radius: 5px;
}

form input[type="submit"] {
	border: 1px solid #0a6491;
	background-color: #0f269b;
	color: #ffffff;
	font-weight: bold;
	padding: 5px 15px;
    border-radius: 30px;
}
fieldset {
	background-color: lightblue;
	border-radius: 5px;
}
```

Dan Hasil dari 2 Kode tersebut sebagai berikut :

![image](https://user-images.githubusercontent.com/101440705/162992608-c20370c0-0392-4fcf-9fa6-4b77c8f9bf02.png)

============================S E L E S A I================================

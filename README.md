#TUGAS 2
PRAKTIKUM PEMOGRAMAN WEB 1
TI 1B

##MATERI INI BERISI TENTANG 
1. HTML
   apa itu html ? html singkatan dari Hypertext Markup Language
   lebih mudah kita anggap seperti hal nya suatu bangunan atau rumah yang di buat
   pastinya harus membutuhkan suatu pondas, begitu juga pemograman akan ada pondasi
   untuk menjalankan suatu program itu dengan html 
2. CSS
   apa itu css? css singkatan dari Cascading Style Sheets atau hiasan agar lebih menarik
   suatu program jika tadi html adalah pondasi maka css adalah cat yang membuat suatu
   bangunan lebih menarik 
3. JAVA SCRIPT
   java script ini tingkatan lebih sulid dari html dan css karena kita harus pandai memakai logika
   algoritma kita harus berjalan karena java script kobinasi dari html dan css
   
Dengan kita belajar html, css, dan juga java script akan lebih memudahkan kita untuk membuat suatu program

##CONTENT

a. Membuat List merek kendaraan

b. Membuat tabel menggunakan border

c. Membuat tabel Mahasiswa menggunakan style css

d. Mencari hasil nilai dari suatu tabel

##PREVIEW

Dibawah ini contoh materi praktikum pemograman web kelas Ti B menggunakan list

<!DOCTYPE html>
<html>
<body>

<h2>Materi Praktikum Web</h2>

<ol>
  <li>HTML</li>
  <li>CSS</li>
  <li>JAVA SCRIPT</li>
</ol>  

</body>
</html>

maksud dari code diatas adalah h2 untuk memberi heading atau judul maupun sub judul yang berukuran 2, lalu ada ol yang fungsi nya untuk menampilkan angka 1,2,3, berikutnya ada li sebagai list 

berikutnya kita akan membuat tabel kontak person mahasiswa dengan mrnggunakan css
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width,initial-scale=1.0">
        <title>Document</title>
        <style>
        #table2 {
            font-family: Arial, Arial, Helvetica, sans-serif;
            border-collapse: collapse;
            width: 50%;
            border: 3px solid green;
        }

        #table2 td, #table2 th{
          border: 2px solid green;
          padding: 6px;
        }
        #table2 tr:nth-child(even){background-color: beige;}

        #table2 tr:hover {background-color: greenyellow;}

        #table2 th{
            padding-top: 15px;
            padding-bottom: 15px;
            text-align: center;
            background-color:chartreuse;
            color: black;
        }
        </style>
        
<table id="table2" style="width:33%">
    <tr>
        <td Colspan = "2" Align = "Center" style="background-color:chartreuse;"><b>Kontak Mahasiswa</b></th>
    </tr>
    <td>Name</td>
    <td>No. Telp</td>
  </tr>
  <tr>
    <td>Ratna</td>
    <td>543.876</td>
  </tr>
  <tr>
    <td rowspan="2">Nayla</td>
    <td>555-1234</td>
  </tr>
  <tr>
    <td>555-8745</td>
  </tr>
  <td>Salma</td>
  <td rowspan="3"><img src="https://static-00.iconduck.com/assets.00/call-icon-2047x2048-1v137evf.png" width="100px" height="100px"></td>
  </tr>
    <td>Arsita</td>
  </tr>
</table>

pertama beri wadah atau tempat menyimpan id tabel dengan simbol pagar # untuk di panggil nanti. lalu di style font, color, backgound color, width, dan juga border lalu id table td dan th untuk garis penyekat tabel di beri border dan padding

lalu pemberian hover yang membuat saat mouse ketika diarahkan kepada table makan table akan berwarna tanpa di klik dengan hover

lalu jika kita akan menggabungkan 2 kolom kita dapat menggunakan colspan lalu jika ingin menggabukan beberapa baris kolom maka menggunakan rowspan 

terakhir kita gunakan gambar dengan menggunakan img src lalu copy link gambar yang akan di gunakan

![Screenshot (236)](https://github.com/NoniAprillia/HTML-CSS-JAVASCRIPT/assets/165237591/04b0e52b-800f-4484-8c64-0a79e2f845da)


- Mencari hasil perkalian menggunakan JavaScript.
```sh
<h1>JavaScript Aritmatic</h1>
<h2>Hitunglah hasil berikut ini</h2>
    <script>
        let a = 5;
        let b = 6;

        function hitungNilai(a, b) {
        return a * b;
        } 
        let hasil = hitungNilai(a, b);

        function myFunction(){
        alert("Hasil "+a+" * "+b+" = "+hasil);
        }
        document.write("Nilai a = "+a+"<br>");
        document.write("Nilai b = "+b+"<br>");
    </script><br>
        <button onclick="myFunction()">Hasil</button>
</body>
</html>
```

h1 merupakan bagian heading atau judul sedangkan h2 nya adalah sub judul 

lalu masuk kebagian script nya ada let a dan let b fungsi nya sebagai wadah untuk menampung dan let hasil kita jadikan kunci untuk dipanggil pada function. 

document write untuk menampilkan hasil yang akan keluar tanpa harus menulis manual dan alert adalah tampilan seperti notif yang muncul menmunculkan hasilnya. 

button sebagai atribut yang di gunakan untuk mengeklik hasil dari suatu proses yang di definisikan sebagai sebuat tombol di dalam butto kita bisa menambahkan text, strong, tebal kata / br, dan juga gambar
biasanya button bertuliskan submit, hasil, hitunglah, atau carilah

![Screenshot (237)](https://github.com/NoniAprillia/HTML-CSS-JAVASCRIPT/assets/165237591/7fa3d880-ebbe-4a73-a0d9-c7a384e298bd)

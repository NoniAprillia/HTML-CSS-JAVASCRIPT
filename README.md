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
Dibawah ini contoh jadwal praktikum pemograman web kelas Ti B menggunakan list

<!DOCTYPE html>
<html>
<body>

<h2>Jadwal Praktikum Web</h2>

<ol>
  <li>HTML</li>
  <li>CSS</li>
  <li>JAVA SCRIPT</li>
</ol>  

</body>
</html>

maksud dari code diatas adalah h2 untuk memberi heading atau judul maupun sub judul yang berukuran 2, lalu ada ol yang fungsi nya untuk menampilkan angka 1,2,3, berikutnya ada li sebagai list 

<!DOCTYPE html>
<html>
<head>
<style>
#customers {
  font-family: Arial, Helvetica, sans-serif;
  border-collapse: collapse;
  width: 100%;
}

#customers td, #customers th {
  border: 1px solid #ddd;
  padding: 8px;
}

#customers tr:nth-child(even){background-color: #f2f2f2;}

#customers tr:hover {background-color: #ddd;}

#customers th {
  padding-top: 12px;
  padding-bottom: 12px;
  text-align: left;
  background-color: #04AA6D;
  color: white;
}
</style>
</head>
<body>

<h1>A Fancy Table</h1>

<table id="customers">
  <tr>
    <th>Company</th>
    <th>Contact</th>
    <th>Country</th>
  </tr>
  <tr>
    <td>Alfreds Futterkiste</td>
    <td>Maria Anders</td>
    <td>Germany</td>
  </tr>
  <tr>
    <td>Berglunds snabbköp</td>
    <td>Christina Berglund</td>
    <td>Sweden</td>
  </tr>
  <tr>
    <td>Centro comercial Moctezuma</td>
    <td>Francisco Chang</td>
    <td>Mexico</td>
  </tr>
  <tr>
    <td>Ernst Handel</td>
    <td>Roland Mendel</td>
    <td>Austria</td>
  </tr>
  <tr>
    <td>Island Trading</td>
    <td>Helen Bennett</td>
    <td>UK</td>
  </tr>
  <tr>
    <td>Königlich Essen</td>
    <td>Philip Cramer</td>
    <td>Germany</td>
  </tr>
  <tr>
    <td>Laughing Bacchus Winecellars</td>
    <td>Yoshi Tannamuri</td>
    <td>Canada</td>
  </tr>
  <tr>
    <td>Magazzini Alimentari Riuniti</td>
    <td>Giovanni Rovelli</td>
    <td>Italy</td>
  </tr>
  <tr>
    <td>North/South</td>
    <td>Simon Crowther</td>
    <td>UK</td>
  </tr>
  <tr>
    <td>Paris spécialités</td>
    <td>Marie Bertrand</td>
    <td>France</td>
  </tr>
</table>

</body>
</html>

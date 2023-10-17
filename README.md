Laporan Tugas Pemrograman Web SRS Si Cookies

Disusun oleh:

1. Ananda Veda Basunjaya (22091397086)
2. Mohammad Rizal Maarif (22091397098)
3. Anis Putri Purwanti   (22091397107)

Program Studi D4 Manajemen Informatika 
Fakultas Vokasi 
Universitas Negeri Surabaya 
2023

1. Tujuan 
Tujuan identifikasi mengenai produk website SiCakies adalah untuk menjelaskan cakupan dari produk yang dijelaskan dalam dokumen SRS, termasuk tujuan dari website, fungsi utama, karakteristik pengguna, lingkungan operasional, kendala desain dan implementasi, dokumentasi pengguna, asumsi dan ketergantungan. Dengan tujuan ini, pembaca dokumen akan memahami produk yang akan dikembangkan dan batasan serta kondisi yang harus dipertimbangkan dalam mengembangkan website tersebut.     
2. Lampiran
  A. Flowchart
  B. Usecase
3. Penjelasan
HTML
 ![image](https://github.com/D4ManajemenInformatika/final-project-website-pemweb10_mic/assets/124486941/7352af1d-fd1c-450a-9842-9140d23633f2)

1.	<!DOCTYPE html>: Ini adalah deklarasi tipe dokumen HTML yang digunakan dalam dokumen. Ini memberi tahu browser bahwa ini adalah dokumen HTML.
2.	<html lang="en">: Ini adalah elemen root yang membungkus seluruh konten halaman web. 
Atribut lang mengindikasikan bahwa bahasa yang digunakan dalam dokumen adalah bahasa Inggris (English).
3.	<head>: Bagian ini mengandung informasi tentang halaman web, seperti meta tag, judul halaman, dan tautan ke berkas-berkas eksternal seperti CSS.
•	<meta charset="UTF-8">: Menentukan bahwa karakter set yang digunakan dalam halaman web adalah UTF-8, yang mendukung karakter internasional.
•	<meta name="viewport" content="width=device-width, initial-scale=1.0">: Ini adalah pengaturan untuk mengatur tampilan halaman web di perangkat seluler. Itu akan mengizinkan tampilan responsif pada perangkat berlayar kecil.
•	<title>tugas</title>: Ini adalah judul dari halaman web yang akan ditampilkan di tab browser.
•	<link rel="stylesheet" href="satu.css">: Ini adalah tautan ke berkas CSS eksternal dengan nama "satu.css" yang akan mengatur tampilan halaman.
4.	<body>: Ini adalah elemen yang mengandung semua konten yang akan ditampilkan di halaman web, termasuk navigasi, teks, gambar, dan lainnya.
5.	<nav>: Ini adalah elemen yang mengandung elemen-elemen yang membentuk menu navigasi situs web.
•	<div class="wrapper">: Ini adalah div dengan kelas "wrapper" yang digunakan untuk mengelompokkan elemen-elemen dalam navigasi.
•	<div class="judul">: Ini adalah div dengan kelas "judul" yang berisi tautan (link) ke halaman utama situs ("SI CAKIES").
•	<div class="menu">: Ini adalah div dengan kelas "menu" yang berisi daftar tautan navigasi dalam sebuah daftar tidak berurutan (unordered list).
6.	<section id="home">: Ini adalah bagian pertama dari halaman web, dengan atribut id yang digunakan untuk menandai bagian ini.
•	<img src="logo.png" width="40%">: Ini adalah elemen gambar yang menampilkan logo dengan lebar 40% dari lebar kontainer.
•	<div class="kolom">: Ini adalah div dengan kelas "kolom" yang berisi teks dan informasi tentang situs web.
•	Beberapa paragraf dan poin dijelaskan dengan tag <p>.
•	Ada pula tautan "Pelajari Lebih Lanjut" dengan kelas "tombol".
7.	<section id="courses">: Ini adalah bagian kedua dari halaman web dengan atribut id yang mengidentifikasinya sebagai "courses".
•	Ini berisi informasi tentang produk-produk yang ditawarkan, termasuk gambar produk dan harga.
•	Setiap produk ditempatkan dalam div dengan kelas "gambar1," "gambar2," dan "gambar3."
8.	<section id="partners">: Ini adalah bagian ketiga dari halaman web dengan atribut id yang mengidentifikasinya sebagai "partners".
•	Ini berisi informasi tentang cara memesan produk, dengan daftar tautan ke layanan pengiriman makanan seperti Go Food, Shopee Food, dan Grab Food.
9.	<div id="contact">: Ini adalah bagian keempat dari halaman web yang berisi informasi kontak tentang bisnis "SI CAKIES." Ini mencakup alamat fisik, media sosial, dan nomor telepon.
10.	<div id="copyright">: Ini adalah bagian terakhir dari halaman web yang berisi hak cipta dan nama situs.



























CSS
 
 
1.	@import url('https://fonts.googleapis.com/css?family=Poppins:400,500,600,700&display=swap');: Ini adalah aturan untuk mengimpor font Poppins dari Google Fonts. Font ini akan digunakan dalam halaman web dan dapat diakses dalam berbagai berat (400, 500, 600, dan 700).
2.	*{ text-decoration: none; margin: 0px; padding: 0px; }: Ini adalah CSS reset. Ini menghilangkan dekorasi teks bawaan, seperti garis bawah dari tautan (link), dan mengatur margin serta padding elemen-elemen HTML menjadi 0px.
3.	body{ margin: 0px; padding: 0px; font-family: poppins; }: Ini mengatur gaya dasar untuk elemen body. Mengatur margin dan padding ke 0px, serta mengatur font yang akan digunakan sebagai Poppins.
4.	.wrapper{ width: 1100px; margin: auto; position: relative; }: Ini mengatur kelas "wrapper" untuk memiliki lebar 1100px dan berada di tengah halaman dengan margin: auto. Ini juga memiliki posisi relatif.
5.	.judul a{ font-size: 50px; font-weight: 800; float: left; color: #d0d9c4; }: Ini mengatur tampilan untuk judul di dalam navigasi. Mengatur ukuran font, berat teks, membuatnya mengapung di sebelah kiri, dan mengubah warna teks.
6.	.menu{ float: right; }: Ini mengatur menu navigasi agar mengapung di sebelah kanan.
7.	nav{ /* CSS untuk elemen navigasi */ }: Ini adalah pengaturan untuk elemen <nav>, seperti lebar, warna latar belakang, dan elemen menunjukkan di atas elemen lain dengan z-index.
8.	.nav ul{ /* CSS untuk daftar tidak berurutan di dalam navigasi */ }: Ini mengatur tampilan daftar tautan di dalam elemen navigasi, menghilangkan daftar, dan mengatur tautan agar mengapung di sebelah kiri.
9.	.nav ul li a{ /* CSS untuk tautan di dalam daftar navigasi */ }: Ini mengatur tampilan tautan di dalam daftar navigasi, termasuk ukuran font, warna teks, dan padding.
10.	.nav ul li a:hover{ /* CSS untuk tautan saat dihover */ }: Ini mengatur tampilan tautan saat kursor diarahkan ke atasnya dengan mengubah dekorasi teks menjadi "underline."
11.	.section{ /* CSS untuk elemen section */ }: Ini adalah pengaturan umum untuk elemen <section>.
12.	#home{ /* CSS untuk bagian "home" */ }: Ini adalah pengaturan tampilan khusus untuk elemen dengan ID "home."
13.	.kelas1{ /* CSS untuk elemen dengan kelas "kelas1" */ }: Ini mengatur tampilan untuk elemen dengan kelas "kelas1."
14.	.gambar1, .gambar2, .gambar3{ /* CSS untuk elemen dengan kelas "gambar1", "gambar2", dan "gambar3" */ }: Ini mengatur tampilan untuk elemen dengan kelas "gambar1", "gambar2", dan "gambar3."
15.	.tengah{ /* CSS untuk elemen "tengah" */ }: Ini mengatur tampilan untuk elemen dengan kelas "tengah."
16.	.partner-list{ /* CSS untuk daftar mitra */ }: Ini mengatur tampilan daftar mitra.
17.	.kartu-partner{ /* CSS untuk elemen mitra */ }: Ini mengatur tampilan elemen mitra dalam daftar, termasuk lebar dan jarak margin.
18.	#contact{ /* CSS untuk bagian "contact" */ }: Ini adalah pengaturan tampilan khusus untuk elemen dengan ID "contact."
19.	.footer{ /* CSS untuk elemen footer */ }: Ini mengatur tampilan elemen footer, termasuk lebar dan tata letaknya.
20.	.footer-section{ /* CSS untuk bagian footer */ }: Ini mengatur tampilan elemen-elemen dalam footer, seperti lebar dan margin.
21.	#copyright{ /* CSS untuk elemen "copyright" */ }: Ini adalah pengaturan tampilan khusus untuk elemen dengan ID "copyright."
22.	.beli{ /* CSS untuk tautan "Beli" */ }: Ini mengatur tampilan tautan "Beli," termasuk warna latar belakang dan padding.


























HTML LOGIN
 





1.	<!DOCTYPE html>: Ini adalah deklarasi tipe dokumen HTML yang digunakan dalam dokumen. Ini memberi tahu browser bahwa ini adalah dokumen HTML.
2.	<html lang="en">: Ini adalah elemen root yang membungkus seluruh konten halaman web. Atribut lang mengindikasikan bahwa bahasa yang digunakan dalam dokumen adalah bahasa Inggris (English).
3.	<head>: Bagian ini mengandung informasi tentang halaman web, seperti meta tag, judul halaman, dan tautan ke berkas-berkas eksternal.
•	<meta charset="UTF-8">: Menentukan bahwa karakter set yang digunakan dalam halaman web adalah UTF-8, yang mendukung karakter internasional.
•	<meta name="viewport" content="width=device-width, initial-scale=1.0">: Ini adalah pengaturan tampilan responsif untuk perangkat seluler.
•	<title>Membuat Form Login</title>: Ini adalah judul halaman yang akan ditampilkan di tab browser.
•	<link rel="stylesheet" href="./stylelogin.css">: Ini adalah tautan ke berkas CSS eksternal (stylelogin.css) yang akan mengatur tampilan halaman.
4.	<body>: Ini adalah elemen yang mengandung semua konten yang akan ditampilkan di halaman web.
5.	.wrapper: Ini adalah div dengan kelas "wrapper" yang mengelompokkan konten halaman.
•	.title-text: Ini adalah div yang berisi judul-judul form.
•	.title.login: Ini adalah judul untuk formulir login.
•	.title.signup: Ini adalah judul untuk formulir pendaftaran.
6.	.form-container: Ini adalah div yang berisi formulir-login dan formulir-pendaftaran.
•	.slide-controls: Ini adalah div yang mengandung kontrol pemilihan formulir (login atau signup).
•	<input type="radio" name="slide" id="login" checked>: Ini adalah input radio yang digunakan untuk memilih formulir login. Atribut checked berarti formulir ini akan ditampilkan secara default.
•	<input type="radio" name="slide" id="signup">: Ini adalah input radio yang digunakan untuk memilih formulir pendaftaran.
•	<label for="login" class="slide login">Login</label>: Ini adalah label yang digunakan untuk memilih formulir login.
•	<label for="signup" class="slide signup">Daftar</label>: Ini adalah label yang digunakan untuk memilih formulir pendaftaran.
•	.slider-tab: Ini adalah elemen yang berfungsi sebagai penunjuk yang akan bergeser saat memilih formulir.
7.	.form-inner: Ini adalah div yang berisi formulir-login dan formulir-pendaftaran.
•	<form action="#" class="login">: Ini adalah formulir login. Atribut class menunjukkan bahwa ini adalah formulir login.
•	.field: Ini adalah div yang mengelompokkan input fields.
•	<input type="text" placeholder="Masukan Email " required>: Ini adalah input field untuk memasukkan alamat email.
•	<input type="password" placeholder="Masukan Password" required>: Ini adalah input field untuk memasukkan kata sandi.
•	.pass-link: Ini adalah div yang berisi tautan "Lupa password?".
•	.field.btn: Ini adalah div yang berisi tombol "Login" yang akan mengirimkan formulir.
•	.signup-link: Ini adalah div yang berisi tautan "Buat akun!" untuk menuju formulir pendaftaran.

•	<form action="#" class="signup">: Ini adalah formulir pendaftaran. Atribut class menunjukkan bahwa ini adalah formulir pendaftaran.
•	.field: Ini adalah div yang mengelompokkan input fields untuk pendaftaran.
•	<input type="text" placeholder="Masukan Nama" required>: Ini adalah input field untuk memasukkan nama.
•	<input type="text" placeholder="Masukan Email" required>: Ini adalah input field untuk memasukkan alamat email.
•	<input type="password" placeholder="Masukan Password" required>: Ini adalah input field untuk memasukkan kata sandi.
•	<input type="password" placeholder="Ulangi password" required>: Ini adalah input field untuk mengulangi kata sandi.
•	.field.btn: Ini adalah div yang berisi tombol "Daftar" yang akan mengirimkan formulir pendaftaran.
•	.signup-link: Ini adalah div yang berisi tautan "Sudah punya akun?" untuk menuju formulir login.
8.	<script src="./script.js"></script>: Ini adalah tautan ke berkas JavaScript eksternal (script.js) yang akan menambahkan fungsi ke halaman web.















CSS
 




 
1.	@import url('https://fonts.googleapis.com/css?family=Poppins:400,500,600,700&display=swap');: Ini adalah aturan CSS yang mengimpor font Poppins dari Google Fonts. Font ini akan digunakan dalam tampilan halaman.
2.	*: Ini adalah selektor universal yang memengaruhi semua elemen pada halaman. Beberapa properti CSS diterapkan pada semua elemen, termasuk margin, padding, box-sizing, dan font-family.
3.	html, body: Ini adalah selektor yang memengaruhi elemen html dan body. Ini mengatur beberapa properti CSS seperti display: grid untuk mengatur konten halaman di tengah, height dan width sebesar 100% untuk mengisi seluruh area layar, dan background-image untuk membuat latar belakang dalam bentuk radial gradient.
4.	::selection: Ini adalah selektor pseudo-elemen yang mengubah tampilan teks yang dipilih. Dalam hal ini, teks yang dipilih akan memiliki latar belakang biru (#1a75ff) dan warna teks putih.
5.	.wrapper: Ini adalah kelas yang digunakan untuk menggambarkan kotak pembungkus yang berisi semua konten. Beberapa properti seperti overflow, max-width, background, padding, border-radius, dan box-shadow digunakan untuk mengatur tampilan wrapper ini.
6.	.wrapper .title-text: Ini adalah div yang berisi judul-judul formulir.
7.	.wrapper .title: Ini adalah judul formulir. Beberapa properti seperti font-size, font-weight, dan text-align digunakan untuk mengatur tampilan judul ini.
8.	.wrapper .slide-controls: Ini adalah div yang berisi kontrol pemilihan formulir (login atau signup). Beberapa properti CSS seperti position, display, height, dan border digunakan untuk mengatur tampilan kontrol ini.
9.	.slide-controls .slide: Ini adalah elemen yang memungkinkan pengguna memilih formulir (login atau signup). Properti seperti height, width, font-size, font-weight, dan text-align digunakan untuk mengatur tampilan elemen ini.
10.	.slide-controls label.signup: Ini adalah label untuk elemen signup.
11.	.slide-controls .slider-tab: Ini adalah elemen yang menunjukkan status pemilihan formulir dengan perpindahan warna.
12.	input[type="radio"]: Ini adalah input radio yang digunakan untuk memilih formulir. Properti display: none digunakan untuk menyembunyikan input ini.
13.	#signup:checked~.slider-tab: Ini adalah aturan yang mengatur tampilan slider-tab ketika formulir signup dipilih (checked). Properti left diubah menjadi 50% untuk menunjukkan pemilihan formulir signup.
14.	#signup:checked~label.signup: Ini adalah aturan yang mengubah tampilan label signup ketika formulir signup dipilih. Warna teks diubah menjadi putih, dan beberapa properti seperti cursor dan user-select diatur.
15.	#signup:checked~label.login: Ini adalah aturan yang mengubah tampilan label login ketika formulir signup dipilih. Ini mengatur properti cursor dan user-select.
16.	#login:checked~label.signup: Ini adalah aturan yang mengubah tampilan label signup ketika formulir login dipilih. Warna teks diubah menjadi hitam.
17.	#login:checked~label.login: Ini adalah aturan yang mengubah tampilan label login ketika formulir login dipilih. Ini mengatur properti cursor dan user-select.
18.	.form-container: Ini adalah div yang berisi formulir-login dan formulir-pendaftaran.
19.	.form-container .form-inner: Ini adalah div yang berisi formulir-login dan formulir-pendaftaran. Properti display diatur menjadi flex untuk mengatur tampilan elemen secara horizontal.
20.	.form-container .form-inner form: Ini adalah formulir login dan pendaftaran. Properti width diatur menjadi 50% untuk membagi tampilan menjadi dua kolom.
21.	.form-inner form .field: Ini adalah div yang mengelompokkan elemen input dalam formulir. Properti seperti height, width, dan margin-top digunakan untuk mengatur tampilan field ini.
22.	.form-inner form .field input: Ini adalah input field dalam formulir. Beberapa properti seperti height, width, outline, padding, border-radius, border, dan font-size digunakan untuk mengatur tampilan input.
23.	.form-inner form .field input:focus: Ini adalah tampilan input saat fokus di atasnya. Warna border diubah menjadi biru (#1a75ff).
24.	.form-inner form .field input::placeholder: Ini mengatur tampilan placeholder pada input field.
25.	form .field input:focus::placeholder: Ini adalah tampilan placeholder saat input di dalamnya mendapat fokus.
26.	.form-inner form .pass-link dan .form-inner form .signup-link: Ini adalah tautan yang menghubungkan ke halaman lupa kata sandi atau pendaftaran. Beberapa properti seperti color dan text-decoration digunakan untuk mengatur tampilan tautan ini.
27.	form .btn: Ini adalah div yang berisi tombol formulir. Properti seperti height, width, border-radius, position, dan overflow digunakan untuk mengatur tampilan tombol.
28.	form .btn .btn-layer: Ini adalah elemen yang digunakan untuk menampilkan lapisan latar belakang pada tombol. Properti left digunakan untuk mengatur lapisan pada posisi awal yang tersembunyi.
29.	form .btn:hover .btn-layer: Ini adalah tampilan saat tombol mendapat sorotan saat pengguna mengarahkan kursor ke atasnya. Lapisan latar belakang diubah untuk menciptakan efek transisi.
30.	form .btn input[type="submit"]: Ini adalah tombol "Submit" dalam formulir. Properti seperti height, width, z-index, background, border, color, padding, border-radius, font-size, dan cursor digunakan untuk mengatur tampilan tombol.










JAVASCRIPT
 
1.	const loginText = document.querySelector(".title-text .login");: Ini adalah deklarasi variabel loginText yang digunakan untuk memilih elemen dengan kelas .login yang berada dalam elemen dengan kelas .title-text. Ini mengacu pada elemen judul "Form Login" di halaman.
2.	const loginForm = document.querySelector("form.login");: Ini adalah deklarasi variabel loginForm yang digunakan untuk memilih elemen <form> dengan kelas .login. Ini mengacu pada formulir login di halaman.
3.	const loginBtn = document.querySelector("label.login");: Ini adalah deklarasi variabel loginBtn yang digunakan untuk memilih elemen <label> dengan kelas .login. Ini mengacu pada label "Login" yang memungkinkan pengguna beralih ke formulir login.
4.	const signupBtn = document.querySelector("label.signup");: Ini adalah deklarasi variabel signupBtn yang digunakan untuk memilih elemen <label> dengan kelas .signup. Ini mengacu pada label "Daftar" yang memungkinkan pengguna beralih ke formulir pendaftaran.
5.	const signupLink = document.querySelector("form .signup-link a");: Ini adalah deklarasi variabel signupLink yang digunakan untuk memilih tautan <a> yang berada dalam elemen dengan kelas .signup-link. Ini mengacu pada tautan "Daftar sekarang" yang memungkinkan pengguna beralih ke formulir pendaftaran.
6.	signupBtn.onclick = (() => { ... });: Ini adalah event handler yang akan dijalankan ketika label "Daftar" diklik. Ketika pengguna mengklik label "Daftar", formulir login akan bergerak ke kiri (dengan mengubah marginLeft menjadi -50%), dan judul "Form Login" juga akan bergerak ke kiri. Ini menciptakan efek transisi ke formulir pendaftaran.
7.	loginBtn.onclick = (() => { ... });: Ini adalah event handler yang akan dijalankan ketika label "Login" diklik. Ketika pengguna mengklik label "Login", formulir login akan kembali ke posisi awal (dengan mengubah marginLeft menjadi 0%), dan judul "Form Login" juga akan kembali ke posisi awal. Ini mengembalikan tampilan ke formulir login.
8.	signupLink.onclick = (() => { ... });: Ini adalah event handler yang akan dijalankan ketika tautan "Daftar sekarang" diklik. Ketika pengguna mengklik tautan ini, sebenarnya itu mengaktifkan klik pada label "Daftar" (dengan signupBtn.click()) untuk mengalihkan tampilan ke formulir pendaftaran. Ini juga mengembalikan false untuk mencegah peristiwa default dari tautan tersebut.

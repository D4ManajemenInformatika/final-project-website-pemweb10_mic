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
   ![image](https://github.com/D4ManajemenInformatika/final-project-website-pemweb10_mic/assets/120777302/35e5fc63-3cc5-4a68-a175-ee3f4f168036)

   B. Usecase
![image](https://github.com/D4ManajemenInformatika/final-project-website-pemweb10_mic/assets/120777302/a6d7a8b6-7038-4f40-b770-e5055717f413)

4. Penjelasan Code

   A. Html

   ![image](https://github.com/D4ManajemenInformatika/final-project-website-pemweb10_mic/assets/124486941/f45a2db0-d8b0-4bf0-8ded-932911b34bcc)



[!DOCTYPE html]: Ini adalah deklarasi tipe dokumen HTML yang digunakan dalam dokumen. Ini memberi tahu browser bahwa ini adalah dokumen HTML.

[html lang="en"]: Ini adalah elemen root yang membungkus seluruh konten halaman web.

Atribut lang mengindikasikan bahwa bahasa yang digunakan dalam dokumen adalah bahasa Inggris (English).

[head]: Bagian ini mengandung informasi tentang halaman web, seperti meta tag, judul halaman, dan tautan ke berkas-berkas eksternal seperti CSS.

• [meta charset="UTF-8"]: Menentukan bahwa karakter set yang digunakan dalam halaman web adalah UTF-8, yang mendukung karakter internasional.

• [meta name="viewport" content="width=device-width, initial-scale=1.0"]: Ini adalah pengaturan untuk mengatur tampilan halaman web di perangkat seluler. Itu akan mengizinkan tampilan responsif pada perangkat berlayar kecil.

• [title]tugas[/title]: Ini adalah judul dari halaman web yang akan ditampilkan di tab browser.

• [link rel="stylesheet" href="satu.css"]: Ini adalah tautan ke berkas CSS eksternal dengan nama "satu.css" yang akan mengatur tampilan halaman.

[body]: Ini adalah elemen yang mengandung semua konten yang akan ditampilkan di halaman web, termasuk navigasi, teks, gambar, dan lainnya.

[nav]: Ini adalah elemen yang mengandung elemen-elemen yang membentuk menu navigasi situs web.

• [div class="wrapper"]: Ini adalah div dengan kelas "wrapper" yang digunakan untuk mengelompokkan elemen-elemen dalam navigasi.

• [div class="judul"]: Ini adalah div dengan kelas "judul" yang berisi tautan (link) ke halaman utama situs ("SI CAKIES").

• [div class="menu"]: Ini adalah div dengan kelas "menu" yang berisi daftar tautan navigasi dalam sebuah daftar tidak berurutan (unordered list).

[section id="home"]: Ini adalah bagian pertama dari halaman web, dengan atribut id yang digunakan untuk menandai bagian ini.

• [img src="logo.png" width="40%"]: Ini adalah elemen gambar yang menampilkan logo dengan lebar 40% dari lebar kontainer.

• [div class="kolom"]: Ini adalah div dengan kelas "kolom" yang berisi teks dan informasi tentang situs web.

• Beberapa paragraf dan poin dijelaskan dengan tag [p].

• Ada pula tautan "Pelajari Lebih Lanjut" dengan kelas "tombol".

[section id="courses"]: Ini adalah bagian kedua dari halaman web dengan atribut id yang mengidentifikasinya sebagai "courses".

• Ini berisi informasi tentang produk-produk yang ditawarkan, termasuk gambar produk dan harga.

• Setiap produk ditempatkan dalam div dengan kelas "gambar1," "gambar2," dan "gambar3."

[section id="partners"]: Ini adalah bagian ketiga dari halaman web dengan atribut id yang mengidentifikasinya sebagai "partners".

• Ini berisi informasi tentang cara memesan produk, dengan daftar tautan ke layanan pengiriman makanan seperti Go Food, Shopee Food, dan Grab Food.
[div id="contact"]: Ini adalah bagian keempat dari halaman web yang berisi informasi kontak tentang bisnis "SI CAKIES." Ini mencakup alamat fisik, media sosial, dan nomor telepon.

[div id="copyright"]: Ini adalah bagian terakhir dari halaman web yang berisi hak cipta dan nama situs.

B. CSS

![image](https://github.com/D4ManajemenInformatika/final-project-website-pemweb10_mic/assets/124486941/c05ee1c7-36c7-4e5b-b967-e5e39c3cd321)

![image](https://github.com/D4ManajemenInformatika/final-project-website-pemweb10_mic/assets/124486941/9a63385a-c899-4380-b68a-b551603022b0)



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


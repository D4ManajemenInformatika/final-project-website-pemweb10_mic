

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

![image](https://github.com/D4ManajemenInformatika/final-project-website-pemweb10_mic/assets/124486941/820cd24c-c5e0-464e-8735-a1824389abe7)


 [body]: Ini adalah elemen HTML yang menunjukkan awal dari konten halaman web yang akan ditampilkan kepada pengguna. Semua elemen HTML yang terlihat di halaman web akan ditempatkan di dalam elemen body ini.
 
[nav]: Ini adalah elemen HTML yang digunakan untuk menentukan bagian navigasi dalam halaman web. Biasanya, elemen ini berisi tautan-tautan menu untuk membantu pengguna berpindah antara halaman atau bagian halaman web.

[div class="wrapper"]: Ini adalah elemen div dengan atribut class yang disebut "wrapper." Elemen div digunakan untuk mengelompokkan atau mengelencengkan sejumlah elemen HTML untuk mengaplikasikan gaya CSS atau JavaScript tertentu. Di sini, "wrapper" mungkin digunakan untuk mengelompokkan elemen-elemen lain dalam tampilan yang sama.

[div class="judul"]: Ini adalah elemen div dengan atribut class yang disebut "judul." Sepertinya ini digunakan untuk mengelompokkan judul atau logo situs web. Terdapat juga sebuah tautan (a) yang kosong di dalamnya yang kemungkinan besar akan ditautkan ke halaman beranda atau ke URL lain.

[div class="menu"]: Ini adalah elemen div dengan atribut class yang disebut "menu." Ini mungkin digunakan untuk mengelompokkan elemen-elemen menu.

[ul]: Ini adalah elemen unordered list (daftar tak terurut) yang digunakan untuk membuat daftar item yang berisi tautan menu.

[li]: Ini adalah elemen list item yang merupakan anak-anak dari elemen ul. Setiap li adalah item dalam daftar menu.

[a]: Ini adalah elemen anchor (tautan) yang digunakan untuk membuat tautan ke halaman lain atau ke bagian lain di halaman web yang saat ini dilihat. Setiap tautan memiliki atribut href yang menentukan URL tautan.

[a] dengan class "signup": Ini adalah tautan yang memiliki class "signup." Class ini mungkin digunakan untuk memberikan tampilan atau perilaku yang berbeda untuk tautan ini, misalnya, tautan "Join Us!" dapat diubah warnanya dengan CSS.

![image](https://github.com/D4ManajemenInformatika/final-project-website-pemweb10_mic/assets/124486941/1972636f-545a-4cda-81cc-e0fb11c124c0)

 [div class="wrapper"]: Ini adalah elemen div dengan atribut class yang disebut "wrapper.
 
" Elemen ini mungkin digunakan untuk mengelompokkan sejumlah elemen HTML dalam tampilan yang sama, seperti yang mungkin diperlukan untuk mengatur tata letak halaman.

[section id="home"]: Ini adalah elemen section dengan atribut id yang disebut "home." Elemen section biasanya digunakan untuk mengelompokkan konten yang memiliki kesamaan tematik atau fungsional dalam halaman web. 

Atribut id "home" digunakan untuk mengidentifikasi elemen ini secara unik, yang dapat digunakan untuk menghubungkannya dengan tautan tertentu atau gaya CSS khusus.

img src="logo.png" width="40%": Ini adalah elemen gambar (img) yang menampilkan gambar dengan atribut src yang merujuk pada file gambar "logo.png." Atribut width digunakan untuk mengatur lebar gambar menjadi 40% lebar elemen yang mengandung gambar ini. [div class="kolom"]: Ini adalah elemen div dengan atribut class "kolom."

Sepertinya ini digunakan untuk mengelompokkan konten teks yang akan ditampilkan dalam kolom tertentu. [h2]SELAMAT DATANG[/h2]: Ini adalah elemen heading level 2 yang berisi teks "SELAMAT DATANG." Heading digunakan untuk menyoroti judul atau bagian penting dari konten.

[p style="text-indent: 45px;"] ... [/p]: Ini adalah elemen paragraf (p) dengan gaya CSS inline yang mengatur tata letak paragraf.

Gaya CSS "text-indent: 45px" digunakan untuk membuat indentasi teks sebesar 45 piksel. Paragraf ini berisi deskripsi tentang produk Cakies atau Cake and Cookies.

[p] ... [/p]: Ini adalah elemen paragraf lainnya yang berisi daftar kelebihan produk. Daftar ini diawali dengan teks "Kelebihan Produk (Strength)" dan diikuti oleh beberapa poin yang menjelaskan keunggulan produk tersebut.

[p][a href="" class="tombol"]Pelajari Lebih Lanjut[/a][/p]: Ini adalah elemen paragraf yang berisi tautan ("a") dengan atribut class "tombol."

Tautan ini mungkin digunakan untuk mengarahkan pengguna ke halaman lain atau sumber informasi tambahan. Saat ini, atribut href kosong, sehingga tidak ada URL yang ditautkan.


![image](https://github.com/D4ManajemenInformatika/final-project-website-pemweb10_mic/assets/124486941/e99a35b7-b798-481e-8971-4ba7af14ed3c)

![image](https://github.com/D4ManajemenInformatika/final-project-website-pemweb10_mic/assets/124486941/61988af0-6905-4c1f-9f02-fa92060b3376)

 div class="kolom": Ini adalah wadah utama yang mengelompokkan seluruh konten dalam bagian "courses". Konten produk akan ditampilkan dalam tiga kolom yang berbeda.

[div class="kelas1"]: Ini adalah elemen yang berisi judul "Product Kami". Judul ini mengidentifikasi bahwa bagian ini adalah tentang produk yang ditawarkan.

[div class="gambar1"]: Ini adalah kolom pertama yang berisi informasi tentang produk pertama.

[img src="cokies.jpeg" align="left" width="250px" height="200px"]: Ini adalah gambar produk (kue Cookies) dengan atribut sumber gambar, penyesuaian ke kiri (align), lebar, dan tinggi.

[h4]Kue Cookies[/h4]: Ini adalah judul produk "Kue Cookies".

[p]...: Ini adalah deskripsi produk yang menjelaskan produk ("Cookies dengan permukaan coklat...") dan harga produk ("Rp 4.000/pcs").

[p][a href="" class="beli"]Beli[/a][/p]: Ini adalah tautan "Beli" yang mungkin mengarahkan pengguna ke halaman atau tindakan pembelian.


[div class="gambar2"]: Ini adalah kolom kedua yang berisi informasi tentang produk kedua (Kue Lumpur) dengan format yang sama seperti produk pertama.

[div class="gambar3"]: Ini adalah kolom ketiga yang berisi informasi tentang produk ketiga (Kue Tart) dengan format yang sama seperti produk pertama.


![image](https://github.com/D4ManajemenInformatika/final-project-website-pemweb10_mic/assets/124486941/fd21fe27-9661-4af1-8697-40167a0bc506)

section id="partners": Ini adalah elemen section yang memiliki atribut id "partners." Elemen section digunakan untuk mengelompokkan konten yang berkaitan dengan topik atau sebagian halaman tertentu. Dalam hal ini, elemen ini mungkin berisi informasi tentang mitra atau layanan pemesanan.
div class="tengah": Ini adalah elemen div dengan atribut class "tengah." Elemen ini mungkin digunakan untuk mengatur tata letak konten dalam "section" agar tengah atau terpusat pada halaman.
div class="kolom": Ini adalah elemen div dengan atribut class "kolom." Elemen ini digunakan untuk mengelompokkan teks dan mungkin digunakan untuk memberikan tampilan atau gaya khusus pada bagian ini.
h2Pemesananh2: Ini adalah elemen heading level 2 yang berisi teks "Pemesanan." Ini adalah judul bagian yang berkaitan dengan pemesanan produk.
p style="text-align: center;" ... /p: Ini adalah elemen paragraf dengan gaya CSS inline yang mengatur tata letak paragraf menjadi tengah dengan "text-align: center." Paragraf ini berisi teks yang menjelaskan bahwa produk kue dapat dipesan melalui aplikasi dan layanan pengiriman.
div class="partner-list": Ini adalah elemen div dengan atribut class "partner-list." Elemen ini mungkin digunakan untuk mengelompokkan daftar mitra atau platform pemesanan.
div class="kartu-partner": Ini adalah elemen div dengan atribut class "kartu-partner." Elemen ini digunakan untuk mengelencengkan setiap mitra atau platform pemesanan.
a href="https://gofood.co.id/en": Ini adalah elemen anchor (tautan) dengan atribut href yang mengarahkan ke situs web Go Food. Ketika pengguna mengklik tautan ini, mereka akan diarahkan ke situs Go Food.
img src="shopefood.png": Ini adalah elemen gambar yang menampilkan gambar logo atau ikon Go Food. Gambar ini mungkin digunakan untuk mengidentifikasi mitra tersebut.
pGo Food p: Ini adalah elemen paragraf yang berisi teks "Go Food," yang mungkin digunakan untuk memberikan label pada mitra.

![image](https://github.com/D4ManajemenInformatika/final-project-website-pemweb10_mic/assets/124486941/7084e024-cceb-4b7d-8376-383e66885dea)

![image](https://github.com/D4ManajemenInformatika/final-project-website-pemweb10_mic/assets/124486941/83a7a8da-d878-4754-af91-62ed24f09f15)

div id="contact": Ini adalah elemen div dengan atribut id "contact." Elemen ini mungkin digunakan untuk mengelompokkan konten yang berkaitan dengan informasi kontak, seperti alamat dan rincian kontak.
div class="wrapper": Ini adalah elemen div dengan atribut class "wrapper." Sepertinya ini digunakan untuk mengelencengkan konten ke tengah atau untuk mengaplikasikan gaya tertentu pada bagian ini.
div class="footer": Ini adalah elemen div dengan atribut class "footer." Elemen ini mungkin digunakan untuk mengelencengkan dan mengelompokkan konten di dalam bagian footer halaman web.
div class="footer-section": Ini adalah elemen div dengan atribut class "footer-section." Sepertinya ini digunakan untuk mengelencengkan setiap bagian dalam footer, termasuk "SI CAKIES," "Contact," dan "Social."
h3SI CAKIES/h3: Ini adalah elemen heading level 3 yang berisi teks "SI CAKIES." Ini mungkin digunakan untuk menyoroti nama atau judul halaman web.
h3Contact/h3: Ini adalah elemen heading level 3 yang berisi teks "Contact." Ini digunakan untuk menandai bagian yang berisi informasi kontak.
Alamat dan rincian kontak: Informasi kontak seperti alamat fisik, nomor telepon, dan kode pos diberikan dalam elemen paragraf (p). Ini adalah informasi kontak yang dapat digunakan oleh pengguna untuk menghubungi pemilik situs web.
h3Socia/h3: Ini adalah elemen heading level 3 yang berisi teks "Social." Ini mungkin digunakan untuk menandai bagian yang berisi tautan ke akun media sosial.
div id="copyright": Ini adalah elemen div dengan atribut id "copyright." Elemen ini mungkin digunakan untuk mengelompokkan informasi hak cipta.

B. CSS

![image](https://github.com/D4ManajemenInformatika/final-project-website-pemweb10_mic/assets/124486941/0928876c-851c-4695-833e-2f1ff124e0ad)

![image](https://github.com/D4ManajemenInformatika/final-project-website-pemweb10_mic/assets/124486941/83cf4d89-5eec-4b66-a693-8262a807c20b)

@import url('https://fonts.googleapis.com/css?family=Poppins:400,500,600,700&display=swap');: Ini adalah aturan @import yang mengimpor jenis font "Poppins" dari Google Fonts. Font ini memiliki beberapa varian berat (400, 500, 600, dan 700) yang dapat digunakan dalam halaman web Anda.
*{ text-decoration: none; margin: 0px; padding: 0px; }: Ini adalah reset CSS dasar yang menghilangkan dekorasi tautan (underline), mengatur margin dan padding ke nol untuk semua elemen HTML, dan menghapus sebagian besar gaya default yang diterapkan oleh browser.
body{ margin: 0px; padding: 0px; font-family: poppins; }: Ini mengatur margin dan padding elemen "body" menjadi nol dan mengatur jenis font default untuk seluruh halaman web sebagai "Poppins."
.wrapper{ … }: Ini adalah gaya untuk elemen dengan class "wrapper." Pengaturan termasuk: width: 1100px;: Mengatur lebar elemen "wrapper" menjadi 1100 piksel.margin: auto;:  Mengatur elemen "wrapper" agar berada di tengah secara horizontal dalam tata letak. position: relative;: Mengatur elemen ini dengan posisi relatif.
.judul a{ ... }: Ini adalah gaya untuk elemen dengan class "judul" yang berisi tautan (anchor). Beberapa pengaturan termasuk: font-size: 50px;: Mengatur ukuran teks menjadi 50 piksel. font-weight: 800; font-weight: bold;: Mengatur berat font menjadi bold dan dengan nilai numerik 800. float: left;: Mengatur tautan agar mengapung ke sisi kiri. font-family: 'montserrat', poppins, poppins;: Mengatur jenis font dengan prioritas yang berisi "montserrat" dan jika tidak tersedia, maka "Poppins" digunakan. color: #d0d9c4;: Mengatur warna teks menjadi "#d0d9c4."
.wrapper p{ text-indent: 45px; }: Ini adalah gaya untuk elemen paragraf yang berada dalam elemen dengan class "wrapper." Ini mengatur indentasi teks paragraf sejauh 45 piksel dari margin kiri.
.menu{ float: right; }: Ini mengatur elemen dengan class "menu" agar mengapung ke sisi kanan.
nav { ... }: Ini adalah gaya untuk elemen "nav." Beberapa pengaturan termasuk: width: 100%;: Mengatur lebar elemen "nav" menjadi 100% lebar tampilan. margin: auto;: Mengatur elemen "nav" agar berada di tengah secara horizontal. display: flex;: Mengatur elemen "nav" agar menggunakan tata letak fleksibel (flex layout).line-height: 80px;: Mengatur ketinggian garis teks (line-height) menjadi 80 piksel. position: sticky; position: -webkit-sticky; top: 0;: Mengatur elemen "nav" agar menempel di bagian atas layar saat pengguna menggulir halaman (sticky navigation). background: #618264;: Mengatur latar belakang elemen "nav" menjadi warna #618264 (hijau). z-index: 1;: Mengatur indeks-z untuk mengontrol tumpukan elemen, yang mungkin diperlukan ketika elemen "nav" menempel di atas elemen lain.border-bottom: 5px solid #fefefe;: Menambahkan garis bawah dengan ketebalan 5 piksel dan warna #fefefe  pada elemen "nav."

![image](https://github.com/D4ManajemenInformatika/final-project-website-pemweb10_mic/assets/124486941/bc8dce29-bc69-483d-8c98-c66ee3b6e100)

nav ul { ... }: Ini adalah gaya yang diterapkan pada elemen ul (unordered list) yang berada dalam elemen "nav." Beberapa pengaturan termasuk: list-style-type: none;: Menghilangkan tanda penomoran atau poin yang biasanya muncul di daftar. margin: 0; padding: 0;: Menghapus margin dan padding bawaan dari elemen ul. overflow: hidden;: Mengatasi masalah "float" di elemen-elemen anak sehingga elemen "nav" meliputi elemen anak yang mengapung.
nav ul li { ... }: Ini adalah gaya yang diterapkan pada elemen li (list item) yang berada dalam elemen ul dalam elemen "nav." Ini mengatur elemen-elemen li agar mengapung ke sisi kiri (float: left), sehingga menu navigasi akan disusun secara horizontal.
nav ul li a { ... }: Ini adalah gaya yang diterapkan pada elemen a (anchor) yang berada dalam elemen li dalam elemen ul dalam elemen "nav." Beberapa pengaturan termasuk: text-align: center;: Mengatur teks tautan agar terletak di tengah secara horizontal. color: hsl(35, 56%, 52%);: Mengatur warna teks tautan menggunakan model warna HSL.padding: 0px 16px 0px 16px;: Mengatur ruang di sekitar teks tautan, yaitu 16 piksel di sisi kanan dan kiri. text-decoration: none;: Menghilangkan garis bawah default yang muncul di tautan. font-weight: bold;: Mengatur teks tautan menjadi tebal (bold). font-size: 20px;: Mengatur ukuran font menjadi 20 piksel.
nav ul li a:hover { ... }: Ini adalah gaya yang diterapkan pada tautan saat pengguna mengarahkan kursor (hover) ke atasnya. Ini mengatur tautan agar memiliki garis bawah saat dihover.
section { ... }: Ini adalah gaya yang diterapkan pada elemen "section." Beberapa pengaturan termasuk: margin: auto;: Mengatur elemen "section" agar terletak di tengah secara horizontal dalam tata letak. display: flex;: Mengatur elemen "section" agar menggunakan tata letak fleksibel (flex layout). margin-bottom: 50px;: Menambahkan margin bawah sebanyak 50 piksel di antara elemen "section."
#home { ... }: Ini adalah gaya yang diterapkan pada elemen dengan id "home." Beberapa pengaturan termasuk: background: #F5F5DC;: Mengatur latar belakang elemen "home" menjadi warna #F5F5DC (beige). margin-left: -10%; margin-right: -5%;: Mengatur margin kiri dan kanan elemen "home" untuk membuatnya lebih lebar daripada lebar tampilan standar.
.kolom { ... }: Ini adalah gaya yang diterapkan pada elemen dengan class "kolom." Beberapa pengaturan termasuk: margin-top: 50px; margin-bottom: 50px;: Menambahkan margin atas dan bawah elemen "kolom" sebanyak 50 piksel. font-family: poppins, poppins, poppins;: Mengatur jenis font yang digunakan dalam elemen ini sebagai "Poppins." #courses { ... }: Ini adalah gaya yang diterapkan pada elemen dengan id "courses." Beberapa pengaturan termasuk: background: #d6ab81;: Mengatur latar belakang elemen "courses" menjadi warna #d6ab81 (cokelat muda). padding: 50px 0px 30px 0px;: Mengatur padding (ruang dalam elemen) pada elemen "courses."

![image](https://github.com/D4ManajemenInformatika/final-project-website-pemweb10_mic/assets/124486941/df85d6f6-830d-4fe8-84cc-83916ccfd8da)

![image](https://github.com/D4ManajemenInformatika/final-project-website-pemweb10_mic/assets/124486941/9d6d2531-6d2a-4da2-bd5e-1d8e928a2bed)

h2 { ... }: Ini adalah gaya yang diterapkan pada elemen heading level 2 (h2). Beberapa pengaturan termasuk: font-family: 'poppins';: Mengatur jenis font untuk teks h2 sebagai "Poppins." font-weight: 800;: Mengatur berat font menjadi 800, yang mungkin menghasilkan teks yang lebih tebal atau bold. font-size: 40px;: Mengatur ukuran font h2 menjadi 40 piksel. margin-bottom: 10px;: Menambahkan margin bawah sebanyak 10 piksel. margin-left: 5%;: Mengatur margin kiri sebanyak 5% dari lebar tampilan. width: 100%;: Mengatur lebar elemen h2 menjadi 100% dari lebar orang tua (jika ada). line-height: 50px;: Mengatur tinggi baris (line-height) h2 menjadi 50 piksel.
a.signup { ... } dan a.tombol { ... }: Ini adalah gaya yang diterapkan pada tautan dengan class "signup" dan "tombol." Beberapa pengaturan termasuk: background: #dac0a3;: Mengatur latar belakang tautan menjadi warna #dac0a3. border-radius: 20px;: Mengatur sudut tautan sehingga tampil dengan sudut bulat (border radius). margin-top: 20px;: Menambahkan margin atas sebanyak 20 piksel.padding: 15px 20px 15px 20px;: Mengatur ruang dalam tautan di sekitar  teks. color: #ffffff;: Mengatur warna teks tautan menjadi putih (#ffffff). cursor: pointer;: Mengubah ikon kursor saat mengarahkan ke tautan, menunjukkan bahwa itu adalah tautan yang dapat diklik. font-weight: bold;: Mengatur teks tautan menjadi tebal.
p { ... }: Ini adalah gaya yang diterapkan pada elemen paragraf (p). Beberapa pengaturan termasuk: margin: 10px 10px 10px 10px; padding: 10px 10px 10px 10px;: Mengatur margin dan padding paragraf sebanyak 10 piksel di semua sisi. text-align: justify;: Mengatur teks paragraf agar rata kanan-kiri (justified). 
.kelas1 { ... }: Ini adalah gaya yang diterapkan pada elemen dengan class "kelas1." Pengaturan termasuk: margin-left: 5%;: Mengatur margin kiri elemen sebanyak 5% dari lebar tampilan.
.gambar1 { ... } dan .gambar2 { ... }: Ini adalah gaya yang diterapkan pada elemen-elemen dengan class "gambar1" dan "gambar2." Beberapa pengaturan termasuk: margin: 3%;: Menambahkan margin sebanyak 3% dari semua sisi elemen. margin-top: 3%;: Menambahkan margin atas sebanyak 3%. display: block;: Mengubah elemen menjadi elemen blok yang memenuhi lebar orang tua dan tidak berbagi baris dengan elemen lain yang mungkin ada di sampingnya. margin-left: 5%;: Mengatur margin kiri sebanyak 5% dari lebar tampilan.

![image](https://github.com/D4ManajemenInformatika/final-project-website-pemweb10_mic/assets/124486941/e6ae9de8-c7bb-4990-b2f4-66fb05b457b6)

![image](https://github.com/D4ManajemenInformatika/final-project-website-pemweb10_mic/assets/124486941/b6f0323c-fc17-491a-bd2d-fbfad4d372d5)

.gambar3 { ... }: Ini adalah gaya yang diterapkan pada elemen dengan class "gambar3." Beberapa pengaturan termasuk: margin: 3%;: Menambahkan margin sebanyak 3% dari semua sisi elemen. margin-top: 1%;: Menambahkan margin atas sebanyak 1%. display: block;: Mengubah elemen menjadi elemen blok. margin-left: 5%;: Mengatur margin kiri elemen sebanyak 5% dari lebar tampilan. 
.tengah { ... }: Ini adalah gaya yang diterapkan pada elemen dengan class "tengah." Pengaturan termasuk: text-align: center;: Mengatur teks dalam elemen ini agar terletak di tengah secara horizontal. width: 95%;: Mengatur lebar elemen menjadi 95% dari lebar tampilan.
.partner-list { ... }: Ini adalah gaya yang diterapkan pada elemen dengan class "partner-list." Beberapa pengaturan termasuk: width: 100%;: Mengatur lebar elemen menjadi 100% dari lebar orang tua (container). position: relative;: Mengatur posisi elemen tersebut sebagai relatif. display: flex;: Mengatur elemen ini menggunakan tata letak fleksibel (flex layout). flex-wrap: wrap;: Mengatur elemen-elemen anak agar membungkus ke baris baru jika tidak cukup ruang.
.kartu-partner { ... }: Ini adalah gaya yang diterapkan pada elemen dengan class "kartu-partner." Pengaturan termasuk: width: 20%;: Mengatur lebar elemen menjadi 20% dari lebar orang tua (container). margin: 0 auto;: Mengatur margin atas dan bawah menjadi 0 dan margin kiri dan kanan secara otomatis agar elemen tetap di tengah.
.kartu-tutor img { ... }: Ini adalah gaya yang diterapkan pada gambar (img) yang mungkin ada dalam elemen dengan class "kartu-tutor." Pengaturan termasuk: width: 80%;: Mengatur lebar gambar menjadi 80% dari lebar elemen yang mengandungnya.
.kartu-tutor p { ... }: Ini adalah gaya yang diterapkan pada teks paragraf (p) yang mungkin ada dalam elemen dengan class "kartu-tutor." Beberapa pengaturan termasuk: font-family: 'poppins';: Mengatur jenis font teks sebagai "Poppins." font-weight: 800;: Mengatur berat font menjadi 800. font-size: 25px;: Mengatur ukuran font menjadi 25 piksel. text-align: center;: Mengatur teks agar terletak di tengah secara horizontal. color: rgb(13, 219, 219);: Mengatur warna teks menggunakan model warna RGB.
#contact { ... }: Ini adalah gaya yang diterapkan pada elemen dengan id "contact." Beberapa pengaturan termasuk: background: #dedede;: Mengatur latar belakang elemen "contact" menjadi warna #dedede. padding: 50px 0px 30px 0px;: Mengatur padding (ruang dalam elemen) pada elemen "contact." margin-left: -10%; margin-right: -5%;: Mengatur margin kiri dan kanan elemen "contact" untuk membuatnya lebih lebar daripada lebar tampilan standar.

![image](https://github.com/D4ManajemenInformatika/final-project-website-pemweb10_mic/assets/124486941/2e8adbeb-0400-405a-bf57-7891a39e2544)

![image](https://github.com/D4ManajemenInformatika/final-project-website-pemweb10_mic/assets/124486941/1f6341e6-6ded-4021-b850-c7ef60739ca8)

}
.footer { ... }: Ini adalah gaya yang diterapkan pada elemen dengan class "footer." Beberapa pengaturan termasuk: width: 100%;: Mengatur lebar elemen "footer" menjadi 100% dari lebar orang tua (container). position: relative;: Mengatur posisi elemen sebagai relatif. display: flex;: Mengatur elemen ini menggunakan tata letak fleksibel (flex layout). flex-wrap: wrap;: Mengatur elemen-elemen anak agar membungkus ke baris baru jika tidak cukup ruang. margin: auto;: Mengatur elemen "footer" agar berada di tengah secara horizontal.
.footer-section { ... }: Ini adalah gaya yang diterapkan pada elemen dengan class "footer-section." Beberapa pengaturan termasuk: width: 30%;: Mengatur lebar elemen "footer-section" menjadi 30% dari lebar orang tua (container). margin: 0 auto;: Mengatur margin kiri dan kanan elemen "footer-section" agar tetap di tengah.
h3 { ... }: Ini adalah gaya yang diterapkan pada elemen heading level 3 (h3). Beberapa pengaturan termasuk: font-family: 'poppins';: Mengatur jenis font untuk teks h3 sebagai "Poppins." font-weight: 800;: Mengatur berat font menjadi 800. font-size: 30px;: Mengatur ukuran font h3 menjadi 30 piksel. margin-bottom: 30px;: Menambahkan margin bawah sebanyak 30 piksel. color: #052822;: Mengatur warna teks menjadi #052822. width: 100%;: Mengatur lebar elemen h3 menjadi 100% dari lebar orang tua. line-height: 0px;: Mengatur tinggi baris (line-height) h3 menjadi 0 piksel.
#copyright { ... }: Ini adalah gaya yang diterapkan pada elemen dengan id "copyright." Beberapa pengaturan termasuk: text-align: center;: Mengatur teks dalam elemen ini agar terletak di tengah secara horizontal. width: 100%;: Mengatur lebar elemen "copyright" menjadi 100% dari lebar orang tua. padding: 50px 0px 50px 0px;: Mengatur padding (ruang dalam elemen) pada elemen "copyright." margin-top: 30px;: Menambahkan margin atas sebanyak 30 piksel.


#partners { ... }: Ini adalah gaya yang diterapkan pada elemen dengan id "partners." Beberapa pengaturan termasuk:background: #B0D9B1;: Mengatur latar belakang elemen "partners" menjadi warna #B0D9B1. padding: 50px 0px 30px 0px;: Mengatur padding pada elemen "partners." margin-left: -10%; margin-right: -5%;: Mengatur margin kiri dan kanan elemen "partners" untuk membuatnya lebih lebar daripada lebar tampilan standar.
.beli { ... }: Ini adalah gaya yang diterapkan pada elemen dengan class "beli." Beberapa pengaturan termasuk: background: #79AC78;: Mengatur latar belakang elemen "beli" menjadi warna #79AC78. border-radius: 20px;: Mengatur sudut elemen "beli" menjadi bulat. margin-top: 20px;: Menambahkan margin atas sebanyak 20 piksel. padding: 10px 20px 10px 20px;: Mengatur ruang dalam elemen "beli" di sekitar teks. color: #ffffff;: Mengatur warna teks menjadi putih (#ffffff). cursor: pointer;: Mengubah ikon kursor saat mengarahkan ke elemen "beli," menunjukkan bahwa itu adalah elemen yang dapat diklik. font-weight: bold;: Mengatur teks elemen "beli" menjadi tebal.


C. HTML LOGIN

![image](https://github.com/D4ManajemenInformatika/final-project-website-pemweb10_mic/assets/120777302/6acd93f0-1c35-4ee9-a688-c7f8a54785d5)

div class="wrapper": Ini adalah elemen pembungkus atau wadah utama yang mungkin digunakan untuk mengelompokkan elemen-elemen yang ada di dalamnya. Ini adalah elemen yang membatasi area konten.
div class="title-text": Ini adalah elemen yang digunakan untuk menampilkan teks judul.
div class="title login" dan div class="title signup": Ini adalah elemen-elemen yang digunakan untuk menampilkan judul "Form Login" dan "Form Registrasi". Masing-masing elemen memiliki class yang mungkin digunakan untuk menggaya atau memanipulasi tampilan teks.
div class="form-container": Ini adalah elemen yang digunakan untuk mengelompokkan elemen-elemen yang terkait dengan formulir login dan pendaftaran.
div class="slide-controls": Ini adalah elemen yang digunakan untuk mengendalikan tab atau geseran antara formulir login dan pendaftaran.
input type="radio" name="slide" id="login" checked dan input type="radio" name="slide" id="signup": Ini adalah elemen-elemen input radio yang digunakan untuk memilih antara formulir login dan pendaftaran. Masing-masing input radio memiliki atribut name yang sama, sehingga hanya satu dari keduanya yang dapat dipilih. Input dengan checked menunjukkan bahwa formulir login akan ditampilkan secara default.
label for="login" class="slide login" dan label for="signup" class="slide signup": Ini adalah elemen-elemen label yang berfungsi sebagai label untuk input radio. Mereka juga memiliki class "slide" dan "login" atau "signup" yang mungkin digunakan untuk menggaya label tersebut.
div class="slider-tab": Ini adalah elemen yang mungkin digunakan untuk menampilkan tab geseran atau indikator yang menunjukkan formulir mana yang sedang ditampilkan saat ini (login atau pendaftaran).

![image](https://github.com/D4ManajemenInformatika/final-project-website-pemweb10_mic/assets/120777302/0c06b84c-91ce-4f6c-8d0f-2441e1a4f63a)

div class="form-inner": Ini adalah elemen yang digunakan untuk mengelompokkan elemen-elemen yang terkait dengan formulir login.
form action="#" class="login": Ini adalah elemen form yang digunakan untuk membuat formulir. Beberapa atribut dan class yang digunakan termasuk:
action="#": Atribut action mengacu pada URL tujuan untuk mengirimkan data formulir. Dalam contoh ini, tanda "#" menunjukkan bahwa formulir akan mengirim data ke halaman yang sama (halaman saat ini).
class="login": Class ini mungkin digunakan untuk menggaya atau memanipulasi tampilan formulir login.
pre /pre: Ini adalah elemen pre yang mungkin digunakan untuk menambahkan beberapa ruang kosong di atas formulir. Biasanya, elemen ini digunakan untuk mengatur tata letak atau tampilan.
div class="field": Ini adalah elemen div yang digunakan untuk mengelompokkan elemen input dalam bentuk field. Dalam contoh ini, ada dua elemen field untuk masukan email dan password.
input type="text" placeholder="Masukan Email " required: Ini adalah elemen input yang digunakan untuk memasukkan alamat email pengguna. Atribut yang digunakan termasuk:
type="text": Menunjukkan bahwa ini adalah elemen input teks.
placeholder="Masukan Email ": Menampilkan teks placeholder di dalam input untuk memberikan petunjuk kepada pengguna. required: Membuat input ini menjadi wajib diisi sebelum formulir dapat dikirim.
input type="password" placeholder="Masukan Password" required: Ini adalah elemen input yang digunakan untuk memasukkan kata sandi pengguna. Atribut yang digunakan mirip dengan elemen sebelumnya, tetapi dengan type="password", yang menyembunyikan karakter yang dimasukkan.
div class="pass-link"a href="#"Lupa password?/a/div: Ini adalah elemen yang mungkin digunakan untuk menambahkan tautan "Lupa password?". Pengguna dapat mengklik tautan ini jika mereka lupa kata sandi mereka.
div class="field btn": Ini adalah elemen div yang digunakan untuk mengelompokkan elemen tombol (button) yang digunakan untuk mengirim formulir. Ini memiliki class "btn" yang mungkin digunakan untuk menggaya tombol tersebut.
div class="btn-layer"/div: Ini adalah elemen div yang mungkin digunakan untuk menambahkan lapisan atau efek visual ke tombol.
input type="submit" value="Login": Ini adalah elemen input dengan type="submit" yang digunakan untuk mengirimkan formulir. Nilai (value) "Login" akan ditampilkan pada tombol sebagai label.
div class="signup-link"Buat akun! a href="" Daftar sekarang/a/div: Ini adalah elemen yang mungkin digunakan untuk menambahkan tautan atau pesan yang mengarahkan pengguna untuk membuat akun baru (daftar).

![image](https://github.com/D4ManajemenInformatika/final-project-website-pemweb10_mic/assets/120777302/259bdde6-954c-4456-85f5-5e4e1f70df2b)

form action="#" class="signup": Ini adalah elemen form yang digunakan untuk membuat formulir pendaftaran. Beberapa atribut dan class yang digunakan termasuk:
action="#": Atribut action mengacu pada URL tujuan untuk mengirimkan data formulir. Dalam contoh ini, tanda "#" menunjukkan bahwa formulir akan mengirim data ke halaman yang sama (halaman saat ini).
class="signup": Class ini mungkin digunakan untuk menggaya atau memanipulasi tampilan formulir pendaftaran.
div class="field": Ini adalah elemen div yang digunakan untuk mengelompokkan elemen input dalam bentuk field. Dalam contoh ini, ada empat elemen field untuk memasukkan nama, alamat email, kata sandi, dan konfirmasi kata sandi.
input type="text" placeholder="Masukan Nama" required: Ini adalah elemen input yang digunakan untuk memasukkan nama pengguna. Atribut yang digunakan termasuk:
type="text": Menunjukkan bahwa ini adalah elemen input teks.
placeholder="Masukan Nama": Menampilkan teks placeholder di dalam input untuk memberikan petunjuk kepada pengguna.
required: Membuat input ini menjadi wajib diisi sebelum formulir dapat dikirim.
input type="password" placeholder="Masukan Password" required: Ini adalah elemen input yang digunakan untuk memasukkan kata sandi pengguna. Atribut yang digunakan mirip dengan elemen sebelumnya, tetapi dengan type="password", yang menyembunyikan karakter yang dimasukkan.
input type="password" placeholder="Ulangi password" required: Ini adalah elemen input yang digunakan untuk mengkonfirmasi kata sandi pengguna. Ini juga memiliki atribut type="password", sehingga karakter yang dimasukkan akan disembunyikan.
div class="field btn": Ini adalah elemen div yang digunakan untuk mengelompokkan elemen tombol (button) yang digunakan untuk mengirim formulir pendaftaran. Ini memiliki class "btn" yang mungkin digunakan untuk menggaya tombol tersebut.
div class="btn-layer"/div: Ini adalah elemen div yang mungkin digunakan untuk menambahkan lapisan atau efek visual ke tombol.
input type="submit" value="Daftar": Ini adalah elemen input dengan type="submit" yang digunakan untuk mengirimkan formulir pendaftaran. Nilai (value) "Daftar" akan ditampilkan pada tombol sebagai label.
div class="signup-link"Sudah punya akun? a href=""Login/a/div: Ini adalah elemen yang mungkin digunakan untuk menambahkan tautan atau pesan yang mengarahkan pengguna untuk masuk ke akun yang sudah ada.

D. CSS LOGIN

 ![image](https://github.com/D4ManajemenInformatika/final-project-website-pemweb10_mic/assets/120777302/7981b22e-298a-4e69-af72-a0f8a9c5a138)

![image](https://github.com/D4ManajemenInformatika/final-project-website-pemweb10_mic/assets/120777302/82abe38e-7900-4e53-93fc-edc2df760154)

![image](https://github.com/D4ManajemenInformatika/final-project-website-pemweb10_mic/assets/120777302/d65ca344-d13d-4dd0-9603-3fe956d6432d)
 
@import url('https://fonts.googleapis.com/css?family=Poppins:400,500,600,700&display=swap');: Ini adalah aturan @import yang digunakan untuk mengimpor jenis huruf Poppins dari Google Fonts. Ini akan membuat jenis huruf Poppins tersedia untuk digunakan dalam halaman web Anda.
*: Ini adalah selektor universal yang berlaku untuk semua elemen HTML. Aturan ini mengatur beberapa nilai yang akan berlaku secara global, termasuk: margin: 0; padding: 0;: Ini menghapus margin dan padding default dari semua elemen. box-sizing: border-box;: Ini mengatur model kotak (box model) sehingga padding dan border termasuk dalam perhitungan lebar dan tinggi elemen. font-family: 'Poppins', sans-serif;: Ini mengatur jenis huruf default ke Poppins, dan jika Poppins tidak tersedia, jenis huruf sans-serif akan digunakan sebagai cadangan.
html, body: Ini adalah selektor untuk elemen HTML dan body. Ini mengatur tata letak halaman web dengan memanfaatkan fitur CSS Grid dan place-items: center untuk mengatur elemen-elemen di tengah halaman. Latar belakang halaman web didefinisikan sebagai gradasi radial dengan warna-warna yang berbeda.

::selection: Ini adalah pseudo-element ::selection yang digunakan untuk menggaya teks yang dipilih oleh pengguna. Ini mengatur latar belakang dan warna teks teks yang dipilih.
.wrapper: Ini adalah selektor class yang menggaya elemen dengan class "wrapper". Elemen ini adalah wadah utama untuk konten halaman web dan memiliki beberapa properti yang mengatur tampilannya, seperti lebar maksimum, latar belakang, padding, border-radius, dan bayangan (box-shadow).
.wrapper .title-text: Ini adalah selektor untuk elemen dengan class "title-text" yang berada di dalam elemen dengan class "wrapper". Elemen ini digunakan untuk mengatur tampilan judul dan konten dalam tata letak yang sesuai.
.wrapper .title: Ini adalah selektor untuk elemen dengan class "title" yang juga berada di dalam elemen dengan class "wrapper". Ini mengatur tampilan judul, termasuk ukuran font, tebal font, dan perubahan tampilan judul saat terjadi transisi.
.wrapper .slide-controls: Ini adalah selektor untuk elemen dengan class "slide-controls" yang juga berada di dalam elemen dengan class "wrapper". Ini mengatur tampilan kontrol slide yang digunakan untuk mengganti antara tampilan judul.
 
![image](https://github.com/D4ManajemenInformatika/final-project-website-pemweb10_mic/assets/120777302/2640cb7b-9cfc-43c6-99e7-f9b30ba1e455)

![image](https://github.com/D4ManajemenInformatika/final-project-website-pemweb10_mic/assets/120777302/4098a596-491a-42d9-868d-00286c5fd9d1)

![image](https://github.com/D4ManajemenInformatika/final-project-website-pemweb10_mic/assets/120777302/f0960291-5f2e-448f-b1f2-5ef071f5494b)
 
.slide-controls .slide: Ini adalah selektor untuk elemen slide di dalam kontrol slide. Ini mengatur tampilan elemen-elemen slide, termasuk warna, ukuran font, tebal font, dan pengaturan tampilan lainnya.
.slide-controls label.signup: Ini adalah selektor untuk label dengan class "signup" di dalam kontrol slide. Ini mengatur warna teks untuk label dengan class "signup".
.slide-controls .slider-tab: Ini adalah selektor untuk elemen slider-tab di dalam kontrol slide. Ini mengatur tampilan slider-tab, termasuk latar belakang gradient yang berubah saat terjadi transisi.
input[type="radio"]: Ini adalah selektor untuk elemen input radio. Aturan ini menyembunyikan input radio karena tidak ingin menampilkannya kepada pengguna. Input radio ini digunakan untuk mengontrol tampilan judul "Login" dan "Daftar" pada halaman.
#signup:checked~.slider-tab: Ini adalah aturan yang akan berlaku saat input radio dengan ID "signup" dicentang. Ini mengubah posisi slider-tab untuk menunjukkan "Daftar".
#signup:checked~label.signup dan #signup:checked~label.login: Ini adalah aturan yang akan berlaku saat input radio dengan ID "signup" dicentang. Mereka mengubah warna teks label "Daftar" dan "Login" untuk menunjukkan tampilan yang sesuai.
#login:checked~label.signup dan #login:checked~label.login: Ini adalah aturan yang akan berlaku saat input radio dengan ID "login" dicentang. Mereka mengubah warna teks label "Daftar" dan "Login" untuk menunjukkan tampilan yang sesuai.
.wrapper .form-container: Ini adalah selektor untuk elemen dengan class "form-container" yang berada di dalam elemen dengan class "wrapper". Ini mengatur tampilan kontainer yang berisi formulir.
.form-container .form-inner: Ini adalah selektor untuk elemen dengan class "form-inner" yang berada di dalam elemen dengan class "form-container". Ini mengatur tampilan elemen yang berisi formulir.
.form-container .form-inner form: Ini adalah selektor untuk elemen form di dalam elemen dengan class "form-inner". Ini mengatur tampilan dari elemen form. Terdapat transisi yang membuatnya berubah tampilan saat beralih antara "Login" dan "Daftar".
 
 ![image](https://github.com/D4ManajemenInformatika/final-project-website-pemweb10_mic/assets/120777302/c2d78f21-d0ed-41c6-8703-24e4b0658df8)

![image](https://github.com/D4ManajemenInformatika/final-project-website-pemweb10_mic/assets/120777302/951f944d-027c-4b1f-bca1-1993cff69685)
 
![image](https://github.com/D4ManajemenInformatika/final-project-website-pemweb10_mic/assets/120777302/0a77d330-f879-48fa-97eb-08ed62e76453)

![image](https://github.com/D4ManajemenInformatika/final-project-website-pemweb10_mic/assets/120777302/96258ea5-9323-4de7-afdf-3bb18582ca96)

 
.form-inner form .field: Ini adalah selektor untuk elemen field (bidang) dalam formulir. Ini mengatur ketinggian, lebar, dan margin atas dari bidang.
.form-inner form .field input: Ini adalah selektor untuk elemen input dalam bidang formulir. Ini mengatur tampilan elemen input, termasuk ketinggian, lebar, tampilan luar (outline), padding, radius sudut (border-radius), dan lain-lain.
.form-inner form .field input:focus: Ini adalah tampilan elemen input saat fokus diberikan ke elemen. Ini mengubah warna border saat elemen input mendapatkan fokus.
.form-inner form .field input::placeholder: Ini mengatur tampilan teks placeholder dalam elemen input. Ini mengubah warna teks placeholder dan animasi saat elemen input mendapatkan fokus.
form .field input:focus::placeholder: Ini mengatur tampilan teks placeholder saat elemen input dalam formulir mendapatkan fokus.
.form-inner form .pass-link dan .form-inner form .signup-link: Ini adalah selektor untuk elemen-elemen yang berisi tautan "Lupa password?" dan "Buat akun!" di dalam formulir. Ini mengatur margin dan tampilan teks tautan.

.form-inner form .pass-link a dan .form-inner form .signup-link a: Ini mengatur tampilan tautan dalam formulir, termasuk warna dan tampilan teks tautan.
form .btn: Ini adalah selektor untuk elemen tombol dalam formulir. Ini mengatur ketinggian, lebar, border-radius, dan elemen lainnya.
form .btn .btn-layer: Ini adalah elemen lapisan (layer) dalam tombol. Ini mengatur tampilan lapisan tombol, termasuk transisi lapisan saat tombol dihover.
form .btn:hover .btn-layer: Ini mengatur perubahan posisi lapisan tombol saat tombol dihover.
form .btn input[type="submit"]: Ini adalah elemen input dengan tipe "submit" dalam formulir. Ini mengatur tampilan tombol submit, termasuk ketinggian, lebar, tampilan luar (outline), warna latar belakang, border, dan lain-lain.


E. JAVASCRIPT 

   ![image](https://github.com/D4ManajemenInformatika/final-project-website-pemweb10_mic/assets/144097689/60b0b76b-b6ef-4a62-8989-84eaaa4db6c1)

Menggunakan document.querySelector untuk memilih elemen-elemen HTML dengan menggunakan kelas dan tag. Ini mengizinkan  untuk berinteraksi dengan elemen-elemen tersebut melalui JavaScript

   ![image](https://github.com/D4ManajemenInformatika/final-project-website-pemweb10_mic/assets/144097689/cf0d7835-4b76-4085-9c28-29f611b22697) 

   Ketika tombol "Daftar" di-klik, Anda mengatur properti marginLeft pada elemen form dan judul "Form Login" untuk menggesernya ke kiri sejauh -50%. Ini menciptakan efek bergeser antara form login dan form registrasi. 

![image](https://github.com/D4ManajemenInformatika/final-project-website-pemweb10_mic/assets/144097689/1e768746-b817-49e1-88a6-6c2bc029e8fd) 

Ketika tombol "Login" di-klik, Anda mengatur properti marginLeft pada elemen form dan judul "Form Login" kembali ke posisi awal (0%). Ini memungkinkan pengguna untuk kembali ke form login.  

![image](https://github.com/D4ManajemenInformatika/final-project-website-pemweb10_mic/assets/144097689/7717914a-b5ce-427b-940d-5319b5d78155)

Ketika tautan "Daftar Sekarang" di-klik, Anda memicu klik pada tombol "Daftar" secara otomatis dengan signupBtn.click(). Ini memungkinkan pengguna untuk beralih ke form registrasi. Kemudian, Anda mengembalikan false untuk menghentikan tindakan bawaan dari tautan tersebut.


   



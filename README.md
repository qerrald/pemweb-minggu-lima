1. Pengertian Bootstrap 
Bootstrap adalah framework CSS yang digunakan untuk mempermudah pembuatan tampilan website agar lebih menarik, rapi, dan responsif. Bootstrap menyediakan komponen siap pakai seperti navbar, tombol, form, card, dan sistem grid sehingga pengembang tidak perlu membuat semuanya dari awal.

2. Memasang Bootstrap
Ada beberapa cara untuk menggunakan Bootstrap dalam sebuah project, yaitu:
-CDN. Tambahkan tag <link> dan <script> yang menunjuk ke URL Bootstrap di internet.
-Unduh manual. Download file CSS dan JavaScript, simpan di folder project, lalu hubungkan lewat tag yang sama.
-npm. Jalankan npm install bootstrap, lalu impor file-nya ke project.
-Build tool seperti Vite. Impor Bootstrap dari file JavaScript atau CSS, dan Vite menggabungkannya saat build.

3. Grid dan Breakpoint
Grid Bootstrap adalah sistem tata letak yang membagi halaman menjadi 12 kolom untuk mengatur posisi dan ukuran elemen. Grid menggunakan class seperti .container, .row, dan .col-md-6. Sementara itu, breakpoint adalah batas ukuran layar yang digunakan untuk menyesuaikan tampilan website pada perangkat berbeda, seperti ponsel, tablet, dan komputer. Contoh breakpoint Bootstrap adalah sm, md, lg, xl, dan xxl.

4. Class Bootstrap 
1).container — membuat wadah untuk mengatur tata letak konten.
2).row — membuat baris dalam sistem grid.
3).col-md-6 — membuat kolom dengan lebar 6 dari 12 kolom mulai dari breakpoint md.
4).btn — memberikan tampilan dasar pada tombol.
5).btn-primary — memberikan warna utama pada tombol.
6).text-center — membuat teks rata tengah.
7).img-fluid — membuat gambar responsif agar menyesuaikan lebar wadahnya.

5. Gambar Responsif
Agar gambar pada website responsif dan menyesuaikan ukuran layar perangkat, digunakan class Bootstrap .img-fluid pada elemen <img>. Class ini menerapkan lebar maksimum 100% dan tinggi otomatis sehingga gambar tidak melebihi wadahnya dan tetap mempertahankan proporsi aslinya.


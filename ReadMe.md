**LAPORAN PRAKTIKUM PEMROGRAMAN WEB | PHP** 

# **LAPORAN PRAKTIKUM PEMROGRAMAN WEB DASAR-DASAR PEMROGRAMAN PHP** 

_Disusun untuk memenuhi tugas mata kuliah:_ 

### **Pemrograman WEB** 

**Nama** Saqila Elby Neina **NIM** 31210173 **Program Studi** Teknik Informatika **Fakultas** Teknik **Dosen Pengampu** Agung Nugroho, S.Kom., M.Kom. 

### **Universitas Pelita Bangsa** 

**Bekasi 2026** 

Praktikum PHP  •  Halaman 1 

**LAPORAN PRAKTIKUM PEMROGRAMAN WEB | PHP** 

## **IDENTITAS DAN INFORMASI PRAKTIKUM** 

Lengkapi bagian bertanda kurung siku sebelum laporan dikumpulkan. Bagian dokumentasi disediakan sebagai tempat untuk menempelkan screenshot hasil eksekusi program dari komputer masing-masing. 

|**Mata Kuliah**|Pemrograman WEB|
|---|---|
|**Topik Praktikum**|Dasar-Dasar Pemrograman PHP|
|**Tanggal Praktikum**|15 Novermber 2026|
|**Nama Praktikan**|Saqila Elby Neina|
|**NIM**|312510173|
|**Kelas**|I253C|



## **1. TUJUAN PRAKTIKUM** 

1. Memahami dasar penggunaan bahasa pemrograman PHP dalam pengembangan web. 

2. Mengetahui cara menggabungkan HTML dengan PHP dalam satu halaman web. 

3. Memahami penggunaan variabel, operator aritmatika, dan percabangan if-else. 

4. Memahami penggunaan array dan perulangan foreach. 

5. Mempelajari pembuatan fungsi (function) untuk melakukan perhitungan. 

6. Memahami penggunaan metode GET dan POST untuk mengirimkan data melalui formulir. 

7. Mempelajari validasi input dan menampilkan hasil pengolahan data menggunakan PHP. 

8. Mengetahui cara menjalankan aplikasi PHP menggunakan server lokal. 

## **2. PERANGKAT YANG DIGUNAKAN** 

|**No.**|**Perangkat**|**Keterangan**|
|---|---|---|
|1|**Laptop/Komputer**|Perangkat untuk menulis dan<br>menjalankan program.|
|2|**Windows**|Sistem operasi komputer.|
|3|**Visual Studio Code**|Editor untuk membuat dan<br>mengedit kode PHP.|
|4|**XAMPP**|Paket server lokal yang|
|||menyediakan Apache dan PHP.|



Praktikum PHP  •  Halaman 2 

**LAPORAN PRAKTIKUM PEMROGRAMAN WEB | PHP** 

|**No.**|**Perangkat**|**Keterangan**|
|---|---|---|
|5|**Apache**|Web server untuk memproses|
|||permintaan halaman lokal.|
|6|**Google Chrome**|Browser untuk menampilkan hasil|
|||program.|
|7|**PHP**|Bahasa pemrograman yang|
|||digunakan dalam praktikum.|



## **3. CARA MENJALANKAN SERVER LOKAL** 

9. Instal XAMPP pada komputer apabila belum tersedia. 

10. Buka aplikasi XAMPP Control Panel. 

11. Pada bagian Apache, klik tombol Start. Pastikan status Apache berubah menjadi Running. 

12. Buka Visual Studio Code dan pilih File > Open Folder. 

13. Buka folder proyek praktikum-php yang berada di dalam folder htdocs. 

14. Pastikan file program tersimpan dengan nama index.php. 

15. Buka browser dan masukkan alamat http://localhost/praktikum-php/. 

16. Halaman praktikum akan tampil apabila Apache aktif dan file tersimpan pada lokasi 

- yang benar. 

##### **DOKUMENTASI OUTPUT** 

Praktikum PHP  •  Halaman 3 

**LAPORAN PRAKTIKUM PEMROGRAMAN WEB | PHP** 



<!-- Start of picture text -->
XAMPP Control Panel v3.3.0 [ Compiled: Apr 6th 2021 ] = ia) x<br>XAMPP Control Panel v3.3.0 ra<br>Service“Wodutes Module —_PID(s) Port(s) Actions @, Netstat<br>Apache Jone 20,443 Stop Admin Config | _Logs Gishret<br>MySQL 5316 3306 Admin | Config | Logs (i Explorer<br>FileZilla Start Admin Config Logs ©& Services<br>Mercury Start Admin Config Logs © Hep<br>Tomcat Start Admin Config Logs IB out<br>/09:20:35 [main] All prerequisites found<br>|09:20:35 [main] Initializing Modules<br>|09:20:35 [main] Starting Check-Timer<br>|09:20:35 [main] Control Panel Ready<br>|09:20:36 [Apache] Attempting to start Apache app.<br>|09-20-37 [Apache] Status change detected: running<br>|09:2009:20 :38 [mysql] AS t temptingatus change to start detected: MySQLrunning app.<br><!-- End of picture text -->

_Keterangan gambar: XAMPP dalam keadaan Running_ 

##### **DOKUMENTASI OUTPUT** 

Praktikum PHP  •  Halaman 4 

**LAPORAN PRAKTIKUM PEMROGRAMAN WEB | PHP** 



<!-- Start of picture text -->
s ia © — B Praktikum PHP x +<br>88 | El import favorites | i$) Diotakit io spotiy<br>Belajar PHP<br>1. Menampilkan Teks dan Waktu Server<br>PHP berhasil dijalankan.<br>Waktu server: 15-11-2026 03:21:19<br>2. Menghitung Nilai Akhir Mahasiswa<br>Nama: Siti<br>Nila akhir: 84.90<br>Predikat: B<br>3. Daftar Mahasiswa<br>1. Alya<br>2. Bima<br>3. Citra<br>4. Doni<br>4. Menghitung Harga Setelah Diskon<br>Harga awal: Rp150.000<br>Diskon: 10%<br>Harga setelah diskon: Rp135.000<br>5. Form Pencarian Menggunakan GET<br><!-- End of picture text -->

_Keterangan gambar: Tampilan running web_ 

## **4. STRUKTUR FILE** 

Seluruh materi praktikum pada laporan ini digabungkan ke dalam satu file utama bernama index.php. File diletakkan di dalam folder proyek pada direktori htdocs milik XAMPP. 

|C:\xampp\htdocs\prakt<br>index.php<br>└──|ikum-php\|
|---|---|
|**htdocs**|Folder utama untuk menyimpan aplikasi web XAMPP.|
|**praktikum-php**|Folder proyek praktikum PHP.|
|**index.php**|File utama yang berisi kode HTML dan PHP untuk seluruh materi<br>praktikum.|



**DOKUMENTASI OUTPUT** 

Praktikum PHP  •  Halaman 5 

**LAPORAN PRAKTIKUM PEMROGRAMAN WEB | PHP** 



<!-- Start of picture text -->
Lab7_php<br>Formulir_Data_Mahasiswa<br>Lab7_php<br>® index.php<br><!-- End of picture text -->

_Keterangan gambar:Susunan folder di vscode_ 

Praktikum PHP  •  Halaman 6 

**LAPORAN PRAKTIKUM PEMROGRAMAN WEB | PHP** 

## **5.1 Menampilkan Teks dan Waktu Server** 

**Tujuan:** Menampilkan teks dan tanggal/waktu server pada halaman web menggunakan perintah echo dan fungsi date(). 

#### **A. Potongan Kode Program** 

<?php echo "<p>PHP berhasil dijalankan.</p>"; echo "<p>Waktu server: " . date("d-m-Y H:i:s") . "</p>"; ?> 

#### **B. Penjelasan Kode** 

- echo digunakan untuk menampilkan teks atau nilai ke halaman web. 

- date("d-m-Y H:i:s") menampilkan tanggal, bulan, tahun, jam, menit, dan detik berdasarkan waktu server. 

- Tanda titik (.) digunakan untuk menggabungkan teks dengan hasil fungsi date(). 

#### **C. Contoh Output yang Diharapkan** 

**HASIL PADA BROWSER** Belajar PHP PHP berhasil dijalankan. Waktu server: [tanggal dan waktu aktual server] 

Penjelasan output: Program menampilkan judul halaman, pesan bahwa PHP berhasil dijalankan, serta waktu server. Nilai waktu dapat berbeda sesuai pengaturan waktu komputer/server. 

**DOKUMENTASI OUTPUT** 



<!-- Start of picture text -->
Belajar PHP<br>1. Menampilkan Teks dan Waktu Server<br>PHP berhasil dijalankan.<br>Waktu server: 15-11-2026 03:21:19<br><!-- End of picture text -->

Praktikum PHP  •  Halaman 7 

**LAPORAN PRAKTIKUM PEMROGRAMAN WEB | PHP** 

## **5.2 Menghitung Nilai Akhir Mahasiswa** 

**Tujuan:** Menghitung nilai akhir mahasiswa berdasarkan bobot tugas, UTS, dan UAS, kemudian menentukan predikat menggunakan percabangan. 

#### **A. Potongan Kode Program** 

$nama = "Siti"; $tugas = 85; $uts = 78; $uas = 90; $nilaiAkhir = ($tugas * 0.30) + ($uts * 0.30) + ($uas * 0.40); if ($nilaiAkhir >= 85) { $predikat = "A"; } elseif ($nilaiAkhir >= 75) { $predikat = "B"; } elseif ($nilaiAkhir >= 60) { $predikat = "C"; } else { $predikat = "D"; } echo "Nama: " . htmlspecialchars($nama) . "<br>"; echo "Nilai akhir: " . number_format($nilaiAkhir, 2) . "<br>"; echo "Predikat: " . $predikat; 

#### **B. Penjelasan Kode** 

- Variabel menyimpan nama dan nilai tugas, UTS, serta UAS. 

- Nilai akhir dihitung dengan bobot tugas 30%, UTS 30%, dan UAS 40%. 

- if, elseif, dan else menentukan predikat berdasarkan rentang nilai. 

- htmlspecialchars() membantu mengamankan teks yang ditampilkan, sedangkan number_format() mengatur tampilan dua angka desimal. 

#### **C. Contoh Output yang Diharapkan** 

**HASIL PADA BROWSER** Nama: Siti Nilai akhir: 84.90 Predikat: B 

Penjelasan output: Nilai akhir Siti adalah 84,90. Berdasarkan aturan pada kode, nilai tersebut termasuk predikat B karena lebih besar atau sama dengan 75 dan kurang dari 85. 

**DOKUMENTASI OUTPUT** 

Praktikum PHP  •  Halaman 8 

**LAPORAN PRAKTIKUM PEMROGRAMAN WEB | PHP** 



<!-- Start of picture text -->
2. Menghitung Nilai Akhir Mahasiswa<br>Nama: Siti<br>Nilai akhir: 84.90<br>Predikat: B<br><!-- End of picture text -->

Praktikum PHP  •  Halaman 9 

**LAPORAN PRAKTIKUM PEMROGRAMAN WEB | PHP** 

## **5.3 Menampilkan Daftar Mahasiswa dengan Array dan** 

## **Foreach** 

**Tujuan:** Menyimpan beberapa nama dalam array dan menampilkannya secara berurutan menggunakan perulangan foreach. 

#### **A. Potongan Kode Program** 

$mahasiswa = ["Alya", "Bima", "Citra", "Doni"]; echo "<ol>"; foreach ($mahasiswa as $nama) { echo "<li>" . htmlspecialchars($nama) . "</li>"; } echo "</ol>"; 

#### **B. Penjelasan Kode** 

- Array $mahasiswa menyimpan empat nama dalam satu variabel. 

- foreach membaca setiap elemen array secara bergantian. 

- Tag HTML <ol> membuat daftar bernomor, sedangkan <li> membuat item daftar. 

- htmlspecialchars() digunakan saat menampilkan isi variabel sebagai teks HTML. 

#### **C. Contoh Output yang Diharapkan** 

**HASIL PADA BROWSER** 

Daftar Mahasiswa 1. Alya 2. Bima 3. Citra 4. Doni 

Penjelasan output: Program berhasil menampilkan empat nama mahasiswa dalam bentuk daftar bernomor. Urutan daftar mengikuti urutan data di dalam array. 

**DOKUMENTASI OUTPUT** 

Praktikum PHP  •  Halaman 10 

**LAPORAN PRAKTIKUM PEMROGRAMAN WEB | PHP** 



<!-- Start of picture text -->
3. Daftar Mahasiswa<br>1. Alya<br>2. Bima<br>3. Citra<br>4. Doni<br><!-- End of picture text -->

Praktikum PHP  •  Halaman 11 

**LAPORAN PRAKTIKUM PEMROGRAMAN WEB | PHP** 

## **5.4 Menghitung Harga Setelah Diskon dengan Function** 

**Tujuan:** Membuat fungsi yang menerima harga dan persentase diskon, lalu mengembalikan harga setelah diskon. 

#### **A. Potongan Kode Program** 

function hitungDiskon($harga, $persen) { $potongan = $harga * ($persen / 100); return $harga - $potongan; } $hargaAkhir = hitungDiskon(150000, 10); echo "Harga awal: Rp150.000<br>"; echo "Diskon: 10%<br>"; echo "Harga setelah diskon: Rp" . number_format($hargaAkhir, 0, ",", "."); 

#### **B. Penjelasan Kode** 

   - function hitungDiskon() mendefinisikan fungsi dengan parameter harga dan persen. 

   - Variabel $potongan menghitung nilai diskon dari harga awal. 

   - return mengembalikan harga setelah dikurangi potongan. 

   - number_format() menampilkan angka dengan pemisah ribuan titik. 

- **C. Contoh Output yang Diharapkan** 

**HASIL PADA BROWSER** Harga awal: Rp150.000 Diskon: 10% Harga setelah diskon: Rp135.000 

Penjelasan output: Diskon 10% dari Rp150.000 adalah Rp15.000. Setelah dikurangi potongan tersebut, harga akhir menjadi Rp135.000. 

##### **DOKUMENTASI OUTPUT** 



<!-- Start of picture text -->
4. Menghitung Harga Setelah Diskon<br>Harga awal: Rp150.000<br>Diskon: 10%<br>Harga setelah diskon: Rp135.000<br><!-- End of picture text -->

Praktikum PHP  •  Halaman 12 

**LAPORAN PRAKTIKUM PEMROGRAMAN WEB | PHP** 

## **5.5 Form Pencarian Menggunakan GET** 

**Tujuan:** Menerima kata kunci dari formulir dan menampilkannya kembali menggunakan metode GET. 

#### **A. Potongan Kode Program** 

<form method="GET" action=""> <label for="kata">Kata kunci:</label> <input id="kata" name="kata" type="text"> <button type="submit">Cari</button> </form> <?php if (isset($_GET["kata"])) { $kata = trim($_GET["kata"]); echo "<p>Kata kunci: " . htmlspecialchars($kata, ENT_QUOTES, "UTF-8") . "</p>"; } ?> 

#### **B. Penjelasan Kode** 

- method="GET" mengirim data melalui parameter URL. 

 name="kata" menjadi nama parameter yang dibaca oleh PHP.  isset() memeriksa apakah parameter kata tersedia.  trim() menghapus spasi di awal dan akhir teks. 

- htmlspecialchars() mengamankan teks sebelum ditampilkan pada halaman. 

#### **C. Contoh Output yang Diharapkan** 

**HASIL PADA BROWSER** Form: Kata kunci: [PHP] [Cari] Setelah dikirim: Kata kunci: PHP Contoh URL: http://localhost/praktikum-php/?kata=PHP 

Penjelasan output: Ketika pengguna mengetik PHP dan menekan tombol Cari, browser mengirimkan parameter kata melalui URL. PHP membaca nilai tersebut dan menampilkannya kembali pada halaman. 

**DOKUMENTASI OUTPUT** 

Praktikum PHP  •  Halaman 13 

**LAPORAN PRAKTIKUM PEMROGRAMAN WEB | PHP** 



<!-- Start of picture text -->
5. Form Pencarian Menggunakan GET<br>Kata kunci: | | Cari |<br>Kata kunci: PHP<br><!-- End of picture text -->

Praktikum PHP  •  Halaman 14 

**LAPORAN PRAKTIKUM PEMROGRAMAN WEB | PHP** 

## **5.6 Form Input Data Mahasiswa Menggunakan POST** 

**Tujuan:** Menerima data nama dan program studi melalui formulir POST, memeriksa kelengkapan data, lalu menampilkan hasilnya. 

#### **A. Potongan Kode Program** 

<form method="POST" action=""> <label for="nama">Nama:</label> <input id="nama" name="nama" type="text" required> <label for="prodi">Program Studi:</label> <input id="prodi" name="prodi" type="text" required> <button type="submit" name="kirim">Kirim Data</button> </form> <?php if ($_SERVER["REQUEST_METHOD"] === "POST" && isset($_POST["kirim"])) { $nama = trim($_POST["nama"] ?? ""); $prodi = trim($_POST["prodi"] ?? ""); if ($nama === "" || $prodi === "") { echo "<p>Semua kolom wajib diisi.</p>"; } else { echo "<h3>Data Diterima</h3>"; echo "Nama: " . htmlspecialchars($nama, ENT_QUOTES, "UTF-8") . "<br>"; echo "Program Studi: " . htmlspecialchars($prodi, ENT_QUOTES, "UTF-8"); } } ?> 

#### **B. Penjelasan Kode** 

- method="POST" mengirim data melalui isi permintaan HTTP, bukan sebagai parameter URL. 

- $_SERVER["REQUEST_METHOD"] memeriksa metode permintaan yang digunakan. 

- $_POST mengambil nilai nama dan program studi dari formulir. 

- required membantu memeriksa input di sisi browser, sedangkan pemeriksaan PHP memvalidasi data kembali di sisi server. 

- htmlspecialchars() mengamankan nilai sebelum ditampilkan. 

Praktikum PHP  •  Halaman 15 

**LAPORAN PRAKTIKUM PEMROGRAMAN WEB | PHP** 

#### **C. Contoh Output yang Diharapkan** 

**HASIL PADA BROWSER** Form: Nama = Siti Program Studi = Sistem Informasi Setelah tombol Kirim Data ditekan: Data Diterima Nama: Siti Program Studi: Sistem Informasi 

Penjelasan output: Program menerima dua data dari formulir. Jika kedua kolom terisi, halaman menampilkan nama dan program studi. Jika ada data kosong, program menampilkan pesan bahwa semua kolom wajib diisi. 

**DOKUMENTASI OUTPUT** 



<!-- Start of picture text -->
6. Form Input Data Mahasiswa Menggunakan POST<br>Name<br>Program Studi: [Fl<br>Data Diterima<br>Nama: Siti<br>Program Studi: Sistem Informasi<br><!-- End of picture text -->

Praktikum PHP  •  Halaman 16 

**LAPORAN PRAKTIKUM PEMROGRAMAN WEB | PHP** 

## **5.7 Menghitung Subtotal Belanja** 

**Tujuan:** Menerima data nama barang, harga, dan jumlah pembelian, melakukan validasi, lalu menghitung subtotal belanja. 

#### **A. Potongan Kode Program** 

$barang = trim($_POST["barang"] ?? ""); $hargaInput = $_POST["harga"] ?? ""; $jumlahInput = $_POST["jumlah"] ?? ""; if ( $barang === "" || !is_numeric($hargaInput) || !ctype_digit((string)$jumlahInput) || (float)$hargaInput < 0 || (int)$jumlahInput < 1 ) { echo "<p>Periksa kembali nama barang, harga, dan jumlah.</p>"; } else { $harga = (float)$hargaInput; $jumlah = (int)$jumlahInput; $subtotal = $harga * $jumlah; echo "<h3>Hasil Perhitungan</h3>"; echo "Nama Barang: " . htmlspecialchars($barang, ENT_QUOTES, "UTF-8") . "<br>"; echo "Harga: Rp" . number_format($harga, 0, ",", ".") . "<br>"; echo "Jumlah: " . $jumlah . "<br>"; echo "Subtotal: Rp" . number_format($subtotal, 0, ",", "."); } 

#### **B. Penjelasan Kode** 

   - Data barang, harga, dan jumlah diambil dari variabel POST. 

   - is_numeric() memeriksa apakah harga berupa angka. 

   - ctype_digit() memeriksa apakah jumlah berisi digit bilangan bulat. 

   - Percabangan memeriksa nama barang, harga tidak negatif, dan jumlah minimal satu. 

   - Subtotal dihitung dengan rumus harga dikalikan jumlah. 

- **C. Contoh Output yang Diharapkan** 

**HASIL PADA BROWSER** Nama Barang: Buku Tulis Harga: Rp10.000 Jumlah: 5 Subtotal: Rp50.000 

Praktikum PHP  •  Halaman 17 

**LAPORAN PRAKTIKUM PEMROGRAMAN WEB | PHP** 

Penjelasan output: Dengan harga Rp10.000 dan jumlah pembelian 5 unit, subtotal yang diperoleh adalah Rp50.000. Apabila input tidak sesuai ketentuan, program menampilkan pesan untuk memeriksa kembali data. 

##### **DOKUMENTASI OUTPUT** 



<!-- Start of picture text -->
a<br>7. Menghitung Subtotal Belanja<br>1<br>Nama Barang:<br>I<br>Harga: | |<br>}Jumlah: |<br>|Hitung Subtotal<br>I<br>Hasil Perhitungan<br>INama Barang: Buku |<br>Harga: Rp10.000 |<br>Jumlah: 5<br>Subtotal: Rp50.000 I<br>a<br><!-- End of picture text -->

Praktikum PHP  •  Halaman 18 

**LAPORAN PRAKTIKUM PEMROGRAMAN WEB | PHP** 

## **6. RINGKASAN HASIL PRAKTIKUM** 

Berdasarkan pengujian program, ringkasan hasil dari setiap materi adalah sebagai berikut: 

|**No.**|**Materi**|**Ringkasan Hasil**|
|---|---|---|
|1|**Echo dan Date**|Menampilkan pesan dan waktu<br>server.|
|2|**If-Else**|Menghitung nilai akhir dan<br>menentukan predikat mahasiswa.|
|3|**Array dan Foreach**|Menampilkan daftar nama<br>mahasiswa.|
|4|**Function**|Menghitung harga setelah diskon.|
|5|**GET**|Menerima dan menampilkan kata<br>kunci melalui URL.|
|6|**POST**|Menerima dan menampilkan data<br>mahasiswa.|
|7|**Validasi dan Aritmatika**|Memvalidasi data barang dan<br>menghitung subtotal.|



## **7. KESIMPULAN** 

Berdasarkan praktikum yang telah dilakukan, dapat disimpulkan bahwa PHP dapat digunakan untuk mengolah data dan menghasilkan halaman web yang dinamis. Materi praktikum mencakup penggunaan variabel, operator aritmatika, percabangan, array, perulangan, fungsi, formulir GET dan POST, serta validasi input. 

Penggunaan XAMPP sebagai server lokal memudahkan proses pengujian program PHP melalui browser tanpa harus mengunggah file ke hosting. Seluruh materi pada praktikum ini dapat disimpan dalam satu file index.php dan dijalankan melalui alamat localhost. 

Praktikum PHP  •  Halaman 19 


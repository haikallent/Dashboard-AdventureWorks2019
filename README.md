# Dashboard-AdventureWorks2019
Berikut ini merupakan file yang kami gunakan untuk menyelesaikan final project mata kuliah Data Warehouse &amp; OLAP.

Program Studi Sistem Informasi

Fakultas Ilmu Komputer

Universitas Pembangunan Nasional "Veteran" Jawa Timur

Berikut ini merupakan anggota kelompok kami:
1. Hussein Muhammad Ibrahim (22082010132)
2. Haikal Lentera Indonesia (24082910273)


NOTES:
1. OLAP.zip merupakan folder untuk menampilkan OLAP dari section sales dan purchase dan file tersebut dimasukkan ke dalam folder mondrian
2. pentaho.ktr merupakan folder untuk menjalankan spoon (pentaho data integration) yang digunakan untuk mengisi tabel fakta di section sales (uts_dwo.sql) dan section purchase (uas_dwo.sql)


Langkah-langkah Implementasi:
1. Buatlah 2 database uas_dwo dan uts_dwo
2. Import masing-masing sql dump ke dalam database tersebut
3. Extract file fp_dwo.zip
4. Copy/cut file tersebut ke address C:\xampp\htdocs
5. Extract file OLAP.zip
6. Copy/cut file index ke address C:\xampp\tomcat\webapps\mondrian. Lalu copy/cut file sisanya ke address C:\xampp\tomcat\webapps\mondrian\WEB-INF\queries
7. Nyalakan Apache, Mysql, dan Tomcat pada XAMPP
8. Kunjungi halaman http://localhost/fp_dwo/index.php untuk mengakses dashboard AdventureWorks2019
9. Masukkan 'admin' (tanpa petik) untuk username dan password

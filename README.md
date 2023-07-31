# Pendaftaran Pasien di Rumah Sakit
Ini adalah repositori untuk aplikasi Pendaftaran Pasien di Rumah Sakit. Aplikasi ini dibuat sebagai tugas besar dari mata kuliah Sister Terdistribusi dengan client-server. Aplikasi terdiri dari dua file, yaitu client.py untuk akses klien dan server.py untuk akses server.

## Fitur
- Pendaftaran pasien ke berbagai poliklinik (poli mata, poli gigi, poli bedah).
- Penyimpanan data pasien secara terpisah berdasarkan jenis poliklinik.

## Instalasi
- Pastikan Python telah terinstal di komputer Anda.
- Install library prettytable dengan menjalankan perintah: pip install prettytable.
- Jalankan server.py untuk memulai server.
- Jalankan client.py untuk mengakses aplikasi client.

## Instruksi Penggunaan
Jalankan server.py terlebih dahulu untuk memulai server.<br>
Jalankan client.py untuk mengakses aplikasi sebagai klien.

### server.py
File server.py berfungsi sebagai aplikasi server yang akan menerima permintaan dari aplikasi client dan memberikan respons sesuai dengan permintaan tersebut. Aplikasi server akan menggunakan protokol XML-RPC untuk berkomunikasi dengan aplikasi client. Beberapa fitur yang dimiliki oleh aplikasi server:
- Menyimpan data seluruh pasien yang mendaftar di rumah sakit dalam list list_pasien.
- Menyimpan data pasien yang telah mendaftar di masing-masing poliklinik dalam list pasien_daftar.
- Menghasilkan nomor rekam medis secara otomatis untuk setiap pasien yang mendaftar.
- Memberikan respons kepada aplikasi client berupa hasil pendaftaran atau data pasien yang diminta.
### client.py
File client.py berfungsi sebagai aplikasi client yang digunakan oleh pengguna untuk melakukan pendaftaran pasien. Aplikasi client akan berkomunikasi dengan server menggunakan protokol XML-RPC. Beberapa fitur yang dimiliki oleh aplikasi client:
- Pendaftaran pasien baru ke berbagai poliklinik dengan menyertakan informasi seperti nama, tanggal lahir, dan nomor rekam medis.
- Menampilkan data seluruh pasien yang telah mendaftar di rumah sakit.
- Menampilkan data pasien yang telah mendaftar di poliklinik tertentu.

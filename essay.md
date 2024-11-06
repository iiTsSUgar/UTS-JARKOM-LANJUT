# Muhammad Aulia Nizar Rahman
# NIM 20210801232

1) Routing Static:
Routing static adalah metode konfigurasi jalur jaringan yang dilakukan secara manual, di mana administrator jaringan menentukan secara eksplisit rute yang harus dilalui paket data untuk mencapai tujuannya. Karakteristik utama:
- Rute dikonfigurasi secara manual oleh administrator
- Cocok untuk jaringan kecil dengan pola traffic yang dapat diprediksi
- Penggunaan CPU dan bandwidth rendah karena rute tidak berubah
- Kurang adaptif terhadap perubahan jaringan
- Memerlukan update manual jika topologi jaringan berubah

2) Routing Dynamic:
Routing dynamic menggunakan protokol yang secara otomatis menemukan dan berbagi informasi routing antar router. Fitur utama:
- Rute dipelajari secara otomatis melalui protokol routing seperti RIP, OSPF, EIGRP
- Lebih baik untuk jaringan besar dengan jalur yang kompleks
- Beradaptasi secara otomatis terhadap perubahan jaringan
- Penggunaan CPU dan bandwidth lebih tinggi
- Lebih kompleks untuk konfigurasi awal tetapi lebih mudah untuk pemeliharaan

3) Firewall:
Firewall adalah perangkat keamanan jaringan yang memantau dan mengontrol lalu lintas jaringan masuk/keluar berdasarkan aturan keamanan yang telah ditentukan. Fungsi meliputi:
- Memfilter lalu lintas berdasarkan aturan
- Memblokir akses yang tidak sah
- Mencegah lalu lintas yang berbahaya
- Membuat zona keamanan
- Mencatat kejadian keamanan
- Dapat berupa perangkat keras atau perangkat lunak

4) NAT (Network Address Translation):
NAT adalah proses mengubah informasi alamat jaringan saat transit melalui perangkat routing. Tujuan utama:
- Memungkinkan alamat IP private untuk mengakses internet menggunakan satu IP public
- Menghemat penggunaan alamat IP public
- Menambah keamanan dengan menyembunyikan struktur jaringan internal
- Jenis NAT: Static NAT, Dynamic NAT, PAT (Port Address Translation)

Keunggulan menggunakan NAT:
- Meningkatkan keamanan jaringan internal
- Menghemat penggunaan alamat IP public
- Memudahkan manajemen jaringan
- Fleksibilitas dalam pengaturan jaringan
- Memungkinkan koneksi banyak perangkat ke internet

# Jarkom-Modul-4-2025-K57

| No | Nama Lengkap         | NRP        |
|----|----------------------|------------|
| 1  | Prabaswara Febrian   | 5027241069 |
| 2  | Erlinda Annisa Zahra | 5027241108 |

### VLSM CPT

Pertama membuat topologi di CPT sesuai soal. Lalu kelompokkan per subnet sesuai dengan format: 

    Router > Node
    Router > Switch > Node > Switch > Node
    Router > Switch > Node
    Router > Router

Dan kelompokkan persubnet dan menjumlah dengan hostnya untuk mendapatkan netmask.

![soal_1](images/topologi.png)

Berikut adalah tabel rute yang dijalankan dan sudah di hitung untuk jumlah host sesuai subnet.

![soal_2](images/rute.png)

Lalu untuk pesebaran IP dengan perhitungan pohon. Dan untuk perhitungannya dimulai dari netmask terkecil.

![soal_3](images/pohontree.png)

Dalam metode VLSM, syarat utama adalah mengurutkan seluruh kebutuhan subnet berdasarkan jumlah host yang paling banyak hingga yang paling sedikit. Subnet terbesar harus ditempatkan lebih dulu agar mendapatkan ruang alamat yang cukup sebelum dialokasikan untuk subnet lain yang lebih kecil.


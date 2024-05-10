# Deskripsi Proyek
Kamu berhasil menunjukkan kinerja yang cemerlang selama mengikuti kursus TripleTen.
Karena itu, kamu pun ditawarkan kesempatan untuk menjalani program magang di departemen analitik perusahaan Y.Afisha.
Nah, tugas pertama yang mereka berikan kepadamu adalah membantu mengoptimalkan anggaran biaya pemasaran. 

Kamu dibekali dengan:

Log/catatan server yang memuat data kunjungan ke situs Y.Afisha dari bulan Januari 2017 hingga bulan Desember 2018
File dump yang memuat semua pesanan untuk periode tersebut
Statistik biaya pemasaran
Kamu akan mempelajari: 

Bagaimana para pengguna menggunakan produk Y.Afisha
Kapan mereka mulai melakukan pembelian
Berapa jumlah uang yang disumbangkan oleh setiap pengguna
Kapan semua biaya pemasaran terbayarkan

# Deskripsi data
## Tabel visits (log/catatan server yang memuat data kunjungan ke situs web):
* Uid — ID pengguna
* Device — perangkat pengguna
* Start Ts — tanggal dan waktu dimulainya sesi
* End Ts — tanggal dan waktu berakhirnya sesi
* Source Id — ID sumber iklan, sumber yang digunakan pengguna untuk datang ke situs web
* Semua tanggal dalam tabel ini menggunakan format YYYY-MM-DD.

## Tabel orders (data terkait pesanan):
* Uid — ID pengguna yang membuat pesanan
* Buy Ts — tanggal dan waktu pesanan dibuat
* Revenue — pendapatan Y.Afisha dari pesanan tersebut

## Tabel costs (data terkait pengeluaran pemasaran):
* source_id — ID sumber iklan
* dt — tanggal
* costs — pengeluaran untuk sumber iklan pada tanggal tersebut

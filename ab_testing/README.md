# Deskripsi Teknis
* Nama eksperimen:󠀲󠀡󠀠󠀦󠀥󠀨󠀢󠀡󠀳 recommender_system_test
* Kelompok: А (kontrol), B (funnel pembayaran yang baru)󠀲󠀡󠀠󠀦󠀥󠀨󠀢󠀢󠀳
* Tanggal dimulainya eksperimen: 07-12-2020󠀲󠀡󠀠󠀦󠀥󠀨󠀢󠀣󠀳
* Tanggal saat mereka berhenti menerima pengguna baru: 21-12-2020󠀲󠀡󠀠󠀦󠀥󠀨󠀢󠀤󠀳
* Tanggal berakhirnya eksperimen: 01-01-2021󠀲󠀡󠀠󠀦󠀥󠀨󠀢󠀥󠀳
* Audiens: 15% pengguna baru dari kawasan Uni Eropa󠀲󠀡󠀠󠀦󠀥󠀨󠀢󠀦󠀳
* Tujuan eksperimen: menguji perubahan terkait pengenalan sistem rekomendasi yang telah ditingkatkan󠀲󠀡󠀠󠀦󠀥󠀨󠀢󠀧󠀳
* Hasil yang diharapkan: dalam kurun waktu 14 hari setelah pendaftaran, para pengguna menunjukkan peningkatan dalam hal konversi ke tayangan halaman produk (peristiwa atau event product_page), aktivitas penambahan item ke keranjang belanja (product_cart), dan pembelian (purchase).󠀲󠀡󠀠󠀦󠀥󠀨󠀢󠀨󠀳󠀰 Pada setiap tahapan funnel product_page → product_cart → purchase, minimal akan ada peningkatan sebesar 10%.󠀲󠀡󠀠󠀦󠀥󠀨󠀢󠀩󠀳
* Jumlah peserta eksperimen yang diharapkan: 6.000󠀲󠀡󠀠󠀦󠀥󠀨󠀣󠀠󠀳

# Deskripsi data

Tersedia 4 datasets:
* ab_project_marketing_events_us.csv — kalender marketing event untuk tahun 2020
* final_ab_new_users_upd_us.csv — semua pengguna yang mendaftar di toko online dari tanggal 7 sampai 21 Desember 2020
* final_ab_events_upd_us.csv — semua peristiwa dari pengguna baru sepanjang periode 7 Desember 2020 sampai 1 Januari 2021
* final_ab_participants_upd_us.csv — tabel yang berisi daftar peserta eksperimen
  
## Struktur dari  ab_project__marketing_events_us.csv:
* name — nama marketing event󠀲󠀡󠀠󠀦󠀥󠀨󠀤󠀠󠀳
* regions — kawasan tempat ad campaign atau kampanye iklan akan berlangsung
* start_dt — tanggal awal campaign
* finish_dt — tanggal akhir campaign

## Struktur dari final_ab_new_users_upd_us.csv:
* user_id
* first_date — tanggal pendaftaran (sign up)
* region
* device — perangkat yang digunakan untuk mendaftar

## Struktur dari final_ab_events_upd_us.csv:
* user_id
* event_dt — tanggal dan waktu peristiwa
* event_name — nama jenis peristiwa
* details — data tambahan terkait peristiwa tersebut (misalnya, jumlah total pesanan dalam USD untuk peristiwa purchase)

## Struktur dari  final_ab_participants_upd_us.csv:
* user_id
* ab_test — nama eksperimen
* group — kelompok eksperimen pengguna berasal

# Tujuan
Menampilkan hasil AB Testing yang telah ditinggalkan oleh analisis data sebelumnya

# Deskripsi Proyek
Kamu bekerja di sebuah startup yang menjual produk makanan.
Kamu perlu mencari tahu perilaku pengguna aplikasi dari perusahaan tersebut.

Pertama-tama, kamu perlu mempelajari funnel penjualannya terlebih dahulu. Temukan jalur yang harus dilalui pengguna untuk bisa mencapai tahap pembelian. Berapa banyak pengguna yang benar-benar berhasil mencapai tahap pembelian? Berapa banyak pengguna yang terhenti pada tahap-tahap sebelumnya? Pada tahap mana persisnya hal tersebut terjadi?

Kemudian, lihat hasil dari A/A/B testing (Baca terus untuk mengetahui informasi lebih lanjut tentang A/A/B testing). Tim web designer ingin mengubah font untuk keseluruhan aplikasi, tetapi product manager merasa khawatir jika para pengguna justru akan merasa bahwa desain baru tersebut mengganggu. Mereka pun memutuskan untuk mengambil keputusan berdasarkan hasil A/A/B testing.

Para pengguna dibagi menjadi tiga kelompok: dua kelompok kontrol diperlihatkan dengan versi font lama dan satu kelompok uji diperlihatkan dengan versi font terbaru. Tugasmu adalah mencari tahu font mana yang akan memberi hasil terbaik.

Membuat dua kelompok A (kontrol) memang memberikan keuntungan tertentu. Kita bisa menetapkan aturan bahwa keakuratan pengujian hanya akan diterima jika kedua kelompok kontrol memberikan hasil yang serupa. Jika ada perbedaan yang signifikan di antara kedua kelompok A, hal ini bisa membantu kita untuk mengidentifikasi faktor-faktor yang mungkin mendistorsi hasil yang kita peroleh. Membandingkan kelompok kontrol juga akan memberikan kita gambaran terkait berapa lama waktu dan data yang diperlukan saat menjalankan proses selanjutnya.


# Deskripsi data
Setiap entri log adalah catatan tindakan pengguna atau suatu peristiwa.
* EventName — nama peristiwa
* DeviceIDHash — ID unik pengguna
* EventTimestamp — waktu peristiwa
* ExpId — nomor eksperimen: 246 dan 247 untuk kelompok kontrol, 248 untuk kelompok uji

# Tujuan
* Menentukan hasil dari A/A/B Testing
* Mencari pada tahap apa mulai kehilangan banyak pengguna
* Menemukan persentase pengguna yang terus berlanjut dari satu tahap ke tahap berikutnya
* Menentukan persentase pengguna yang menyelesaikan dari tahap awal sampai dengan pembayaran

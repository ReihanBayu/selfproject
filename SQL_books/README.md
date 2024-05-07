# Pendahuluan
Virus corona yang kehadirannya mengejutkan seluruh dunia telah mengubah rutinitas harian semua orang.󠀲󠀡󠀠󠀦󠀥󠀨󠀧󠀢󠀳󠀰 Kini, warga kota tidak lagi menghabiskan waktu luangnya di luar rumah seperti pergi ke kafe dan mal. Mereka lebih sering berada di rumah, menghabiskan waktunya dengan membaca buku.󠀲󠀡󠀠󠀦󠀥󠀨󠀧󠀣󠀳󠀰 Hal ini pun mendorong perusahaan startup untuk mengembangkan aplikasi baru bagi para pecinta buku.󠀲󠀡󠀠󠀦󠀥󠀨󠀧󠀤󠀳
Kamu telah diberi sebuah database dari salah satu perusahaan yang bersaing dalam industri ini.󠀲󠀡󠀠󠀦󠀥󠀨󠀧󠀥󠀳󠀰 Database tersebut berisi data tentang buku, penerbit, penulis, serta rating dan ulasan pelanggan atas buku terkait.󠀲󠀡󠀠󠀦󠀥󠀨󠀧󠀦󠀳󠀰 Informasi ini akan digunakan dalam membuat penawaran harga untuk sebuah produk baru.

# Deskripsi Data

## books:

󠀰Berisi data tentang buku:
* book_id — ID buku
* author_id — ID penulis
* title — judul buku
* num_pages — jumlah halaman
* publication_date — tanggal penerbitan
* publisher_id — ID penerbit

## authors:
Berisi data tentang penulis:
* author_id — ID penulis
* author — nama penulis

## publishers:
Berisi data tentang penerbit:
* publisher_id — ID penerbit
* publisher — nama penerbit

## ratings:
󠀰Berisi data tentang rating pengguna:
* rating_id — ID rating
* book_id — ID buku
* username — nama pengguna yang memberi rating buku
* rating

## reviews:
Berisi data tentang ulasan pelanggan:
* review_id — ID ulasan
* book_id — ID buku
* username — nama pengguna yang mengulas buku
* text — teks ulasan

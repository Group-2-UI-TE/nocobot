# Nikea

  Pada proyek ini, kami mengambil topik niaga-el (e-commerce) yang berfokus pada penjualan produk perabot rumah tangga yang kami namakan “Nikea”. Niaga-el merupakan suatu proses yang dilakukan oleh konsumen (customer) dalam membeli dan menjual berbagai macam produk secara elektronik dari perusahaan ke perusahaan lain dengan menggunakan perangkat keras serta internet dan sarana daring lainnya sebagai perantara transaksi bisnis yang akan dilakukan. Singkatnya, niaga-el adalah suatu alat yang memenuhi keinginan perusahaan, manajemen, dan konsumen guna mengurangi biaya layanan (service cost) ketika meningkatkan kualitas suatu barang dan meningkatkan kecepatan layanan pengiriman.

  Rumah tentu semakin nyaman jika dilengkapi dengan peralatan penunjang kebutuhan rumah tangga yang biasa digunakan dalam kehidupan sehari-hari. Tak bisa dimungkiri bahwa penggunaan produk tersebut menjadi hal yang lumrah, bahkan sangat dibutuhkan oleh khalayak modern. Produk tersebut meliputi barang elektronik, furnitur, kebutuhan dapur, dan lain-lain.

  Nikea dibuat untuk memudahkan para pembeli untuk berbelanja kebutuhan rumah tangga dan elektronik secara daring tanpa harus datang ke toko, terutama pada situasi pandemi seperti saat ini yang mengharuskan masyarakat untuk tetap berada di rumah masing-masing.

  Dalam situs web yang akan kami buat terdapat beberapa peran pengguna (users roles) yang terlibat, di antaranya

• administrator (pengelola),

• pemilik toko (platform),

• pelanggan (customers), dan

• jasa pengantar logistik.

  Selain itu, terdapat juga proses penting dalam situs web tersebut. Berikut adalah proses penting tersebut.

• Pemenuhan pemesanan (Ordering Fulfillment)

  Proses pertama adalah Ordering Fulfillment atau Pemenuhan pemesanan dimana proses ini melibatkan 2 role atau peran yaitu pelanggan (customers) dan pemilik toko. Proses ini terdiri dari 4 yaitu yang pertama adalah pesanan atau order yang dapat dibuat oleh pelanggan lalu ada juga proses pesanan diubah yang dilakukan oleh pemilik toko, pesanan disetujui oleh pemilik toko, dan pesanan ditolak oleh pemilik toko yang akan dilakukan jika dalam jangka waktu tertentu (tiga hari) tidak dikonfirmasi maka proses pemesanan akan dihentikan. Namun, jika proses pemesanan diteruskan, maka logical arrangements akan diinisialisasi dalam proses Carrier Appointment).

• Carrier Appointment

  Carrier appointment adalah proses pengurusan data untuk persiapan pengiriman barang, pengaturan pengiriman barang seperti rute pengiriman, volume/bobot paket, penentuan angkutan, serta penjemputan barang oleh Jasa Pengantar Logistik. Jika proses persiapan ini tidak tepat waktu maka pesanan akan dibatalkan, sebaliknya jika proses persiapan tepat waktu maka barang/paket akan diambil (pick-up) oleh Jasa Pengantar Logistik yang artinya proses payment atau pembayaran dan Freight in Transit atau pengangkutan dilakukan secara paralel/bersamaan bisa dilakukan.

• Payment

  Proses yang ketika adalah pembayaran (payment), berkaitan dengan proses pembayaran untuk barang dan biaya pengiriman barang. Dalam prosesnya terdapat beberapa kegiatan yang dilakukan, yaitu mengirim invoice, melakukan konfirmasi pembayaran, membuat Shipment Remittance Advice , mengeluarkan Shipment Payment Order, approve shipment payment, serta memproses pembayaran untuk pengiriman. Role yang terlibat dalam proses tersebut hanyalah pelanggan (customer) saja.

• Freight Transit

  Pada proses pengangkutan barang/Freight in Transit, Order Department melakukan pemeriksaan setelah status pengiriman dalam perjalanan, dan juga menangani notifikasi progress pengiriman dari Carrier Department. Proses ini diakhiri dengan pengiriman barang ke Customer. Dalam proses tersebut, role yang terlibat hanyalah jasa pengantar logistik.

• Freight Delivered

  Proses yang terakhir setelah proses pembayaran dan pengiriman barang selesai adalah proses Freight Delivered atau proses pengiriman barang, proses ini menangani klaim kerusakan atau kehilangan barang pesanan dan juga permintaan pengembalian barang. Jika tidak ada klaim kerusakan atau kehilangan dalam jangka waktu tertentu, maka proses pemesanan selesai. Dalam proses tersebut, role yang terlibat adalah administrator, pelanggan (customer), dan pemilik toko.

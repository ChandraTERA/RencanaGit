Git adalah perangkat lunak pengendali versi atau proyek manajemen kode perangkat lunak yang diciptakan oleh Linus Torvalds, yang pada awalnya ditujukan untuk pengembangan kernel Linux. Desain Git terinspirasi oleh BitKeeper dan Monotone.[2][3] Git pada awalnya hanya dirancang sebagai mesin tingkat rendah yang dapat digunakan oleh tampilan muka (front end) lain seperti Cogito atau StGIT.[4] Namun selanjutnya proyek inti Git telah berkembang menjadi pengendali revisi lengkap yang dapat digunakan langsung.[5] Saat ini, beberapa perangkat lunak terkenal menggunakan Git sebagai pengendali revisinya,[6] antara lain kernel Linux, Server X.org, pengembangan inti OLPC (One Laptop per Child),[7] serta kerangka kerja web Ruby on Rails.[8]

Pemeliharaan perangkat lunak Git saat ini diawasi oleh Junio Hamano. Dirilis di bawah Lisensi Publik Umum GNU versi 2, Git adalah suatu perangkat lunak bebas.

Pengembangan Git dimulai pada April 2005, setelah banyak pengembang kernel Linux berhenti menggunakan BitKeeper, sebuah sistem manajemen kendali kode sumber propiertary yang telah mereka gunakan untuk mememelihara proyek Linux sejak tahun 2002.[9][10] Pemegang hak cipta BitKeeper, Larry McVoy, menghentikan penggunaan gratis produk tersebut setelah mengklaim bahwa Andrew Tridgell telah membuat SourcePuller dengan cara merekayasa balik protokol BitKeeper.[11]

Linus Torvalds menginginkan sebuah sistem terdistribusi yang bisa dia gunakan seperti BitKeeper, tetapi tidak ada sistem gratis yang memenuhi kebutuhannya. Torvalds menyebutkan contoh sebuah sistem manajemen kode sumber yang memerlukan 30 detik untuk menerapkan tambalan dan memperbarui semua metadata yang terkait, dan mengatakan bahwa ini tidak akan cukup untuk memenuhi kebutuhan pengembangan kernel Linux, di mana sinkronisasi antarpengguna bisa membutuhkan 250 tindakan pada saat yang bersamaan. Untuk kriteria desainnya, dia menetapkan bahwa penambalan sebaiknya tidak menghabiskan lebih dari tiga detik, dan menambahkan tiga hal lainnya:[12]

Menggunakan Concurrent Versions System (CVS) sebagai contoh apa yang jangan dilakukan; apabila ragu, lakukan kebalikan dari yang CVS lakukan.[13]
Mendukung alur kerja terdistribusi yang menyerupai BitKeeper.[13]
Memiliki pelindung sangat kuat terhadap kerusakan data, baik yang tidak disengaja maupun yang berniat buruk.[14]
Kriteria-kriteria tersebut tidak dipenuhi oleh semua sistem kendali versi yang tersedia pada saat itu, jadi setelah rilis pengembangan Linux 2.6.12-rc2, Torvalds mulai menulis sistem kendali versinya sendiri.[13]

Pengembangan Git dimulai pada 3 April 2005.[15] Torvalds mengumumkan proyeknya pada 6 April dan Git mampu melakukan self-hosting pada keesokan harinya.[15][16] Penggabungan (merge) beberapa cabang pertama kali dilakukan pada 18 April.[17] Torvalds mencapai sasaran performanya; pada 29 April, Git sudah tercatat mengirim tambalan ke pohon kernel Linux dengan kecepatan 6,7 tambalan per detik.[18] Pada 16 Juni, Git mengurus rilis 2.6.12 kernel Linux.[19]

Torvalds menyerahkan pemeliharaan pada 26 Juli 2005 kepada Junio Hamano, seorang kontributor besar dalam proyek.[20] Hamano bertanggung jawab atas rilis 1.0 pada 21 Desember 2005 dan terus menjadi pemelihara utama proyek.[21]  








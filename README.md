# Belajar Sendiri Ilmu Komputer

> Dokumen ini adalah terjemahan dari [TeachYourselfCS](https://teachyourselfcs.com/). Untuk versi aslinya, [lihat di sini](https://teachyourselfcs.com/).

> Catatan: panduan ini telah diperbarui pada Mei 2020. Untuk versi sebelumnya, [lihat di sini](https://teachyourselfcs.com/2016/).

Jika Anda adalah seorang _engineer_ autodidak atau lulusan _bootcamp_, Anda berutang pada diri Anda untuk mendalami ilmu komputer. Untungnya, Anda bisa mendapat pendidikan ilmu komputer kelas dunia tanpa harus menghabiskan waktu dan uang untuk program sarjana 💸.

Ada banyak sumber belajar di luar sana, tapi beberapa lebih baik dari yang lain. Anda tidak perlu lagi artikel "200+ Kursus Online Gratis". Anda perlu jawaban dari pertanyaan ini:

- **Mata pelajaran** apa yang harus dipelajari, dan mengapa?
- Apa **buku atau seri video pembelajaran terbaik** untuk setiap mata pelajaran?

Panduan ini adalah upaya kami untuk menjawab pertanyaan tersebut.

## TL;DR:

Pelajari kesembilan mata pelajaran di bawah, dalam urutan yang disajikan, baik menggunakan buku teks atau seri video pembelajaran yang disarankan, tapi lebih ideal menggunakan keduanya. Targetkan 100-200 jam belajar untuk setiap topik, lalu ulas kembali topik favorit sepanjang karir Anda 🚀.

| Mata pelajaran                                                          | Mengapa dipelajari?                                                                                                                                                              | Buku                                                | Video                                |
| ----------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------- | ------------------------------------ |
| **[Pemrograman](#pemrograman)**                                         | Jangan menjadi orang yang "tidak mengerti" sesuatu seperti rekursi.                                                                                                              | _Structure and Interpretation of Computer Programs_ | Berkeley CS 61A oleh Brian Harvey    |
| **[Arsitektur Komputer](#arsitektur-komputer)**                         | Jika Anda tidak memiliki pemahaman yang kuat tentang cara kerja komputer, semua abstraksi tingkat tinggi Anda akan rapuh.                                                        | _Computer Systems: A Programmer's Perspective_      | Berkeley CS 61C                      |
| **[Algoritma dan Struktur Data](#algoritma-dan-struktur-data)**         | Jika Anda tidak tahu cara menggunakan struktur data yang sering digunakan seperti tumpukan, antrian, pohon, dan grafik, Anda tidak akan dapat memecahkan masalah yang menantang. | _The Algorithm Design Manual_                       | Video perkuliahan oleh Steven Skiena |
| **[Matematika untuk Ilmu Komputer ](#math-for-cs)**                     | Ilmu komputer pada dasarnya adalah cabang matematika terapan, jadi mempelajari matematika akan memberi Anda keunggulan kompetitif.                                               | _Mathematics for Computer Science_                  | MIT 6.042J oleh Tom Leighton         |
| **[Sistem Operasi](#sistem-operasi)**                                   | Sebagian besar kode yang Anda tulis dijalankan oleh sistem operasi, jadi Anda harus tahu bagaimana mereka berinteraksi.                                                          | _Operating Systems: Three Easy Pieces_              | Berkeley CS 162                      |
| **[Jaringan Komputer](#jaringan-komputer)**                             | Internet telah menjadi suatu hal yang penting: pahami cara kerjanya untuk membuka potensi penuhnya.                                                                              | _Computer Networking: A Top-Down Approach_          | Stanford CS 144                      |
| **[Basis Data](#basis-data)**                                           | Data adalah bagian terpenting inti dari sebuah program, tetapi hanya sedikit yang memahami bagaimana sistem basis data bekerja.                                                  | _Readings in Database Systems_                      | Berkeley CS 186 oleh Joe Hellerstein |
| **[Bahasa Pemrograman dan Kompiler](#bahasa-pemrograman-dan-kompiler)** | Jika Anda memahami cara kerja bahasa pemrograman dan kompiler, Anda dapat menulis kode dengan lebih baik dan mempelajari bahasa pemrograman baru dengan lebih mudah              | _Crafting Interpreters_                             | Kursus online oleh Alex Aiken di edX |
| **[Sistem Terdistribusi](#sistem-terdistribusi)**                       | Saat ini, sebagian besar sistem adalah sistem terdistribusi.                                                                                                                     | _Designing Data-Intensive Applications_             | MIT 6.824                            |

## Masih terlalu banyak?

Jika mempelajari 9 topik selama beberapa tahun terasa berlebihan, kami sarankan Anda fokus hanya pada dua buku: _Computer Systems: A Programmer's Perspective_ dan _Designing Data-Intensive Applications_. Berdasarkan pengalaman kami, kedua buku ini memberikan manfaat yang sangat besar atas waktu yang diinvestasikan, terutama untuk _engineer_ autodidak dan lulusan _bootcamp_ yang bekerja pada aplikasi yang terhubung dengan jaringan. Kedua buku tersebut juga berfungsi sebagai pengantar untuk topik dan sumber belajar lain yang tercantum di atas.

## Mengapa mempelajari ilmu komputer?

<img align="right" width="480" src="https://teachyourselfcs.com/bilotta-tweet.png">

Ada 2 jenis _software engineer_: mereka yang memahami ilmu komputer dengan baik sehingga dapat melakukan pekerjaan yang menantang dan inovatif, dan mereka yang dapat bertahan hanya karena mereka terbiasa menggunakan _framework_, _library_ dan alat-alat lain.

Keduanya disebut _software engineer_, dan keduanya cenderung mendapat gaji yang sama di awal karir mereka. Tetapi _engineer_ jenis pertama punya perkembangan menuju pekerjaan yang lebih memuaskan dengan bayaran yang meningkat seiring waktu, baik itu dari pekerjaan biasa atau proyek _open source_ yang memberi terobosan baru, menjadi pemimpin dalam hal teknis, atau dari kontribusi sebagai individu berkualitas tinggi.

_Engineer_ jenis pertama menemukan cara mempelajari ilmu komputer secara mendalam, baik melalui cara konvensional atau dengan belajar tanpa henti sepanjang karir mereka. _Engineer_ jenis kedua biasanya hanya berada di atas, mempelajari alat dan teknologi tertentu daripada mempelajari fondasi yang mendasarinya, hanya menambah keterampilan baru ketika tren berubah.

Saat ini, jumlah orang yang memasuki industri ini meningkat pesat, sementara jumlah lulusan ilmu komputer relatif tetap. Kelebihan pasokan _engineer_ jenis kedua ini dapat mengurangi kesempatan kerja dan menjauhkan mereka dari pekerjaan yang lebih memuaskan pada industri ini. Apakah karena Anda ingin menjadi _engineer_ jenis pertama atau sekadar mencari keamanan kerja yang lebih tinggi, mempelajari ilmu komputer adalah satu-satunya jalan yang dapat diandalkan.

## Panduan mata pelajaran

### Pemrograman

<img align="right" width="200" src="https://teachyourselfcs.com/sicp.jpg">

Sebagian besar program sarjana ilmu komputer dimulai dengan "pengantar" pemrograman komputer. Versi terbaik dari kursus ini tidak hanya diperuntukkan bagi pemula, tetapi juga bagi mereka yang melewatkan konsep dan model pemrograman yang penting ketika pertama kali belajar.

Rekomendasi kami untuk topik ini adalah buku klasik _Structure and Interpretation of Computer Programs_, yang tersedia secara daring dan gratis baik sebagai [buku](https://mitpress.mit.edu/sites/default/files/sicp/full-text/book/book.html), maupun sebagai seri [video perkuliahan dari MIT](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/). Meskipun seri video tersebut bagus, kami lebih menyarankan video kuliah SICP oleh Brian Harvey (untuk kursus 61A di Berkeley). Video kuliah ini lebih baik dan lebih pantas ditargetkan pada mahasiswa baru daripada video kuliah dari MIT.

Kami merekomendasikan untuk setidaknya menyelesaikan tiga bab pertama SICP beserta latihannya. Untuk latihan tambahan, Anda bisa mengerjakan masalah pemrograman seperti yang ada pada [exercism](https://exercism.org/).

Sejak panduan ini pertama kali diterbitkan pada tahun 2016, salah satu pertanyaan yang paling sering diajukan adalah apakah kami akan merekomendasikan rekaman terbaru kuliah 61A yang diajarkan oleh John DeNero, dan/atau buku panduannya [_Composing Programs_](https://composingprograms.com/), yang “sesuai dengan tradisi SICP” tetapi menggunakan Python. Menurut kami sumber belajar dari DeNero juga bagus, dan beberapa siswa mungkin akhirnya lebih menyukainya, tetapi kami tetap menyarankan SICP, Scheme, dan video kuliah oleh Brian Harvey sebagai rangkaian sumber belajar pertama untuk dicoba.

Mengapa? Karena SICP sangat unik dalam kemampuannya—setidaknya secara potensial—untuk mengubah pemahaman dasar Anda tentang komputer dan pemrograman. Tidak semua orang akan merasakannya. Beberapa akan membenci buku itu, bahkan ada yang tidak akan melewati beberapa halaman pertama. Tetapi potensi manfaatnya membuatnya layak untuk dicoba.

Jika Anda tidak dapat menikmati SICP, cobalah _Composing Programs_. Jika masih tidak sesuai, maka cobalah [_How to Design Programs_](https://htdp.org/). Jika tidak ada satu pun dari buku-buku ini yang memberi manfaat bagi Anda, mungkin itu pertanda bahwa Anda harus fokus pada topik lain untuk sementara waktu, dan meninjau kembali disiplin ilmu pemrograman dalam satu atau dua tahun ke depan.

Dan terakhir, satu poin klarifikasi: panduan ini TIDAK dirancang untuk mereka yang baru memulai pemrograman. Kami berasumsi bahwa Anda adalah seorang _programmer_ yang kompeten tanpa latar belakang ilmu komputer, yang ingin mengisi kesenjangan pengetahuan. Alasan kami menyertakan bagian tentang "pemrograman" hanyalah pengingat bahwa mungkin masih ada banyak hal untuk dipelajari. Bagi mereka yang belum pernah menulis kode sebelumnya, dan ingin memulai, Anda mungkin lebih suka panduan seperti ini.

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

Sejak panduan ini pertama kali diterbitkan pada tahun 2016, salah satu pertanyaan yang paling sering diajukan adalah apakah kami akan merekomendasikan rekaman terbaru kuliah 61A yang diajarkan oleh John DeNero, dan/atau buku panduannya [_Composing Programs_](https://composingprograms.com/), yang "sesuai dengan tradisi SICP" tetapi menggunakan Python. Menurut kami sumber belajar dari DeNero juga bagus, dan beberapa siswa mungkin akhirnya lebih menyukainya, tetapi kami tetap menyarankan SICP, Scheme, dan video kuliah oleh Brian Harvey sebagai rangkaian sumber belajar pertama untuk dicoba.

Mengapa? Karena SICP sangat unik dalam kemampuannya—setidaknya secara potensial—untuk mengubah pemahaman dasar Anda tentang komputer dan pemrograman. Tidak semua orang akan merasakannya. Beberapa akan membenci buku itu, bahkan ada yang tidak akan melewati beberapa halaman pertama. Tetapi potensi manfaatnya membuatnya layak untuk dicoba.

Jika Anda tidak dapat menikmati SICP, cobalah _Composing Programs_. Jika masih tidak sesuai, maka cobalah [_How to Design Programs_](https://htdp.org/). Jika tidak ada satu pun dari buku-buku ini yang memberi manfaat bagi Anda, mungkin itu pertanda bahwa Anda harus fokus pada topik lain untuk sementara waktu, dan meninjau kembali disiplin ilmu pemrograman dalam satu atau dua tahun ke depan.

Dan terakhir, satu poin klarifikasi: panduan ini TIDAK dirancang untuk mereka yang baru memulai pemrograman. Kami berasumsi bahwa Anda adalah seorang _programmer_ yang kompeten tanpa latar belakang ilmu komputer, yang ingin mengisi kesenjangan pengetahuan. Alasan kami menyertakan bagian tentang "pemrograman" hanyalah pengingat bahwa mungkin masih ada banyak hal untuk dipelajari. Bagi mereka yang belum pernah menulis kode sebelumnya, dan ingin memulai, Anda mungkin lebih suka panduan seperti ini.

### Sistem Operasi

<img align="right" width="200" src="https://teachyourselfcs.com/ostep.jpeg">

[_Operating System Concepts_](https://www.amazon.com/dp/1118063333/) ("_Dinosaur book_") dan [_Modern Operating Systems_](https://www.amazon.com/dp/1118063333/) adalah dua buku "klasik" tentang sistem operasi. Keduanya menuai kritik karena kurang jelas dan tidak ramah bagi siswa pada umumnya.

_Operating Systems: Three Easy Pieces_ adalah alternatif yang [tersedia gratis secara daring](https://pages.cs.wisc.edu/~remzi/OSTEP/). Kami sangat menyukai struktur dan keterbacaan buku ini, dan merasa bahwa latihan yang terdapat pada buku ini sangat bermanfaat.

Setelah OSTEP, kami ingin Anda mengeksplorasi beberapa keputusan pada rancangan sistem operasi tertentu, melalui beberapa buku "{nama sistem operasi} Internals" seperti [_Lions' commentary on Unix_](https://www.amazon.com/Lions-Commentary-Unix-John/dp/1573980137/), [_The Design and Implementation of the FreeBSD Operating System_](https://www.amazon.com/Design-Implementation-FreeBSD-Operating-System/dp/0321968972/), dan [_Mac OS X Internals_](https://www.amazon.com/Mac-OS-Internals-Systems-Approach/dp/0321278542/). Untuk Linux, kami menyarankan buku Robert Love yang luar biasa, yaitu [_Linux Kernel Development_](https://www.amazon.com/Linux-Kernel-Development-Robert-Love/dp/0672329468).

Cara yang bagus untuk memperkuat pemahaman Anda tentang sistem operasi adalah dengan membaca _source code_ dari kernel sistem operasi kecil dan mencoba menambahkan fitur baru. Salah satu pilihan adalah [xv6](https://pdos.csail.mit.edu/6.828/2016/xv6.html), sebuah _port_ sistem operasi Unix V6 ke bahasa ANSI C dan arsitektur x86, yang dikembangkan untuk pembelajaran di MIT. Pada buku OSTEP terdapat lampiran [xv6 labs](https://pages.cs.wisc.edu/~remzi/OSTEP/lab-projects-xv6.pdf) yang penuh dengan ide-ide hebat untuk proyek-proyek potensial.

### Jaringan Komputer

<img align="right" width="200" src="https://teachyourselfcs.com/top-down.jpg">

> Anda tidak bisa menatap bola kristal dan melihat masa depan. Apa yang akan menjadi Internet di masa depan adalah apa yang dibuat oleh masyarakat.

— _Bob Kahn_

Mengingat begitu banyak rekayasa perangkat lunak ada di server dan klien web, salah satu bidang ilmu komputer yang paling penting adalah jaringan komputer. Siswa kami yang mempelajari jaringan secara autodidak menemukan bahwa mereka akhirnya memahami istilah, konsep, dan protokol yang telah berada di sekitar mereka selama bertahun-tahun.

Buku favorit kami tentang topik ini adalah [_Computer Networking: A Top-Down Approach_](https://smile.amazon.com/Computer-Networking-Top-Down-Approach-7th/dp/0133594149/). Proyek-proyek kecil dan latihan dalam buku ini sangat layak untuk dikerjakan, dan kami sangat menyukai _Wireshark labs_ yang telah mereka [sediakan gratis secara daring](http://www-net.cs.umass.edu/wireshark-labs/).

Bagi mereka yang lebih menyukai materi dalam bentuk video, kami menyarankan video kuliah [Introduction to Computer Networking](https://www.youtube.com/playlist?list=PLoCMsyE1cvdWKsLVyf6cPwCLDIZnOj0NS) dari Stanford yang sebelumnya ada pada platform belajar online mereka, tapi sayangnya sekarang hanya tersedia sebagai playlist tidak resmi di YouTube.

## Pertanyaan yang sering diajukan

#### Untuk siapa panduan ini dibuat?

Kami paham bahwa Anda adalah seorang _software engineer_ autodidak, lulusan _bootcamp_ atau siswa SMA yang ingin tahu, atau mahasiswa yang ingin melengkapi pendidikan formal Anda dengan belajar mandiri. Pertanyaan tentang kapan memulai perjalanan ini sepenuhnya bersifat pribadi, tetapi kebanyakan orang cenderung mendapat manfaat dari memiliki beberapa pengalaman profesional sebelum menyelam terlalu jauh ke dalam teori ilmu komputer. Misalnya, kami melihat bahwa siswa suka belajar tentang sistem basis data jika mereka telah bekerja dengan basis data secara profesional, atau tentang jaringan komputer jika mereka pernah mengerjakan satu atau dua proyek aplikasi web.

#### Bagaimana dengan AI/grafis/topik favorit X?

Kami telah mencoba membatasi daftar kami pada topik ilmu komputer yang kami rasa perlu diketahui oleh setiap _software engineer_, terlepas dari spesialisasi atau industri, tetapi dengan fokus pada sistem. Dari pengalaman kami, ini akan menjadi topik dengan manfaat terbesar untuk sebagian besar _engineer_ autodidak dan lulusan _bootcamp_, dan memberikan dasar yang kuat untuk studi lebih lanjut. Selanjutnya, Anda akan berada dalam posisi yang jauh lebih baik untuk membaca buku teks atau makalah lanjutan dan mempelajari konsep utama tanpa banyak panduan. Berikut adalah titik awal yang kami sarankan untuk beberapa "topik pilihan" umum:

- Untuk topik kecerdasan buatan: selesaikan [kursus pengantar AI dari Berkeley](http://ai.berkeley.edu/) dengan menonton video dan mengerjakan proyek Pacman yang luar biasa. Untuk buku teks, gunakan _Artificial Intelligence: A Modern Approach_ oleh Russell dan Norvig.
- Untuk topik _machine learning_: selesaikan kursus di Coursera oleh Andrew Ng. Bersabarlah, dan pastikan Anda memahami dasar-dasarnya sebelum beralih ke topik baru yang menarik seperti _deep learning_.
- Untuk grafik komputer: pelajari materi [CS 184 Berkeley](https://inst.eecs.berkeley.edu/~cs184/fa12/onlinelectures.html), dan gunakan [_Computer Graphics: Principles and Practice_](https://www.amazon.com/Computer-Graphics-Principles-Practice-3rd/dp/0321399528) sebagai buku teks.

#### Seberapa ketat urutan yang disarankan?

Jika diperhatikan, semua mata pelajaran ini memiliki sejumlah bagian yang saling tumpang tindih, dan saling merujuk satu sama lain. Anda dapat mengambil contoh hubungan antara matematika diskrit dan algoritma: mempelajari matematika terlebih dahulu akan membantu Anda menganalisis dan memahami lebih dalam algoritma Anda, tetapi mempelajari algoritma terlebih dahulu akan memberikan motivasi dan konteks yang lebih besar untuk matematika diskrit. Idealnya, Anda akan mengunjungi kembali kedua topik ini berkali-kali sepanjang karier Anda.

Dengan demikian, urutan yang kami sarankan dapat membantu Anda _untuk langsung memulai_... jika Anda memiliki alasan kuat untuk memilih urutan yang berbeda, maka lakukanlah. Beberapa "prasyarat" yang menurut kami penting adalah: arsitektur komputer sebelum sistem operasi atau database, dan jaringan dan sistem operasi sebelum sistem terdistribusi.

#### Apa perbedaan panduan ini dengan kurikulum Open Source Society atau freeCodeCamp?

Ketika panduan ini pertama kali ditulis pada tahun 2016, [panduan OSS](https://github.com/open-source-society/computer-science) membahas terlalu banyak mata pelajaran, menyarankan sumber belajar yang tidak lebih baik dari kebanyakan, dan tidak memberikan alasan atau panduan seputar mengapa atau aspek apa dari kursus tertentu yang lebih bermanfaat. Kami berusaha untuk membatasi daftar kursus kami hanya untuk kursus yang _benar-benar harus Anda ketahui_ sebagai _software engineer_, terlepas dari spesialisasi Anda, dan untuk membantu Anda memahami mengapa setiap kursus disertakan. Di tahun-tahun berikutnya, kualitas panduan OSS telah meningkat, tetapi kami masih berpikir bahwa panduan ini memberikan jalur pembelajaran yang lebih jelas dan lebih terpadu.

freeCodeCamp sebagian besar berfokus pada pemrograman, bukan ilmu komputer. Untuk alasan mengapa Anda mungkin ingin mempelajari ilmu komputer, coba lihat [di atas](#mengapa-mempelajari-ilmu-komputer). Jika Anda baru memulai pemrograman, kami sarankan untuk memprioritaskan kurikulum tersebut, dan kembali ke panduan ini dalam satu atau dua tahun ke depan.

#### Bagaimana dengan bahasa pemrograman X?

Mempelajari bahasa pemrograman tertentu adalah hal yang sangat berbeda dengan mempelajari bidang pada ilmu komputer — mempelajari bahasa pemrograman jauh _lebih mudah_ dan _tidak lebih penting_ manfaatnya. Jika Anda sudah mengetahui beberapa bahasa pemrograman, kami sangat menyarankan Anda untuk mengikuti panduan kami dan menyesuaikan penguasaan bahasa pemrograman di sela waktu, atau setelah menyelesaikannya. Jika Anda telah mempelajari pemrograman dengan baik (seperti melalui _Structure and Interpretation of Computer Programs_), dan terutama jika Anda telah mempelajari kompiler, Anda hanya akan membutuhkan waktu setidaknya satu akhir pekan untuk mempelajari bahasa pemrograman baru, setelah itu Anda dapat mempelajarinya tentang _library_/_tooling_/ekosistem di tempat kerja.

#### Bagaimana dengan teknologi terbaru X?

Tidak ada satu teknologi pun yang lebih penting sehingga belajar menggunakannya harus menjadi bagian inti dari pendidikan Anda. Di sisi lain, adalah hal yang sangat bagus bahwa Anda bersemangat untuk mempelajari teknologi tersebut. Triknya adalah memulai dari bidang atau konsep yang mendasari teknologi tertentu, dan mempelajarinya secara mendalam sebelum melihat bagaimana teknologi terbaru Anda mengisi gambaran yang lebih besar.

#### Mengapa Anda masih merekomendasikan SICP?

Anda perlu mencoba buku SICP. Beberapa orang menganggap SICP mencengangkan, ciri yang hanya dimiliki oleh segelintir buku. Jika Anda tidak menyukainya, Anda dapat mencoba buku lain dan setelah itu mungkin kembali ke SICP.

#### Mengapa Anda masih merekomendasikan _Dragon book_?

_Dragon book_ masih merupakan sumber tunggal terlengkap untuk topik seputar kompiler. Buku tersebut sering mendapat reputasi buruk, biasanya karena terlalu menekankan pada topik tertentu yang kurang populer untuk dibahas secara detail, seperti _parsing_. Masalahnya adalah, buku itu tidak pernah dimaksudkan untuk dipelajari dari sampul ke sampul, hanya untuk menyediakan materi pembelajaran yang cukup bagi seorang instruktur untuk menyusun materi kuliah. Demikian pula, seorang pembelajar mandiri dapat memilih petualangan mereka melalui buku, atau lebih baik mengikuti saran yang telah dibuat oleh dosen dalam garis besar mata kuliah mereka.

#### Bagaimana saya bisa mendapatkan buku teks yang terjangkau?

Kebanyakan dari buku teks yang kami sarankan tersedia secara daring dan gratis, berkat kemurahan hati penulisnya. Untuk buku yang tidak tersedia gratis, kami sarankan untuk membeli buku bekas edisi lama. Sebagai aturan umum, jika suatu buku teks punya lebih dari beberapa edisi, kemungkinan besar edisi lama sudah cukup memadai. Jelas tidak mungkin versi terbaru 10x lebih baik daripada yang lama, meskipun harganya berbeda!

#### Siapa yang menulis panduan ini?

Panduan ini ditulis oleh [Oz Nova](https://twitter.com/oznova_) dan [Myles Byrne](https://twitter.com/quackingduck), dengan pembaruan pada tahun 2020 oleh Oz. Panduan ini dibuat berdasarkan pengalaman kami mengajar dasar-dasar ilmu komputer kepada lebih dari 1000 _engineer_ autodidak atau lulusan _bootcamp_ dalam kelompok kecil di San Francisco dan secara daring. Terima kasih kepada semua siswa kami atas masukan tentang sumber belajar mandiri.

Kami yakin Anda dapat mempelajari semua hal di atas, dengan waktu dan motivasi yang cukup. Tetapi jika Anda lebih menyukai program intensif, terstruktur, dan dibimbing oleh instruktur, Anda mungkin tertarik dengan program [Computer Science Intensive](https://bradfieldcs.com/csi/) dari kami. Kami [TIDAK](https://ozwrites.com/masters/) menyarankan untuk mengejar gelar magister.

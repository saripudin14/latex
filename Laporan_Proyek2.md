IMPLEMENTASI SISTEM INFORMASI PEMINJAMAN SARANA DAN PRASARANA KAMPUS BERBASIS WEB MENGGUNAKAN CRUD RDBMS


LAPORAN PROYEK II
Diajukan untuk Memenuhi Kelulusan Matakuliah Proyek 2 pada Program Studi DIV Teknik Informatika





DISUSUN OLEH :
714230008	MUHAMMAD ARIF RIVALDI
714230041	RADITYA RIZKI RAHARJA



PROGRAM STUDI DIV TEKNIK INFORMATIKA 
SEKOLAH VOKASI
UNIVERSITAS LOGISTIK DAN BISNIS INTERNASIONAL

BANDUNG 2025
  
LEMBAR PENGESAHAN

IMPLEMENTASI SISTEM INFORMASI PEMINJAMAN SARANA DAN PRASARANA KAMPUS BERBASIS WEB MENGGUNAKAN CRUD RDBMS

Diajukan untuk memenuhi kelulusan matakuliah Proyek II
Program Studi Diploma IV Teknik Informatika
 Oleh :
Muhammad Arif Rivaldi	714240008
Raditya Rizki Raharja	714240041




 
SURAT PERNYATAAN TIDAK MELAKUKAN PLAGIARISME 

Nama		: Muhammad Arif Rivaldi
NPM		: 714240008
Program Studi	: DIV Teknik Informatika
Judul		: Implemntasi Sistem Informasi Peminjaman Sarana dan Prasarana Kampus
Berbasis Web Menggunakan CRUD RDBMS

Menyatakan bahwa :
1.	Proyek Pemrograman Aplikasi (Proyek III) saya ini adalah asli dan belum pernah diajukan untuk memenuhi kelulusan Proyek III pada program studi DIV Teknik Informatika baik di Universitas Logistik & Bisnis Internasional (ULBI) maupun di perguruan tinggi lainnya.
2.	Proyek Pemrograman Aplikasi (Proyek III) ini adalah murni gagasan, rumusan, dan penelitian saya sendiri tanpa bantuan orang lain, kecuali arahan pembimbing.
3.	Dalam Proyek Pemrograman Aplikasi (Proyek III) ini tidak terdapat karya atau pendapat yang telah ditulis ataupun dipublikasi orang lain, kecuali secara tertulis dengan jelas dicantumkan sebagai acuan dalam naskah dengan disebutkan nama pengarang dan dicantumkan dalam daftar pustaka.
4.	Pernyataan ini saya buat dengan sesungguhnya dan apabila di kemudian hari terdapat penyimpangan-penyimpangan dan ketidakbenaran dalam pernyataan ini, maka saya bersedia menerima sanksi akademik berupa pencabutan gelar yang telah diperoleh karena karya ini, serta sanksi lainnya sesuai dengan norma yang berlaku di perguruan tinggi lainnya.

SURAT PERNYATAAN TIDAK MELAKUKAN PLAGIARISME

Nama		: Raditya Rizki Raharja
NPM		: 714240041
Program Studi	: DIV Teknik Informatika
Judul		: Implemntasi Sistem Informasi Peminjaman Sarana dan Prasarana Kampus
Berbasis Web Menggunakan CRUD RDBMS

Menyatakan bahwa :
1.	Proyek Pemrograman Aplikasi (Proyek III) saya ini adalah asli dan belum pernah diajukan untuk memenuhi kelulusan Proyek III pada program studi DIV Teknik Informatika baik di Universitas Logistik & Bisnis Internasional (ULBI) maupun di perguruan tinggi lainnya.
2.	Proyek Pemrograman Aplikasi (Proyek III) ini adalah murni gagasan, rumusan, dan penelitian saya sendiri tanpa bantuan orang lain, kecuali arahan pembimbing.
3.	Dalam Proyek Pemrograman Aplikasi (Proyek III) ini tidak terdapat karya atau pendapat yang telah ditulis ataupun dipublikasi orang lain, kecuali secara tertulis dengan jelas dicantumkan sebagai acuan dalam naskah dengan disebutkan nama pengarang dan dicantumkan dalam daftar pustaka.
4.	Pernyataan ini saya buat dengan sesungguhnya dan apabila di kemudian hari terdapat penyimpangan-penyimpangan dan ketidakbenaran dalam pernyataan ini, maka saya bersedia menerima sanksi akademik berupa pencabutan gelar yang telah diperoleh karena karya ini, serta sanksi lainnya sesuai dengan norma yang berlaku di perguruan tinggi lainnya.


 
ABSTRACT 
ABSTRAK

 
KATA PENGANTAR

 
DAFTAR ISI

 
DAFTAR GAMBAR


 
DAFTAR TABEL
 
 
BAB 1 PENDAHULUAN
PENDAHULUAN

1.1	Deskripsi Aplikasi
Pemanfaatan teknologi informasi dalam bidang pendidikan memiliki peran penting dalam mendukung efektivitas pengelolaan sarana dan prasarana kampus. Sarana dan prasarana merupakan komponen pendukung utama dalam pelaksanaan kegiatan akademik maupun non-akademik, sehingga pengelolaannya perlu dilakukan secara terencana dan terdokumentasi dengan baik. Namun, pada banyak institusi pendidikan, proses pengelolaan dan peminjaman sarana dan prasarana masih dilakukan secara manual atau menggunakan media pencatatan yang terpisah, sehingga berpotensi menimbulkan berbagai permasalahan, seperti kesulitan pencarian data, keterlambatan penyusunan laporan, serta rendahnya efisiensi kerja pengelola (Nabella et al., 2025).
Perkembangan teknologi informasi mendorong penerapan sistem informasi berbasis web sebagai solusi alternatif untuk mengatasi permasalahan tersebut. Sistem informasi berbasis web memungkinkan pengelolaan data dilakukan secara terpusat serta dapat diakses secara fleksibel oleh pengguna yang berkepentingan. Dalam konteks institusi pendidikan tinggi, sistem peminjaman fasilitas kampus berbasis web dinilai mampu membantu pengguna dalam melakukan pengajuan peminjaman secara lebih mudah, serta membantu pengelola dalam melakukan pencatatan, pengawasan, dan pelaporan peminjaman fasilitas secara lebih efektif dan terstruktur (Purwati et al., 2022).
Selain itu, ketersediaan informasi peminjaman fasilitas secara real-time juga berperan penting dalam meminimalkan kesalahan informasi dan bentrok jadwal penggunaan sarana dan prasarana kampus. Sistem informasi peminjaman berbasis web dapat memberikan transparansi terkait ketersediaan fasilitas, sehingga proses peminjaman dapat berjalan lebih tertib dan terkoordinasi (Herlambang et al., 2020).
Berdasarkan permasalahan tersebut, dikembangkan Sistem Informasi Peminjaman Sarana dan Prasarana Kampus Berbasis Web Menggunakan CRUD RDBMS sebagai solusi untuk mengelola proses peminjaman fasilitas kampus secara terintegrasi. Sistem ini dirancang untuk mendukung proses pengajuan, persetujuan, serta pendokumentasian peminjaman sarana dan prasarana kampus. Dengan adanya sistem ini, diharapkan pengelolaan sarana dan prasarana kampus dapat dilakukan secara lebih efektif, transparan, dan akuntabel.



1.2	Rumusan Masalah
Berdasarkan latar belakang yang telah diuraikan sebelumnya, maka permasalahan dalam Proyek II ini dapat dirumuskan dalam bentuk pertanyaan sebagai berikut:
1.	Bagaimana merancang sistem informasi berbasis web yang mampu mengelola proses peminjaman sarana dan prasarana kampus secara efektif, terintegrasi, dan terkomputerisasi ?
2.	Bagaimana menyediakan mekanisme pengajuan dan pemantauan status peminjaman sarana dan prasarana kampus yang mudah diakses oleh mahasiswa secara real-time ?
3.	Bagaimana sistem informasi dapat meminimalkan terjadinya bentrok jadwal peminjaman serta mendukung pengelolaan data peminjaman yang terdokumentasi dengan baik untuk keperluan pelaporan dan evaluasi ?
1.3	Tujuan
Berdasarkan rumusan masalah yang telah diuraikan sebelumnya, maka tujuan dari pelaksanaan Proyek II ini adalah sebagai berikut:
1.	Untuk merancang dan membangun sistem informasi peminjaman sarana dan prasarana kampus berbasis web yang terintegrasi guna mendukung proses pengelolaan fasilitas kampus secara efektif dan terstruktur.
2.	Untuk menyediakan mekanisme pengajuan serta pemantauan status peminjaman sarana dan prasarana kampus yang mudah diakses oleh mahasiswa secara real-time.
3.	Untuk mendokumentasikan proses perancangan, implementasi, dan pengujian sistem peminjaman sarana dan prasarana kampus sebagai pemenuhan persyaratan mata kuliah Proyek II.
1.4	Lingkup Dokumentasi
Ruang lingkup dokumentasi dalam laporan ini meliputi:
1.	Perancangan dan implementasi sistem peminjaman sarana dan prasarana kampus yang mencakup proses pengajuan, persetujuan, dan pencatatan kehadiran peminjam.
2.	Analisis kebutuhan fungsional dan non-fungsional sistem yang mendukung pengelolaan peminjaman secara terintegrasi.
3.	Pengelolaan data inventaris sarana dan prasarana yang dibatasi pada operasi tambah, ubah (edit), dan hapus data, tanpa mencakup proses pengadaan atau manajemen stok lanjutan. 
BAB 2 LANDASAN TEORI
LANDASAN TEORI

2.1 Tinjauan Pustaka
Tinjauan pustaka berfungsi sebagai landasan teoritis dalam pengembangan sistem informasi peminjaman sarana dan prasarana kampus. Pengelolaan fasilitas kampus yang belum terintegrasi secara sistematis berpotensi menimbulkan berbagai permasalahan, seperti kesulitan pencatatan data, ketidakteraturan penggunaan fasilitas, serta keterlambatan dalam penyusunan laporan. Oleh karena itu, diperlukan sistem informasi yang mampu mengelola data sarana dan prasarana secara terstruktur guna mendukung efektivitas pengelolaan fasilitas di lingkungan pendidikan (Nabella et al., 2025).
Selain pengelolaan fasilitas, proses peminjaman juga memerlukan sistem yang terkomputerisasi agar berjalan lebih efisien dan transparan. Sistem informasi peminjaman berbasis web memungkinkan proses pengajuan, persetujuan, serta pendokumentasian peminjaman dilakukan secara terpusat dan mudah diakses oleh pengguna. Hal ini sejalan dengan penelitian yang menyatakan bahwa penerapan sistem informasi peminjaman berbasis web dapat meningkatkan efisiensi operasional serta mempermudah pengelolaan data peminjaman di lingkungan institusi pendidikan (Purwati et al., 2022).
2.1.1 Sistem Informasi
Sistem informasi merupakan kombinasi dari manusia, proses, data, dan teknologi yang saling berinteraksi untuk mengumpulkan, mengolah, menyimpan, dan menyebarkan informasi guna mendukung tujuan organisasi (Rukmana et al., 2023). Penerapan sistem informasi bertujuan untuk meningkatkan efisiensi, akurasi, serta kemudahan dalam pengelolaan data dan penyajian informasi.
Dalam sistem informasi peminjaman sarana dan prasarana kampus yang dikembangkan, konsep sistem informasi ini diterapkan untuk mengintegrasikan data pengguna, data sarana, proses peminjaman, serta proses persetujuan dalam satu platform berbasis web. Dengan adanya integrasi tersebut, proses pengelolaan peminjaman dapat dilakukan secara lebih terstruktur, transparan, dan mudah diakses oleh pihak terkait.
2.1.2 Sarana dan Prasarana
Sarana merupakan segala sesuatu yang digunakan secara langsung sebagai alat untuk menunjang kegiatan pendidikan, sedangkan prasarana adalah perangkat kelengkapan dasar yang tidak digunakan secara langsung namun berfungsi mendukung terselenggaranya proses pendidikan (Sopian, 2019).
Dalam sistem informasi peminjaman sarana dan prasarana kampus, sarana dan prasarana menjadi objek utama yang dikelola oleh sistem. Oleh karena itu, diperlukan pengelolaan data sarana dan prasarana yang terstruktur agar proses pencatatan, peminjaman, dan pelaporan dapat dilakukan secara tertib dan akurat.
2.1.3 Website
Website berfungsi sebagai media penyimpanan dan penyajian informasi secara digital yang dapat diakses kapan saja dan dari berbagai perangkat. Seiring perkembangannya, website tidak hanya dimanfaatkan sebagai media penyampaian informasi, tetapi juga sebagai sarana interaksi serta pengelolaan data, sehingga banyak digunakan sebagai platform pendukung berbagai kebutuhan organisasi dan institusi (Sanjaya & Hesinto, 2017).
Pada sistem informasi peminjaman sarana dan prasarana kampus, website digunakan sebagai platform utama yang memfasilitasi proses pengajuan peminjaman, persetujuan, serta pengelolaan data sarana dan prasarana secara terpusat. Penggunaan website memungkinkan sistem diakses dengan mudah oleh pengguna sesuai dengan hak akses yang dimiliki.
2.1.4 CRUD
CRUD merupakan operasi dasar dalam pengelolaan data pada sistem basis data yang meliputi Create, Read, Update, dan Delete. Operasi ini menjadi komponen utama dalam sistem informasi berbasis database karena seluruh proses pengolahan data dilakukan melalui mekanisme CRUD.
Pada sistem informasi peminjaman sarana dan prasarana, operasi CRUD digunakan untuk mengelola data sarana, data pengguna, serta data transaksi peminjaman, sehingga pengolahan data dapat dilakukan secara terstruktur dan terdokumentasi. Penerapan CRUD yang tepat juga berpengaruh terhadap kinerja sistem, karena metode implementasi CRUD dapat memengaruhi kecepatan dan efisiensi akses data (Zmaranda et al., 2020).
2.1.5 RDBMS
Relational Database Management System (RDBMS) merupakan sistem manajemen basis data yang menyimpan data dalam bentuk tabel-tabel yang saling berhubungan satu sama lain. Setiap tabel terdiri atas baris dan kolom, di mana hubungan antar tabel dibangun menggunakan primary key dan foreign key sehingga data dapat dikelola secara terstruktur dan terorganisir (Setyawati et al., 2020).
RDBMS mendukung pengelolaan dan manipulasi data menggunakan bahasa standar SQL (Structured Query Language) yang memungkinkan pengguna melakukan berbagai operasi terhadap data, termasuk penambahan, penampilan, pembaruan, dan penghapusan data. Dengan kemampuan tersebut, RDBMS banyak digunakan dalam pengembangan sistem informasi karena mampu menjaga konsistensi, integritas, serta kemudahan dalam pengelolaan data sesuai dengan kebutuhan sistem (Setyawati et al., 2020).
Berdasarkan landasan teori yang telah diuraikan, sistem informasi peminjaman sarana dan prasarana kampus dianalisis dan dirancang dengan mengacu pada konsep sistem informasi, website, operasi CRUD, serta pengelolaan basis data menggunakan RDBMS. Landasan teori ini menjadi dasar dalam penyusunan analisis kebutuhan dan perancangan sistem yang dibahas pada bab selanjutnya.
BAB 3 METODOLOGI PENELITIAN
METODE PENELITIAN

3.1	Jenis dan Metode Penelitian
Pemilihan metode dan pendekatan penelitian pada pengembangan Sistem Informasi Peminjaman Sarana dan Prasarana Kampus disesuaikan dengan karakteristik permasalahan yang dihadapi serta kebutuhan pengguna sistem. Permasalahan pengelolaan peminjaman fasilitas kampus yang masih dilakukan secara manual dan semi-digital menuntut adanya solusi sistem informasi yang terstruktur, adaptif, dan mampu mendukung proses operasional secara efektif. Oleh karena itu, metode dan pendekatan penelitian yang digunakan diarahkan untuk menghasilkan sistem yang tidak hanya memenuhi kebutuhan fungsional pengguna, tetapi juga mampu diimplementasikan secara optimal dalam lingkungan operasional kampus.
3.1.1 Jenis Penelitian
Penelitian ini merupakan penelitian terapan (applied research) yang berfokus pada pengembangan sistem informasi untuk mendukung proses peminjaman sarana dan prasarana kampus. Penelitian terapan dipilih karena tujuan utama penelitian ini bukan hanya menghasilkan kajian teoritis, tetapi juga menghasilkan produk perangkat lunak yang dapat digunakan secara langsung untuk menyelesaikan permasalahan nyata yang terjadi di lingkungan kampus.
Pendekatan yang digunakan dalam penelitian ini adalah rekayasa perangkat lunak, di mana proses penelitian meliputi analisis kebutuhan, perancangan sistem, pengembangan aplikasi, serta pengujian fungsional sistem.
3.1.2 Metode Penelitian
Metode penelitian yang digunakan adalah Scrum, yaitu salah satu metode pengembangan perangkat lunak berbasis Agile yang bersifat iteratif dan inkremental. Pemilihan metode Scrum didasarkan pada karakteristik permasalahan yang ditemukan dari hasil observasi dan wawancara dengan staf Sarana dan Prasarana kampus, antara lain:
1.	Kebutuhan sistem yang dinamis dan dapat berubah seiring proses pengembangan.
2.	Keterlibatan banyak pemangku kepentingan (Mahasiswa/UKM, Staf Sarpras, dan Security).
3.	Perlunya evaluasi berkala terhadap sistem yang dikembangkan agar sesuai dengan kebutuhan pengguna.
Metode Scrum memungkinkan pengembangan sistem dilakukan secara bertahap melalui beberapa sprint, sehingga setiap tahapan pengembangan dapat dievaluasi dan disempurnakan berdasarkan umpan balik pengguna.

3.1.3 Objek dan Subjek Penelitian
3.1.3.1 Objek Penelitian
Objek penelitian dalam penelitian ini adalah Sistem Informasi Peminjaman Sarana dan Prasarana Kampus ULBI, yang mencakup proses pengelolaan jadwal ruangan, pengajuan peminjaman, verifikasi peminjaman, validasi kehadiran, serta pembuatan laporan peminjaman secara terintegrasi. Sistem ini dirancang untuk menggantikan proses manual dan semi-digital yang sebelumnya digunakan, sehingga diharapkan dapat meningkatkan efisiensi, akurasi data, serta transparansi proses peminjaman.
3.1.3.2 Subjek Penelitian
Subjek penelitian adalah pihak-pihak yang terlibat langsung dalam penggunaan sistem, yaitu:
1.	Mahasiswa/UKM, sebagai pihak pemohon peminjaman sarana dan prasarana.
2.	Staf Sarana dan Prasarana, sebagai pihak pengelola dan pemberi persetujuan peminjaman.
3.	Petugas Keamanan (Security), sebagai pihak yang melakukan validasi kehadiran dan izin kegiatan di lapangan.
4.	Menggali kebutuhan sistem yang diharapkan.
5.	Mengidentifikasi kendala dalam proses peminjaman yang sedang berjalan.
6.	Menentukan fitur utama yang harus tersedia dalam sistem.
Penentuan subjek penelitian ini mengacu pada hasil analisis kebutuhan dan Use Case Diagram yang menggambarkan interaksi aktor dengan sistem.
3.1.4 Teknik Pengumpulan Data
3.1.4.1 Observasi
Teknik observasi dilakukan dengan mengamati secara langsung proses peminjaman sarana dan prasarana yang berjalan di lingkungan kampus. Observasi difokuskan pada proses pencatatan jadwal, pengajuan peminjaman, serta mekanisme verifikasi kegiatan yang masih dilakukan secara manual atau semi-digital. Hasil observasi digunakan sebagai dasar untuk mengidentifikasi permasalahan operasional yang terjadi pada sistem lama.
3.1.4.2 Wawancara
Wawancara dilakukan dengan staf Sarana dan Prasarana sebagai pihak yang bertanggung jawab dalam pengelolaan peminjaman fasilitas kampus. Wawancara Menggali kebutuhan sistem yang diharapkan.
1.	Menggali kebutuhan sistem yang diharapkan.
2.	Mengidentifikasi kendala dalam proses peminjaman yang sedang berjalan.
3.	Menentukan fitur utama yang harus tersedia dalam sistem.
Hasil wawancara ini kemudian dirangkum dalam dokumen spesifikasi kebutuhan perangkat lunak (SKPL).
3.1.4.3 Studi Pustaka
Pengelolaan sarana dan prasarana di institusi pendidikan memerlukan sistem informasi yang terintegrasi untuk mengatasi permasalahan pencatatan manual, keterlambatan informasi, serta kesulitan dalam penyusunan laporan. Penelitian sebelumnya menunjukkan bahwa sistem informasi manajemen sarana dan prasarana mampu meningkatkan efisiensi pengelolaan fasilitas, mempercepat proses administrasi, serta mempermudah monitoring penggunaan aset di lingkungan pendidikan (Nabella et al., 2025) 
Dalam pengembangan sistem informasi berbasis web, metode Agile khususnya Scrum banyak digunakan karena mampu menangani kebutuhan sistem yang bersifat dinamis dan melibatkan banyak pemangku kepentingan. Scrum menerapkan pengembangan secara iteratif dan inkremental melalui tahapan product backlog, sprint planning, sprint, sprint review, dan sprint retrospective, sehingga memungkinkan sistem dikembangkan secara bertahap sesuai kebutuhan pengguna (Nugraha & Hardian, 2021)
Penerapan Scrum pada sistem informasi sektor publik juga menunjukkan hasil yang efektif. Penelitian mengenai pengembangan Sistem Informasi Pendataan Bangunan (SIPBANG) pada instansi pemerintahan membuktikan bahwa Scrum mampu menghasilkan sistem yang sesuai dengan kebutuhan pengguna meskipun terdapat keterbatasan waktu dan kompleksitas proses bisnis. Evaluasi hasil sprint menunjukkan bahwa sistem yang dikembangkan dengan Scrum lebih adaptif dan mudah disesuaikan dengan kebutuhan organisasi (Rifky et al., 2022)
Selain itu, kajian metodologis yang mengombinasikan Scrum dengan model pengembangan lain menunjukkan bahwa Scrum memiliki keunggulan dalam fleksibilitas dan pengelolaan perubahan kebutuhan, khususnya pada pengembangan perangkat lunak berbasis website. Pendekatan Scrum dinilai efektif dalam meningkatkan kualitas produk perangkat lunak karena memungkinkan evaluasi dan perbaikan dilakukan secara berkelanjutan pada setiap iterasi pengembangan (Tumbade et al., 2024)
Pada tahap pengujian sistem, Black Box Testing merupakan teknik pengujian yang umum digunakan untuk memastikan fungsionalitas sistem berjalan sesuai dengan spesifikasi yang telah ditentukan. Pengujian ini berfokus pada kesesuaian antara input dan output sistem tanpa memperhatikan struktur internal kode program. Penelitian terdahulu menunjukkan bahwa Black Box Testing efektif digunakan untuk menguji kesiapan sistem sebelum digunakan oleh pengguna akhir, khususnya pada sistem berbasis web (Putra et al., 2020).



Berdasarkan hasil studi pustaka tersebut, dapat disimpulkan bahwa pengembangan sistem informasi manajemen sarana dan prasarana menggunakan metode Scrum serta pengujian Black Box Testing merupakan pendekatan yang relevan dan didukung oleh penelitian sebelumnya. Studi pustaka ini menjadi landasan teoritis dalam perancangan dan pengembangan Sistem Informasi Peminjaman Sarana dan Prasarana Kampus pada penelitian ini.
3.1.5 Tahapan Metode Penelitian Menggunakan Scrum
Metode penelitian yang digunakan dalam pengembangan Sistem Informasi Peminjaman Sarana dan Prasarana Kampus adalah Scrum, yang diterapkan secara iteratif dan inkremental. Tahapan Scrum dalam penelitian ini disusun berdasarkan diagram metodologi Scrum yang telah dirancang, sehingga setiap tahapan memiliki luaran yang jelas dan dapat dibuktikan pada tahap hasil penelitian (BAB IV).
Berdasarkan diagram metodologi Scrum yang digunakan dalam penelitian ini, proses penelitian dan pengembangan sistem dilakukan secara iteratif dan inkremental, dimulai dari tahap perencanaan produk hingga evaluasi berkelanjutan melalui beberapa siklus sprint.
 
Gambar 3.1 Alur Metode Scrum

3.1.5.1  Product Planning
Tahap awal dalam metode Scrum adalah Product Planning, yang bertujuan untuk mengidentifikasi dan mendefinisikan kebutuhan sistem secara menyeluruh. Pada tahap ini, kebutuhan sistem diperoleh dari Dokumen Spesifikasi Kebutuhan Perangkat Lunak (SKPL) yang disusun berdasarkan hasil observasi dan wawancara dengan staf Sarana dan Prasarana kampus.
Dalam Product Planning, Product Owner, yang diperankan oleh staf Sarpras, berperan dalam memvalidasi kebutuhan pengguna serta memastikan bahwa kebutuhan tersebut sesuai dengan proses bisnis peminjaman sarana dan prasarana kampus. Tahap ini menghasilkan pemahaman awal terhadap ruang lingkup sistem yang akan dikembangkan.
3.1.5.2 Product Backlog
Berdasarkan hasil Product Planning, selanjutnya disusun Product Backlog, yaitu daftar kebutuhan sistem yang telah diprioritaskan. Product Backlog disusun mengacu pada kebutuhan fungsional yang telah didefinisikan dalam dokumen SKPL dan Use Case Diagram.
Product Backlog pada penelitian ini mencakup fitur utama seperti kalender ketersediaan ruangan secara real-time, pencegahan bentrok jadwal (double booking), form peminjaman dan validasi kapasitas, unggah surat digital dan persetujuan admin, tampilan mobile untuk petugas keamanan, serta fitur laporan rekapitulasi peminjaman. Product Backlog ini menjadi dasar perencanaan pengembangan sistem pada setiap sprint.
3.1.5.3 Sprint Planning
Setelah Product Backlog disusun, dilakukan Sprint Planning untuk menentukan item Product Backlog yang akan dikerjakan dalam satu iterasi pengembangan. Sprint Planning dilakukan dengan mempertimbangkan prioritas kebutuhan pengguna dan kemampuan tim pengembang.
Hasil dari Sprint Planning adalah Sprint Backlog, yaitu daftar fitur terpilih yang akan dikembangkan oleh Scrum Team dalam satu sprint. Pada penelitian ini, durasi setiap sprint ditetapkan selama 1–2 minggu.
3.1.5.4 Sprint Execution
Tahap Sprint Execution merupakan tahap pelaksanaan pengembangan sistem oleh Scrum Team, yang dalam penelitian ini diperankan oleh mahasiswa/peneliti. Pada tahap ini, pengembangan sistem dilakukan secara bertahap yang meliputi analisis kebutuhan fitur, perancangan sistem, implementasi kode program, serta pengujian fungsional awal.


Selama Sprint Execution berlangsung, dilakukan Daily Scrum (stand-up meeting) untuk memantau progres pengembangan, mengidentifikasi kendala yang muncul, serta memastikan pekerjaan berjalan sesuai dengan rencana sprint yang telah ditetapkan.
3.1.5.5 Sprint Review and Delivery
Setelah Sprint Execution selesai, sistem yang telah dikembangkan menghasilkan Shippable Increment, yaitu modul sistem yang telah dapat dijalankan dan diuji. Increment ini kemudian dipresentasikan pada tahap Sprint Review, yang melibatkan pihak staf Sarpras dan petugas keamanan (Security).
Sprint Review bertujuan untuk memperoleh umpan balik pengguna serta melakukan validasi terhadap kesesuaian sistem dengan kebutuhan operasional di lapangan. Hasil Sprint Review menjadi dasar perbaikan atau penyesuaian fitur pada sprint berikutnya.
3.1.5.6 Sprint Retrospective
Tahap akhir dalam satu siklus sprint adalah Sprint Retrospective, yaitu evaluasi internal yang dilakukan oleh Scrum Team terhadap proses pengembangan yang telah berlangsung. Evaluasi ini bertujuan untuk mengidentifikasi kekurangan, hambatan, serta peluang perbaikan dalam proses pengembangan sistem.
Hasil Sprint Retrospective digunakan sebagai dasar perbaikan berkelanjutan (continuous improvement) pada sprint berikutnya, sehingga kualitas sistem dan proses pengembangan dapat terus ditingkatkan.
3.1.6 Teknik Pengujian
Pengujian sistem pada penelitian ini dilakukan untuk memastikan bahwa Sistem Informasi Peminjaman Sarana dan Prasarana Kampus yang dikembangkan telah berfungsi sesuai dengan kebutuhan pengguna yang telah didefinisikan pada tahap analisis kebutuhan. Pengujian sistem merupakan bagian penting dari proses pengembangan menggunakan metode Scrum, di mana setiap increment sistem yang dihasilkan pada akhir sprint harus memenuhi kriteria fungsional yang telah ditetapkan.
3.1.6.1 Metode Pengujian
Metode pengujian yang digunakan dalam penelitian ini adalah Black Box Testing. Black Box Testing merupakan metode pengujian perangkat lunak yang berfokus pada pengujian fungsionalitas sistem tanpa memperhatikan struktur internal atau kode program yang digunakan.
Pemilihan metode Black Box Testing didasarkan pada pertimbangan bahwa tujuan utama pengujian adalah untuk memastikan bahwa setiap fitur sistem dapat berjalan sesuai dengan kebutuhan pengguna, sebagaimana yang telah dirumuskan dalam dokumen spesifikasi kebutuhan perangkat lunak dan use case diagram.
3.1.6.2 Ruang Lingkup Pengujian
Ruang lingkup pengujian sistem mencakup seluruh fitur utama yang dikembangkan pada setiap sprint, khususnya fitur-fitur yang berkaitan langsung dengan proses peminjaman sarana dan prasarana kampus. Fitur yang diuji meliputi:
1.	Fitur login pengguna sesuai dengan hak akses masing-masing aktor.
2.	Fitur tampilan kalender ketersediaan ruangan secara real-time.
3.	Fitur pengajuan peminjaman ruangan dan sarana.
4.	Fitur validasi kapasitas ruangan dan pencegahan double booking.
5.	Fitur unggah surat digital dan proses verifikasi oleh admin.
6.	Fitur verifikasi kehadiran oleh petugas keamanan.
7.	Fitur notifikasi status pengajuan dan laporan rekapitulasi peminjaman.
Pengujian dilakukan untuk memastikan bahwa setiap fitur tersebut memberikan keluaran yang sesuai dengan hasil yang diharapkan.
3.1.6.3 Skenario dan Prosedur Pengujian
Pengujian sistem dilakukan dengan menyusun skenario pengujian berdasarkan fungsi-fungsi utama sistem. Setiap skenario pengujian terdiri dari beberapa komponen, yaitu kondisi awal, langkah pengujian, data masukan, hasil yang diharapkan, dan hasil pengujian aktual.
Prosedur pengujian dilakukan dengan cara menjalankan sistem sesuai dengan skenario yang telah ditentukan, kemudian membandingkan hasil aktual dengan hasil yang diharapkan. Apabila hasil pengujian sesuai dengan hasil yang diharapkan, maka fitur tersebut dinyatakan berhasil. Sebaliknya, apabila terjadi perbedaan, maka fitur tersebut akan diperbaiki dan diuji kembali pada sprint berikutnya.
3.1.6.4 Waktu dan Pelaksanaan Pengujian
Pengujian sistem dilakukan pada akhir setiap sprint, setelah tahap Sprint Execution selesai. Dengan demikian, setiap increment sistem yang dihasilkan telah melalui proses pengujian sebelum diserahkan pada tahap Sprint Review.
Pendekatan ini sejalan dengan prinsip Scrum yang menekankan pada pengujian dan evaluasi berkelanjutan, sehingga kesalahan atau kekurangan sistem dapat segera diidentifikasi dan diperbaiki pada sprint berikutnya.
3.1.6.5 Hasil Pengujian
Hasil pengujian sistem didokumentasikan dalam bentuk tabel pengujian Black Box Testing yang memuat informasi mengenai skenario pengujian, hasil yang diharapkan, hasil aktual, serta status keberhasilan pengujian. Dokumentasi hasil pengujian ini akan disajikan dan dibahas secara rinci pada BAB IV sebagai bukti bahwa sistem yang dikembangkan telah memenuhi kebutuhan fungsional yang ditetapkan.

3.2 Analisis Sistem
Analisis sistem dilakukan untuk mengidentifikasi kebutuhan dan karakteristik Sistem Informasi Peminjaman Sarana dan Prasarana Kampus yang dikembangkan. Analisis ini bertujuan untuk memahami proses bisnis yang berjalan, kebutuhan pengguna, serta fungsi-fungsi yang harus disediakan oleh sistem agar mampu mendukung pengelolaan peminjaman sarana dan prasarana kampus secara efektif, terstruktur, dan terkomputerisasi.
Dalam penelitian ini, teknik analisis data digunakan untuk mengolah dan menafsirkan data yang diperoleh selama proses pengembangan dan pengujian sistem. Analisis data bertujuan untuk menilai kesesuaian antara sistem yang dikembangkan dengan kebutuhan pengguna yang telah ditetapkan pada tahap analisis kebutuhan. Pendekatan analisis data yang digunakan adalah analisis kualitatif, karena data yang dianalisis berupa hasil observasi, wawancara, evaluasi sprint, serta hasil pengujian fungsional sistem.
3.2.1 Analisis Kebutuhan Sistem
Analisis kebutuhan sistem dilakukan dengan mengkaji hasil observasi dan wawancara yang telah dirangkum dalam Dokumen Spesifikasi Kebutuhan Perangkat Lunak (SKPL). Data kebutuhan dianalisis untuk mengidentifikasi permasalahan utama dalam proses peminjaman sarana dan prasarana kampus, seperti pencatatan peminjaman yang belum terintegrasi, kesulitan pemantauan status peminjaman, serta keterbatasan dokumentasi data peminjaman.
Hasil analisis kebutuhan ini digunakan sebagai dasar dalam penyusunan Product Backlog serta penentuan prioritas fitur pada setiap sprint pengembangan, sehingga sistem yang dikembangkan sesuai dengan kebutuhan pengguna dan proses bisnis yang berjalan.
3.2.2 Analisis Fungsional
Analisis fungsional bertujuan untuk mengidentifikasi fungsi utama yang harus dimiliki oleh Sistem Informasi Peminjaman Sarana dan Prasarana Kampus dalam mendukung proses peminjaman secara terkomputerisasi. Sistem menerapkan konsep CRUD (Create, Read, Update, Delete) untuk mengelola data peminjaman dan sarana secara terintegrasi.
Secara fungsional, sistem diawali dengan proses autentikasi pengguna untuk membatasi hak akses. Mahasiswa dapat mengajukan peminjaman sarana dan prasarana, sementara admin bertugas mengelola data sarana, memverifikasi, serta menyetujui atau menolak pengajuan peminjaman. Seluruh data peminjaman disimpan dalam basis data dan statusnya dapat dipantau oleh pengguna.





Berdasarkan analisis tersebut, kebutuhan fungsional sistem meliputi:
1.	Fitur notifikasi status pengajuan dan laporan rekapitulasi peminjaman.
2.	Autentikasi dan login pengguna berdasarkan hak akses.
3.	Pengajuan peminjaman sarana dan prasarana oleh mahasiswa.
4.	Penampilan informasi ketersediaan dan riwayat peminjaman.
5.	Persetujuan atau penolakan peminjaman oleh sarpras
6.	Pengelolaan data sarana dan prasarana menggunakan operasi CRUD.
7.	Penyediaan laporan data peminjaman.
Analisis kebutuhan fungsional ini menjadi dasar dalam tahap perancangan sistem yang dibahas pada subbab selanjutnya.
3.2.3 Analisis Non-Fungsional
Analisis non-fungsional dilakukan untuk mengidentifikasi kebutuhan pendukung yang memastikan Sistem Informasi Peminjaman Sarana dan Prasarana Kampus dapat berjalan secara optimal, aman, dan mudah digunakan. Kebutuhan non-fungsional ini tidak berkaitan langsung dengan fungsi utama sistem, tetapi berperan penting dalam menjamin kualitas layanan sistem secara keseluruhan.
Adapun kebutuhan non-fungsional sistem adalah sebagai berikut:
1.	Keamanan, sistem menerapkan mekanisme autentikasi pengguna untuk membatasi akses sesuai dengan hak akses masing-masing pengguna.
2.	Kinerja (performance), sistem mampu memproses data peminjaman dan menampilkan informasi secara responsif.
3.	Ketersediaan (availability), sistem dapat diakses melalui web browser kapan saja selama terhubung dengan jaringan internet.
4.	Usability, antarmuka sistem dirancang agar mudah dipahami dan digunakan oleh pengguna.
5.	Kompatibilitas, sistem dapat dijalankan pada berbagai perangkat dan peramban web.
Dengan adanya kebutuhan non-fungsional ini, sistem diharapkan mampu memberikan layanan peminjaman sarana dan prasarana kampus yang andal, aman, dan nyaman digunakan. Analisis kebutuhan non-fungsional ini selanjutnya menjadi dasar dalam tahap perancangan sistem.
3.2.4 Analisis Proses Pengembangan Sistem
Analisis proses pengembangan sistem dilakukan dengan mengevaluasi pelaksanaan setiap tahapan Scrum yang telah dijalankan. Data yang dianalisis meliputi hasil Sprint Planning, Sprint Execution, Sprint Review, dan Sprint Retrospective.
Analisis ini bertujuan untuk menilai efektivitas penerapan metode Scrum dalam pengembangan sistem, serta untuk mengidentifikasi kendala dan perbaikan yang dilakukan selama proses pengembangan berlangsung.
3.2.5 Analisis Hasil Pengujian Sistem
Analisis hasil pengujian sistem dilakukan dengan mengkaji hasil pengujian Black Box Testing terhadap fitur-fitur utama sistem. Data pengujian dianalisis dengan membandingkan hasil aktual sistem dengan hasil yang diharapkan pada setiap skenario pengujian.
Fitur yang memenuhi kriteria pengujian dinyatakan berfungsi dengan baik, sedangkan fitur yang belum memenuhi kriteria akan diperbaiki dan diuji kembali pada sprint berikutnya.
3.3 Perancangan
Perancangan sistem dilakukan sebagai tahap lanjutan dari hasil analisis kebutuhan fungsional dan non-fungsional yang telah dijelaskan sebelumnya. Tahap ini bertujuan untuk menerjemahkan kebutuhan sistem ke dalam bentuk rancangan teknis yang menggambarkan struktur, alur, dan komponen sistem yang akan dibangun.
Perancangan sistem pada Sistem Informasi Peminjaman Sarana dan Prasarana Kampus meliputi perancangan use case, aktor sistem, proses bisnis, struktur menu, basis data, serta logika proses sistem. Rancangan ini digunakan sebagai acuan dalam tahap implementasi dan pengujian sistem pada bab selanjutnya.
3.3.1 Usecase Diagram
 
Gambar 3.2 Usecase Diagram
Use Case Diagram pada Sistem Informasi Peminjaman Sarana dan Prasarana Kampus menggambarkan interaksi antara aktor dengan sistem berdasarkan hak akses dan peran masing-masing. Penjelasan Use Case Diagram disajikan dalam bentuk tabel aktor dan tabel use case sebagai berikut.

Tabel 3.1 Aktor Sistem
No.	Aktor	Deskripsi
1.	Mahasiswa	Pengguna sistem yang mengajukan peminjaman sarana dan prasarana kampus, melihat jadwal ruangan, serta mengunggah surat digital sebagai dokumen pendukung peminjaman.
2.	Sarpras	Pengelola sarana dan prasarana kampus yang bertugas mengelola data ruangan dan barang, melihat laporan peminjaman, serta melakukan verifikasi pengajuan peminjaman.
3.	Security	Petugas yang melakukan verifikasi kehadiran peminjam pada saat peminjaman berlangsung dan memicu pengiriman notifikasi otomatis.

Tabel 3.2 Usecase Sistem
No.	Usecase	Deskripsi
1.	Login	Proses autentikasi pengguna untuk dapat mengakses sistem sesuai dengan hak akses masing-masing.
2.	Mengajukan Peminjaman	Proses pengajuan peminjaman sarana dan prasarana kampus dengan mengisi data peminjaman.
3.	Upload Surat Digital	Proses unggah dokumen pendukung peminjaman sebagai kelengkapan pengajuan.
4.	Melihat Jadwal Ruangan	Proses melihat jadwal penggunaan ruangan untuk menghindari bentrok peminjaman.
5.	Mengelola Data Ruangan dan Barang	Proses pengelolaan data sarana dan prasarana kampus menggunakan operasi CRUD.
6.	Melihat Laporan Peminjaman	Proses melihat data dan rekap laporan peminjaman sarana dan prasarana kampus.
7.	Verifikasi Peminjaman	Proses verifikasi dan persetujuan atau penolakan pengajuan peminjaman yang diajukan mahasiswa.
8.	Verifikasi Kehadiran Peminjam	Proses pemeriksaan kehadiran peminjam pada saat penggunaan sarana dan prasarana.
9.	Mengirim Notifikasi Otomatis	Proses pengiriman notifikasi secara otomatis sebagai tindak lanjut dari verifikasi kehadiran atau peminjaman.






3.3.2 Flowchart Diagram
3.3.2.1 Flowchart Pengajuan Peminjaman
Flowchart Pengajuan peminjaman menggambarkan alur proses pengajuan peminjaman sarana dan prasarana kampus oleh mahasiswa, mulai dari login hingga pengajuan berhasil dikirim ke sistem. Proses ini bertujuan untuk memastikan bahwa pengajuan peminjaman dilakukan secara terstruktur, lengkap, dan sesuai dengan ketentuan yang berlaku.
 
Gambar 3.3 Flowchart Pengajuan Peminjaman

Proses peminjaman dimulai setelah mahasiswa berhasil login dan memilih menu Pinjam Ruangan. Mahasiswa dapat melihat daftar ruangan beserta jadwal ketersediaannya, kemudian mengajukan peminjaman dengan mengisi formulir yang memuat informasi kegiatan, waktu peminjaman, serta mengunggah surat pemberitahuan. Jika diperlukan, mahasiswa dapat menambahkan barang pendukung beserta jumlahnya. Sistem akan memeriksa kelengkapan data, dan apabila telah lengkap pengajuan dikirim dengan status menunggu verifikasi, disertai notifikasi bahwa pengajuan berhasil diajukan.
Dengan adanya flowchart peminjaman ini, alur proses pengajuan peminjaman sarana dan prasarana kampus oleh mahasiswa dapat dipahami secara jelas dan terstruktur. Flowchart ini menjadi acuan dalam implementasi fitur peminjaman serta membantu memastikan bahwa setiap pengajuan yang dikirimkan telah melalui proses validasi sebelum dilakukan verifikasi oleh pihak pengelola.
3.3.2.2 Flowchart Verifikasi Peminjaman
Flowchart verifikasi peminjaman menggambarkan alur proses pemeriksaan dan pengambilan keputusan terhadap pengajuan peminjaman sarana dan prasarana kampus yang dilakukan oleh Admin atau Sarpras. Proses ini bertujuan untuk memastikan bahwa pengajuan yang masuk telah memenuhi ketentuan administratif, jadwal penggunaan, serta kelengkapan dokumen pendukung sebelum peminjaman disetujui atau ditolak.
Proses verifikasi peminjaman dimulai ketika Admin atau pihak Sarana dan Prasarana (Sarpras) melakukan login ke dalam sistem informasi peminjaman. Setelah berhasil masuk, Admin diarahkan ke halaman dashboard admin yang menampilkan notifikasi pengajuan peminjaman baru dari mahasiswa sebagai penanda bahwa terdapat permohonan yang perlu ditindaklanjuti.
Selanjutnya, Admin membuka detail pengajuan peminjaman untuk melakukan pemeriksaan secara menyeluruh terhadap data yang diajukan oleh mahasiswa. Pada tahap ini, Admin mengecek kelengkapan dokumen pendukung, seperti surat pemberitahuan atau surat permohonan peminjaman, serta memverifikasi kesesuaian jadwal peminjaman dengan ketersediaan sarana dan prasarana yang diminta. Pemeriksaan ini bertujuan untuk memastikan bahwa pengajuan telah memenuhi ketentuan, prosedur, dan aturan peminjaman yang berlaku di lingkungan kampus.
Setelah seluruh data dan dokumen dinyatakan telah diperiksa, Admin kemudian mengambil keputusan terhadap pengajuan peminjaman tersebut. Apabila pengajuan tidak memenuhi persyaratan atau terjadi ketidaksesuaian jadwal maupun dokumen, Admin dapat menolak pengajuan dengan mengisi alasan penolakan secara jelas dan sistem akan secara otomatis mengubah status peminjaman menjadi rejected. Sebaliknya, apabila pengajuan dinyatakan sesuai dan memenuhi seluruh ketentuan, Admin menyetujui permohonan tersebut dan sistem akan mengubah status peminjaman menjadi approved.


 
Gambar 3.4 Flowchart Verifikasi Peminjaman
Pada tahap akhir, sistem secara otomatis mengirimkan notifikasi kepada mahasiswa mengenai hasil verifikasi peminjaman, baik berupa persetujuan maupun penolakan beserta alasannya. Dengan adanya flowchart verifikasi peminjaman ini, alur pemeriksaan, pengambilan keputusan, dan penyampaian informasi dapat dipahami secara jelas dan sistematis serta menjadi acuan dalam implementasi fitur verifikasi peminjaman agar pengelolaan sarana dan prasarana berjalan lebih efektif dan terstruktur.
3.3.2.3 Flowchart Verifikasi Kehadiran Peminjam
Flowchart verifikasi kehadiran peminjam menggambarkan proses pemeriksaan kehadiran peminjam sarana dan prasarana kampus yang dilakukan oleh petugas security. Proses ini bertujuan untuk memastikan bahwa peminjam yang datang ke lokasi benar-benar sesuai dengan data peminjaman yang telah disetujui sebelumnya oleh pihak Sarpras.
 
Gambar 3.5 Flowchart Verifikasi Kehadiran Peminjam

Proses verifikasi kehadiran dimulai ketika peminjam datang ke lokasi dan melapor kepada petugas security dengan menunjukkan bukti persetujuan peminjaman. Petugas kemudian membuka menu Jadwal Hari Ini untuk memeriksa data peminjaman yang terjadwal. Sistem menampilkan data peminjaman, lalu petugas melakukan pengecekan kesesuaian identitas peminjam. Jika data tidak sesuai, akses ditolak dan proses dihentikan. Jika sesuai, petugas memperbarui status kehadiran menjadi HADIR, membuka akses ruangan, dan sistem secara otomatis mencatat waktu masuk peminjam. Proses verifikasi kehadiran kemudian dinyatakan selesai.
Flowchart verifikasi kehadiran ini berfungsi sebagai acuan dalam pengawasan penggunaan sarana dan prasarana kampus, sehingga proses peminjaman dapat berlangsung secara tertib, aman, dan terkontrol.
3.3.3 Sequence Diagram
3.3.3.1 Sequence Diagram Pengajuan Peminjaman
Sequence diagram ini menggambarkan alur interaksi antara Mahasiswa, Web App, System, Database, dan Email Service dalam proses pengajuan peminjaman ruangan. Proses dimulai ketika mahasiswa melakukan login melalui Web App. Permintaan login divalidasi oleh System dengan melakukan pengecekan data ke Database. Jika data valid, sistem menampilkan dashboard kepada mahasiswa.
 
Gambar 3.6 Sequence Diagram Pengajuan Peminjaman

Selanjutnya, mahasiswa membuka menu jadwal ruangan. Web App meminta data jadwal kepada System, yang kemudian mengambil data ketersediaan ruangan dari Database dan menampilkannya kembali kepada mahasiswa melalui Web App.
Mahasiswa kemudian mengisi dan mengirimkan formulir pengajuan peminjaman. System memvalidasi data pengajuan. Jika data valid, sistem menyimpan data peminjaman ke Database dengan status PENDING dan mengirimkan notifikasi email konfirmasi melalui Email Service. Web App menampilkan pesan bahwa pengajuan berhasil dikirim. Jika data tidak valid, sistem menolak pengajuan dan Web App menampilkan pesan kesalahan kepada mahasiswa.
Sequence diagram ini menunjukkan alur komunikasi antar komponen sistem secara berurutan dalam mendukung proses pengajuan peminjaman ruangan.
3.3.3.2 Sequence Diagram Verifikasi Peminjaman
Sequence diagram ini menggambarkan alur interaksi antara aktor Admin dengan Web App, System, Database, dan Email Service dalam proses verifikasi pengajuan peminjaman. Proses diawali ketika admin melakukan login melalui Web App. System memvalidasi kredensial admin dengan melakukan pengecekan ke Database. Jika login berhasil, sistem memberikan akses dan menampilkan dashboard admin.
Admin kemudian membuka daftar pengajuan peminjaman. Web App meminta data pengajuan dengan status PENDING kepada System, yang selanjutnya mengambil data tersebut dari Database dan menampilkannya dalam bentuk tabel. Admin memilih salah satu pengajuan untuk melihat detail lengkap, dan System mengambil serta menampilkan detail pengajuan dari Database.
Pada tahap pengambilan keputusan, admin dapat menyetujui atau menolak pengajuan. Jika pengajuan disetujui, System memperbarui status peminjaman menjadi APPROVED di Database dan mengirimkan notifikasi persetujuan kepada mahasiswa melalui Email Service. Jika pengajuan ditolak, System memperbarui status menjadi REJECTED beserta alasan penolakan dan mengirimkan notifikasi penolakan kepada mahasiswa. Setelah proses selesai, Web App menampilkan konfirmasi kepada admin.
 
Gambar 3.7 Sequence Diagram Verifikasi Peminjaman
Sequence diagram ini menunjukkan alur komunikasi sistem dalam memastikan setiap pengajuan peminjaman diverifikasi secara terkontrol dan terdokumentasi dengan baik.
3.3.3.3 Sequence Diagram Verifikasi Kehadiran
Sequence diagram ini menggambarkan alur interaksi antara aktor Security dengan Web App, System, dan Database dalam proses verifikasi kehadiran peminjam. Proses dimulai ketika security melakukan login melalui Web App, yang kemudian divalidasi oleh System dengan melakukan pengecekan kredensial ke Database. Setelah login berhasil, sistem menampilkan dashboard security.
 
Gambar 3.8 Sequence Diagram Verifikasi Kehadiran
Ketika peminjam datang, security melakukan pengecekan identitas dan mencari data peminjaman pada jadwal yang tersedia melalui Web App. System memproses permintaan tersebut dan memeriksa kesesuaian data dengan Database. Jika data peminjaman ditemukan dan sesuai jadwal, security melakukan verifikasi kehadiran. System kemudian mencatat kehadiran dengan memperbarui status menjadi HADIR beserta waktu masuk pada Database, dan menampilkan konfirmasi bahwa verifikasi berhasil sehingga peminjam diizinkan masuk ke ruangan.
Sebaliknya, apabila data peminjaman tidak ditemukan atau tidak sesuai, sistem menolak proses verifikasi dan security tidak memberikan izin masuk ke ruangan. Sequence diagram ini menunjukkan alur komunikasi sistem dalam memastikan bahwa hanya peminjam yang sah yang dapat menggunakan sarana dan prasarana kampus.
3.3.4 Entity Relationship Diagram
 
Gambar 3.9 Entity Relationship Diagram
Entity Relationship Diagram (ERD) digunakan untuk menggambarkan struktur basis data serta hubungan antar entitas yang terlibat dalam Sistem Informasi Peminjaman Sarana dan Prasarana Kampus. ERD ini menunjukkan keterkaitan antara data pengguna, data sarana dan prasarana, transaksi peminjaman, serta proses pendukung seperti verifikasi kehadiran, notifikasi, dan pencatatan aktivitas. Perancangan ERD dilakukan untuk memastikan integritas data dan mendukung pengolahan data menggunakan pendekatan Relational Database Management System (RDBMS).
Tabel 3.3 Relasi Antar Entitas
No.	Entitas Utama	Entitas Terkait	Jenis Relasi	Keterangan
1.	users	organisasi	One-to-Many	Satu organisasi dapat memiliki banyak pengguna
2.	users	peminjaman	One-to-Many	Satu pengguna dapat mengajukan lebih dari satu peminjaman
3.	ruangan	peminjaman	One-to-Many	Satu ruangan dapat digunakan dalam beberapa transaksi peminjaman
4.	kegiatan	peminjaman	One-to-Many	Satu kegiatan dapat menjadi dasar beberapa peminjaman
5.	peminjaman	peminjaman_barang	One-to-Many	Satu peminjaman dapat memiliki lebih dari satu barang
6.	barang	peminjaman_barang	One-to-One	Satu barang dapat tercatat pada banyak transaksi peminjaman
7.	peminjaman	kehadiran_peminjam	One-to-Many	Setiap peminjaman memiliki satu data kehadiran
8.	users	mailbox	One-to-Many	Satu pengguna dapat menerima banyak notifikasi
9.	peminjaman	mailbox	One-to-Many	Satu peminjaman dapat menghasilkan banyak pesan
10.	users	log_aktivitas	One-to-Many	Aktivitas pengguna tercatat dalam log sistem
11.	peminjaman	log_aktivitas	One-to-Many	Aktivitas terkait peminjaman tercatat dalam log

Dengan perancangan ERD yang terstruktur dan relasi antar entitas yang jelas, Sistem Informasi Peminjaman Sarana dan Prasarana Kampus mampu mendukung pengelolaan data peminjaman secara terintegrasi dan konsisten. Struktur basis data ini menjadi acuan utama dalam implementasi sistem, khususnya dalam penerapan operasi CRUD serta pengelolaan data peminjaman, verifikasi, dan pelaporan pada tahap implementasi sistem.
3.3.5 Class Diagram
Class Diagram digunakan untuk menggambarkan struktur kelas dalam sistem beserta atribut, tipe data, serta hubungan antar kelas. Diagram ini merepresentasikan rancangan statis sistem yang menjadi dasar dalam proses implementasi, khususnya dalam pembuatan struktur database, model data, dan logika bisnis aplikasi.
Tabel 3.3 Deskripsi Nama Kelas
No.	Nama Kelas	Deskripsi
1.	Users	Merepresentasikan pengguna sistem dengan peran mahasiswa, sarpras, atau security
2.	Organisasi	Menyimpan data organisasi atau unit yang terkait dengan pengguna dan kegiatan
3.	Ruangan	Menyimpan data ruangan yang dapat dipinjam
4.	Barang	Menyimpan data barang atau inventaris yang dapat dipinjam
5.	Kegiatan	Menyimpan data kegiatan yang menjadi dasar peminjaman
6.	Peminjaman	Menyimpan data utama transaksi peminjaman sarana dan prasarana
7.	PeminjamanBarangDetail	Menyimpan detail barang yang dipinjam dalam satu transaksi
8.	KehadiranPeminjam	Menyimpan data verifikasi kehadiran peminjam
9.	Notifikasi	Menyimpan data notifikasi sistem kepada pengguna
10.	LogAktivitas	Menyimpan catatan aktivitas pengguna dalam sistem

 
Gambar 3.10 Class Diagram
Berdasarkan Class Diagram pada Gambar 3.4, sistem peminjaman sarana dan prasarana kampus terdiri dari beberapa kelas utama, yaitu User, Peminjaman, Barang, Ruangan, Kegiatan, Organisasi, serta kelas pendukung seperti PeminjamanBarangDetail, KehadiranPeminjam, Notifikasi, dan LogAktivitas.
Kelas Peminjaman berperan sebagai pusat relasi yang menghubungkan pengguna dengan sarana dan prasarana yang dipinjam, kegiatan yang dilaksanakan, serta proses verifikasi dan kehadiran. Untuk menjaga konsistensi status dan peran dalam sistem, digunakan beberapa enumeration seperti RoleEnum, PeminjamanStatusEnum, KehadiranStatusEnum, NotifikasiJenisEnum, dan NotifikasiStatusEnum.
Dengan adanya Class Diagram ini, struktur kelas dan hubungan antar komponen dalam Sistem Informasi Peminjaman Sarana dan Prasarana Kampus dapat dipahami secara jelas. Class Diagram ini menjadi acuan dalam proses implementasi sistem, khususnya dalam pembuatan model data, pengelolaan relasi antar entitas, serta penerapan logika bisnis sesuai dengan kebutuhan sistem.

3.3.6 BPNM Diagram
3.3.6.1 BPMN Proses Peminjaman
BPMN Proses Peminjaman menggambarkan alur peminjaman sarana dan prasarana kampus secara end-to-end yang melibatkan Mahasiswa, Sarpras, Security, dan Sistem Informasi. Proses dimulai dari login mahasiswa dan pengajuan peminjaman dengan melengkapi data serta unggah surat digital, kemudian sistem menyimpan pengajuan dan menetapkan status menunggu verifikasi.
Gambar 3.11 BPMN Proses Peminjaman
Selanjutnya, Sarpras melakukan review pengajuan untuk menentukan persetujuan atau penolakan, di mana pengajuan yang ditolak akan diakhiri oleh sistem dengan status DITOLAK, sedangkan pengajuan yang disetujui ditetapkan berstatus DISETUJUI dan diinformasikan kepada mahasiswa serta petugas keamanan. Pada hari pelaksanaan, Security melakukan verifikasi kehadiran peminjam; jika peminjam hadir, sistem memperbarui status peminjaman menjadi ONGOING yang menandakan kegiatan berlangsung, sedangkan jika peminjam tidak hadir, sistem mencatat kondisi tersebut dan proses peminjaman dinyatakan selesai.
3.3.6.2 BPMN Verifikasi Peminjaman
BPMN Verifikasi Peminjaman menggambarkan alur pemeriksaan dan pengambilan keputusan terhadap pengajuan peminjaman sarana dan prasarana oleh pihak Sarpras. Proses dimulai ketika pengajuan peminjaman masuk ke dalam sistem, kemudian Sarpras melakukan login dan mengakses dashboard untuk meninjau serta memeriksa kelengkapan dan kebenaran data pengajuan, seperti identitas peminjam, jenis sarana atau prasarana, jadwal penggunaan, dan dokumen pendukung.
Gambar 3.12 BPMN Verifikasi Peminjaman


Berdasarkan hasil verifikasi tersebut, Sarpras mengambil keputusan untuk menyetujui atau menolak pengajuan peminjaman. Pada kondisi pengajuan disetujui, Sarpras mengisi catatan persetujuan, kemudian sistem mengonfirmasi pengajuan dan secara otomatis mengirimkan notifikasi serta email persetujuan kepada mahasiswa. Sebaliknya, apabila pengajuan ditolak, Sarpras mengisi alasan penolakan yang dicatat oleh sistem, kemudian sistem mengonfirmasi penolakan dan mengirimkan notifikasi serta email penolakan kepada mahasiswa. Proses verifikasi peminjaman dinyatakan selesai setelah keputusan akhir disampaikan kepada pemohon dan tercatat dalam sistem.
3.3.6.3 BPMN Verifikasi Kehadiran
BPMN Verifikasi Kehadiran Peminjam menggambarkan proses pemeriksaan kehadiran peminjam sarana dan prasarana kampus yang dilakukan oleh petugas Security pada hari pelaksanaan peminjaman. Proses dimulai ketika Security melakukan login ke sistem dan mengakses dashboard untuk melakukan verifikasi kehadiran peminjam berdasarkan data peminjaman yang telah disetujui.
Gambar 3.13 BPMN Verifikasi Kehadiran
Selanjutnya, Security melakukan pemeriksaan apakah peminjam hadir sesuai dengan jadwal yang ditentukan, di mana pada kondisi peminjam hadir Security mengisi catatan kehadiran dan sistem mengonfirmasi hasil verifikasi dengan menetapkan status peminjaman menjadi ONGOING, sedangkan pada kondisi peminjam tidak hadir Security mengisi catatan ketidakhadiran dan sistem mengonfirmasi hasil verifikasi dengan menetapkan status peminjaman menjadi FINISHED. Proses verifikasi kehadiran ini berfungsi sebagai kontrol akhir untuk memastikan bahwa penggunaan sarana dan prasarana kampus berjalan sesuai dengan persetujuan dan ketentuan yang berlaku.






BAB 4 IMPLEMENTASI DAN PENGUJIAN
IMPLEMENTASI DAN PENGUJIAN

4.1 Lingkungan Implementasi Sistem
4.1.1 Perangkat Keras
Perangkat keras yang digunakan dalam implementasi sistem memiliki spesifikasi sebagai berikut:
•	Laptop			: Lenovo LOQ 15 IRX9
•	Prosesor			: Intel Core i5-13450HX
•	Kartu Grafis			: NVIDIA GeForce RTX 3050 6GB GDDR6
•	Memori			: 20 GB DDR5 4800 MHz
•	Penyimpanan Utama		: NVMe SSD 512 GB PCIe Gen 4.0 x4
Spesifikasi perangkat keras tersebut dinilai telah memadai untuk menjalankan aplikasi backend, basis data, serta proses pengembangan dan pengujian sistem secara bersamaan tanpa mengalami kendala performa yang signifikan.
4.1.2 Perangkat Lunak
Perangkat lunak yang digunakan dalam implementasi sistem meliputi sistem operasi, bahasa pemrograman, basis data, serta berbagai tools pendukung pengembangan sebagai berikut:
•	Sistem Operasi
o	Windows 11 sebagai sistem operasi utama pengembangan
•	Backend
o	Bahasa pemrograman Go versi 1.25.3
o	PostgreSQL sebagai sistem manajemen basis data relasional
o	Supabase sebagai platform hosting database dan penyimpanan file
o	Air sebagai development tool untuk hot reload selama pengembangan
•	Frontend
o	HTML5 untuk struktur halaman web
o	CSS3 untuk pengaturan tampilan dan tata letak
o	JavaScript (Vanilla) untuk logika interaksi pengguna
•	Library dan Dependency Backend
o	github.com/golang-jwt/jwt/v5 untuk implementasi autentikasi berbasis JSON Web Token
o	github.com/jackc/pgx/v5 sebagai driver PostgreSQL
o	golang.org/x/crypto/bcrypt untuk enkripsi kata sandi
o	github.com/joho/godotenv untuk manajemen environment variables
o	github.com/xuri/excelize/v2 untuk fitur ekspor laporan ke format Excel
Pemilihan perangkat lunak tersebut didasarkan pada pertimbangan performa, keamanan, kemudahan pengembangan, serta dukungan komunitas yang baik, sehingga mendukung implementasi sistem secara efektif dan berkelanjutan.
4.2 Implementasi Desain Tampilan
4.2.1 Halaman Utama (Guest)
Halaman Utama (Guest) merupakan halaman publik yang dapat diakses oleh pengguna tanpa melakukan login ke dalam sistem. Halaman ini berfungsi sebagai pusat informasi awal yang menampilkan ketersediaan sarana dan prasarana kampus secara umum, sehingga pengguna dapat memperoleh gambaran kondisi fasilitas sebelum mengajukan peminjaman.
 
Gambar 4.1 Halaman Utama
Pada halaman ini ditampilkan informasi berupa kalender aktivitas, jadwal peminjaman harian, daftar ruangan, serta inventaris barang yang tersedia. Seluruh informasi disajikan secara ringkas dan mudah dipahami untuk mendukung transparansi data peminjaman. Dengan adanya Halaman Utama ini, pengguna dapat memantau jadwal penggunaan fasilitas kampus secara efektif dan memperoleh informasi awal tanpa harus masuk ke dalam sistem.
4.2.2 Halaman Login
Halaman Login digunakan sebagai gerbang autentikasi bagi pengguna untuk dapat mengakses sistem sesuai dengan hak akses yang dimiliki. Pada halaman ini, pengguna diminta untuk memasukkan email dan kata sandi yang telah terdaftar sebagai proses verifikasi identitas sebelum masuk ke dalam sistem.

 
Gambar 4.2 Halaman Login
Sistem akan melakukan validasi terhadap data yang dimasukkan oleh pengguna. Apabila data yang diberikan valid, pengguna akan diarahkan ke dashboard sesuai dengan peran masing-masing, seperti mahasiswa, admin Sarpras, atau petugas security. Sebaliknya, jika data tidak valid, sistem akan menampilkan pesan kesalahan sebagai informasi kepada pengguna. Halaman Login dirancang dengan tampilan sederhana dan responsif guna memberikan kemudahan serta kenyamanan dalam proses autentikasi pengguna.
4.2.3 Halaman Register
Halaman Register digunakan oleh pengguna baru untuk melakukan pendaftaran akun sebelum dapat mengakses sistem. Pada halaman ini, pengguna diminta untuk mengisi data diri secara lengkap, seperti nama, email, kata sandi, identitas mahasiswa, serta informasi organisasi yang terkait dengan pengajuan peminjaman.
 
Gambar 4.3 Halaman Register

Sistem melakukan validasi terhadap data yang dimasukkan untuk memastikan keakuratan dan kelengkapan informasi. Setelah proses pendaftaran berhasil, data pengguna akan disimpan ke dalam sistem dan akun dapat digunakan untuk melakukan login. Halaman Register dirancang agar mudah dipahami dan digunakan, sehingga proses pembuatan akun dapat dilakukan secara efektif dan efisien oleh pengguna.
4.2.4 Dashboard Mahasiswa
Dashboard Mahasiswa merupakan halaman utama yang diakses oleh mahasiswa setelah berhasil melakukan login ke dalam sistem. Halaman ini berfungsi sebagai pusat informasi dan aktivitas mahasiswa dalam proses peminjaman sarana dan prasarana kampus.
 
Gambar 4.4 Dashboard Mahasiswa

Pada dashboard ini ditampilkan ringkasan informasi peminjaman, kalender jadwal penggunaan fasilitas, serta agenda harian yang berkaitan dengan peminjaman yang diajukan. Selain itu, mahasiswa dapat mengakses fitur utama seperti pengajuan peminjaman, melihat status dan riwayat peminjaman, serta memantau jadwal penggunaan sarana dan prasarana. Dashboard Mahasiswa dirancang untuk memudahkan pengguna dalam memantau dan mengelola aktivitas peminjaman secara terstruktur dan efisien.
4.2.5 Form Pengajuan Peminjaman
Form Pengajuan Peminjaman digunakan oleh mahasiswa untuk mengajukan peminjaman sarana dan prasarana kampus melalui sistem. Pada halaman ini, mahasiswa mengisi data pengajuan yang meliputi informasi kegiatan, pilihan ruangan dan/atau barang yang akan dipinjam, jadwal penggunaan, serta dokumen pendukung peminjaman.
 
Gambar 4.5 Form Pengajuan
Sistem akan melakukan validasi terhadap data yang dimasukkan sebelum pengajuan diproses. Setelah pengajuan dikirim, data akan disimpan dalam sistem dan menunggu proses verifikasi oleh pihak Sarpras. Form ini dirancang secara terstruktur dan mudah digunakan untuk membantu mahasiswa dalam menyampaikan pengajuan peminjaman secara jelas dan terdokumentasi dengan baik.

4.2.6 Dashboard Sarpras
Dashboard Sarpras merupakan halaman utama yang digunakan oleh pihak Sarana dan Prasarana untuk mengelola dan memantau seluruh proses peminjaman dalam sistem. Halaman ini menampilkan ringkasan informasi pengajuan peminjaman, khususnya pengajuan yang masih menunggu proses verifikasi.
 
Gambar 4.6 Dashboard Sarpras
Melalui Dashboard Sarpras, admin dapat mengakses fitur manajemen data sarana dan prasarana, melakukan verifikasi pengajuan peminjaman, serta memantau jadwal penggunaan fasilitas kampus. Dashboard ini dirancang untuk membantu pihak Sarpras dalam menjalankan tugas pengelolaan peminjaman secara terpusat, efisien, dan terkontrol.

4.2.7 Form Verifikasi Peminjaman
Form Verifikasi Peminjaman digunakan oleh pihak Sarpras untuk melakukan pemeriksaan dan pengambilan keputusan terhadap pengajuan peminjaman yang diajukan oleh mahasiswa. Pada halaman ini, Sarpras dapat melihat daftar pengajuan yang menunggu verifikasi beserta detail informasi peminjaman yang diajukan.
 
Gambar 4.7 Form Verifikasi Peminjaman
Berdasarkan hasil pemeriksaan data dan dokumen pendukung, Sarpras dapat memberikan keputusan berupa persetujuan atau penolakan pengajuan peminjaman. Setiap keputusan yang diambil akan dicatat oleh sistem dan disampaikan kepada mahasiswa melalui notifikasi sebagai informasi hasil verifikasi. Form ini dirancang untuk mendukung proses verifikasi peminjaman secara sistematis, transparan, dan terdokumentasi.
4.2.8 Halaman Laporan Peminjaman
Halaman Laporan Peminjaman digunakan oleh pihak Sarpras untuk melihat rekapitulasi data peminjaman sarana dan prasarana yang tersimpan dalam sistem. Halaman ini menyajikan informasi peminjaman secara terstruktur sehingga memudahkan proses pemantauan dan evaluasi.
 
Gambar 4.8 Halaman Laporan Peminjaman
Pada halaman ini, pengguna dapat melakukan penyaringan data berdasarkan periode waktu dan status peminjaman. Data laporan dapat digunakan sebagai bahan dokumentasi dan pendukung dalam penyusunan laporan administrasi. Halaman Laporan Peminjaman dirancang untuk membantu pihak Sarpras dalam memperoleh informasi peminjaman secara akurat dan sistematis.
4.2.9 Dashboard Security
Dashboard Security merupakan halaman utama yang digunakan oleh petugas keamanan untuk memantau dan memverifikasi kehadiran peminjam sarana dan prasarana kampus. Halaman ini menampilkan daftar jadwal peminjaman yang berlangsung pada hari berjalan beserta status verifikasi kehadiran peminjam.
 
Gambar 4.9 Dashboard Security
Melalui Dashboard Security, petugas dapat melakukan pengecekan kehadiran peminjam berdasarkan jadwal yang telah disetujui serta mencatat hasil verifikasi ke dalam sistem. Dashboard ini dirancang untuk mendukung proses pengawasan penggunaan fasilitas kampus agar sesuai dengan jadwal dan ketentuan yang telah ditetapkan.


4.2.10 Form Verifikasi Kehadiran
Form Verifikasi Kehadiran digunakan oleh petugas security untuk mencatat dan memverifikasi kehadiran peminjam pada saat penggunaan sarana dan prasarana kampus. Pada halaman ini, petugas dapat melihat detail jadwal peminjaman yang sedang berlangsung serta melakukan konfirmasi kehadiran peminjam sesuai dengan data yang tercatat dalam sistem.
 
Gambar 4.10 Form Verifikasi Kehadiran
Hasil verifikasi kehadiran akan disimpan dan terdokumentasi sebagai bagian dari riwayat peminjaman. Form ini dirancang untuk memastikan penggunaan sarana dan prasarana sesuai dengan jadwal yang telah disetujui serta mendukung pengawasan dan pengendalian fasilitas kampus secara tertib dan terstruktur.
4.3 Pengujian
4.3.1 Pengujian Black Box
Pengujian Black Box dilakukan dengan memvalidasi input dan output sistem tanpa melihat struktur internal kode. Pengujian mencakup modul autentikasi, master data, peminjaman, kehadiran, notifikasi, RBAC, serta pengujian antarmuka pengguna (UI). Berdasarkan hasil pengujian, seluruh skenario uji berhasil dijalankan dengan status PASS.
No.	Modul/Fitur	Skenario Uji	Hasil Yang Diharapkan	Hasil Uji
1.	Login	Input email & password valid	Masuk dashboard sesuai role	Passed
2.	Login	Input password salah	Pesan error muncul	Passed
3.	Register	Data valid	Akun berhasil dibuat	Passed
4.	Pengajuan Peminjaman	Data lengkap	Status PENDING	Passed
5.	Verifikasi Peminjaman	Approve data	Status APPROVED	Passed
6.	Pembatalan Peminjaman	Klik batal	Status CANCELED	Passed
7.	Kehadiran	Input kehadiran	Data tersimpan	Passed
8.	Role-Based Access Control	Akses tanpa hak	Akses ditolak	Passed
9.	Notifikasi	Aksi peminjaman	Notifikasi muncul	Passed
10.	Logout	Klik logout	Kembali ke halaman login	Passed
Tabel 4.1 Pengujian Aplikasi
Berdasarkan tabel di atas, dapat disimpulkan bahwa seluruh fungsi sistem telah berjalan sesuai dengan spesifikasi dan tidak ditemukan kegagalan pada proses pengujian fungsional.
4.3.2 Pengujian Code Coverage
Pengujian Code Coverage dilakukan pada sisi backend untuk mengetahui persentase baris kode yang telah dieksekusi selama proses pengujian unit. Hasil pengujian menunjukkan bahwa beberapa modul inti telah diuji dengan tingkat keterujian yang baik, khususnya pada layanan autentikasi dan peminjaman.
No.	Nama Unit	Persentase
1.	auth_service.go	83.3%
2.	code_generator.go	100%
3.	kehadiran_service.go	83.3%
4.	peminjaman_service.go	34.7%
5.	export_service.go	0.0%
	Total Coverage	31.9%
Tabel 4.2 Hasil Code Coverage
Hasil visual pengujian Code Coverage disajikan dalam bentuk laporan HTML dan dilampirkan pada bagian Lampiran Code Coverage sebagai bukti pendukung
4.4 Repository GitHub Project
Repository GitHub digunakan sebagai media penyimpanan dan pengelolaan source code dalam pengembangan Sistem Informasi Peminjaman Sarana dan Prasarana Kampus. Repository ini mendukung pengendalian versi dan dokumentasi selama proses pengembangan. Struktur repository dipisahkan antara backend dan frontend untuk memudahkan pengelolaan kode. Repository proyek dapat diakses melalui:
•	https://github.com/ditverse/proyek-2-backend
•	https://github.com/ditverse/proyek-2-frontend
Penggunaan GitHub membantu memastikan proses pengembangan sistem berjalan secara terstruktur dan terdokumentasi dengan baik.
 
BAB 5 KESIMPULAN DAN SARAN
KESIMPULAN DAN SARAN

5.1 Kesimpulan
Berdasarkan hasil pengembangan Sistem Informasi Peminjaman Sarana dan Prasarana Kampus Berbasis Web Menggunakan CRUD RDBMS, dapat disimpulkan bahwa:
1.	Sistem berhasil mendukung proses pengelolaan peminjaman dan inventaris sarana dan prasarana kampus secara terkomputerisasi dan terintegrasi.
2.	Penerapan konsep CRUD dan RDBMS memungkinkan pengelolaan data inventaris, pengguna, dan transaksi peminjaman dilakukan secara terstruktur dan terdokumentasi dengan baik.
3.	Metode Scrum efektif digunakan dalam pengembangan sistem karena mendukung proses iteratif, evaluasi berkala, dan penyesuaian kebutuhan pengguna.
4.	Sistem menyediakan fitur utama meliputi pengelolaan inventaris, pengajuan peminjaman, verifikasi peminjaman, verifikasi kehadiran, serta laporan peminjaman.
5.	Hasil Black Box Testing menunjukkan seluruh fungsi utama sistem berjalan sesuai kebutuhan, dan pengujian code coverage membuktikan modul inti sistem telah diuji dan berfungsi dengan baik.
5.2 Saran
Adapun saran untuk pengembangan sistem selanjutnya adalah sebagai berikut:
1.	Menambahkan fitur monitoring kondisi dan riwayat penggunaan inventaris untuk mendukung manajemen aset kampus.
2.	Meningkatkan cakupan unit testing agar persentase code coverage dapat lebih optimal pada seluruh modul sistem.
3.	Memperkuat aspek keamanan dan audit log untuk meningkatkan keandalan dan pelacakan perubahan data sistem.






DAFTAR PUSTAKA

Herlambang, A. D., Rachmadi, A., Rahmatika, A. P., Utami, D. I. D., & Hapsari, S. W. (2020). V-model untuk pengembangan sistem informasi manajemen ruang rapat. Jurnal Teknologi Informasi dan Ilmu Komputer (JTIIK), 7(2), 313–322. https://doi.org/10.25126/jtiik.2020721893
Nabella, P., Herteno, R., Saputro, S. W., Abadi, F., & Mazdadi, M. I. (2025). Pengembangan sistem manajemen sarana dan prasarana, IT, serta laboratorium di SMK Telekomunikasi. Jurnal Teknologi Informasi dan Ilmu Komputer (JTIIK), 12(1), 1–10. https://doi.org/10.25126/jtiik.2025128649
Nugraha, T. S., & Hardian, R. (2021). Rancang bangun sistem informasi company profile dengan menggunakan metode Scrum pada PT Hasna Satya, 03(02).
Purwati, N., Pratama, M. W., & Rapiyanta, P. T. (2022). Sistem informasi peminjaman peralatan jaringan dan multimedia berbasis website di Biro Sistem Informasi UMY. INFOMATEK: Jurnal Informatika, Manajemen dan Teknologi, 24(2), 119–124. https://doi.org/10.23969/infomatek.v24i2.6019
Putra, W., Sukerti, N. K., & Hadi, R. (2020). Penerapan helpdesk system dengan pengujian blackbox testing, 2(02).
Rifky, M., Mursityo, Y. T., & Prakoso, B. S. (2022). Pengembangan aplikasi sistem informasi pendataan bangunan (SIPBANG) pada Dinas Pekerjaan Umum dan Penataan Ruang Kota Malang menggunakan framework Scrum. Jurnal Teknologi Informasi dan Ilmu Komputer (JTIIK), 9(1), 69–78. https://doi.org/10.25126/jtiik.202293877
Rukmana, A. Y., Rahman, R., Afriyadi, H., Moeis, D., Setiawan, Z., Subchan, N., & Kusuma, A. T. A. P. (2023). Pengantar sistem informasi: Panduan praktis pengenalan sistem informasi & penerapannya. PT Sonpedia Publishing Indonesia.
Sanjaya, R., & Hesinto, S. (2017). Rancang bangun website profil Hotel Agung Prabumulih menggunakan framework Bootstrap. Jurnal Teknologi dan Informasi, 7(2), 57–64. https://doi.org/10.34010/jati.v7i2.758
Setyawati, E., Wijoyo, H., & Soeharmoko, N. (2020). Relational database management system (RDBMS). https://doi.org/10.31237/osf.io/wuk6q
Tumbade, M. O., Hartomo, K. D., & Purnomo, H. D. (2024). Pengembangan perangkat lunak berbasis website menggunakan kombinasi metode Scrum dan V-Model (Hybrid Scrum and V-Model). Jurnal Teknologi Informasi dan Ilmu Komputer (JTIIK), 11(3), 447–460. https://doi.org/10.25126/jtiik.938456
Zmaranda, D., Pop-Fele, L. L., Gyorödi, C., Gyorödi, R., & Pecherle, G. (2020). Performance comparison of CRUD methods using .NET object relational mappers: A case study. International Journal of Advanced Computer Science and Applications, 11(1). https://doi.org/10.1177/2515245920917961

 
LAMPIRAN

 
 
 
 
 
  
GLOSARIUM

Teknis
1.	Sistem Informasi: Kumpulan komponen yang saling terintegrasi untuk mengolah data menjadi informasi guna mendukung proses operasional dan pengambilan keputusan.
2.	CRUD (Create, Read, Update, Delete): Operasi dasar dalam pengelolaan data yang meliputi pembuatan, pembacaan, pembaruan, dan penghapusan data.
3.	Database: Media penyimpanan data yang terstruktur dan terorganisir agar mudah diakses, dikelola, dan diperbarui.
4.	RDBMS (Relational Database Management System): Sistem manajemen basis data yang menyimpan data dalam bentuk tabel yang saling berelasi.
5.	Backend: Bagian sistem yang menangani logika bisnis, pemrosesan data, dan interaksi dengan database.
6.	Frontend: Bagian sistem yang berinteraksi langsung dengan pengguna melalui antarmuka visual.
7.	API (Application Programming Interface): Antarmuka yang memungkinkan komunikasi dan pertukaran data antar sistem atau aplikasi.
8.	Authentication: Proses verifikasi identitas pengguna sebelum diberikan akses ke dalam sistem.
9.	Authorization: Proses penentuan hak akses pengguna terhadap fitur atau data tertentu dalam sistem.
10.	UML (Unified Modeling Language): Bahasa pemodelan standar yang digunakan untuk menggambarkan struktur dan perilaku sistem perangkat lunak.
11.	Use Case Diagram: Diagram UML yang menggambarkan interaksi antara aktor dan sistem.
12.	Sequence Diagram: Diagram UML yang menunjukkan urutan interaksi antar objek dalam sistem berdasarkan waktu.
13.	Code Coverage: Persentase bagian kode program yang telah dijalankan dan diuji melalui proses pengujian perangkat lunak.
14.	Black Box Testing: Metode pengujian perangkat lunak yang berfokus pada input dan output tanpa memperhatikan struktur internal kode.
15.	Scrum: Metodologi pengembangan perangkat lunak berbasis Agile yang dilakukan secara iteratif melalui sprint.
Non-Teknis
1.	Mahasiswa: Pengguna sistem yang memiliki hak untuk mengajukan peminjaman sarana dan prasarana kampus.
2.	Admin: Pengguna sistem yang bertugas mengelola data, memverifikasi pengajuan, dan memantau operasional sistem.
3.	Security: Petugas yang bertanggung jawab melakukan verifikasi kehadiran dan pengawasan penggunaan sarana dan prasarana.
4.	Sarana dan Prasarana: Fasilitas fisik kampus yang dapat digunakan untuk menunjang kegiatan akademik maupun non-akademik.
5.	Peminjaman: Proses pengajuan penggunaan sarana dan prasarana kampus oleh mahasiswa melalui sistem.
6.	Inventaris: Daftar aset atau fasilitas kampus yang tercatat dan dikelola secara sistematis.
7.	Verifikasi: Proses pemeriksaan dan validasi data atau pengajuan yang dilakukan oleh pihak berwenang.
8.	Laporan: Rekapitulasi data peminjaman yang digunakan sebagai dokumentasi dan bahan evaluasi.
9.	Dashboard: Halaman utama sistem yang menampilkan ringkasan informasi dan status data secara visual.
10.	Hak Akses: Batasan wewenang pengguna dalam menggunakan fitur tertentu pada sistem.
# PENGERTIAN
Dalam komputasi,*data as a service (DaaS)*, adalah sepupu dari *software as a service (SaaS)*. Seperti semua anggota keluarga "*as a service*" (aaS), DaaS dibangun dengan konsep produk (dalam hal ini adalah data) dapat di sesuaikan dengan permintaan pengguna, terlepas dari pemisahan geografis atau organisasi dari penyedia dan konsumen. Selain itu, kemunculan  *service-oriented architecture (SOA)* dan meluasnya penggunaan *application programming interface (API)* juga menjadikan platform aktual tempat data menjadi tidak relevan. Perkembangan ini telah memungkinkan munculnya konsep DaaS yang relatif baru.

Data yang disediakan sebagai layanan dimulai dengan mashup Web, tetapi pada 2015 semakin banyak digunakan baik secara komersial dan organisasi yang kurang umum seperti PBB.

Secara tradisional, sebagian besar organisasi telah menggunakan data yang disimpan dalam repositori mandiri, yang perangkat lunaknya dikembangkan secara khusus untuk mengakses dan menyajikan data dalam bentuk yang dapat dibaca manusia. Salah satu hasil dari paradigma ini adalah bundling data dan perangkat lunak yang diperlukan untuk menafsirkannya menjadi satu paket, dijual sebagai produk konsumen. Karena jumlah paket perangkat lunak / data yang digabungkan semakin banyak dan diperlukan interaksi antara satu sama lain, maka diperlukan lapisan antarmuka lain. Antarmuka ini, secara kolektif dikenal sebagai  *enterprise application integration (EAI)*, sering cenderung mendorong vendor lock-in , karena umumnya mudah untuk mengintegrasikan aplikasi yang dibangun dengan teknologi yang sama.

Hasil dari paket perangkat lunak / gabungan data konsumen dan middleware EAI yang dibutuhkan telah meningkatkan jumlah perangkat lunak untuk dikelola dan dikelola organisasi, hanya untuk penggunaan data tertentu. Selain biaya perawatan rutin, sejumlah pembaruan perangkat lunak diperlukan karena format data berubah. Keberadaan situasi ini berkontribusi pada daya tarik DaaS kepada data konsumen, karena memungkinkan pemisahan biaya data dan penggunaan data dari biaya lingkungan atau platform perangkat lunak tertentu. *Sensing as a Service (S 2 aaS)* juga memiliki visi yang sama. S 2 aaS disajikan sebagai model bisnis yang bertujuan untuk menggunakan data Internet of Things untuk membuat pasar perdagangan data.

Baru-baru ini, solusi *Data as a Service* yang ditawarkan oleh vendor terkemuka (MuleSoft, Oracle, Microsoft) membantu organisasi lebih cepat menggunakan volume data yang besar, mengintegrasikan data itu, menganalisis data, dan menerbitkan data kepada pengguna bisnis secara real-time menggunakan layanan Web API yang mematuhi batasan arsitektur REST (juga dikenal sebagai RESTful API )

# MANFAAT
*Data as a service* membawa gagasan bahwa kualitas data dapat terjadi di tempat yang terpusat, membersihkan dan memperkaya data dan menawarkannya ke sistem, aplikasi atau pengguna yang berbeda, terlepas dari di mana mereka berada di organisasi atau di jaringan. Dengan demikian, solusi *Data as a service* memberikan keuntungan berikut:

**Agility**- Pelanggan dapat bergerak cepat karena kesederhanaan akses data dan fakta bahwa mereka tidak memerlukan pengetahuan luas tentang data yang mendasarinya. Jika pelanggan memerlukan struktur data yang sedikit berbeda atau memiliki persyaratan lokasi khusus , penerapannya mudah karena perubahannya minimal.

**Efektivitas biaya** - Penyedia dapat membangun basis dengan para ahli data dan mengalihdayakan lapisan presentasi, yang membuat interface pengguna sangat hemat biaya dan membuat permintaan perubahan pada lapisan presentasi jauh lebih layak.

**Kualitas data** - Akses ke data dikendalikan melalui layanan data, yang cenderung meningkatkan kualitas data, karena ada satu titik untuk pembaruan. Setelah layanan tersebut diuji secara menyeluruh, mereka hanya perlu diuji regresi, jika tetap tidak berubah untuk penyebaran berikutnya.

# MODEL HARGA
Ada ratusan vendor DaaS di Web, dan model penetapan harga dimana mereka menagih pelanggan mereka dalam dua kategori utama.

Model berbasis volume yang memiliki dua pendekatan:

**Harga berdasarkan kuantitas**: Ini adalah model paling sederhana untuk diterapkan. Vendor menagih pelanggan mereka berdasarkan jumlah data yang ingin mereka gunakan. Langganan untuk jumlah data yang tidak terbatas disebut sebagai pendekatan fire-hose.

**Bayar per panggilan**: Dalam pendekatan ini, vendor mengenakan biaya untuk setiap panggilan dari pelanggan ke API.

**Model berbasis tipe data**: Dalam model ini, vendor mengenakan biaya berdasarkan pada tipe atau atribut data yang dibutuhkan pelanggan. Misalnya, data geografis, keuangan, dan historis yang diperlukan untuk bisnis pelanggan adalah contoh tipe data yang menjadi dasar penetapan harga. Beberapa vendor seperti Microsoft Azure menyimpan data dalam tiga jenis berbeda (gumpalan, antrian, dan tabel).
Beberapa vendor DaaS memiliki batasan berlangganan, seperti ruang dan waktu minimum atau maksimum (bulanan atau tahunan).

# KELEMAHAN
Kelemahan data sebagai layanan pada umumnya mirip dengan yang terkait dengan semua jenis komputasi awan , seperti ketergantungan pelanggan pada kemampuan penyedia layanan untuk menghindari downtime server. Khusus untuk model DaaS, kelemahan yang umum adalah bahwa bila dibandingkan dengan pengiriman data tradisional, konsumen benar-benar hanya "menyewa" data, menggunakannya untuk menghasilkan grafik, bagan atau peta, atau mungkin melakukan analisis, tetapi untuk data sebagai layanan, umumnya data tidak tersedia untuk diunduh.

"*Service automation units*" (kode yang mengekspresikan layanan interface) dapat berisi metode untuk semua operasi " CRUD " (buat, baca, perbarui, hapus), seperti dalam operasi data tradisional, tetapi data sebagai layanan umumnya terbatas untuk dibaca.

SUMBER : [WIKIPEDIA.ORG](https://en.wikipedia.org/wiki/Data_as_a_service)
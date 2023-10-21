# 2022a-kelompok6

Software Requirements
Specification

for

OnBook Website

Version 1.0 approved

Disusun Oleh :

1. Muhammad Ainur Rofik (22091397005)
2. Farida Muthi’ah Fathin (22091397007)
3. Yunike Shandy Jholan Ninggar (22091397008)

D4 Manajemen Informatika 2022 A Fakultas Vokasi Universitas Negeri Surabaya

Tahun 2023


**1. Introduction**

 Pada era revolusi industri 5.0 ini banyak teknologi yang berkembang di berbagai daerah, terutama perkembangan pada design dan website. Contoh perkembangan teknologi pada bidang desain sendiri yaitu seperti adanya aplikasi-aplikasi mengenai colour pallet dan ada juga aplikasi yang menyediakan objek gambar untuk akses pengeditan dan masih banyak lagi. Kemudian pada website sendiri banyak dipakai oleh orang untuk mempermudah mereka untuk pencarian sesuatu lebih cepat. Banyak fungsi website yang dikembangkan pada era ini, seperti model tampilan yang dipercantik, banyak fitur baru yang ditambahkan, kemudian juga mempermudah user dalam mengakses website tersebut. Di sini kami membuat website dengan nama OnBook. Tujuan kami membuat website ini yaitu untuk membantu user agar lebih mudah dalam mencari toko penjual buku yang dicari oleh user itu sendiri, selain itu juga untuk memberikan gambaran kepada user tentang buku yang ingin dibeli.
 Website ini menjelaskan tentang penjualan buku yang mungkin ada pada toko-toko buku yang tersambung atau sudah bekerja sama dengan website kami. Yang mana website kami akan memberitahukan informasi tentang buku yang dicari oleh user, kemudian website OnBook akan menampilkan buku-buku dan harga pada buku tersebut, setelah itu akan ditunjukkan rekomendasi toko-toko yang menjual buku yang dicari. Pada awalnya website kami hanya dirancang secara sederhana hanya untuk menampilkan harga buku-buku yang ada, namun setelahnya dirubah menjadi lebih kompleks dan juga lebih rapi. Di sini juga ditambahkan fitur untuk menampilkan toko yang berjualan buku yang dicari untuk mempermudah user.


1.1 Purpose

Dokumen ini berisi Software Requirement Specification (SRS). Tujuan dibuatnya dokumen ini yaitu untuk memperjelas pengertian dari website OnBook secara lebih rinci dan lebih jelas untuk mempermudah pembaca. Dokumen SRS ini juga bertujuan memudahkan pengguna atau audiens untuk lebih mengerti mengenai website SRS yang dibuat. Diharapkan website ini dapat membantu pengguna agar lebih teliti ketika ingin membeli buku, karena website ini akan menjelaskan isi detail setiap jenis buku.

1.2 Document Conventions
Di sini akan dijelaskan mengenai singkatan dan pengertian dari file juga istilah yang berhubungan dengan website yang dibuat. Berikut konversi dokumen yang kami gunakan pada website OnBook:
- Software : Perangkat lunak yang berisikan data atau file yang dapat disimpan, dibuka, dan dibaca pada komputer.
- Website : Yaitu halaman informasi yang disediakan melalui jalur internet yang bisa diakses oleh seluruh dunia selama terkoneksi dengan internet.
- Domain : Alamat website, yaitu dapat mengantarkan kita ke alamat website yang dituju.
- Server : Merupakan sistem komputer yang memiliki layanan khusus berupa penyimpanan data.
- HTML : Hypertext Markup Language merupakan bahasa yang digunakan untuk membuat struktur website ini.
- CSS : Cascading Style Sheet yaitu bahasa yang digunakan untuk mengatur tampilan website OnBook ini.
- Format penulisan pada dokumen SRS ini menggunakan font Arial dengan spasi 1 berwarna hitam. Prioritas dari website “OnBook” ini adalah untuk memberikan informasi kepada pembaca mengenai buku-buku, seperti novel, komik, ensiklopedia, pengetahuan, dan lain sebagainya. Website ini akan memberikan ulasan buku yang disediakan informatif, terstruktur dengan baik, dan ditulis dengan gaya bahasa yang menarik.

1.3 Intended Audience and Reading Suggestions
Dokumen ini dipertunjukkan kepada beberapa pihak, yaitu:
- Pengguna. Pengguna dapat menggunakan dokumen ini untuk referensi isi website OnBook dan mengetahui rincian website OnBook. Pengguna yang dituju yaitu semua orang yang memiliki smartphone dan yang ingin mengetahui harga buku di toko-toko yang menjualnya (biasanya anak-anak, remaja atau orang dewasa).
- Audiens. Audiens yang dituju adalah semua umur dari kecil sampai dewasa. Terutama yang tertarik untuk membeli buku tetapi masih kurang yakin dengan isi bukunya dan kebingungan dimana untuk membeli buku dimana.

Saran pengembangan dalam website OnBook yaitu:
1. Meningkatkan fitur keamanan. Dengan meningkatkan fitur keamanan dapat memberikan kenyamanan lebih bagi user tanpa mengkhawatirkan akan data-data pribadinya.
2. Pengembangan AI pada website OnBook. Mengembangkan website untuk meningkatkan fungsi website ini sendiri. Contohnya seperti menyediakan fitur belanja online dan kerjasama dengan aplikasi Shopee.
3. Mmperhatikan Ulasan Pengguna. Ulasan dari pengguna harus diperhatikan dan kita sebagai pengelola harus bisa mengembangkan aplikasi sesuai dengan ulasan dan lebih memperbaikinya lagi.

1.4 Product Scope
OnBook merupakan website yang dibuat untuk memudahkan pengguna dalam mencari dan membeli buku yang diinginkan. Pada website ini pengguna dapat mengetahui dari cover buku dan deskripsi dari buku tersebut. Jadi pengguna dapat mempertimbangkan keinginannya untuk membeli buku dengan cara mengetahui deskripsi dan rate buku-buku tersebut. Untuk fitur sendiri terdapat akses login dan beranda, yang mana pada login pengguna harus memasukkan email beserta kata sandinya. Terdapat halaman rekomendasi yang menampilkan buku-buku yang mungkin disukai oleh pengguna. Dan yang terakhir adalah halaman popular, menampilkan buku-buku yang paling banyak dibeli oleh para pengguna dan yang paling banyak memiliki rate tertinggi. Website ini juga menyediakan fitur notifikasi, jadi jika ada buku terbaru yang masuk kategori popular maupun rekomendasi akan muncul notifikasi pada handphone maupun PC.


**2. Overall Description**

2.1 Product Perspective

OnBook merupakan website yang didesain dan dibuat untuk memudahkan pengguna mengetahui buku-buku yang ingin dicari. Pada website OnBook ini setiap buku yang dicari akan menjelaskan deskripsi dari buku tersebut. Pengguna yang akan membeli buku dapat mencari tahu isi buku di website ini. Cara kerja website ini yaitu pengguna hanya perlu login menggunakan email dan memasukkan passwordnya untuk masuk website agar website bisa berjalan dengan lancar.

2.2 Product Functions

Website ini dikembangkan dengan melakukan beberapa fungsi sebagai berikut:
- Registrasi akun: Fungsi memungkinkan pengguna website OnBook untuk membuat akun dan pengguna dapat mengisi data pribadi seperti Email dan kata sandinya.
- Menampilkan tampilan dan deskripsi buku: Fungsi ini untuk memudahkan pengguna dalam mencari buku yang diinginkan dan mengetahui isi deskripsi buku tersebut.
- Menampilkan toko penjual buku: Pada bagian ini menunjukkan toko yang menjual buku yang dicari pengguna, contohnya Gramedia.

2.3 User Classes and Characteristics
Hak Akses dari Website OnBook adalah sebagai berikut:
- Admin : Hak akses pada setiap data yang ada. Mendata email beserta kata sandi yang sudah masuk pada website.
- Pengguna : Mengisi ketentuan seperti email dan kata sandi pada halaman login. Memberikan ulasan ke website OnBook. Melihat rekomendasi buku dan toko penjual buku.

2.4 Operating Environment
Website OnBook dapat beroperasi berdasarkan spesifikasi sebagai berikut:
- Dapat diakses selama 24 jam
- Tidak adanya ketentuan minimal RAM pada laptop atau smartphone
- Bisa diakses kapan saja dan dimana saja asalkan terhubung dengan internet yang baik

2.5 Design and Implementation Constraints
Kendala yang mungkin terjadi pada website OnBook yaitu:
- Jaringan internet yang tidak stabil. Karena website OnBook ini harus memakai akses internet, ketidakstabilan jaringan dapat mengganggu pengguna dalam menjalankan website ini.
- Kurangnya keamanan. Karena pada website kami diperlukan email dan password email, dikhawatirkan email yang dipakai bisa dibobol oleh pihak yang tidak bertanggung jawab.

2.6 User Documentation
   Dalam pengimplementasiannya, website OnBook komponen dokumentasi yang dapat diberikan sebagai bantuan untuk menyelesaikan masalah dalam mengakses website OnBook yaitu:
   - Video Tutorial: Video ini berfungsi untuk memberitahu pengguna tutorial cara mengakses website yang baik dan benar. Akan diberitahukan step-one-step dalam penjelasan penggunaan website.
   - Adanya fitur komentar: Mempermudah pengguna untuk menyampaikan keluh kesahnya atas pelayanan website yang dibuat.
   
2.7 Assumptions and Dependencies
Website OnBook ini mempunyai dua interface. Yang pertama yaitu dapat dikunjungi oleh admin. Di sini admin memiliki hak akses untuk melihat dan juga mengelola semua data-data dari user. Semisal terjadi hal yang mencurigakan d dalm data, admin dapat menindaklanjuti hal tersebut. Interface yang selanjutnya yaitu tampilan halaman website OnBook bagi para user. Di sini user memiliki hak akses pada segala hal yang sudah disediakan dalam web OnBook sendiri. Seperti pencarian buku, rekomendasi, toko, dan lain sebagainya.

**3. External Interface Requirements**

3.1 User Interfaces

   Antarmuka pengguna yang ada pada website OnBook adalah sebagai berikut:
      1. Beranda: Pada halaman beranda ini, terdapat menu login untuk pengguna
      2. Rekomendasi: Halaman ini menampilkan beberapa buku rekomendasi yang disarankan kepada pengguna
      3. Popular: Halaman ini akan menampilkan buku-buku yang sedang popular

3.2 Hardware Interfaces

   Website Onbook didukung pada SmartPhone maupun PC yang terhubung dengan jaringan internet. Perangkat keras lainya yang mendukung pengaksesan website OnBook dapat dijelaskan seperti berikut:
      1. SmartPhone/PC : Untuk mengakses website OnBook
      2. Monitor : Menampilkan halaman website OnBook
      3. Keyboard : Untuk memasukkan input ke website OnBook
      4. Mouse : Untuk mempermudah navigasi pengguna

3.3 Software Interfaces

   Kebutuhan antarmuka perangkat lunak sangat dibutuhkan untuk membuat websie OnBook. Berikut adalah beberapa hal yag dibutuhkan untuk membuat website OnBook:
      1. HTML: HTML digunakan untuk mendefinisikan struktur dasar halaman web, menyusun teks, paragraf, daftar, dan elemen-elemen teks lainnya, serta untuk menghubungkan halaman web dan membentuk struktur navigasi.
      2. CSS : CSS digunakan untuk mengubah tampilan elemen-elemen HTML, termasuk warna latar belakang, teks, font, dan border.

3.4 Communications Interfaces

   Website OnBok membutuhkan laptop, PC, maupun SmartPhone yang tersambung ke internet.

3.5 Desain Graphical User Interface

\*Penjelasan HTML

![halaman utama](./imgsrs/beranda.png)
![halaman utama](./imgsrs/halaman1.png)
bagian Header untuk mengdefinisikan bagian nama dan navigasi dari web.
Pada header tersebut menggunakan tags

1. **h1** untuk membuat nama web
2. **span** untuk mengelompokkan Sebagian text kemudian diberi warna menggunakan style color.
3. **nav** digunakan untuk menandai bagian dari sebuah halaman web yang berisi menu navigasi.
4. **ul** digunakan untuk membuat daftar tak-terurut dari navigasi (unordered list).
5. **a** digunakan untuk membuat tautan atau hyperlink. Ini memungkinkan Anda untuk menghubungkan halaman web atau sumber daya lain dengan halaman web saat ini.

Pada bagian halaman Login menggunakan tags

1. **div** untuk membuat container box pada halaman web.
2. **Img** untuk menampilkan gambar pada web dengan menentukan sumber gambar dengan atribut src yang mengacu pada URL atau path file gambar.
3. **fieldset** digunakan untuk mengelompokkan beberapa elemen formulir dalam satu kerangka, seperti digunakan untuk form login yang berisikan E-mail dan Password.
4. **legend** digunakan sebagai judul atau keterangan untuk elemen formulir yang ada dalam <fieldset>.
5. **tabel** untuk membuat tabel pada halaman web yang dimana dalam tabel tersebut digunakan untuk menampilkan dan Menyusun dalam bentuk baris dan kolom.
6. **tr** digunakan untuk mendefinisikan baris dalam tabel.
7. **th** digunakan untuk mendefinisikan sel header dalam tabel. Sel header digunakan untuk memberikan informasi tambahan tentang konten di dalam sel-sel yang terkait di baris atau kolom yang sama.
8. **td** digunakan untuk mendefinisikan sela tau elemen data dalam tabel.
9. **button** digunakan untuk membuat tombol yang dapat digunakan oleh pengguna, dapat berupa pengiriman formulir atau pun tidakan lainnya yang ingin dilakukan dalam halaman web.
10. **h2** digunakan untuk menandai judul dengan ketebalan tingkat 2.
11. **h3** digunakan untuk menandai judul dengan ketebalan tingkat 3.

\*Penjelasan CSS

![halaman utama](./imgsrs/1.jpg)

Letakkan penjelasannya disini ya...

![halaman utama](./imgsrs/2.jpg)

Letakkan penjelasannya disini ya...

![halaman utama](./imgsrs/3.jpg)

Letakkan penjelasannya disini ya...

![halaman utama](./imgsrs/4.jpg)

Letakkan penjelasannya disini ya...

![halaman utama](./imgsrs/5.jpg)

Letakkan penjelasannya disini ya...

![halaman utama](./imgsrs/6.jpg)

Letakkan penjelasannya disini ya...

![halaman utama](./imgsrs/7.jpg)

Letakkan penjelasannya disini ya...

![halaman utama](./imgsrs/8.jpg)

Letakkan penjelasannya disini ya...

![halaman utama](./imgsrs/9.jpg)

Letakkan penjelasannya disini ya...

![halaman utama](./imgsrs/10.jpg)

Letakkan penjelasannya disini ya...

![halaman utama](./imgsrs/11.jpg)

Letakkan penjelasannya disini ya...

![halaman utama](./imgsrs/12.jpg)

Letakkan penjelasannya disini ya...

![halaman utama](./imgsrs/13.jpg)

Letakkan penjelasannya disini ya...

![halaman utama](./imgsrs/14.jpg)

Letakkan penjelasannya disini ya...

![halaman utama](./imgsrs/15.jpg)

Letakkan penjelasannya disini ya...

![halaman utama](./imgsrs/16.jpg)

Letakkan penjelasannya disini ya...

![halaman utama](./imgsrs/17.jpg)

Letakkan penjelasannya disini ya...

![halaman utama](./imgsrs/18.jpg)

Letakkan penjelasannya disini ya...

![halaman utama](./imgsrs/19.jpg)

Letakkan penjelasannya disini ya...

![halaman utama](./imgsrs/20.jpg)

Letakkan penjelasannya disini ya...

![halaman utama](./imgsrs/21.jpg)

Letakkan penjelasannya disini ya...

![halaman utama](./imgsrs/22.jpg)

Letakkan penjelasannya disini ya...

![halaman utama](./imgsrs/23.jpg)

Letakkan penjelasannya disini ya...

![halaman utama](./imgsrs/24.jpg)

Letakkan penjelasannya disini ya...

![halaman utama](./imgsrs/25.jpg)

Letakkan penjelasannya disini ya...

![halaman utama](./imgsrs/26.jpg)

Letakkan penjelasannya disini ya...

![halaman utama](./imgsrs/27.jpg)

Letakkan penjelasannya disini ya...

![halaman utama](./imgsrs/28.jpg)

Letakkan penjelasannya disini ya...

![halaman utama](./imgsrs/29.jpg)

Letakkan penjelasannya disini ya...

![halaman utama](./imgsrs/30.jpg)

Letakkan penjelasannya disini ya...

![halaman utama](./imgsrs/31.jpg)

Letakkan penjelasannya disini ya...

![halaman utama](./imgsrs/32.jpg)

Letakkan penjelasannya disini ya...

![halaman utama](./imgsrs/33.jpg)

Letakkan penjelasannya disini ya...

![halaman utama](./imgsrs/34.jpg)

Letakkan penjelasannya disini ya...

![halaman utama](./imgsrs/35.jpg)


**4. System Features**

4.1 Halaman Beranda
   
4.1.1 Description and Priority

   Halaman beranda merupakan fitur utama dalam website OnBook. Pada halaman ini, pengguna diminta untuk login ke dalam website agar bisa melihat ulasan buku lebih lanjut.   
   
4.1.2 Stimulus/Response Sequences

   Stimulus = Pengguna akan melihat halaman beranda yang menampilkan kolom untuk login
   Respon = Pengguna melakukan login
   
4.1.3 Functional Requirements

   Fitur Pendaftaran/Login. Website OnBook ini harus memiliki fitur pendaftaran ataupun login yang memungkinkan pengguna untuk mengakses akun mereka atau membuat akun baru.

4.2 Halaman Rekomendasi
   
4.2.1 Description and Priority

   Halaman rekomendasi adalah halaman yang menyajikan buku-buku yang direkomendasikan kepada pengguna. Halaman ini bertujuan untuk memberikan pengalaman yang personal dan relevan kepada pengguna, memungkinkan mereka menemukan buku-buku baru yang mungkin menarik dan sesuai dengan minat mereka.
   
4.2.2 Stimulus/Response Sequences

   Stimulus = Pengguna akan melihat beberapa buku rekomendasi yang sedang best seller.
   Respon = Pengguna melihat informasi mengenai buku tersebut dan membaca deskripsi dan ulasan pada halaman buku rekomendasi.

   Stimulus 2 = Pengguna tertarik untuk membeli buku yang telah dilihat dan dibaca.
   Respon 2 = Pengguna menekan tombol toko buku yang kemudian diarahkan ke website gramedia untuk membelinya.
   
4.2.3 Functional Requirements

   Fitur Ulasan. Fitur ulasan pada OnBook memungkinkan pengguna untuk memberikan ulasan dan peringkat buku yang telah mereka baca. Ulasan ini dapat berisi pendapat, komentar, atau tanggapan pengguna terhadap buku yang ingin dinilai oleh para pengguna.
   

4.3 Halaman Popular
   
4.3.1  Description and Priority

   Halaman populer pada website OnBook adalah halaman yang menampilkan daftar buku-buku yang saat ini paling populer atau diminati oleh pengguna. Populeritas buku ini dapat diukur berdasarkan peringkat, jumlah ulasan, penjualan, atau metrik lainnya yang relevan, maka dari itu buku dengan nilai kepopuleran paling tinggi akan muncul pada halaman website ini.

4.3.2	Stimulus/Response Sequences

   Stimulus 1 = Pengguna melihat buku-buku yang ditampilkan pada halaman popular.
   Respon 1 = Pengguna merasa tertarik dan penasaran dengan buku-buku yang ditampilkan. Mereka mulai melihat informasi mengenai buku tersebut dan membaca ulasan.

   Stimulus 2 = Pengguna tertarik untuk membeli buku yang telah dilihat dan dibaca.
   Respon 2 = Pengguna menekan tombol "toko buku" yang kemudian diarahkan ke website gramedia untuk melakukan pembelian

**5. Other Nonfunctional Requirements**

5.1 Performance Requirements
Terdapat beberapa persyaratan kinerja pada jalannya website OnBook ini :
- Website OnBook ini dapat diakses selama 24 jam selama masih tetap terhubung dengan internet.
- Server harus bisa memberikan informasi mengenai buku yang dicari user.
- Server harus bisa memberikan informasi tentang harga buku.
- Server harus bisa memberitahukan kepada user toko mana saja yang menjual buku yang dicari.

5.2 Safety Requirements
 Website OnBook merupakan website dengan keamanan yang cukup baik. Kami akan memastikan website OnBook ini akan aman digunakan bagi seluruh pengguna yang mengakses website ini. Walau website ini bisa diakses oleh seluruh dunia, keamanan pengguna dipastikan dengan cukup baik. Pada login website terdapat urutan cara untuk memasukkan email dan sandinya untuk memperketat keamanan. Jadi pengguna tidak perlu khawatir dalam kecolongan data, penipuan identitas, akses dari pihak yang tidak bertanggung jawab pada website ini.

5.3 Security Requirements
Untuk persyaratan keamanan pada website OnBook ini yaitu :
- Pada bagian login dilengkapi dengan email dan kata sandi, jadi ketika pengguna mendaftar maka email dan kata sandi ini akan tertampil untuk diisi pengguna sebagai syarat keamanan yang ada.
- Server down yang terjadi pada website maksimal 24 jam.
- Keamanan terjamin karena sistem akan memastikan data-data yang sudah didaftarkan melalui email dan kata sandi yang sudah didaftarkan.
- Email dan kata sandi dapat diganti sesuai keinginan pengguna.

5.4 Software Quality Attributes
Beberapa Kualitas pada Website yang ada yaitu sebagai berikut:
- Keandalan
   Website ini dapat diakses selama 24 jam penuh asalkan tetap terhubung pada internet.
- Keamanan
   Keamanan pengguna dapat terjaga karena terdapat email dan kata sandi pribadi dari setiap user.
- Portability
   Sistem ini portable karena pengguna dan admin dapat mengakses website ini kapan saja dan dimana saja.

5.5 Business Rules
 Aturan bisnis yang ada pada website OnBook ini yaitu kerjasama dengan pihak toko yang terkait. Website ini akan memberikan informasi tentang buku dan informasi toko penjual buku. Di sini bisa dibilang website OnBook ini akan mempromosikan toko yang diajak kerjasama, maka dari itulah website OnBook ini mendapatkan keuntungan. Pengguna yang sudah daftar dan login akan dapat mengakses website OnBook dengan baik.

**6. Other Requirements**

Appendix A: Glossary

- Software : Perangkat lunak yang berisikan data atau file yang dapat disimpan, dibuka, dan dibaca pada komputer.
- Website : Yaitu halaman informasi yang disediakan melalui jalur internet yang bisa diakses oleh seluruh dunia selama terkoneksi dengan internet.
- Domain : Alamat website, yaitu dapat mengantarkan kita ke alamat website yang dituju.
- Server : Merupakan sistem komputer yang memiliki layanan khusus berupa penyimpanan data.
- HTML : Hypertext Markup Language merupakan bahasa yang digunakan untuk membuat struktur website ini.
- CSS : Cascading Style Sheet yaitu bahasa yang digunakan untuk mengatur tampilan website OnBook ini.

Appendix B: Analysis Models

Flowchart

![flowchart](./image/flowchart.jpg)

Use Case Diagram

![flowchart](./image/usecase.jpg)

Appendix C: To Be Determined List

Untuk daftar yang akan ditentukan ada beberapa yang akan dikembangkan, yaitu:

1. Kami akan mengembangkan website OnBook ini dengan menambahkan beberapa fitur untuk lebih mempermudah pengguna.
2. Kami akan memperbaiki tampilan pada website agar lebih menarik.
3. Menambah akses keamanan data pengguna yang sudah pernah login ke website OnBook.
4. Menambahkan fitur-fitur baru untuk menarik minat pengguna.

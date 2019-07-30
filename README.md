# iap-cv-decorus
iap-cv-decorus: dokumentasi magang USAID,Cisco,SENADA

Dokumentasi  mengenai  jaringan komputer di CV Decorus

CV Decorus menggunakan jasa 2 ISP yaitu Telkom dan Indonet. Untuk memberikan akses internet ke jaringan Decorus, 
digunakan 1 buah modem TP Link TD 8817 dan terhubung ke Telkom. Untuk wireless router Asus WL-500W merupakan router 
sekaligus accesspoint untuk perangkat-perangkat PC dengan wireless card dan memberikan akses internet kepada para buyer 
di ruang tamu lantai bawah.

Untuk perangkat PC yang ada di CV Decorus berjumlah 26 PC. 26 PC tersebut 23 diantaranya terhubung ke jaringan di Decorus, 
sedangkan sisanya tidak. Untuk sistem operasi yang digunakan adalah Microsoft Windows XP Home edition SP2 (20 PC) dan 3 PC lainnya 
menggunakan Microsoft Windows XP Profesional Edition SP2. CV Decorus memiliki 1 buah server dengan Operating system Fedora Core 6.

Dari lantai 2 ini, router Asus WL-500W akan membagi akses internet ke switch D-Link yang berada di ruang cost accounting ,accounting. 
Dari Asus WL-500W ini akses internet juga terbagi ke switch Dlink yang berada di ruang Engineer lantai 1.

Kami sebagai mahasiswa Program Magang IAP ingin mengajukan Proposal untuk penggunaan voucher Cisco IAP  senilai US$500 
untuk Pembenahan dan pengembangan jaringan komputer yang ada di CV Decorus.

I.	Identifikasi Masalah
  CV. Decorus adalah Perusahaan Industri Kecil Menengah yang bergerak dibidang Furniture. Memiliki 26 Unit Komputer, 23 PC terhubung 
ke jaringan. Dengan perangkat penghubungnya saat ini yaitu 2 buah Switch masing-masing swicth berjumlah 8 Port dan 16 port. CV Decorus 
menggunakan 2 ISP untuk terhubung ke internet, yaitu indonet dan telkom speedy.

  Penggunaan dua buah perangkat Wireless Router ASUS WL-500W yang berfungsi sebagai router juga sebagai accesspoint 
dan Modem Router TP-Link TD-8817 (Modem+Router) untuk memberikan akses internet untuk jaringan Decorus kurang tepat. 
Hal ini dikarenakan tidak adanya fasilitas dari ke dua router tersebut untuk melakukan pengaturan bandwitdh secara efisien, dan optimal. 
Selain itu kedua router tersebut tidak memiliki 2 port WAN untuk dapat menggunakan jasa kedua ISP secara balance dan optimal.
Selain berfungsi sebagai router ASUS WL-500W juga berfungsi sebagai Accespoint untuk beberapa perangkat. 
Ada beberapa perangkat yang menggunakan fasilitas dari wireless router ASUS tersebut antara lain: PC yang digunakan untuk akses CCTV, 
melayani akses internet buyer, dan juga akses internet dari bagian marketing+sekretaris. Karena beban kerja dari wireless router ini 
relatif berat, maka hal tersebut juga membebani jaringan Decorus secara keseluruhan. Hal ini sangat terasa lambat (patah-patah) 
saat mencoba akses CCTV melalui media notebook/PC di lokal jaringan Decorus atau mengakses CCTV Decorus dari luar kantor dengan web broswer. 

  Selain itu router ASUS WL-500W juga berfungsi sebagai gateway untuk jaringan kabel LAN meliputi ruang Engineer, ruang cost accounting, 
dan ruang accounting. Sehingga semua trafik lalulintas data keluar dan masuk hanya melalui 1 pintu.
Selain penggunaan sebuah perangkat (ASUS WL-500W) untuk melayani keseluruhan jaringan, penggunaan switch yang memiliki kapasitas 
jumlah port transfer data yang sedikit dan tidak lagi optimal untuk melayani tranfer data antar PC dijaringan.  
Switch di CV Decorus untuk Lantai 2 hanya berjumlah 8 port dan sudah terpakai sebanyak 6 port. 
Untuk switch di ruang engineer, Decorus menggunakan switch dengan jumlah port 16 dan ini masih cukup untuk melayani 8 PC yang 
saling berbagi pakai dan mentransfer file ke server Decorus. 

  Terkadang pula staff IT di Decorus yang mencoba mengirim file berukuran 10 megabyte ke PC lain di LAN Decorus merasa proses transfer 
data yang lambat dan lama. Ini akan mengurangi kinerja dan efisiensi jaringan secara keseluruhan dan berimbas pada kinerja perusahaan 
sendiri.

  Ketika buyer atau tamu datang, pihak Decorus juga memberikan akses internet untuk melakukan transaksi atau membantu untuk melakukan 
pengambilan keputusan disaat yang mendesak. Penggunaan router ASUS WL-500W sebagai wireless accesspoint sangat tidak optimal, 
karena WAP tersebut juga bertugas untuk memastikan CCTV dapat diakses dengan lancar tanpa mempengaruhi kinerja jaringan lainnya juga. 
Untuk itu perlu digunakan WAP yang dikhususkan untuk melayani buyer,customer dan tamu-tamu, tanpa adanya pembatasan pengunaan akses 
internet sebanyak 4 buah PC/Notebook. Akan lebih baik dan aman untuk perangkat jaringan itu diletakan pada sebuah ruangan khusus 
sehingga tidak semua karyawan boleh masuk  ke ruang server, hanya owner dan staff IT saja berhak untuk mengelola dan mengakses. 
Untuk PC yang digunakan untuk akses CCTV bisa diletakan di ruang direktur untuk melihat proses bisnis perusahaan secara detail.


1. `http.cap`: Berkas ini berisi data paket jaringan yang terkait dengan protokol HTTP (Hypertext Transfer Protocol). HTTP adalah protokol yang digunakan untuk mengirimkan permintaan dan menerima respons antara klien (biasanya web browser) dan server web.

2. `telnet-cooked.cap`: Telnet adalah protokol jaringan yang digunakan untuk mengakses jarak jauh ke perangkat yang menjalankan layanan konsol atau shell. File ini mungkin berisi data paket jaringan yang terkait dengan sesi Telnet.

3. `dns.cap`: Berkas ini berisi data paket jaringan yang terkait dengan protokol DNS (Domain Name System). DNS digunakan untuk menerjemahkan nama domain (seperti www.example.com) menjadi alamat IP yang sesuai.

- **Ping**: Ping adalah perintah di dalam komputer yang digunakan untuk menguji konektivitas jaringan dan mengukur waktu respons dari host lain. Ketika Anda melakukan ping ke suatu alamat IP atau nama domain, komputer Anda akan mengirimkan pesan ke tujuan tersebut, dan jika tujuan merespons, Anda akan menerima pesan balasan. Ini membantu Anda memeriksa apakah suatu host dapat dijangkau melalui jaringan dan memberikan indikasi tentang seberapa cepat koneksi ke host tersebut.

- **Traceroute**: Traceroute (atau tracert di lingkungan Windows) adalah perintah yang digunakan untuk melacak jalur yang dilalui oleh paket data saat mereka bergerak melalui jaringan dari satu host ke host lainnya. Traceroute bekerja dengan mengirimkan serangkaian paket dengan TTL (Time to Live) yang semakin bertambah, sehingga paket-paket tersebut akan dijatuhkan oleh setiap hop di rute jaringan. Setiap kali paket dijatuhkan, Anda akan menerima informasi tentang hop tersebut dan waktu yang dibutuhkan untuk mencapai hop tersebut. Ini membantu Anda memahami jalur yang dilalui oleh paket data dan mengidentifikasi bottleneck atau masalah di dalam rute jaringan.


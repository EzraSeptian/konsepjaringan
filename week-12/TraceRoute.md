# Trace Route

## Trace route 1.1.1.1
![gambar](asset/traceroute1111.png)

![gambar](asset/traceroute11112.png)

### Penjelasan:
Trace route (traceroute) adalah alat diagnostik yang digunakan untuk melacak rute yang diambil oleh paket-paket melintasi jaringan. Dalam trace route yang tersebut diberikan, ada tiga contoh, dan masing-masing mewakili jalur yang diambil oleh paket untuk mencapai alamat IP tujuan 1.1.1.1. Mari analisis setiap hop:

### Trace Route 1:
1. **_gateway (192.168.3.1):** Ini adalah gateway lokal, titik awal trace route.
2. **10.252.108.212:** Ini kemungkinan adalah router perantara di jaringan lokal.
3. **241.56.pens.ac.id (103.24.56.241):** Ini adalah server atau router spesifik pada alamat IP 103.24.56.241.
4. **core-router.pens.ac.id (202.9.85.1):** Router lain di jalur, mungkin merupakan router inti untuk jaringan tersebut.
5. **edge-router.pens.ac.id (10.252.0.1):** Ini tampaknya adalah router tepi, mungkin terhubung ke jaringan yang lebih luas.
6. **114-4-97-169.resources.indosat.com (114.4.97.169):** Ini adalah server atau router dengan domain yang terkait dengan Indosat, perusahaan telekomunikasi Indonesia.
7. **114-0-78-196.resources.indosat.com (114.0.78.196):** Server atau router lain dalam jaringan Indosat.
8. **(Dilewati):** Ada beberapa waktu habis yang ditunjukkan dengan tanda asterisk. Ini bisa disebabkan oleh kepadatan jaringan, konfigurasi firewall, atau perangkat yang tidak merespons permintaan ICMP.
9. **172.70.146.3:** Sebuah alamat IP, mungkin mewakili perangkat perantara lain.
10. **one.one.one.one (1.1.1.1):** Alamat IP tujuan, yang merupakan server DNS publik Cloudflare.

### Trace Route 2:
Ada sedikit variasi dalam waktu respons dan rute. Ini normal karena sifat dinamis internet. Rute yang berbeda mungkin diambil berdasarkan kondisi jaringan, pembagian beban, atau perubahan dalam topologi jaringan. Beberapa perbedaan khusus termasuk perubahan dalam waktu respons dan penambahan alamat IP baru seperti 13335.sgw.equinix.com (27.111.228.132).

### Trace Route 3:
Trace route ini menunjukkan perbedaan lebih lanjut, dengan alamat IP baru seperti 162.158.39.3 dan waktu habis tambahan. Sekali lagi, variasi ini umum terjadi dalam jaringan dinamis.

Secara ringkas, trace routes dapat berbeda karena sifat dinamis internet, kondisi jaringan yang beragam, dan keberadaan beberapa rute yang dapat diambil paket untuk mencapai tujuan. Beberapa router atau server juga mungkin dikonfigurasi untuk menurunkan prioritas atau menolak lalu lintas ICMP, menyebabkan waktu habis dalam hasil trace route.


## Trace Route detik.com
![gambar](asset/traceroutedetik.png)

![gambar](asset/traceroutedetik(2).png)


### Penjelasan

Pada trace route pertama (203.190.242.211), mari kita lihat setiap hop:

    Hop 1 (_gateway - 192.168.3.1): Ini adalah router gateway lokal pada jaringan Anda (router rumah atau kantor).
    Hop 2 (10.252.108.212): Ini mungkin adalah router atau perangkat jaringan di dalam jaringan lokal Anda.
    Hop 3 (241.56.pens.ac.id - 103.24.56.241): Ini adalah node di jaringan Institut Teknologi Sepuluh Nopember (PENS) dengan alamat IP 103.24.56.241.
    Hop 4 (core-router.pens.ac.id - 202.9.85.1): Ini mungkin adalah router inti di jaringan PENS.
    Hop 5 (edge-router.pens.ac.id - 10.252.0.1): Kemungkinan besar ini adalah router tepi (edge router) di jaringan PENS.
    Hop 6 (124-195-39-3.resources.indosat.com - 124.195.39.3): Node ini mungkin terletak di jaringan penyedia layanan internet (ISP) Indosat.
    Hop 7: Tidak ada respons (* * *). Ini mungkin disebabkan oleh aturan firewall atau konfigurasi yang tidak mengizinkan respon ICMP dari node tertentu.
    Hop 8 (218.100.36.9): Node ini mungkin adalah bagian dari jaringan Indosat.
    Hop 9 (s2-211-242.190.203.detik.com - 203.190.242.211): Ini adalah server detik.com dengan alamat IP 203.190.242.211.

Sekarang, mengenai perbedaan pada trace route yang pertama dan yang kedua, perbedaan tersebut terjadi pada hop 6 (124-195-39-3.resources.indosat.com). Pada trace route pertama, ada tiga kali percobaan, tetapi hanya satu yang memberikan respons. Pada trace route kedua, semua tiga percobaan memberikan respons. Hal ini bisa disebabkan oleh fluktuasi jaringan yang normal, lalu lintas yang berubah-ubah, atau aturan firewall yang mengizinkan respons ICMP pada percobaan kedua. Hal ini adalah sesuatu yang umum terjadi di Internet, dan fluktuasi semacam ini adalah hal yang normal.

## Route print

![gambar](asset/routeprint.png)


## Route List

![gambar](asset/routelist.png)

## RIP Network

![gambar](asset/RIP.png)

## RIP Interfaces

![gambar](asset/RIP_interface.png)

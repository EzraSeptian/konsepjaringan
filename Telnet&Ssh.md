# Telnet & SSH
Telnet adalah sebuah protokol jaringan yang digunakan untuk mengakses dan mengendalikan perangkat jarak jauh melalui jaringan, seperti mengakses server atau perangkat yang menjalankan layanan jarak jauh. Telnet memungkinkan pengguna untuk berinteraksi dengan perangkat atau sistem yang berjalan di jaringan, seolah-olah mereka berada di lokasi fisik yang sama dengan perangkat tersebut. Ini adalah salah satu protokol yang awalnya digunakan secara luas untuk akses remote sebelum keamanan menjadi perhatian utama.

Spesifikasi Telnet terdokumentasi dalam RFC 854. RFC 854 adalah dokumen standar Internet yang mendefinisikan protokol Telnet dan menjelaskan karakteristik utamanya. Berikut adalah beberapa karakteristik kunci dari Telnet (dalam konteks TCP):

1. Protokol Teks: Telnet adalah protokol berbasis teks, yang berarti data yang ditransmisikan antara client dan server adalah teks mentah yang dapat dibaca manusia. Ini memungkinkan pengguna untuk berinteraksi dengan perangkat jarak jauh menggunakan perintah dan respon teks.

2. Port Default: Port standar untuk Telnet adalah 23.

3. Clear Text: Salah satu karakteristik yang penting untuk dicatat adalah bahwa Telnet mengirim data dalam bentuk teks biasa (clear text) tanpa enkripsi. Oleh karena itu, data yang dikirim melalui Telnet tidak aman jika melintasi jaringan yang tidak aman. Ini adalah alasan mengapa penggunaan Telnet telah berkurang dan sering digantikan oleh protokol lain seperti SSH (Secure Shell) yang menawarkan keamanan lebih baik melalui enkripsi.

4. Tersedia di Banyak Sistem Operasi: Klien dan server Telnet tersedia di berbagai sistem operasi, sehingga memungkinkan pengguna dari berbagai platform untuk terhubung dan berinteraksi dengan perangkat atau sistem yang menjalankan layanan Telnet.

5. Berbasis TCP: Telnet berjalan di atas protokol transport TCP (Transmission Control Protocol) untuk memastikan pengiriman data yang andal.

6. Akses Jarak Jauh: Telnet digunakan untuk mengakses perangkat atau sistem dari jarak jauh melalui jaringan. Ini berarti pengguna dapat mengendalikan dan berinteraksi dengan perangkat atau sistem yang berada di lokasi geografis yang berbeda.

7. Kurang Aman: Salah satu kekurangan utama Telnet adalah kurangnya keamanan bawaan. Karena data yang dikirim melalui Telnet tidak dienkripsi, informasi sensitif seperti kata sandi dapat dengan mudah dicuri jika data ini disadap selama transmisi. Itu sebabnya penggunaan Telnet di jaringan yang tidak aman sangat tidak disarankan.

Karena kelemahan keamanannya, Telnet telah digantikan oleh protokol SSH yang menawarkan enkripsi dan tingkat keamanan yang lebih tinggi. Oleh karena itu, dalam banyak kasus, Telnet tidak lagi digunakan dalam lingkungan produksi yang mengharuskan tingkat keamanan yang lebih tinggi.

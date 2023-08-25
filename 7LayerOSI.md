# 7 Layer OSI
Protokol komunikasi sering dipecah menjadi beberapa lapisan yang berbeda, di mana setiap lapisan memiliki tugas khusus dalam proses komunikasi. Model Referensi OSI adalah salah satu model yang menggambarkan lapisan-lapisan ini. Berikut adalah deskripsi tiap lapisan pada Model Referensi OSI beserta tugas-tugas utamanya:

1. **Lapisan Fisik (Physical Layer)**:
   - Lapisan terbawah yang mengatur transmisi bit mentah melalui media fisik seperti kabel atau gelombang radio.
   - Bertanggung jawab atas karakteristik fisik seperti tegangan, arus, dan frekuensi yang digunakan untuk mengirim data.
   - Definisi tipe kabel, konektor, dan perangkat keras fisik lainnya.
   - Tugas utama: Mengirim dan menerima sinyal bit.

2. **Lapisan Data Link (Data Link Layer)**:
   - Mengatur aliran data di antara dua perangkat yang langsung terhubung.
   - Menyediakan pengiriman data yang andal dengan mendeteksi dan memperbaiki kesalahan dalam frame data.
   - Mengelola akses media bersama (shared media access) dengan protokol seperti Ethernet.
   - Tugas utama: Deteksi dan koreksi kesalahan, pengelompokan data menjadi frame, pengaturan aliran data.

3. **Lapisan Jaringan (Network Layer)**:
   - Bertanggung jawab atas pengiriman paket data dari sumber ke tujuan melalui jaringan yang kompleks.
   - Menentukan rute terbaik untuk paket data melalui berbagai jaringan dan node (router).
   - Menggunakan alamat IP untuk mengidentifikasi perangkat dalam jaringan.
   - Tugas utama: Pengalihan paket, routing, pengalamatan jaringan.

4. **Lapisan Transport (Transport Layer)**:
   - Menangani pengiriman data yang andal antara perangkat yang terhubung.
   - Memecah data menjadi segmen atau paket yang lebih kecil untuk dikirimkan melalui jaringan.
   - Menyediakan kontrol aliran dan pengaturan koneksi end-to-end.
   - Tugas utama: Pemecahan data menjadi segmen, kontrol aliran, pengaturan koneksi.

5. **Lapisan Sesi (Session Layer)**:
   - Menangani pembentukan, pengelolaan, dan akhir sesi komunikasi antara perangkat.
   - Mengatur awal dan akhir dialog antara aplikasi di perangkat yang berkomunikasi.
   - Menyediakan sinkronisasi data dan pemulihan setelah gangguan.
   - Tugas utama: Pengelolaan sesi, sinkronisasi data.

6. **Lapisan Presentasi (Presentation Layer)**:
   - Bertanggung jawab atas konversi, enkripsi, dan kompresi data.
   - Menangani format data dan representasi yang berbeda antara perangkat.
   - Memastikan data dapat dipahami oleh perangkat penerima.
   - Tugas utama: Enkripsi, kompresi, konversi format.

7. **Lapisan Aplikasi (Application Layer)**:
   - Lapisan teratas yang berhubungan langsung dengan aplikasi pengguna.
   - Menyediakan layanan dan protokol yang digunakan oleh aplikasi untuk berkomunikasi.
   - Contoh protokol di lapisan ini termasuk HTTP, SMTP, dan FTP.
   - Tugas utama: Layanan aplikasi, komunikasi aplikasi-ke-aplikasi.

Penting untuk diingat bahwa beberapa protokol komunikasi dapat mencakup beberapa lapisan, dan nama lapisan dan tugas-tugas yang dijelaskan di atas dapat bervariasi dalam implementasi nyata tergantung pada protokol yang digunakan.

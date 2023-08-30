# konsepjaringan
1. **Kenapa FTP dapat menggunakan protokol UDP dan TCP?**
File Transfer Protocol (FTP) adalah protokol yang digunakan untuk mentransfer file antara komputer di dalam jaringan. Meskipun FTP pada dasarnya menggunakan protokol TCP (Transmission Control Protocol), ada beberapa aspek yang memungkinkan FTP untuk beroperasi melalui TCP atau UDP (User Datagram Protocol), tergantung pada cara implementasinya.

    TCP (Transmission Control Protocol):
    Mayoritas implementasi FTP menggunakan TCP sebagai protokol transportnya. TCP adalah protokol yang andal dan terjamin pengiriman datanya. Ini cocok untuk transfer file karena memastikan bahwa setiap paket data dikirim dan diterima dengan benar. Penggunaan TCP juga memungkinkan mekanisme pengaturan aliran dan pengendalian kesalahan.

    UDP (User Datagram Protocol):
    Beberapa implementasi FTP, terutama varian FTP yang disebut TFTP (Trivial File Transfer Protocol), menggunakan UDP sebagai protokol transport. TFTP adalah bentuk sederhana dari FTP yang digunakan untuk transfer file ringan, terutama dalam lingkungan booting jaringan. UDP digunakan karena kesederhanaannya dan kenyataan bahwa dalam beberapa kasus, kecepatan lebih penting daripada keandalan. Namun, penggunaan UDP dapat menyebabkan hilangnya paket atau ketidakberurutanan paket.

      Jadi, FTP sendiri lebih sering menggunakan TCP karena karakteristiknya yang lebih andal dan cocok untuk transfer file besar. Namun, dalam kasus seperti TFTP atau implementasi alternatif lainnya, UDP digunakan terutama untuk kecepatan transfer dengan sedikit perhatian terhadap keandalan.

  2. **Narasikan bagaimana proses terjadinya Connection estabilishment**   
      Pikirkan proses pembentukan koneksi seperti saat kamu ingin menghubungi temanmu lewat telepon. Bayangkan kamu ingin mengirim pesan ke temanmu, tetapi sebelum kamu bisa mulai bicara, kamu harus melalui beberapa langkah pertama.
      
      **Permintaan Bicara (SYN - Synchronize):**
      Pertama, kamu menekan tombol panggilan pada teleponmu, seperti memberi tahu temanmu bahwa kamu ingin bicara. Ini seperti mengirimkan pesan "Hai, aku mau ngobrol nih!" ke temanmu. Pada saat yang sama, kamu juga memberikan nomor urut pertama agar kamu berdua tahu dari mana kamu memulai.
      
      **Respon dari Teman (SYN-ACK - Synchronize-Acknowledge):**
      Kemudian, temanmu mengangkat teleponnya dan menjawab, "Hai! Aku siap mendengarkan." Ini seperti temanmu memberitahu kamu bahwa ia juga ingin bicara. Dia memberikan nomor urut pertama dari sisinya dan menyebutkan nomor urut pertamamu.
      
      **Konfirmasi Bicara (ACK - Acknowledge):**
      Setelah kamu mendengar temanmu, kamu mengatakan, "Baiklah, aku siap." Ini seperti memberitahu temanmu bahwa kamu menerima tanggapannya dan kamu siap untuk memulai percakapan. Kamu juga memberikan nomor urut pertama dari sisimu.
      
      Setelah langkah-langkah ini selesai, koneksi antara kamu dan temanmu telah dibuat. Kalian berdua sekarang tahu nomor-nomor khusus ini untuk memastikan bahwa obrolan kalian berdua akan berjalan dengan lancar. Setelah koneksi terbentuk, kalian bisa saling berbicara dan menukar pesan dengan nyaman.
      
      Ingatlah bahwa proses ini mirip dengan cara komputer berkomunikasi melalui jaringan. Sebelum komputer bisa mengirim data, mereka harus "berbicara" satu sama lain untuk mengatur segalanya dengan baik.

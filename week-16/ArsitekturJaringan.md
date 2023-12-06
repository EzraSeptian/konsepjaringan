Arsitektur jaringan yang umum digunakan di kampus adalah arsitektur jaringan berbasis kabel (wired network) dan sering kali mencakup struktur topologi jaringan yang berbeda. Contoh yang umum adalah topologi jaringan bintang (star topology) dan mungkin juga topologi jaringan campuran.

### Contoh: Arsitektur Jaringan Kampus Berbasis Topologi Bintang

Topologi bintang adalah topologi jaringan di mana semua perangkat terhubung ke satu titik sentral, yang disebut sebagai switch atau pusat distribusi. Ini adalah salah satu topologi yang paling umum digunakan karena memiliki manajemen yang baik dan mudah diimplementasikan.

**Deskripsi:**

1. **Switch Pusat:**

   - Titik sentral di kampus adalah switch pusat yang menghubungkan semua perangkat ke jaringan. Ini bisa menjadi switch utama di pusat data atau ruang server.

2. **Gedung dan Kamar:**

   - Setiap gedung atau area di kampus memiliki kabel jaringan yang diarahkan menuju switch pusat. Setiap kabel mewakili konektivitas jaringan untuk gedung atau ruangan tertentu.

3. **Perangkat Pengguna:**

   - Setiap perangkat pengguna seperti komputer, laptop, printer, atau perangkat jaringan lainnya dihubungkan ke switch pusat melalui kabel.

4. **Access Points (AP):**
   - Jika ada jaringan nirkabel (Wi-Fi) di kampus, maka access points akan terhubung ke switch pusat untuk menyediakan konektivitas nirkabel di seluruh kampus.

**Gambar:**

```
               +------------------+
               | Switch Pusat     |
               +--------+---------+
                        |
   +-----------+--------+--------+--------+
   | Gedung A  | Gedung B | Gedung C | ...
   +--+----+---+--+-----+--+----+--+
      |    |      |     |     |
      |    |      |     |     |
   +--+ +--+  +--+ +--+ +--+ +--+
   |PC| |PC|  |PC| |PC| |PC| |PC|
   +--+ +--+  +--+ +--+ +--+ +--+
```

Pada gambar di atas, setiap gedung atau area di kampus terhubung ke switch pusat. Setiap perangkat pengguna dihubungkan ke switch pusat menggunakan kabel, dan jika diperlukan konektivitas nirkabel, access points juga terhubung ke switch pusat.

Perhatikan bahwa ini hanya contoh umum, dan arsitektur jaringan di kampus bisa sangat bervariasi tergantung pada ukuran kampus, kebutuhan jaringan, dan teknologi yang digunakan.

# Physical Router

![gambar](asset/physicalrouter.PNG)

Pada laporan ini, kita melakukan praktikum secara langsung menggunakan bentuk fisik dari router dan melakukan configurasi langsung ke router dimana router
tersebut juga berfungsi sebagai switch yang menghubungkan router ke pc lab dimana kelompok kita mendapat IP antar router yaitu 10.252.108.13/24 dan network ke pc 192.168.3.0/24.

## Configurasi pada mikrotik

### 1. Koneksi

![gambar](asset/01.png)

### 2. Tambah Bridge & Port (ether 2-9)

![gambar](asset/bridge.png)

![gambar](asset/ether1-9.png)

### 3. Tambah dan config address

![gambar](asset/adress(kepc).png)

![gambar](asset/adress(kerouter).png)

![gambar](asset/adresslist.png)

### 4. Tambah Route

![gambar](asset/setrouteatas.png)

![gambar](asset/setroutekita.png)

![gambar](asset/setroute1.png)

![gambar](asset/setroute2.png)

![gambar](asset/setroute4.png)

![gambar](asset/setroute5.png)

![gambar](asset/setroute6.png)

![gambar](asset/setroute7.png)

![gambar](asset/setroute8.png)

![gambar](asset/setroute9.png)

![gambar](asset/setroute10.png)

![gambar](asset/routelist1.png)

![gambar](asset/routelist2.png)

![gambar](asset/iprouteprint.png)

6. Uji Ping (Antar PC dengan IP 192.168.3.2 dalam 1 Router)

Ping ke PC dengan IP 192.168.3.3

![gambar](asset/pingke3.png)

Ping ke PC dengan IP 192.168.3.4

![gambar](asset/pingke4.png)

Ping ke Router dengan Gateway 192.168.3.1

![gambar](asset/pingkerouter.png)

7. Uji Ping (Ping ke router lain dalam 10.252.108.0/24)

![gambar](asset/pingantarrouter.png)

# Cisco 6 Subnet 1 Router 6 Pc
![gambar](asset/cisco2.png)

**Configurasi:**


Router 1:

- FastEthernet 0/0:
  
  - IP Address: 12.32.0.1
  - Subnet Mask: 255.224.0.0
    
- FastEthernet 1/0:
  
  - IP Address: 12.64.0.1
  - Subnet Mask: 255.224.0.0
    
- FastEthernet 2/0:
  
  - IP Address: 12.96.0.1
  - Subnet Mask: 255.224.0.0
    
- FastEthernet 3/0:
  
  - IP Address: 12.128.0.1
  - Subnet Mask: 255.224.0.0
    
- FastEthernet 4/0:
  
  - IP Address: 12.160.0.1
  - Subnet Mask: 255.224.0.0
    
- FastEthernet 5/0:
  
  - IP Address: 12.192.0.1
  - Subnet Mask: 255.224.0.0
    

PC 1:

- IP Address: 12.32.0.2
- Subnet Mask: 255.224.0.0
- Gateway: 12.32.0.1

PC 2:

- IP Address: 12.64.0.2
- Subnet Mask: 255.224.0.0
- Gateway: 12.64.0.1

PC 3:

- IP Address: 12.96.0.2
- Subnet Mask: 255.224.0.0
- Gateway: 12.96.0.1

PC 4:

- IP Address: 12.128.0.2
- Subnet Mask: 255.224.0.0
- Gateway: 12.128.0.1

PC 5:

- IP Address: 12.160.0.2
- Subnet Mask: 255.224.0.0
- Gateway: 12.160.0.1

PC 6:

- IP Address: 12.192.0.2
- Subnet Mask: 255.224.0.0
- Gateway: 12.192.0.1


## Penjelasan

IP address pada Router dimulai dari 12.32 sampai 12.192 dikarenakan kita membutuhkan 6 subnet pada kasus ini. Karena kita membutuhkan 6 subnet maka kita akan menggeser bit host sebanyak 3 bit, dimana 3 bit didapat dari 2^m-2, m merupakan banyak bit host yang digunakan untuk subnet (hasil 2^m-2 dianjurkan harus mendekati banyak subnet yang diperlukan). Karena rumus tersebut maka kemungkinan angka yang dapat muncul pada 3 bit tersebut yaitu 32,64,96,128,160 dan 192 dan untuk Subnet Mask berubah yang awalnya 255.0.0.0 menjadi 255.224.0.0, dimana nilai 224 di dapat dari ketika 3 bit host yang kita gunakan bernilai 1 semua sehingga akan bernilai 128,64,32 dan jumlahkan 3 bilangan tersebut untuk menghasilkan nilai 224.

Untuk Range IP address (yang dapat digunakan host) dan digunakan IP broadcast pada tiap subnet yaitu:

Subnet 1:

- IP address: 12.32.0.0 sampai 12.63.255.254
- IP broadcast: 12.63.255.255

Subnet 2:

- IP address: 12.64.0.0 sampai 12.95.255.254
- IP broadcast: 12.95.255.255

Subnet 3:

- IP address: 12.96.0.0 sampai 12.127.255.254
- IP broadcast: 12.127.255.255
  
Subnet 4:

- IP address: 12.128.0.0 sampai 12.159.255.254
- IP broadcast: 12.159.255.255

Subnet 5:

- IP address: 12.160.0.0 sampai 12.191.255.254
- IP broadcast: 12.191.255.255

Subnet 6:

- IP address: 12.192.0.0 sampai 12.223.255.254
- IP broadcast: 12.223.255.255

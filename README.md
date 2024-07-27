![Porto_project_3_networking](https://github.com/user-attachments/assets/dd894475-b156-46be-b571-8d5835a1899f)


# Project Networking 3 Hotel Management Menggunakan EIGRP


Project Networking 3 Hotel Management Menggunakan EIGRP
Sebagai bagian dari proyek jaringan, untuk merancang dan mengimplementasikan jaringan Vic Modern Hotel. Hotel ini memiliki tiga lantai; di lantai pertama ada tiga departemen (Reception, store dan Logistics), di lantai dua ada tiga departemen (Finance, HR dan Sales/Marketing), sedangkan lantai tiga menjadi tuan rumah IT dan Admin. Oleh karena itu, berikut ini adalah bagian dari pertimbangan selama desain dan implementasi;
Harus ada tiga router yang menghubungkan setiap lantai (semuanya ditempatkan di ruang server di departemen TI).
Semua router harus terhubung satu sama lain menggunakan kabel serial DCE.

- Setiap 3 router terkoneksi beberapa lantai (semuanya di tempatkan di ruang server di departemen IT)
- Jaringan antara router harus 10.10.10.0/30, 20.20.20.0/30 dan 30.30.30.0/30.
- Setiap lantai diharapkan memiliki satu sakelar (ditempatkan di lantai masing-masing).
- Setiap lantai diharapkan memiliki jaringan WIFI yang terhubung ke laptop dan ponsel, dan tablet PC.
- Setiap departemen diharapkan memiliki printer.
- Setiap departemen diharapkan berada di VLAN yang berbeda dengan rincian sebagai berikut;

- lantai 1
  - Resepsionis-vlan 60, network 192.168.8.0/24
  - Logistik vlan 80, network 192.168.80.0/24
  - Store vlan 70, network 192.168.40.0/24
 
- Lantai 2
  - Sales vlan 10, network 192.168.10.0/24
  - HR vlan 20, network 192.168.20.0/24
  - Finance Vlan 50, network 192.168.30.0/24
- Lantai 3
  - Admin vlan 40, network 192.168.200.0/24
  - IT vlan 30, network 192.168.100.0/24

Menggunakan IERGP Routing dalam route setiap router dan traffic data.
 


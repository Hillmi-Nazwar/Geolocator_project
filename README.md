# Geolocator_Project

**Tugas 1**: Geocoding (Alamat dari Koordinat)
Saat ini kita hanya menampilkan Lat/Lng. Buatlah agar aplikasi menampilkan alamat
(nama jalan, kota, dll) dari koordinat yang didapat.
Petunjuk:
1. Anda sudah menambahkan paket geocoding di pubspec.yaml.
2. Import paketnya: import ’package:geocoding/geocoding.dart’;
3. Buat variabel String? currentAddress; di MyHomePageState.
4. Buat fungsi baru getAddressFromLatLng(Position position).
5.  Panggil fungsi getAddressFromLatLng( currentPosition!) di dalam getLocation
dan startTracking (di dalam .listen()) setelah setState untuk currentPosition.
6. Tampilkan currentAddress di UI Anda, di bawah Lat/Lng.



===================================================================================
## Beberapa Bagian

ini adalah fungsi untuk mengkoversi koordinat menjadi alamat dan fungsi ini menggunakan paket geocoding untuk mendapatkan detail alamat.
<img width="1850" height="930" alt="carbon (7)" src="https://github.com/user-attachments/assets/d7f25a2b-c5a3-4d3e-8e0c-f8936045a6c9" />

ini adalah fungsi untuk mendapatkan lokasi sekarang.
<img width="1312" height="670" alt="carbon (10)" src="https://github.com/user-attachments/assets/dfd1cf0a-2e21-4223-96b8-51628c5b20ba" />


ini adalah fungsi untuk melacak lokasi, dan ini akan diupdate secara real time.
<img width="1092" height="744" alt="carbon (8)" src="https://github.com/user-attachments/assets/3f224433-e03d-4d2c-ab75-0762b8f17244" />


ini adalah fungsi untuk menampilkan lokasi yang sudah dikumpulkan.
<img width="1986" height="1192" alt="carbon (9)" src="https://github.com/user-attachments/assets/af10ff30-ca8c-4ef5-952c-21ae9c70e562" />



## Berikut adalah hasilnya
Tampilan Sebelum 
![alt text](sebelum-1.jpg)

Tampilan Setelah
![alt text](sesudah-1.jpg)


# Tugas 2
## Hasil nya 
![Tugas 2](https://github.com/user-attachments/assets/3b6947a7-cba6-4a6d-9239-202c92e14c04)

 


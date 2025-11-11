# geo_project

A. new Flutter project Geolocator .
 yang harus dilakukan adalah menambahkan dependencies pada puspec.yaml
 1.geolocator: ^14.0.2
 2. geocoding: ^4.0.0

B.Menambahkan kode di AndroidManifest.xml
![alt text](image.png)
## membuat praktikum sensor maps pada aplikasi mobile

1. Import paketnya: import ’package:geocoding/geocoding.dart’;
![alt text](image-1.png)
3. Buat variabel String? currentAddress; di MyHomePageState.
![alt text](image-2.png)
4. Buat fungsi baru getAddressFromLatLng(Position position).
![alt text](image-3.png)
5.  Panggil fungsi getAddressFromLatLng( currentPosition!) di dalam getLocation
dan startTracking (di dalam .listen()) setelah setState untuk currentPosition.
![_handleGetLocation](image-4.png)
![_handleStartTracking](image-5.png)
6. Tampilkan currentAddress di UI Anda, di bawah Lat/Lng.
![alt text](image-6.png)

Hasil project praktikum
![alt text](hasilProject.jpeg)


## tugas 2 Jarak Real-time ke Titik Tetap

1. Buat variabel String? distanceToPNB; di MyHomePageState.
![alt text](image-7.png)
2. Di dalam startTracking (di dalam .listen()), panggil fungsi untuk menghitung
jarak:
![alt text](image-9.png)
3. Simpan hasilnya di distanceToPNB menggunakan setState.
![alt text](image-10.png)
4. Tampilkan distanceToPNB di UI agar jaraknya ter-update secara real-time saat
Anda bergerak
![alt text](image-11.png)

Hasil Tugas 2
![alt text](tugas2.jpeg)
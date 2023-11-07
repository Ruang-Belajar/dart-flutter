# Flutter

## Persiapan
Setup dan persiapan yang perlu dilakukan untuk memulai Flutter
- Download & Install Android Studio
  - Install _Android SDK_
  - Untuk panduan, check [Youtube: Dart & Flutter Installation (Erico Darmawan Handoyo)](https://youtu.be/asNdz10WR6w?si=ePXjDAwlqsD8POSw)
- Download & Install Visual Studio Code
  - Install extension: _Flutter_ dan _Dart_
- Download & Install [Desktop development with C++](https://visualstudio.microsoft.com/downloads/#build-tools-for-visual-studio-2022)
  - Untuk panduan, check [YouTube: Fix Flutter Doctor Visual Studio Not Installed - Please Install the Desktop Development With C++](https://www.youtube.com/watch?v=9Tux8qPK-mk)
- Download & Setup Flutter
  - [Install Flutter](https://docs.flutter.dev/get-started/install)
  - gunakan perintah `flutter doctor` untuk memeriksa kelengkapan instalasi
  - Dalam kondisi jika kita hanya mau melakukan development aplikasi Windows saja, tanpa Android, kita bisa menonaktifkan pemeriksaan `flutter doctor` terhadap _Android SDK_ lewat perintah `flutter config --no-enable-android`
- Setup HP sebagai perangkat test aplikasi
  - Masuk ke _Developer Mode_ di HP.
  - Sambungkan HP ke PC menggunakan kabel USB.
  - Set aktif mode _USB Debugging_ dan _Install via USB_. Pada saat Anda mengaktifkan opsi ini, pop-up pada layar HP akan muncul meminta ijin. Centang _Always Allow_ kemudian klik _OK_.
  - Gunakan perintah `flutter devices` pada terminal untuk mengecek apakah perangkat sudah tersambung.
  - Jika Anda melakukannya dengan benar, maka Anda akan menemukan nama model HP yang tersambung di pojok kanan bawah _VS Code_.
  - Untuk bantuan, Anda bisa check [Youtube: Running App Flutter di Handphone Langsung via kabel USB](https://www.youtube.com/watch?v=f3p6fF79k0M)



## Materi Khusus
1. [Stateless & Stateful Widget](stateless-stateful.md)

---

## Catatan Belajar
- [Widget Catalog](widget-catalog.md)
- [Contoh Layout](contoh-layout.md)

## Dokumentasi
- [Flutter Documentation](https://docs.flutter.dev/)
- [Navigate to a new screen and back](https://docs.flutter.dev/cookbook/navigation/navigation-basics)
- [Membuka URL di Flutter](https://nextgen.co.id/membuka-url-di-flutter/)

## Referensi Belajar
- [iampawan/FlutterExampleApps](https://github.com/iampawan/FlutterExampleApps)
- [Solido/awesome-flutter](https://github.com/Solido/awesome-flutter)
- [Tutorial Belajar Flutter - PT Nextgen Inovasi Indonesia](https://nextgen.co.id/tutorial-belajar-flutter)
- [Youtube: Flutter Tutorial - Flutter Fundamentals (Erico Darmawan Handoyo)](https://www.youtube.com/watch?v=SoX3cel4LRM&list=PLZQbl9Jhl-VACm40h5t6QMDB92WlopQmV)

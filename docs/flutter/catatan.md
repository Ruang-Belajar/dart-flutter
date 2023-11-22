# Catatan Pertemuan

## Pertemuan 1
- Pengenalan Dart & Flutter
- Instalasi
- check materi pelajaran di [ruang-belajar.github.io/dart-flutter](ruang-belajar.github.io/dart-flutter)
  
## Pertemuan 2
- Instalasi
- Membuat program flutter mengunakan [dartpad.dev](https://dartpad.dev)
- Membuat program sederhana, menggunakan: `Scaffold`, `Container`, `Text`, `Expand`, `Column`
  ```dart
  Scaffold(
      body: Column(
          children: [
            Expanded(
              child: Container(
                color: Colors.yellow,
                child: Text("Baris 1"),
              )
            ),
            Text("Baris 2"),
            Text("Baris 3")
          ],
        ),
    );
  ```
- Tugas: Setup Visual Studio Code sehingga bisa menjalankan program Flutter.
  Anda bisa check [Youtube: Dart & Flutter Installation (Erico Darmawan Handoyo)](https://youtu.be/asNdz10WR6w?si=ePXjDAwlqsD8POSw) untuk petunjuk _step-by-step_ instalasi.

## Pertemuan 3
- Setup Github.
- Membuat Layout [contoh-layout-1](res/contoh-layout-1.jpg)
  - Widget: `Column`, `Row`, `Expanded`, `Container`, `Text`, `Icon`, `Image`.
  - Mendaftarkan folder _assets_
  - Submit ke repositori
- Membuat Layout [contoh-layout-4](res/contoh-layout-4.png)
  - Membagi bagian-bagian ke dalam bentuk _function_
  - Submit ke repositori

## Pertemuan 4
- New Project: Layout2
- Stack
- ElevatedButton
- Multiple page view ➡️ [Navigate to a new screen and back](https://docs.flutter.dev/cookbook/navigation/navigation-basics)
- contoh: [contoh-layout-5](res/contoh-layout-5.png)

## Pertemuan 5
- Lanjutkan Layout2
- Shortcut `Ctrl+Alt+F` untuk merapihkan kode program
- Shortcut `Ctrl+.` untuk menampilkan menu bantuan memisahkan/membungkus kode program
- Memisahkan _halaman_ ke beda file
- Gunakan snippet `stless` untuk otomatis generate struktur kode widget (stateless)

## Pertemuan 6
- url_launcher
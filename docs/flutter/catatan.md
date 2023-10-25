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
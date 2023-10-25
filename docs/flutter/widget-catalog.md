# Widget Catalog
Daftar ini diambil dari [Flutter - Widget Catalog](https://docs.flutter.dev/ui/widgets). Hanya menampilkan widget yang akan dipakai umum dipakai (dalam perkuliahan).

### AppBar

**Referensi"**
- [AppBar - Flutter Docs](https://api.flutter.dev/flutter/material/AppBar-class.html)


### ElevatedButton
```dart
ElevatedButton(
  style: style,
  onPressed: () {},
  child: const Text('Enabled'),
),
```
**Referensi:**
- [ElevatedButton -  Flutter Docs](https://api.flutter.dev/flutter/material/ElevatedButton-class.html)

### Icon
```dart
Icon(
  Icons.favorite,
  color: Colors.pink,
  size: 24.0,
  semanticLabel: 'Text to announce in accessibility modes',
),
```
Daftar _icon_ yang bisa digunakan check di [Google Fonts - Material Icons](https://fonts.google.com/icons)
**Referensi:**
- [Icon - Flutter Docs](https://api.flutter.dev/flutter/widgets/Icon-class.html)


### Image
```dart
// membaca gambar dari URL
const Image(
  image: ImageNetwork('https://flutter.github.io/assets-for-api-docs/assets/widgets/owl.jpg'),
)
```
```dart
// Cara 1: membaca data dari asset
Image.asset('assets/images/lake.jpg'),
```

Untuk bisa menggunakan assets, pastikan Anda mendaftarkan folder/file aset pada file `pubspec.yaml`
```yaml
flutter:
  assets:
    - assets/
    - images/gambar1.jpg
```

**Referensi:**
[Image - Flutter Docs](https://api.flutter.dev/flutter/widgets/Image-class.html)
- [How to add image in flutter - stackoverflow](https://stackoverflow.com/questions/50903106/how-to-add-image-in-flutter)

### Scaffold
`Scaffold` adalah sebuah widget dalam flutter yang menyediakan banyak widget seperti `Drawer`, `  `, `BottomNavigationBar`, `FloatingActionButton`, `AppBar`, dan lain-lain. `Scaffold` akan memperluas atau menempati seluruh layar perangkat. Widget ini akan menempati ruang yang tersedia. `Scaffold` akan memberikan kerangka untuk menerapkan layout dasar material design dari aplikasi.
```dart
Scaffold(
  appBar: AppBar(
    title: Text('Nextgen Tutorial'),
  ),
  body: Center(
    child: Text("Selamat Datang di Nextgen Tutorial!!"),
  ),
)
```
**Referensi:**
- [Scaffold - Flutter Docs](https://api.flutter.dev/flutter/material/Scaffold-class.html?)

### Text

### Center
`Center` adalah blok pengaturan (_alignment block_) yang digunakan untuk mengatur _child_-nya pada posisi tengah.

```dart
Center(
  child: Text('Hello World'),
),
```

### Column
```dart
Column(
  children: <Widget>[
    Text('Baris 1'),
    Text('Baris 2'),
  ],
) 
```
**Referensi"**
- [Column - Flutter Docs](https://api.flutter.dev/flutter/widgets/Column-class.html)
- [Catatan Column](column.md)


### GridView
Membuat tampilan berbentuk _grid_.
**Referensi:**
- [GridView - Flutter Docs](https://api.flutter.dev/flutter/material/GridView-class.html?)

### Container
`Container` digunakan untuk "membungkus" _child_, mengatur ukuran blok area dan memberikan dekorasi seperti warna, _padding_, _border radius_.
Jika parameter `aligment` diisi, maka `Container` menyesuaikan ukuran ke _parent_.s
```dart
Container(
  padding: EdgeInsets.all(8.0),  // jarak dari border ke child
  color: Colors.blue[600], // warna background
  alignment: Alignment.center, // posisi child
  child: Text("Hello"),
)
```

**Referensi"**
- [Container - Flutter Docs](https://api.flutter.dev/flutter/widgets/Container-class.html)
- [Catatan `Container`](container.md)

### Row
**Referensi:**
- [Catatan Row](row.md)
- [Row - Flutter Docs](https://api.flutter.dev/flutter/widgets/Row-class.html)

### Expanded
Wadah yang secara otomatis mengatur ukurannya sehingga memenuhi area. Biasa digunakan sebagai _children_ `Row` dan `Column`.
```dart
Expanded(
  flex: 1,
  child: Text("Hallo")
)
```

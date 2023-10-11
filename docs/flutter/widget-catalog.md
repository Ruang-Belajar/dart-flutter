# Widget Catalog
Daftar ini diambil dari [Flutter - Widget Catalog](https://docs.flutter.dev/ui/widgets). Hanya menampilkan widget yang akan dipakai umum dipakai (dalam perkuliahan).

## Basic
### AppBar

**Referensi"**
- [AppBar - Flutter Docs](https://api.flutter.dev/flutter/material/AppBar-class.html)

### Container
**Referensi"**
- [Container - Flutter Docs](https://api.flutter.dev/flutter/widgets/Container-class.html)

### Column
```dart
const Column(
  children: <Widget>[
    Text('Baris 1'),
    Text('Baris 2'),
  ],
)
```
**Referensi"**
- [Column - Flutter Docs](https://api.flutter.dev/flutter/widgets/Column-class.html)

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
const Image(
  image: ImageNetwork('https://flutter.github.io/assets-for-api-docs/assets/widgets/owl.jpg'),
)
```
```dart
Image.asset('assets/images/lake.jpg'),
```
**Referensi:**
[Image - Flutter Docs](https://api.flutter.dev/flutter/widgets/Image-class.html)
- [How to add image in flutter - stackoverflow](https://stackoverflow.com/questions/50903106/how-to-add-image-in-flutter)


### Placeholder

### Row

### Scaffold

### Text
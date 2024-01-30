# Soal 5

Perbaiki program dibawah ini, isi bagian `______` akan program bisa dijalankan sesuai contoh. Perhatikan label _// A //B //C //D_ ...


```dart
import 'package:flutter/material.dart';

void main() {
  runApp(const MainApp());
}

class MainApp extends StatelessWidget {
  const MainApp({super.key});

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Scaffold(
        body: ______( // A
          children: [
            ______( // B
                image: NetworkImage('https://github.com/ruang-belajar/dart-flutter/raw/master/docs/res/res-14.jpg')),
            Container(
              padding: EdgeInsets.fromLTRB(30, 100, 30, 0),
              alignment: Alignment.center,
              child: ______(
                children: [ // C
                  Text('WELCOME', style: TextStyle(fontSize: 30, fontWeight: FontWeight.bold, color: Colors.white)),
                  ______( // D
                      padding: EdgeInsets.fromLTRB(30, 10, 30, 40),
                      child: Text('Your journey starts here', style: TextStyle(fontSize: 20))),
                  ______( // E
                      onPressed: () {},
                      child: ______( // F
                        width: 100,
                        padding: EdgeInsets.all(10),
                        child: ______( // G
                          mainAxisAlignment: MainAxisAlignment.center,
                          children: [
                            Icon(______.home), // H
                            Text('______'), // I
                          ],
                        ),
                      ))
                ]),
            )
          ],
        ),
      ),
    );
  }
}

```

![](res/soal5.png)
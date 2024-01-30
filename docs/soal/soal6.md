# Soal 6

Perbaiki program dibawah ini, isi bagian `______` akan program bisa dijalankan sesuai contoh. Perhatikan label _// A //B //C //D_ ...

```dart
______ 'package:flutter/material.dart'; // A

void main() {
  runApp(const MainApp());
}

class MainApp extends StatefulWidget {
  const MainApp({super.key});

  @override
  State<MainApp> createState() => _MainAppState();
}

class _MainAppState extends State<MainApp> {
  String _nomor = "";
  ______ nomor = TextEditingController(); // B
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Scaffold(
        body: Stack(
          children: [
            Image(image: AssetImage("assets/res-9.jpg")),
            Container(
                padding: EdgeInsets.all(30),
                child: Column(
                  ______: [  // C
                    Icon(Icons.mail, size: 70, color: Colors.white),
                    ______(  // D
                        decoration: InputDecoration(
                          fillColor: Colors.white,
                          filled: true,
                          border: OutlineInputBorder(),
                          labelText: 'Nomor WA',
                        ),
                        controller: nomor),
                    Padding(
                      padding: const EdgeInsets.all(10.0),
                      child: Container(
                        width: 150,
                        height: 50,
                        child: ElevatedButton(
                            style: ElevatedButton.styleFrom(
                                shape: const StadiumBorder(), backgroundColor: Colors.deepPurpleAccent),
                            onPressed: () {
                              _nomor = nomor.text;

                              // validasi
                              if (_nomor.substring(0, 1) == '0') {
                                _nomor = "62" + _nomor.substring(1);
                              }
                              if (_nomor.substring(0, 1) == "+") {
                                _nomor = _nomor.substring(1);
                              }
                              _nomor = _nomor.replaceAll(" ", "");
                              nomor.text = _nomor;
                            },
                            child: Row(
                              children: [
                                ______(Icons.send, color: Colors.white), // E
                                ______("  Send WA", style: TextStyle(color: Colors.white)),  // F
                              ],
                            )),
                      ),
                    ),
                  ],
                ))
          ],
        ),
      ),
    );
  }
}


```

![](res/soal6.png)
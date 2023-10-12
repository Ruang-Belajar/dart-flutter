# Container

```dart
Container(
    decoration: const BoxDecoration( 
        color: Colors.grey, // backgroud color
        borderRadius: BorderRadius.all(Radius.circular(10)) // border radius
        border: Border.all(width: 2, color: Colors.deepPurple) // border color
    ),
    padding: const EdgeInsets.all(10), // padding
    child: Text('Hello'),
),
```

```dart
Container(
    color: Colors.indigo[200],
    alignment: Alignment.center, // jika alignment diisi, maka otomatis akan expand memenuhi parent
    child: Column(          
        children: <Widget>[
        Text("Hello"),
        ],
    ),
),
```
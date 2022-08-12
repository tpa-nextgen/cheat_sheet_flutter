# Stack

### With Positioned

```dart 
Stack(
  children: <Widget>[
    Positioned(
      top: 0,
      left: 0,
      child: Icon(
        Icons.flutter_dash,
        size: 80,
      ),
    ),
    Positioned(
      top: 340,
      left: 250,
      child: Icon(
        Icons.flutter_dash,
        size: 80,
      ),
    ),
  ],
)
```

<img src=https://i.imgur.com/dt78zA9.png height=300>

### With Align and predefined alignment

```dart 
Stack(
  children: <Widget>[
    Align(
      alignment: Alignment.topLeft,
      child: Icon(
        Icons.flutter_dash,
        size: 80,
      ),
    ),
    Align(
      alignment: Alignment.bottomRight,
      child: Icon(
        Icons.flutter_dash,
        size: 80,
      ),
    ),
  ],
)
```

<img src=https://i.imgur.com/Kzgf3ga.png height=300>

### With Align and custom alignment

```dart 
Stack(
  children: <Widget>[
    Align(
      alignment: Alignment(-0.6, -0.8),
      child: Icon(
        Icons.flutter_dash,
        size: 140,
      ),
    ),
    Align(
      alignment: Alignment(0.9, 0.9),
      child: Icon(
        Icons.flutter_dash,
        size: 80,
      ),
    ),
  ],
)
```

<img src=https://i.imgur.com/F66Wwd0.png height=300>
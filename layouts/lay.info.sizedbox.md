# SizedBox

### With height

```dart 
Column(
  children: <Widget>[
    Icon(Icons.flutter_dash, size: 80),
    SizedBox(
      height: 100,
    ),
    Icon(Icons.flutter_dash, size: 80),
    Icon(Icons.flutter_dash, size: 80),
  ],
)
```

<img src=https://i.imgur.com/Z5TWMk1.png height=300>

### With width

```dart 
Row(
  children: <Widget>[
    Icon(Icons.flutter_dash, size: 80),
    SizedBox(
      width: 100,
    ),
    Icon(Icons.flutter_dash, size: 80),
    Icon(Icons.flutter_dash, size: 80),
  ],
)
```

<img src=https://i.imgur.com/fzXdCEw.png height=300>

### As big as possible

```dart 
Container(
  color: Colors.yellowAccent,
  child: SizedBox.expand(),
)
```

<img src=https://i.imgur.com/TMlwBvJ.png height=300>

### As small as possible

```dart 
Container(
  color: Colors.yellowAccent,
  child: SizedBox.shrink(),
)
```

<img src=https://i.imgur.com/eustKqX.png height=300>
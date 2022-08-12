# Container
## Container as a layout tool

### Child only

```dart
Container(
  color: Colors.yellowAccent,
  child: Text(
    'Hello world',
    style: TextStyle(fontSize: 48),
  ),
)
```

<img src=https://i.imgur.com/HsA0t6d.png height=300></th>

### Infinity size

```dart
Container(
  height: double.infinity,
  width: double.infinity,
  color: Colors.yellowAccent,
  child: Text(
    'Hello world',
    style: TextStyle(fontSize: 48),
  ),
)
```

<img src=https://i.imgur.com/OV5lf9D.png height=300>

### Padding

```dart
Container(
  padding: EdgeInsets.only(left: 50, top: 100),
  color: Colors.yellowAccent,
  child: Text(
    'Hello world',
    style: TextStyle(fontSize: 48),
  ),
)
```

<img src=https://i.imgur.com/0BAD8Mw.png height=300>

### Margin

```dart
Container(
  margin: EdgeInsets.only(left: 50, top: 100),
  color: Colors.yellowAccent,
  child: Text(
    'Hello world',
    style: TextStyle(fontSize: 48),
  ),
)
```

<img src=https://i.imgur.com/sDSkH8O.png height=300>

## Container as decoration

### Color

```dart
Container(
  height: double.infinity,
  width: double.infinity,
  decoration: BoxDecoration(
	color: Colors.yellowAccent,
	),
  child: Text(
    'Hello world',
    style: TextStyle(fontSize: 48),
  ),
)
```
<img src=https://i.imgur.com/GfN4F6q.png height=300>

### Border

```dart
Container(
  height: 200,
  width: 200,
  decoration: BoxDecoration(
    color: Colors.yellowAccent,
    border: Border.all(
      color: Colors.black,
      width: 3,
    ),
  ),
)
```

<img src=https://i.imgur.com/pTQGKDT.png height=300>

### Border radius

```dart
Container(
  height: 200,
  width: 200,
  decoration: BoxDecoration(
    color: Colors.yellowAccent,
    border: Border.all(
      color: Colors.black,
      width: 3,
    ),
    borderRadius: BorderRadius.all(
      Radius.circular(18),
    ),
  ),
)
```

<img src=https://i.imgur.com/YX6n2YE.png height=300>

### BoxShape

```dart
Container(
  height: 200,
  width: 200,
  decoration: BoxDecoration(
    color: Colors.yellowAccent,
    shape: BoxShape.circle,
  ),
)
```

<img src=https://i.imgur.com/CzwJwMY.png height=300>

### BoxShadow

```dart
Container(
  height: 200,
  width: 200,
  decoration: BoxDecoration(
    color: Colors.yellowAccent,
    boxShadow: const [
      BoxShadow(blurRadius: 10),
    ],
  ),
)
```

<img src=https://i.imgur.com/vbPZLxp.png height=300>

### Gradient

```dart
Container(
  height: 200,
  width: 200,
  decoration: BoxDecoration(
    gradient: LinearGradient(
      colors: const [
        Colors.yellowAccent,
        Colors.orange,
      ],
    ),
  ),
)
```

<img src=https://i.imgur.com/TEyDELP.png height=300>

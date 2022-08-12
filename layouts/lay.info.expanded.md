# Expanded

### Equal Flex

```dart 
Row(
  children: <Widget>[
    Expanded(
      child: Container(
        color: Colors.red,
      ),
    ),
    Expanded(
      child: Container(
        color: Colors.green,
      ),
    ),
    Expanded(
      child: Container(
        color: Colors.blue,
      ),
    ),
  ],
)
```

<img src=https://i.imgur.com/QMAJaAH.png height=300>

### Different Flex

```dart 
Row(
  children: <Widget>[
    Expanded(
      child: Container(
        color: Colors.red,
      ),
      flex: 3,
    ),
    Expanded(
      child: Container(
        color: Colors.green,
      ),
      flex: 2,
    ),
    Expanded(
      child: Container(
        color: Colors.blue,
      ),
      flex: 1,
    ),
  ],
)
```

<img src=https://i.imgur.com/gySSRMp.png height=300>

### Single Expanded widget

```dart 
Row(
  children: <Widget>[
    Expanded(
      child: Container(
        color: Colors.red,
        child: Text(
          'Hey',
          style: TextStyle(fontSize: 48),
        ),
      ),
    ),
    Container(
      color: Colors.green,
      child: Text(
        'Hi',
        style: TextStyle(fontSize: 48),
      ),
    ),
    Container(
      color: Colors.blue,
      child: Text(
        'Hello',
        style: TextStyle(fontSize: 48),
      ),
    ),
  ],
)
```
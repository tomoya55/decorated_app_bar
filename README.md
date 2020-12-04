# Decorated App Bar

TODO(tom): update description
Love the material AppBar? Do you want to add more color to the appbar? Here's a DecoratedAppBar.

It works just like the normal AppBar. Also with actions, back buttons, titles. So it's just your normal AppBar, but with a twist!

## Screenshots

![image](https://user-images.githubusercontent.com/7083755/43866104-e9bc98ea-9b64-11e8-9115-b2deec915dbd.png)
![image](https://user-images.githubusercontent.com/7083755/43866237-4f8e6a5e-9b65-11e8-8adf-2514a9b1e10c.png)


## Getting Started

1. Depend on it by adding this to your pubspec.yaml file: ```decorated_app_bar: ^1.22.4```

2. Import it: ```import 'package:decorated_app_bar/decorated_app_bar.dart'```

3. Replace your current AppBar (In the scaffold) to DecoratedAppBar.


```
appBar: DecoratedAppBar(
    title: Text('Flutter'),
    decoration: BoxDecoration(gradient: LinearGradient(colors: [Colors.blue, Colors.purple, Colors.red]))
  ),
```

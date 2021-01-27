# Decorated App Bar

TODO(tom): update description
Love the material DecoratedAppBar? Do you want to add more color to the DecoratedAppBar? Here's a DecoratedAppBar.

It works just like the normal DecoratedAppBar. Also with actions, back buttons, titles. So it's just your normal DecoratedAppBar, but with a twist!

## Screenshots

(TBW)
## Getting Started

1. Depend on it by adding this to your pubspec.yaml file: ```decorated_app_bar: ^1.22.4```

2. Import it: ```import 'package:decorated_app_bar/decorated_app_bar.dart'```

3. Replace your current DecoratedAppBar (In the scaffold) to DecoratedAppBar.


```
appBar: DecoratedAppBar(
    title: Text('Flutter'),
    decoration: BoxDecoration(gradient: LinearGradient(colors: [Colors.blue, Colors.purple, Colors.red]))
  ),
```

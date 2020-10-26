# Flutter animated button

![Plugin example demo](assets/normal_1.gif)![Plugin example demo](assets/strip_1.gif)



A flutter package which contains a collection of some cool and awesome button animations.

![Plugin example demo](demo.gif)


# Installing

### 1. Depend on it
Add this to your package's `pubspec.yaml` file:

```yaml
dependencies:
  flutter_animated_button: <latest_version>
```

### 2. Install it

You can install packages from the command line:

with `pub`:

```css
$ pub get
```

with `Flutter`:

```css
$ flutter packages get
```

### 3. Import it

Now in your `Dart` code, you can use:

```dart
import 'package:flutter_animated_button/flutter_animated_button.dart';
```

# Usage

You can override the `animationDuration` of animation of the button by setting its duration in each AnimatedButton class, also you can get `animationController` for animation status and animation value during the animation. You can change text style, selected  textColor and background color of button by `textStyle`,`selectedTextColor`,`unSelectedBackgroundColor` and `selectedBackgroundColor`. If you want revert animation when button already select then you can do it by `isReverse` property.

```dart
 AnimatedButton(
                width: 200,
                text: 'SUBMIT',
                isReverse: true,
                selectedTextColor: Colors.black,
                transitionType: TransitionType.BOTTOM_TO_TOP,
                textStyle: TextStyle(
                    fontSize: 28,
                    letterSpacing: 5,
                    color: Colors.white,
                    fontWeight: FontWeight.w300),
```


# Bugs or Requests

If you encounter any problems feel free to open an [issue](https://github.com/NikhilVadoliya/FlutterAnimatedButton/issues/new?template=bug_report.md). If you feel the library is missing a feature, please raise a [ticket](https://github.com/NikhilVadoliya/FlutterAnimatedButton/issues/new?template=feature_request.md) on GitHub and I'll look into it. Pull request are also welcome.

License
----

MIT License

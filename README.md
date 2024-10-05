# flutter_tailwind_colors
Tailwind CSS 3.4.13 Colors

Dart package exposing Tailwind Colors to be used in flutter in a way similar to the Material colors.

Installation
----
1. Add to your `pubspec.yaml` file:

```yaml
dependencies:
    tailwind_colors: ^0.0.3
```

2. Get the package via your IDE or via the command line by typing:
```bash
$ pub get
```

3. Import the `flutter_tailwind_colors` package
```dart
import 'package:flutter_tailwind_colors/flutter_tailwind_colors.dart';
```

How to Use
----
Tailwind Colors can be created and used in the same way as the usual Material color palette.


```dart
    // TWColors has shades starting from 50 up to 950 in increment of 50 or 100
    Color primaryColor = TWColors.emerald.shade50;
    Color secondColor = TWColors.rose.shade950;
```
TWColors features:
- slate
- gray
- zinc
- neutral
- stone
- red
- orange
- amber
- yellow
- lime
- green
- emerald
- teal
- cyan
- sky
- blue
- indigo
- violet
- purple
- fuchsia
- pink
- rose

TWColors features the Tailwind 3.4.13 color palette:
- The palette can be found on the [TailwindCSS website](https://tailwindcss.com/docs/customizing-colors)


## Use as a theme

Every colors from the TWColors palettes can be used.

```dart
return MaterialApp(
      title: 'Flutter Demo',
      theme: ThemeData(
        primarySwatch: TWColors.emrald,
      ),
      home: MyHomePage(
          title: 'Flutter Demo Home Page',
      ),
    );
```

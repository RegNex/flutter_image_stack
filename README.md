# flutter_image_stack

`FlutterImageStack` is a pure dart package for creating image stack in Flutter. This package give you a widget to easily create image stack for your need.

UI created by this package is mainly found in profile picture stacks in so many apps but it can be used at any place where you feel it will look good.

Pub Package: [flutter_image_stack](https://pub.dev/packages/flutter_image_stack)

Medium Article: [Building profile image stack in Flutter](https://medium.com/@piyushmaurya23/building-profile-image-stack-in-flutter-2156102f65dd)

## Installation

In the dependencies: section of your `pubspec.yaml`, add the following line:

```yaml
flutter_image_stack: <latest_version>
```

## Usage

```dart
import 'package:flutter_image_stack/flutter_image_stack.dart';

class MyWidget extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    List<string> images = ["image1Link", "image2Link", "image3Link", "image4Link"];
    return ImageStack(
            imageList: images,
            imageRadius: 25, // Radius of each images
            imageCount: 3, // Maximum number of images to be shown in stack
            imageBorderWidth: 3, // Border width around the images
        );
  }
}
```

## Example

View the Flutter app in the `example` directory.

## Screenshot

![Flutter Image Stack Screenshot](screenshot.png)

## Contributors

- [Etornam Sunu Bright](https://github.com/RegNex)

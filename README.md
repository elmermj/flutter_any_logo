# flutter_any_logo

A Flutter plugin that provides asset images for popular industry categories.
It includes 5 main classes, Sports, Fashion, Tech, Food, and Media, each extending their respective interface.
This plugin can be useful for projects that require industry-related images. This plugin can be useful for various
projects, such as Quizz app, Catalogs, eCommerce App, Templates, Websites, and more. It can be especially useful for projects that require industry-related images.

## Screenshots

<p align="center">
  <img src="https://user-images.githubusercontent.com/49708438/234598133-8159f94e-63ac-4dfc-acd8-bb5c7901c0da.gif" alt="Demo"/>
</p>


## Installation

Add `flutter_any_logo` as a dependency in your `pubspec.yaml` file.

```
dependencies:
  flutter_any_logo: ^1.0.0
```

Then, run `flutter pub get` in your terminal to install the plugin.

## Usage

Import the `flutter_any_logo` package in your Dart code:

```dart
import 'package:flutter_any_logo/flutter_any_logo.dart';
```

You can now use the provided `Logo` widgets to display the logos in your app. For example, to display the Instagram logo:

```dart
import 'package:flutter_any_logo/flutter_any_logo.dart';

class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return Container(
      child: Column(
        children: [
          Image(
            image: Nba.atlantaHawks,
          ),
          Image(
            image: Fashion.lvmh,
          ),
          Image(
            image: Tech.lenovo,
          ),
          Image(
            image: Food.nutella,
          ),
          Image(
            image: Media.netflix,
          ),
        ],
      ),
    );
  }
}
```


`flutter_any_logo` currently supports the following categories and logos:

### Media

- Instagram: `Media.instagram`
- Facebook: `Media.facebook`
- Twitter: `Media.twitter`
- TikTok: `Media.tiktok`

### Sports

- NBA: `Nba.atlanta`
- NFL: `Nfl.detroitLions`
- Football: `UEFA.barcelona`


### Tech

- Apple: `Tech.apple`
- Tesla: `Tech.tesla`
- Samsung: `Tech.samsung`
- Lenovo: `Tech.lenovo`

### Food

- Cocacola: `Food.cocaCola`
- Nutella: `Food.nutella`
- McDonalds: `Food.mcDonalds`
- Starbucks: `Food.starBucks`


### Fashion

- Louis Vuitton: `Fashion.lvmh`
- Dior: `Fashion.dior`
- Gucci: `Fashion.gucci`

## Contributing

Contributions to `flutter_any_logo` are welcome! If you find a bug or would like to suggest a new logo, please create an issue on the GitHub repository.

## License

`flutter_any_logo` is released under the [MIT License](https://github.com/example/flutter_any_logo/blob/main/LICENSE).


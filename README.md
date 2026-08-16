# Flutter Lab: Images & Assets

In this lab, you will learn the two primary ways to display images in a Flutter application: fetching them over the internet via a URL, and bundling them locally within your app's assets.

## Prerequisites
1. Clone this repository to your local machine.
2. Run `flutter pub get` in your terminal.
3. Verify that there is an `assets/` folder in the project root containing an image file (e.g., `img-2.webp`).
4. Launch an emulator or connect a physical device, and run the app. 

## Instructions
This exercise is split between modifying your Dart code and your project configuration file.

1. **Network Image**: Open `lib/main.dart` and locate `TODO 1`. Replace the placeholder with an `Image.network` widget to pull an image directly from a web URL.
2. **Asset Registration**: Open `pubspec.yaml` and locate `TODO 2`. Flutter requires you to explicitly declare local files before they can be used. Uncomment the assets section to register the `assets/` directory.
3. **Asset Image**: Go back to `lib/main.dart` and locate `TODO 3`. Replace the placeholder with an `Image.asset` widget, passing the local directory path to your image.

## Expected Output
When successfully completed, your screen should display two images stacked vertically: the top image fetched dynamically from the web, and the bottom image loaded locally from your project files.

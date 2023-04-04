# EverWrite
This is a Flutter application that allows users to draw on multiple sheets of paper using different colors and pen sizes. It also has the ability to erase, change the background color, take screenshots and use image recognition technology to detect drawn objects.

## Installation

1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/suprabhatrijal/everwrite
    ```

2. Download the Google Cloud Vision API JSON file.

    * Name the file `cred.json` and place it in the project main directory.

3. Install Flutter if you haven't already, here is the [official installation page](https://docs.flutter.dev/get-started/install)

4. Connect your device or start up an emulator:

    - For physical devices, make sure USB debugging is enabled and connect your device to your computer with a USB cable.
    - For emulators, you can create one using Android Studio or Visual Studio Code.


5. Run `flutter run` in the project directory:
    - Open your terminal or command prompt and navigate to the project directory.
    - Type flutter run and hit enter. The app should compile and launch on your device or emulator.

*Note*: You might need to run `flutter doctor` first to check if all necessary dependencies are installed and to configure your development environment. Follow the instructions provided by `flutter doctor` to resolve any issues.


## Features

### Draw on Multiple Sheets
The app allows users to draw on multiple sheets of paper, which can be navigated through using the navigation buttons at the bottom of the screen.

### Pen and Eraser
Users can select different colors and pen sizes to draw with, as well as erase mistakes using the eraser tool.

### Background Color
The background color can be changed to any color of the user's choice.

### Screenshots
Users can take screenshots of their drawings using the app's built-in screenshot tool.

## Acknowledgments

This project was built using the following software and libraries:

* [Flutter](https://docs.flutter.dev/)
* [DART](https://dart.dev/tools/jetbrains-plugin)
* [Android Studio](https://developer.android.com/studio)
* [Google Cloud Vision API](https://cloud.google.com/vision)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
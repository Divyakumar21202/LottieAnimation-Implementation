# Lottie Animation Implementation in Android

This repository contains a sample Android project demonstrating how to implement a Lottie animation using the `LottieAnimationView` from the Airbnb Lottie library.


## Getting Started

These instructions will help you set up and run the project on your local machine.

### Prerequisites

- Android Studio (version XYZ or higher)
- Android SDK (minimum SDK version ABC)

### Installing

1. Clone the repository to your local machine using the following command:

   ```
   git clone https://github.com/DivyaKumar21202/lottie-animation-android.git
   ```

2. Open Android Studio and select "Open an existing Android Studio project." Navigate to the cloned repository and select the project folder.

3. Build the project by clicking the "Build" button in the Android Studio toolbar or by pressing `Ctrl + F9`.

4. Run the project on an emulator or a connected device by clicking the "Run" button in the Android Studio toolbar or by pressing `Shift + F10`.

## How It Works

The project demonstrates how to integrate a Lottie animation into an Android layout using the `LottieAnimationView` widget.
The animation is loaded from a raw resource (`SplashAnimation.json`) and is set to loop continuously with autoplay enabled.

### Project Structure

- `app/src/main/res/raw/SplashAnimation.json`: The Lottie animation JSON file.
- `app/src/main/java/com/example/lottieanimation/SplashLottieActivity.java`: The activity that hosts the Lottie animation.
- `app/src/main/res/layout/activity_splash_lottie.xml`: The XML layout file for the activity, containing the `LottieAnimationView`.

## Configuration Options

You can customize the behavior of the Lottie animation by modifying the attributes of the `LottieAnimationView` in the XML layout file (`activity_splash_lottie.xml`).

- `app:lottie_rawRes`: The reference to the Lottie animation JSON file.
- `app:lottie_loop`: Set to `"true"` to make the animation loop.
- `app:lottie_autoPlay`: Set to `"true"` to make the animation play automatically when the view is loaded.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Airbnb Lottie: [GitHub Repository](https://github.com/airbnb/lottie-android)

---

Feel free to customize this README file according to your project's specific details and requirements. 
Make sure to replace placeholders like `DivyaKumar21202` with your actual GitHub username and update any other information as needed.

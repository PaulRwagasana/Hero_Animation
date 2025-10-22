# Hero Animation Demo

A Flutter widget demonstrating hero animations between two screens with interactive image transitions.

## Run Instructions

1. Ensure you have Flutter installed and set up
2. Place an image named `flippers-alpha.png` in your project's `images/` directory
3. Run `flutter pub get`
4. Execute `flutter run`

## Hero Attributes

- **tag**: Unique identifier linking hero widgets across routes
- **child**: The widget to animate between screens (typically an image)
- **flightShuttleBuilder**: Optional custom transition behavior

## Final UI

![Hero Animation Demo](https://via.placeholder.com/300x600/378CE7/FFFFFF?text=Hero+Animation+Demo+Screen)

*The demo shows a main screen with a large image that smoothly transitions to a smaller version on a blue background when tapped, then animates back when the back button is pressed.*

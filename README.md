# counter_app

This is a simple counter application built with Flutter. The app demonstrates the use of Flutter's state management using the `flutter_bloc` package.

## Features

- Increment and decrement the counter
- State management using `flutter_bloc`
- Responsive UI with `flutter_screenutil`

## Getting Started

### Prerequisites

- Flutter SDK: [Install Flutter](https://flutter.dev/docs/get-started/install)
- Dart SDK: Included with Flutter

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/The-Black-Shadow/counter_app.git
   ```
2. Navigate to the project directory:
   ```sh
   cd counter_app
   ```
3. Install dependencies:
   ```sh
   flutter pub get
   ```

### Running the App

1. Run the app on an emulator or connected device:
   ```sh
   flutter run
   ```

### Running Tests

1. Run the widget tests:
   ```sh
   flutter test
   ```

## Project Structure

- `lib/`: Contains the main application code
  - `main.dart`: Entry point of the application
  - `app.dart`: Main app widget
  - `cubit/`: Contains the `CounterCubit` for state management
  - `view/`: Contains the UI components (`CounterPage` and `CounterView`)

## Dependencies

- `flutter_bloc`: State management
- `flutter_screenutil`: Responsive UI

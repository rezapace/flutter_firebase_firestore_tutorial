# Flutter Firebase Firestore Tutorial

This project is a Flutter application demonstrating the integration of Firebase Firestore.

## Getting Started

### Prerequisites

- [Flutter SDK](https://flutter.dev/docs/get-started/install)
- [Firebase CLI](https://firebase.google.com/docs/cli)
- A Firebase project

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/flutter_firebase_firestore_tutorial.git
   cd flutter_firebase_firestore_tutorial
   ```

2. **Install dependencies:**
   ```sh
   flutter pub get
   ```

3. **Set up Firebase:**
   - Follow the [Firebase setup guide](https://firebase.google.com/docs/flutter/setup) to add Firebase to your Flutter app.
   - Place the `google-services.json` (for Android) and `GoogleService-Info.plist` (for iOS) in the respective directories.

4. **Run the app:**
   ```sh
   flutter run
   ```

### Project Structure

- `lib/main.dart`: Entry point of the application.
- `lib/pages/home_page.dart`: Home page UI and logic.
- `lib/models/todo.dart`: Todo model.
- `lib/services/database_service.dart`: Firestore database service.

### Features

- Add, update, and delete todos.
- Real-time synchronization with Firestore.

### Resources

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)
- [Flutter Documentation](https://docs.flutter.dev/)

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


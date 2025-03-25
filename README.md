# Meal Tracker App

## Description
The **Meal Tracker App** is a Flutter-based mobile application designed to help users log and track their daily meals. The app allows users to add meals with details such as name, calorie count, time of consumption, and an optional photo. It uses **Flutter Bloc (Cubit)** for state management and **Shared Preferences** for local storage, ensuring meals are saved even after restarting the app.

## Features
- **Add Meals**: Users can add meals with a name, calorie count, time, and an image.
- **View and Sort Meals**: Meals can be sorted by name, calorie count, or time.
- **Persist Data**: Uses **Shared Preferences** to save meals locally.
- **Delete Meals**: Users can remove meals, and changes are updated in local storage.
- **Image Picker Support**: Users can capture or select meal photos from their gallery.

## Technologies Used
- **Flutter** for UI development.
- **Cubit (Flutter Bloc)** for state management.
- **Shared Preferences** for data persistence.
- **Image Picker** for handling meal images.

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/meal-tracker.git
   ```
2. Navigate to the project directory:
   ```sh
   cd meal-tracker
   ```
3. Install dependencies:
   ```sh
   flutter pub get
   ```
4. Run the application:
   ```sh
   flutter run
   ```

## APK Build
To generate a release APK, use the command:
```sh
flutter build apk --release
```

## File Structure
```
meal-tracker/
│── lib/
│   ├── cubit/meal_cubit.dart   # Handles state management
│   ├── models/meal.dart        # Meal data model
│   ├── screens/home_screen.dart  # Main screen displaying meals
│   ├── screens/add_meal_screen.dart  # Screen for adding meals
│   ├── main.dart               # Entry point of the app
│── android/                    # Android-specific files
│── pubspec.yaml                 # Project dependencies
```

## Screenshots
_Add screenshots of the app here_![Simulator Screenshot - iPhone 15 - 2025-03-24 at 18 41 28](https://github.com/user-attachments/assets/c46a0267-dd41-49d8-8f8f-4ce9692c3078)

![Simulator Screenshot - iPhone 15 - 2025-03-24 at 16 47 23](https://github.com/user-attachments/assets/249b8c9a-8b59-48f2-8391-5feefde729d5)![Simulator Screenshot - i![Simulator Screenshot - iPhone 15 - 2025-03-24 at 16 46 46](https://github.com/user-attachments/assets/701d1d22-d34c-4706-abbe-d5d5a20d672e)
Phone 15 - 2025-03-24 at 16 47 13](https://github.com/user-attachments/assets/85da6222-f624-456b-9e90-3960586dd062)


## License
MIT License

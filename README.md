# Shopping List Flutter Application

This project is a simple **Shopping List** application built using **Flutter**. It allows users to add, display, and remove grocery items. The app communicates with a backend using Firebase.

## Features

- **Add New Items:** Users can add new grocery items, specifying the name, quantity, and category.
- **View Grocery List:** The main screen displays all added items in a list.
- **Remove Items:** Swipe-to-dismiss functionality allows users to remove items from the list.
- **Persistent Storage:** Items are stored and retrieved using a Firebase backend.
- **Error Handling:** The app includes error handling for failed network requests.
- **Dark Theme:** The app uses a dark theme for its UI.

## Project Structure

The project follows a clean and modular structure:

```
shopping_list/
├── lib/
│   ├── main.dart           # Entry point of the application
│   ├── models/             # Data models (Category, GroceryItem)
│   ├── widgets/            # UI screens (GroceryList, NewItem)
│   └── data/               # Predefined categories data
└── pubspec.yaml            # Project metadata and dependencies
```

## How to Run

1. Ensure that you have Flutter installed. If not, follow the [Flutter installation guide](https://docs.flutter.dev/get-started/install).
2. Clone this repository.
3. Navigate to the project directory.
4. Run `flutter pub get` to install dependencies.
5. Add a `.env` file in the root directory with your Firebase URL:

   ```
   FIREBASE_URL=your_firebase_database_url
   ```
6. Run the app using the command:

   ```
   flutter run
   ```

## Dependencies

The project uses the following dependencies:

- **`flutter`**: SDK for building cross-platform applications.
- **`cupertino_icons`**: For iOS-style icons.
- **`http`**: For making HTTP requests.
- **`flutter_dotenv`**: For loading environment variables.
- **`flutter_test`**: For writing and running tests.
- **`flutter_lints`**: For enforcing good coding practices.

## Future Enhancements

- Add the ability to edit existing items.
- Implement user authentication.
- Add filtering and sorting options for the grocery list.

⭐⭐⭐⭐⭐


# Notes Pro - Your Digital Notebook

Welcome to the Notes Pro repository! This Android app allows users to create, manage, and organize their notes using Firebase as the backend. Below, we provide an overview of key files, functionalities, and usage instructions:

## Features

- **User Authentication:** Secure user login and registration using Firebase Authentication.
- **Real-time Note Management:** Create, edit, and delete notes, with changes reflected in real-time.
- **Sorting Notes:** Display notes in descending order of their creation timestamp.
- **Logout:** Log out securely with a single click using the menu button.
- **Intuitive UI:** A clean and user-friendly interface for seamless note management.

## Files and Activities

- `CreateAccountActivity.java`: Handles user registration with Firebase Authentication.
- `LoginActivity.java`: Manages user login using Firebase Authentication.
- `MainActivity.java`: The app's main screen for viewing and managing notes.
- `Note.java`: Represents the structure of a note.
- `NoteAdapter.java`: RecyclerView adapter for displaying notes in the main activity.
- `NoteDetailsActivity.java`: Allows users to view and edit note details.
- `SplashActivity.java`: Displays a splash screen on app startup.
- `Utility.java`: Contains utility functions for interacting with Firebase.

## Getting Started

1. Clone or download the repository to your local machine.
2. Set up your Firebase project and add the `google-services.json` file.
3. Open the project in Android Studio.
4. Run the app on your Android device or emulator.
5. Register or log in to start managing your notes!

## Usage

- **Add a Note:** Click the "+" button to create a new note.
- **View/Edit a Note:** Tap on a note in the main screen to view or edit its content.
- **Delete a Note:** Swipe left on a note to reveal the delete button.
- **Logout:** Tap the menu button to access the logout option.

## Important Note

- This app utilizes Firebase for authentication and Firestore for real-time database functionality.
- Ensure your Firebase configuration is correctly set up for the app to work.
- Securely manage sensitive information like Firebase credentials and API keys.

## Resources

- [Firebase Documentation](https://firebase.google.com/docs)
- [Firestore Documentation](https://firebase.google.com/docs/firestore)
- [Firebase UI for Android](https://github.com/firebase/FirebaseUI-Android)

Feel free to explore, customize, and contribute to this project. Happy note-taking and coding!

---

*Disclaimer: This repository is for educational purposes and does not provide guarantees or warranties for any purpose. Ensure you follow best practices for security and sensitive information.*

 
SIGNUP Screen
![Screen Shot 2023-01-30 at 19 41 18_google-pixel5-justblack-portrait](https://user-images.githubusercontent.com/60041910/215503634-077226b2-005a-4368-9c13-07bb183f6cc5.png)

LOGIN Screen

![Screen Shot 2023-01-30 at 19 42 15_google-pixel5-justblack-portrait](https://user-images.githubusercontent.com/60041910/215503800-ae9c9873-b437-4050-bfd8-cc39f610a650.png)

ADD NEW NOTE Screen
![Screen Shot 2023-01-30 at 19 43 20_google-pixel5-justblack-portrait](https://user-images.githubusercontent.com/60041910/215503928-e4071c0e-4a92-43aa-b785-49aae176a7b6.png)

NOTES HOME Screen
![215493758-1819fffc-6e1e-4133-b686-15c7b461624a_google-pixel5-justblack-portrait](https://user-images.githubusercontent.com/60041910/215504096-70f8f260-6bba-4988-9aa9-39e8a9df0058.png)

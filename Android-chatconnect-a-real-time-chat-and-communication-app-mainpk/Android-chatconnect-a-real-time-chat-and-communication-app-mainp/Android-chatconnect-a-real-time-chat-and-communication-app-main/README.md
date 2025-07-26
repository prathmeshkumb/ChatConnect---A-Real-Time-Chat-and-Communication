# Chatconnect - Real-Time Chat App

Chatoon is a modern Android group chat application built with Jetpack Compose and Firebase. It allows users to register, log in, create chat rooms, and exchange messages in real time. The app features a clean UI, dynamic theming, and robust authentication.

## Features

- **User Authentication**: Register and log in with email and password using Firebase Authentication.
- **Chat Rooms**: Create and join multiple chat rooms.
- **Real-Time Messaging**: Send and receive messages instantly with Firebase Firestore.
- **User Avatars & Colors**: Each user is assigned a unique color for easy identification.
- **Modern UI**: Built with Jetpack Compose for a smooth and responsive experience.
- **Dark/Light Theme**: Supports dynamic theming based on system settings.
- **Input Validation**: Robust validation for registration and login forms.

## Screenshots

*(Add screenshots here if available)*

## Getting Started

### Prerequisites

- Android Studio (Flamingo or newer recommended)
- Android device or emulator (API 28+)
- [Firebase Project](https://console.firebase.google.com/) with Authentication and Firestore enabled

### Setup

1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/android-chatconnect-real-time-chat-app.git
   cd android-chatconnect-real-time-chat-app
   ```

2. **Firebase Configuration:**
   - Create a Firebase project.
   - Enable Email/Password Authentication.
   - Create a Firestore database in test mode.
   - Download the `google-services.json` file and place it in `app/`.

3. **Build the project:**
   - Open the project in Android Studio.
   - Let Gradle sync and download dependencies.

4. **Run the app:**
   - Connect your device or start an emulator.
   - Click **Run** in Android Studio.

## Project Structure

```
app/
 ├── src/
 │    ├── main/
 │    │    ├── java/com/example/myapplication/
 │    │    │    ├── view/           # UI screens (login, register, home, chatroom)
 │    │    │    ├── nav/            # Navigation logic
 │    │    │    ├── ui/theme/       # App theming (colors, typography)
 │    │    │    └── Constants.kt    # App-wide constants
 │    │    ├── res/                 # Resources (layouts, drawables, values)
 │    │    └── AndroidManifest.xml
 │    └── ...
 ├── build.gradle
 └── google-services.json
```

## Dependencies

- [Jetpack Compose](https://developer.android.com/jetpack/compose)
- [Firebase Authentication](https://firebase.google.com/docs/auth)
- [Firebase Firestore](https://firebase.google.com/docs/firestore)
- [AndroidX Navigation Compose](https://developer.android.com/jetpack/compose/navigation)

See [app/build.gradle](app/build.gradle) for the full list.

## Customization

- **Themes & Colors**: Modify colors in [`Color.kt`](app/src/main/java/com/example/myapplication/ui/theme/Color.kt).
- **Typography**: Adjust font styles in [`Type.kt`](app/src/main/java/com/example/myapplication/ui/theme/Type.kt).
- **Icons & Images**: Replace images in `app/src/main/res/drawable/` and `mipmap-*/`.


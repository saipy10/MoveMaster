# MoveMaster

Welcome to MoveMaster, a feature-rich chess application built using Flutter and Firebase. This app offers both multiplayer and offline gameplay options, allowing users to challenge friends or play against a powerful AI opponent, Stockfish.

## Features

- **Multiplayer Support**: Play chess games with friends or other players online.
- **Offline Support**: Enjoy chess games even without an internet connection.
- **Stockfish Integration**: Challenge yourself against the renowned Stockfish chess engine.
- **Real-time Updates**: Experience seamless, real-time game updates with Firebase.
- **User Authentication**: Secure login and registration using Firebase Authentication.
- **Cross-Platform**: Available on both iOS and Android.

## Screenshots

![Game Screen](path_to_screenshot_1)
![Multiplayer Lobby](path_to_screenshot_2)
![Game History](path_to_screenshot_3)

## Getting Started

### Prerequisites

- Flutter SDK: [Installation Guide](https://flutter.dev/docs/get-started/install)
- Firebase Project: [Setup Guide](https://firebase.google.com/docs/flutter/setup)
- Stockfish Engine: Precompiled binary or source [Download](https://stockfishchess.org/download/)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/movemaster.git
   cd movemaster
   ```

2. **Install dependencies:**

   ```bash
   flutter pub get
   ```

3. **Set up Firebase:**

   - Follow the Firebase setup guide for Flutter.
   - Add your `google-services.json` (for Android) and `GoogleService-Info.plist` (for iOS) files to the appropriate directories.

4. **Integrate Stockfish:**

   - Place the Stockfish binary in the appropriate directory within your project.
   - Ensure the app has permissions to execute the binary.

5. **Run the app:**

   ```bash
   flutter run
   ```

## Usage

### Multiplayer Mode

1. **Sign Up / Log In**: Create an account or log in using your existing credentials.
2. **Create / Join Game**: Start a new game or join an existing game from the lobby.
3. **Play**: Make your moves and enjoy real-time updates.

### Offline Mode

1. **Select Offline Mode**: Choose to play offline from the main menu.
2. **Play Against Stockfish**: Challenge the AI and improve your skills.

## Contributing

We welcome contributions to enhance this project! Here’s how you can help:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch-name`.
3. Make your changes and commit: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature-branch-name`.
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Flutter](https://flutter.dev/)
- [Firebase](https://firebase.google.com/)
- [Stockfish](https://stockfishchess.org/)

## Contact


Enjoy playing chess with MoveMaster! We hope it helps you hone your skills and provides hours of entertainment.
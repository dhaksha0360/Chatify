
Chatify

Chatify is a real-time messaging application developed using Flutter and Firebase, designed to provide a seamless communication experience. The application includes features like real-time messaging, full-text user search, media sharing, group chats, real-time status indicators, authentication, and auto-login for a user-friendly experience.

Features

Chatify allows users to send and receive messages in real time, search for other users through a full-text search mechanism, and share media files such as images and videos. Users can create and participate in group chats, view real-time status indicators such as online presence and typing status, and securely log in using Firebase Authentication. The auto-login feature ensures a seamless user experience by maintaining active sessions.

Technology Used

The frontend is built using Flutter with Dart, while the backend is powered by Firebase, leveraging services such as Cloud Firestore for real-time data, Firebase Authentication for secure login, and Firebase Storage for handling media files. Provider is used for state management.

Installation

To set up Chatify on your local machine, clone the repository using the following command:

git clone https://github.com/dhaksha0360/Chatify.git
cd chatify  

Install the required dependencies by running:

flutter pub get  

Set up Firebase by creating a project in the Firebase Console and enabling Firebase Authentication, Cloud Firestore, and Firebase Storage. Download the google-services.json file for Android and the GoogleService-Info.plist file for iOS, and place them in their respective directories: android/app and ios/Runner.

Once the setup is complete, run the application on your device or emulator. Use the command flutter run for both Android and iOS. Ensure Xcode is installed for running the app on iOS.

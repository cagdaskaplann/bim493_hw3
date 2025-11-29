# BIM493 - Mobile Programming I - Assignment #3

This repository contains the third assignment for the BIM493 Mobile Programming I course at Eskişehir Technical University, Department of Computer Engineering.

## Project Description

A real-time messaging application developed with Flutter and Firebase, featuring:
* **Real-time Messaging:** Users can send and receive messages instantly over the internet using **Firebase Firestore** backend.
* **Cloud Storage:** Messages are stored in the cloud rather than local device memory, ensuring data persistence.
* **Live Updates:** Uses `StreamBuilder` to listen to database changes and update the UI immediately when a new message arrives.
* **Timestamp Sorting:** Messages are ordered chronologically (newest at the bottom) using server-side timestamps.
* **User Interface:** Clean interface with a text input field and a scrollable list of messages, based on the `Week08_CommentList` example.

## Group Members

* **Name:** `Çağdaş Kaplan`
    **Student ID:** `41615046366`
* **Name:** `Özgün Saz`
    **Student ID:** `12125201262`
* **Name:** `Ali Görkem Sali`
    **Student ID:** `12245973452`

## How to Run

1.  Ensure you have the Flutter SDK installed.
2.  Clone this repository or extract the project zip file.
3.  Navigate to the project directory.
4.  **Important:** Ensure the `google-services.json` file is placed inside the `android/app/` directory for Firebase connectivity.
5.  Run `flutter pub get` to install dependencies (firebase_core, cloud_firestore).
6.  Run `flutter run` on a connected device or emulator.
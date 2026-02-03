# Flutter Accordion Collections UI

## Overview
This project is a Flutter UI assignment that demonstrates an
accordion-style list of product collections. Each collection card
can be expanded or collapsed to reveal product images with smooth
animations, following modern UI/UX principles.



## 🎯 Requirements Covered
- Scrollable list of collection cards
- Accordion expand/collapse behavior
- Only one collection expanded at a time
- Horizontal image preview with +N overlay
- Vertical image list on expansion
- Smooth animations
- Rounded cards with elevation



## 🛠 Tech Stack
- Flutter
- Dart
- Material UI



## 📱 UI Behavior
- Tapping a collection expands or collapses it
- When expanded, images appear vertically
- Collapsed state shows horizontal preview
- +N overlay indicates additional images



## 🧠 Approach
State is managed using a StatefulWidget by tracking the currently
expanded collection index. Flutter’s AnimatedContainer and
AnimatedCrossFade widgets are used to provide smooth UI transitions.
The project follows a clean and scalable structure.



## 📁 Project Structure
lib/
├── main.dart
├── screens/
│   └── collections_screen.dart
├── widgets/
│   └── collection_card.dart
├── models/
│   └── collection_model.dart
└── data/
    └── dummy_data.dart

## ▶️ How to Run
```bash
flutter pub get
flutter run

## 👩‍💻 Author
Bhavana Kulkarni

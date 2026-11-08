# Web View App

Simple Flutter app that opens any website inside the app with `webview_flutter`. Type a URL in the address bar (`https://` is added automatically) and browse — a starting point for turning a website into a mobile app.

## Stack
Flutter · webview_flutter

## Run
```bash
flutter pub get
flutter run
```
To ship a fixed website as an app, change the start URL in `lib/main.dart` (currently `https://flutter.dev`).

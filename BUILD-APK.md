# Build the Android APK

1. Install Node.js 20+.
2. Install EAS CLI: `npm install -g eas-cli`.
3. Create an Expo account and run `eas login`.
4. Enter `mobile/`.
5. Copy `.env.example` to `.env`.
6. Put your Google Maps Android API key in `EXPO_PUBLIC_GOOGLE_MAPS_API_KEY`.
7. Run `npm install`.
8. Run `eas build:configure` if EAS asks for project setup.
9. Run `eas build -p android --profile preview`.
10. When the cloud build finishes, EAS provides the APK build page/link. Download the APK to the Android phone and install it.

The API must be hosted on an address reachable by the phone. For local Wi-Fi testing, use the computer's LAN IP, not `localhost`.

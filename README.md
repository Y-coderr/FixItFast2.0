# FixItFast2.0

**On-Road Vehicle Breakdown Assistant**

An Android application that lets users pin their location when their vehicle breaks down, helping rescue teams locate them more easily. Users also receive real-time notifications from the rescue team.

---

## 🛠️ Features

- Pin your current GPS location with a tap when your vehicle breaks down  
- Rescue teams can see your location and respond  
- Receive push notifications / alerts from rescue team  
- Firebase integration for backend & push messaging  
- Google Maps API for map & location services  

---

## 🧩 Technologies & Tools

- Android (Java / Kotlin)  
- Google Maps API  
- Firebase (Realtime Database / Cloud Messaging / Authentication etc.)  
- Gradle build system  

---

## 🚀 Setup & Installation

1. **Clone / prepare the code**  
   ```
    https://github.com/Y-coderr/FixItFast2.0.git

2. **Add your Google Maps API Key**  
   In your `local.properties` (or appropriate config), include:

3. **Add Firebase config file**  
Place the `google-services.json` downloaded from Firebase into the `app/` folder.

4. **Build & Run**  
Open the project in Android Studio (or your IDE of choice), sync Gradle, and run on an emulator or device.

---
## 📲 Download Mobile Ready Application (.apk)

[⬇️ Click here to download the latest FixItFast APK](https://github.com/Y-coderr/FixItFast2.0/tree/main/app-release)



## 🧭 Usage

1. Launch the app on your Android device.  
2. When your vehicle breaks down, press the “Pin Location” or equivalent button.  
3. The app sends your location to the backend / Firebase.  
4. Rescue teams (or admins) receive location details and send notifications.  
5. You’ll receive notifications with updates or arrival status.

---

## ⚠️ Notes & Best Practices

- **Do not commit** your `google-services.json` or any API keys to a public repository.  
- Use environment variables or local config for sensitive credentials.  
- Make sure location permissions are requested at runtime on Android 6.0+  
- Enable appropriate security rules in Firebase to restrict access.

---

## 🗂️ Acknowledgements

This project builds upon:
- Google Maps Platform  
- Firebase services  
- Android open-source libraries  

---

## 📬 Contact / Support

If you have questions, face issues, or would like to contribute, feel free to reach out or open issues / pull requests.  

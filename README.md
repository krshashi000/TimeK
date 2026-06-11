TimeK 🕒

A beautiful, minimalist Android Live Wallpaper that visualizes your year at a single glance. Inspired by the "OneDot" aesthetic, TimeK replaces your standard background with a dynamic 12-month dot calendar, showing you exactly how much of the year has passed to remind you to Make It Count.

✨ Features

Dynamic 12-Month Calendar Grid: Watch the year fill up day by day with bright, luminous green dots against a deep forest green background.

Accurate Calendar Math: The grid automatically aligns with the correct days of the week for every month, complete with leap-year support.

Customizable Week Start: Choose whether your calendar weeks start on Sunday or Monday.

Massive iOS-Style Clock: Toggle a giant, frosted-glass style clock on your lock screen, or turn it off for a more compact date/time header.

Progress Tracking: Always know exactly where you stand with a live counter showing the exact number of days left and the percentage (%) of the year completed.

Battery Friendly: The wallpaper service is highly optimized, redrawing the canvas only once per minute to preserve battery life.

🛠️ Built With

Kotlin

Android Canvas API (for high-performance wallpaper rendering)

Jetpack Compose (for the sleek installer UI and settings)

Note: This project is a heavily customized fork, originally based on the LifeDots repository by humonious17.

🚀 Installation & Setup

To install TimeK on your Android device, you will need to build the APK from the source code.

1. Build the APK (Android Studio)

Clone this repository to your local machine:

git clone [https://github.com/YourUsername/TimeK.git](https://github.com/YourUsername/TimeK.git)


Open the project in Android Studio.

Let Gradle sync and download dependencies.

From the top menu, go to Build > Build Bundle(s) / APK(s) > Build APK(s).

Once finished, locate the app-debug.apk file in app/build/outputs/apk/debug/.

2. Install on Your Phone

Transfer the app-debug.apk to your Android phone.

Tap the file to install it (you may need to allow "Install from unknown sources" in your settings).

Open the TimeK app from your app drawer.

Configure your settings (Clock size, Sunday/Monday start).

Tap Apply Wallpaper and select whether you want it on your Home Screen or Lock Screen.

⚠️ Special Note for Xiaomi/MIUI/HyperOS Users

If you are trying to install directly via USB debugging from Android Studio and getting an INSTALL_FAILED_USER_RESTRICTED error:

Go to your phone's Developer Options.

Turn on Install via USB (requires a Mi Account and SIM card).

Try running the app from Android Studio again.

📜 License

This project is open-source and available for customization. Feel free to fork it and make it your own!
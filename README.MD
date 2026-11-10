# Fear & Hunger — Android Edition

An optimized, fully stable Android build of *Fear & Hunger*, built to eliminate performance bottlenecks and freeze issues found in existing mobile ports (inspired by [Chokage's Fear-And-Hunger-Android-Application](https://github.com/Chokage/Fear-And-Hunger-Android-Application) project).

## Key Improvements

* **Critical Hit Performance Fix:** Resolved the severe 500–1000ms Main Thread freeze on critical hits. Replaced CPU-bound Canvas pixel blending (`setBlendColor`) in `rpg_sprites.js` with GPU-accelerated `tint` and `scale` transformations.
* **Modern Android Compatibility:** Cleaned up and updated `index.html` dependencies for smooth execution on modern Android WebView containers (Android 12–14+) without frame drops.
* **Expanded Touch & Controls:** Fully customizable and expanded on-screen touch controller layout for better ergonomics across various screen sizes. All PC default buttons are available!
* **Community Fixes & QoL:** Integrated essential community patches and quality-of-life improvements while keeping core game files and logic completely intact. Such as: "https://www.youtube.com/watch?v=7nkl8lOYhos"

## Downloads

* **`fear_hunger.apk`** — Clean production build optimized for maximum performance.
* **`fear_hunger_eruda.apk`** — Developer build featuring an integrated [Eruda](https://github.com/liriliri/eruda) mobile console for testing and debugging. Very helpful if you're having issues with mods or the client on your device!

## Installation

Simply download and install the preferred APK on your Android device. No additional steps required!

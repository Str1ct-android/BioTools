# 🧬 BioTools - Android Bio Link Builder

![Kotlin](https://img.shields.io/badge/Kotlin-1.9.0-purple?logo=kotlin)
![Compose](https://img.shields.io/badge/Jetpack%20Compose-Material3-blue?logo=android)
![Platform](https://img.shields.io/badge/Platform-Android-green)

**BioTools** is a powerful "No-Code" Android application that allows you to create, customize, and deploy personal bio websites (link-in-bio) directly to **GitHub Pages**.

It features a custom graphics engine that translates Android **AGSL Shaders** into **WebGL** code, ensuring your website looks exactly 1:1 like the app preview.

<!-- СКРИНШОТЫ -->
<p align="center">
  <img src="screenshots/editor.png" width="24%" />
  <img src="screenshots/shaders.png" width="24%" />
  <img src="screenshots/preview.png" width="24%" />
  <img src="screenshots/web.png" width="24%" />
</p>

## ✨ Features

### 🎨 Visual Engine
*   **Live Shaders:** Real-time backgrounds (Matrix Rain, Digital Noise) powered by **AGSL** (Android) and **WebGL** (Web).
*   **Customizable:** Adjust speed, zoom, colors, and border radius instantly.
*   **Code Editor:** Write your own GLSL shader effects.

### 🔗 Content Management
*   **Link Editor:** Add links with custom icons (upload your own) or presets.
*   **Smart Styling:** Choose between Fill, Outline, and Glassmorphism button styles.
*   **Sortable:** Easily reorder your links.

### ☁️ Cloud & Deploy
*   **GitHub Integration:** Full OAuth 2.0 login.
*   **One-Click Publish:** Automatically creates a repo, uploads `index.html` + `config.json`, and enables **GitHub Pages**.
*   **Sync:** Restore your profile settings on any device via GitHub.

### 🧩 Widgets
*   **Last.fm:** Real-time music widget showing your current track.
*   **GitHub Graph:** Displays your contribution calendar on your site.
*   **SEO:** Custom meta tags and descriptions.

## 📥 How to Install

1.  Go to the **[Releases](../../releases)** page of this repository.
2.  Download the latest **`BioTools.apk`** file.
3.  Open the file on your Android device.
4.  If prompted, allow installation from unknown sources.
5.  Launch the app and start building your site!

## 🛠 Tech Stack (Under the hood)

*   **Language:** Kotlin
*   **UI:** Jetpack Compose (Material 3)
*   **Architecture:** MVVM + Clean Architecture
*   **Database:** Room (SQLite)
*   **Networking:** Retrofit + OkHttp (GitHub REST API)
*   **Graphics:**
    *   Android: `RuntimeShader` (AGSL)
    *   Web Export: Custom GLSL generator for WebGL
*   **Image Loading:** Coil (GIF support)

---
*Created with ❤️ by [STR@CT](https://github.com/Str1ct-Android)*
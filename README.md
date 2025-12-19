# 🧬 BioTools - Android Bio Link Builder

![Kotlin](https://img.shields.io/badge/Kotlin-1.9.0-purple?logo=kotlin)
![Compose](https://img.shields.io/badge/Jetpack%20Compose-Material3-blue?logo=android)
![Platform](https://img.shields.io/badge/Platform-Android-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

**BioTools** is a powerful "No-Code" Android application that allows users to create, customize, and deploy personal bio websites (link-in-bio) directly to **GitHub Pages**. 

It features a custom graphics engine that translates Android **AGSL Shaders** into **WebGL** code, ensuring the website looks exactly 1:1 like the app preview.

<!-- ВСТАВЬ СЮДА СКРИНШОТЫ (См. инструкцию ниже) -->
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
*   **Code Editor:** Built-in shader code editor for advanced users.

### 🔗 Content Management
*   **Link Editor:** Add links with custom icons (upload your own) or presets.
*   **Smart Styling:** Choose between Fill, Outline, and Glassmorphism button styles.
*   **Drag & Drop:** Reorder links easily.

### ☁️ Cloud & Deploy
*   **GitHub Integration:** Full OAuth 2.0 login.
*   **One-Click Publish:** Automatically creates a repo, uploads `index.html`, and enables **GitHub Pages**.
*   **Sync:** Saves `config.json` to the cloud. Restore your profile on any device.

### 🧩 Widgets
*   **Last.fm:** Shows current playing track (Real-time).
*   **GitHub Graph:** Displays your contribution calendar.
*   **SEO:** Custom meta tags and descriptions.

## 🛠 Tech Stack

*   **Language:** Kotlin
*   **UI:** Jetpack Compose (Material 3)
*   **Architecture:** MVVM + Clean Architecture
*   **Database:** Room (SQLite)
*   **Networking:** Retrofit + OkHttp (GitHub REST API)
*   **Graphics:**
    *   Android: `RuntimeShader` (AGSL)
    *   Web Export: Custom GLSL generator for WebGL
*   **Image Loading:** Coil (GIF support)

## 🚀 How to Build

1.  Clone the repository.
2.  Open in **Android Studio**.
3.  **Important:** You need to provide your own API Keys.
    *   Go to `data/network/GitHubConstants.kt` and add your **GitHub Client ID/Secret**.
    *   Go to `generator/HtmlGenerator.kt` and add your **Last.fm API Key**.
4.  Build and Run.

## 📱 Screenshots

| Editor | Matrix Effect | Preview Mode | Generated Site |
|:---:|:---:|:---:|:---:|
| <img src="screenshots/editor.png" width="200"/> | <img src="screenshots/shaders.png" width="200"/> | <img src="screenshots/preview.png" width="200"/> | <img src="screenshots/web.png" width="200"/> |

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
*Created with ❤️ by [Your Name](https://github.com/YourUsername)*

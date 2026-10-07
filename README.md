# GalleryTaskApp

A modern, responsive Android application that displays a collection of images in a clean, scrollable two-column grid layout built with Kotlin and XML.

---

## 📱 Features

- **Grid Layout**: Displays photos seamlessly in a balanced 2-column structure using `GridLayout`.
- **Smooth Scrolling**: Integrated with `ScrollView` to support fluid browsing for multiple media items.
- **Responsive UI**: Scales across various screen densities and device orientations.
- **Lightweight & Fast**: Built using native Android UI components for optimal performance.

---

## 🛠️ Tech Stack & Tools

- **Language**: Kotlin
- **UI Framework**: XML Layouts (`GridLayout`, `ScrollView`, `ImageView`)
- **IDE**: Android Studio
- **Minimum SDK**: API 21 (Android 5.0 Lollipop) or higher
- **Build System**: Gradle (Kotlin DSL / Groovy)

---

## 📂 Project Structure

```text
app/
 ├── src/
 │    └── main/
 │         ├── java/com/example/gallerytaskapp/
 │         │    └── MainActivity.kt
 │         ├── res/
 │         │    ├── drawable/        # Image assets (ani1, ani2, ani3, etc.)
 │         │    └── layout/
 │         │         └── activity_main.xml
 │         └── AndroidManifest.xml
 └── build.gradle.kts

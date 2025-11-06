# ProfileApp (Simple Android Profile Viewer)

A simple, two-screen Android application built with Kotlin. This app demonstrates basic navigation between activities and the use of ViewBinding.

## 📝 Description

This project consists of two screens:

1.  **Main Screen (`MainActivity`):** Displays a central profile image with a short caption underneath.
2.  **Detail Screen (`DetailActivity`):** When the user taps the image on the main screen, this screen opens to display static profile details (Name, Email, and Phone).

## ✨ Features

* **Clean UI:** Simple and focused layout using `LinearLayout`.
* **ViewBinding:** Uses modern Android ViewBinding to safely access UI components (instead of `findViewById`).
* **Activity Navigation:** Demonstrates basic navigation from one `Activity` to another using an `Intent`.
* **Resource Management:** Uses `strings.xml` for all user-facing text.

## 🛠️ Tech Stack

* **Language:** Kotlin
* **Toolkit:** Android SDK
* **UI Layout:** XML
* **Architecture:** ViewBinding

## 🚀 How to Run

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YOUR_USERNAME/ProfileApp.git](https://github.com/YOUR_USERNAME/ProfileApp.git)
    ```
    *(Remember to replace `YOUR_USERNAME` with your GitHub username)*

2.  **Open in Android Studio:**
    * Open Android Studio.
    * Select "Open an Existing Project".
    * Navigate to the cloned `ProfileApp` directory and open it.

3.  **Add Profile Image:**
    * Find or create an image (e.g., `avatar.png`).
    * Place this image inside the `app/src/main/res/drawable/` directory.
    * Rename the image to `profile_placeholder.png` (or update the `android:src` tag in `activity_main.xml` to match your image name).

4.  **Sync & Run:**
    * Let Android Studio sync the Gradle files.
    * Select an emulator or connect a physical device.
    * Click the "Run" button.

## 📱 Screenshots

*(Optional: Add screenshots of your app here!)*

| Main Screen | Detail Screen |
| :---: | :---: |
| 

[Image of Main Screen]
 | 

[Image of Detail Screen]
 |
 

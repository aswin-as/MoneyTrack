

📱 Android Project Setup Guide

This guide will help beginners clone this project from GitHub and run it in Android Studio.


---

🔽 Step 1: Clone the Project

1. Open Android Studio.


2. On the Welcome Screen, click "Get from VCS" (Version Control).

If a project is already open, go to File > New > Project from Version Control.



3. In the dialog:

Select Git.

Paste the GitHub repository URL:


https://github.com/aswin-as/MoneyTrack.git


4. Choose the folder location on your system.


5. Click Clone.




---

⚙️ Step 2: Sync Gradle

After cloning, Android Studio will automatically try to sync Gradle.

Wait for all dependencies to download (this may take some time depending on internet speed).

If prompted, click "Sync Now".



---

▶️ Step 3: Run the Project

1. Connect an Android device (with USB debugging enabled) OR start an Android Emulator from AVD Manager.


2. Click the green Run ▶️ button on the top toolbar in Android Studio.


3. The app will build and launch on your device/emulator. 🎉




---

❗ Troubleshooting

If you get errors during sync:

Make sure you have the latest Android Studio and SDK tools installed.

Check your internet connection for Gradle dependencies.

If needed, click File > Invalidate Caches / Restart.




---

📂 Project Structure

app/ → Main application code

build.gradle → Project dependencies and build setup

AndroidManifest.xml → App configuration



---

📌 Requirements

Android Studio Giraffe (or newer)

Java 11+

Gradle (comes with Android Studio)

Internet connection (for dependencies)





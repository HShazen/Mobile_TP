# Lab 1 – Getting Started with Android Studio

## Objectives
- Install and configure Android Studio.  
- Create a simple Android project.  
- Understand the structure of an Android project.  
- Run and customize your first Android app.

---

## Part 1: Installing Android Studio
1. Go to the official website: [https://developer.android.com/studio](https://developer.android.com/studio)  
2. Download Android Studio for your operating system (Windows, Linux, or macOS).  
3. Install it using the default options (SDK + Android Virtual Device).  
4. On first launch:
   - Choose a theme (light or dark).  
   - Check that the Android SDK is installed (`File → Settings → Android SDK`).  
   - Download an SDK version (API 33 or API 34 is recommended).

---

## Part 2: Creating Your First Project
1. Open Android Studio → **New Project**.  
2. Select **Empty Activity**.  
3. Configure the project:
   - **Name:** HelloWorldApp  
   - **Language:** Java  
   - **Minimum SDK:** API 21 or higher  
4. Click **Finish**.

---

## Part 3: Exploring the Project Structure
- **manifests:** Contains the `AndroidManifest.xml` file.  
- **java:** Contains the source code.  
- **res:** Contains resources (layouts, strings, colors, images, etc.).  
- **Gradle Scripts:** Contains Gradle configuration files.

---

## Part 4: Modify and Run the App
1. Open `res/layout/activity_main.xml`.  
2. Find the `TextView` widget and change its text to:  

# TaskShedulerApp

## About  
This is an Android application designed for managing daily tasks with a custom calendar view. It features task creation, weekly navigation, and Firebase integration for data storage and management.  

---

## Setup Guide  

Follow these steps to set up and run the project:  

### Prerequisites  
Ensure you have the following installed on your system:  
- **Android Studio**: Latest version recommended.  
- **Java JDK**: Version 8 or higher.  
- **Gradle**: Comes with Android Studio (ensure it is updated).  
- **7-Zip**: For extracting `.7z` files if not already extracted.  

---

### Steps to Set Up  

1. **Download the Repository**  
   - Clone the repository using Git:  
     ```bash
     git clone https://github.com/MemonFaizan/TaskShedulerApp.git
     ```  
     OR  
     - Download the `.7z` file from the repository and extract it using [7-Zip](https://www.7-zip.org/).  

2. **Open the Project in Android Studio**  
   - Launch Android Studio.  
   - Click on **File > Open**.  
   - Navigate to the extracted project folder and select it.  

3. **Sync Gradle Files**  
   - Once the project opens, Android Studio will prompt you to sync Gradle.  
   - Click on "Sync Now."  
   - Ensure that all dependencies are downloaded without errors.  

4. **Configure Firebase**  
   - Go to the [Firebase Console](https://console.firebase.google.com/).  
   - Create a new project (if not already created).  
   - Add an Android app to the Firebase project using your app's package name.  
   - Download the `google-services.json` file from Firebase.  
   - Place the `google-services.json` file in the `app/` directory of the project.  

5. **Build the Project**  
   - In Android Studio, go to **Build > Clean Project**.  
   - Then, click on **Build > Rebuild Project**.  

6. **Run the Application**  
   - Connect your Android device via USB or set up an emulator.  
   - Click on the green "Run" button in Android Studio or press `Shift + F10`.  

---

### Troubleshooting  
- **Gradle Sync Issues**:  
  Ensure you have a stable internet connection and the correct Gradle version is installed.  
- **Firebase Errors**:  
  Verify the `google-services.json` file is correctly placed and the Firebase dependencies are included in `build.gradle`.  

---

## Features  
- Add, update, and delete tasks dynamically.  
- Navigate through a custom weekly calendar.  
- Integrated Firebase backend for seamless data storage.  
- Intuitive Material Design user interface.  

---

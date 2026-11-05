BMC Finals Biodata Firebase
An Android application project.

Requirements
Android Studio
Git
An Android device or emulator
A Firebase account, if the app requires Firebase
Download the project
Clone the repository:

bash
git clone https://github.com/Inanomercy/BMCFinalsBiodataFirebase.git

Or download it as a ZIP file from the GitHub repository page and extract it.

Open in Android Studio
Open Android Studio.
Select File → Open.
Select the downloaded project folder. If that folder does not contain the Gradle project files, open the myapp folder instead.
Wait for Gradle sync to finish. Install any Android SDK components Android Studio requests.
Configure Firebase
If the app uses Firebase:

Find the app’s applicationId in its Gradle file.

In the Firebase Console, create or select a Firebase project.

Register an Android app using the exact applicationId.

Download google-services.json.

Put the file in the app module folder, usually:

text
myapp/app/google-services.json

Enable any Firebase services the app needs in the Firebase Console.

Run the app
In Android Studio, select an emulator or connect an Android device with USB debugging enabled.
Click Run.
Build a debug APK
From the folder containing the Gradle wrapper, run:

bash
./gradlew assembleDebug

On Windows, run:

bat
gradlew.bat assembleDebug

The APK is usually created in the app module’s build/outputs/apk/debug/ folder.

Repository
https://github.com/Inanomercy/BMCFinalsBiodataFirebase


# how-to-change-your-app-icon-with-capacitor
How to change your App icon with Angular Capacitor
![ScreenShot](/ios-11-icons-giuliosmedile.jpg)

So you have to change all the image in the generated folder android\app\src\main\res\mipmap[…] with my app icon

<h2>Sync your web code to your project</h2>
Once you've created your native projects, you can sync your web application to your native project by running the following command.

```
npx cap sync
```

Opening the Android Project
To open the project in Android Studio, run:

```
npx cap open android
```
Alternatively, you can open Android Studio and import the android/ directory as an Android Studio project.

Running Your App
You can either run your app on the command-line or with Android Studio.

Running on the Command-Line
To run the project on a device or emulator, run:

```
npx cap run android
```

The command will prompt you to select a target.

Running with Android Studio
In Android Studio, first select the device or emulator and then click the run or debug button to run your app. Unless you're debugging Java or Kotlin code, the run button is preferred.

![ScreenShot](/running-a42ce0daf3b9d2dd5ee6b94d1c378220.png)

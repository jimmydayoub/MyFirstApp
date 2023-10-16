1. The system specs running React Native currently are:

Processor	12th Gen Intel(R) Core(TM) i5-1235U   1.30 GHz
Installed RAM	8.00 GB (7.68 GB usable)
System type	64-bit operating system, x64-based processor
(Windows 10)

2,3. First, we must install node.js. Without it, the " npx react-native@latest init MyFirstApp" command will not work. After that, you can install React Native. To do this, install Android Studio and make sure the SDKs are correct. The SDKs you need are Android API 34, Android SDK Build-Tools 34. Android Emulator, Intel accelerator, Android SDK Platform 34. After that, add the variables. ANDROID_HOME as the variable name, and it's installation path as the path.


4. To make a new project, we will run npx react-native@latest init MyFirstApp. Make sure that you are currently cd in the folder you want the project to be in. When it is done, you might get a notification saying that your npm needs to be updated. If that is the case, run npm i -g npm. After that, you can open it in VSCode. Go to App.tsx and change it to .jsx, with removing all red lines if you want to switch to JSX.


5. To run the emulator, go to Device Manager and select your emulator. Press the play button on it and it will be emulated. To run the project, open Android Studio and press open file. Direct it to your android folder inside your project directory. Then, press build. Once building is done, run it.

6. If you get the metro not running error, run npm run start in the cmd of your app to make it work. Make sure to press r to reload the app.

7. https://reactnative.dev/docs/environment-setup


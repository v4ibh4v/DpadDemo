To build DpadDemo sources you will need: 
1) Download android sdk from https://developer.android.com/sdk/installing/index.html?pkg=tools
2) Set ANDROID_HOME to the path of Android sdk folder
3) Open Android SDK manager and install
  - Tools/Android SDK Build-tools 23.0.3
  - Android 6.0 (API 23)
  - Extras/Android Support Repository
  - Extras/Google Repository

DpadDemo uses gradle as build system.
Here are commands to build and install the project from command line:
1) Assemble only debug apk: ./gradlew assembleDebug
2) Install debug apk on connected device: ./gradlew installDebug  

Devices having D-pad are not easily available so to test this project on emulator 

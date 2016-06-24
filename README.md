## Build
To build DpadDemo sources you will need to: 

1.  Download android sdk from https://developer.android.com/sdk/installing/index.html?pkg=tools
2.  Set ANDROID_HOME to the path of Android sdk folder
3.  Open Android SDK manager and install
  - Tools/Android SDK Build-tools 23.0.3
  - Android 6.0 (API 23)
  - Extras/Android Support Repository
  - Extras/Google Repository

DpadDemo uses gradle as build system.
Here are commands to build and install the project from command line:

1.  Assemble only debug apk: ./gradlew assembleDebug
2.  Install debug apk on connected device: ./gradlew installDebug  

## Test
Devices having D-pad are not common these days so to test this project on emulator 
you will need to do the following:

1.  Run the app and you get to see 'Select Deployment Target' dialog.
2.  Click 'Create New Emulator' then select a device and click 'Clone Device'
3.  On the 'Hardware Profile Configuration' window check both the checkboxes in 'Input' row and the select 'D-pad' from 'Navigation Style' dropdown.
4.  Click 'Finish' and you are done.
5.  When emulator opens up, you can click more options and go to Directional pad tab to use it.

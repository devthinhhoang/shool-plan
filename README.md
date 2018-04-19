# shool-plan
app example
# Create your first Cordova app
npm install -g cordova
# Create the App
cordova create hello com.example.hello HelloWorld
# Add Platforms
cordova platform add android
# Install pre-requisites for building
Requirements check results for android:
Java JDK: installed .
Android SDK: installed
Android target: installed android-19,android-21,android-22,android-23,Google Inc.:Google APIs:19,Google Inc.:Google APIs (x86 System Image):19,Google Inc.:Google APIs:23
Gradle: installed

Requirements check results for ios:
Apple OS X: not installed
Cordova tooling for iOS requires Apple OS X
Error: Some of requirements check failed

# Build the App
	# Android
		cordova build android
# Test the App
	# start emulator
	cordova run --emulator
	cordova run android



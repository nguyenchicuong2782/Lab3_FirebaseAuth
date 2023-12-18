scoop install nodejs-lts openjdk17 android-clt
corepack enable

yarn create expo

yarn expo prebuild

"Add file google-services.json to ./android/app/"

"Sign out"

sdkmanager --licenses

sdkmanager --install platform-tools

"adb connect"

yarn android

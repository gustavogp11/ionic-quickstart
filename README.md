# Quickstart
A simple template for ionic with android (working example taken from Ionic tutorials)

## Installation links followed to intall the app and set android:
_Note: instead of using `ionic cap open android` follow the steps from #3 to generate the apk without opening Android Studio_
1. https://ionicframework.com/docs/intro/cli
2. https://ionicframework.com/docs/angular/your-first-app/deploying-mobile
3. Execute `ionic capacitor build android --no-open`
4. `cd android`
5. `./gradlew assembleDebug`

## Steps to install ionic and create the project with android
1. `npm install -g @ionic/cli`
2. `ionic start`
3. `cd app-name`
4. `ionic cap add android`
5. `ionic cap copy`
6. `ionic cap sync`
7. `ionic cap build android --no-open`
8. `cd android/`
9. `./gradlew assembleDebug`

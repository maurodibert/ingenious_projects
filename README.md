
![logo](assets/images/icon.png)
# imTracker
Determine whether lifestyle factors might be associated with daily outcomes.

![demo](assets/gifs/demo.gif)

## :pencil: How to Use 
**Step 1:**
Download or clone this repo.

**Step 2:**
Go to project root and execute the following command in console to get the required dependencies: 
```
flutter pub get 
```
**Step 3:**
Run the app
```
flutter run
```
**APK:**
Just download and run in device
```
final_builds/app-release.apk
```

## :wrench: Libraries & Tools
* *[SQFlite](https://pub.dev/packages/sqflite)*, for local storage.
* *[Provider](https://pub.dev/packages/provider)*, for state management.
* *[Get It](https://pub.dev/packages/get_it)*, for dependency injection.
* *[Flutter Icon](https://www.fluttericon.com/)*, to make icons' usage really easy.
* *[Validated](https://pub.dev/packages/sqflite)*, for emojis and strings validation.
* *[CSV](https://pub.dev/packages/csv)* and *[share](https://pub.dev/packages/share)*, for exporting CSV files.
* *[Splash Screen](https://pub.dev/packages/splashscreen)*, for rapid fire splashScreen creation.
* *[Flutter Native Timezone](https://pub.dev/packages/flutter_native_timezone)*, to get local timezone.
* *[Flutter Local Notification](https://pub.dev/packages/flutter_local_notifications)*, for obvious reasons!.



## :mag: Structure
With the separation of concerns in mind, I've built the application applying an MVVM architectural pattern, following the next folder structure:
```
lib
└── core
    └── helpers
    └── models
    └── services
    constants
└── ui
    └── library: reusable components
    └── screens
        └── views: particular UI
        screen: UI
        viewModel: logic

```
At the same time, the code is categorized to make the maintenance easier and pleasurable; 
from scratch, perhaps, could be a little bit cumbersome for an app this small, but as soon as it gets bigger
will make for devs, life much more comfortable. 

## :gift: Features
- Local DataBase
- Emoji validation
- CSV exportation
- URL launcher
- Local Notifications
- Alarm setter
- Timezones checker
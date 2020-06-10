# flutter
## Officials
### https://flutter.dev/docs/reference/tutorials
## Labs
### https://codelabs.developers.google.com/codelabs/first-flutter-app-pt1
## Courses
### https://www.appbrewery.co/p/intro-to-flutter
### https://www.pluralsight.com/search?q=flutter
### https://codelabs.developers.google.com/codelabs/google-photos-sharing/index.html?index=..%2F..index#0
## Prerequisites
### Dart
### https://codelabs.developers.google.com/codelabs/from-java-to-dart/index.html?index=..%2F..index#0
### Turn off Hyper-V
![Turn off Hyper-V](https://snipboard.io/iwCyha.jpg)
## Lab
### https://codelabs.developers.google.com/codelabs/google-maps-in-flutter/index.html?index=..%2F..index
## Tools
### flutter sdk
### choco install androidstudio
### AVD Manager
### https://rive.app/
### https://appicon.co/
### https://icons8.com/ouch
### https://www.vecteezy.com/
### https://www.canva.com/
### https://pub.dev/packages/flutter_bloc
### https://pub.dev/packages/lumberdash
### https://pub.dev/packages/ozzie
### https://pub.dev/packages/flutter_platform_widgets


* [Flutter Succinctly](https://www.syncfusion.com/ebooks/flutter-succinctly)

* [Build a Photo Sharing app with Google Photos and Flutter](https://codelabs.developers.google.com/codelabs/google-photos-sharing/index.html?index=..%2F..index#0)

* Creating Layouts with Flutter[@](https://app.pluralsight.com/library/courses/creating-layouts-flutter/table-of-contents)[PluralSight](http://referral.pluralsight.com/mQfBZ9r)

[Environment](https://flutter.dev/docs/get-started/install/windows)

* [powershell-6](https://www.thomasmaurer.ch/2019/03/how-to-install-and-update-powershell-6/)

iex "& { $(irm https://aka.ms/install-powershell.ps1) } -UseMSI"

* [Git](https://git-scm.com/download/win)

* [Download Visual Studio Code Insiders](https://code.visualstudio.com/insiders/)

Visual Studio Code Extensions
* Dart
* [Flutter](https://marketplace.visualstudio.com/items?itemName=Dart-Code.flutter)

Should run VS Code as administrator

Set format on save

Control + Shift + P

Create Flutter Project

Could not find a Flutter SDK. Please ensure flutter is installed and in your PATH (you may need to restart).

Config Android version `android/app/build.gradle`

[`minSdkVersion`, `targetSdkVersion`](https://developer.android.com/guide/topics/manifest/uses-sdk-element?utm_campaign=adp_series_sdkversion_010616&utm_source=medium&utm_medium=blog#ApiLevels)

[i18n, l10n](https://phraseapp.com/blog/posts/how-to-internationalize-a-flutter-app/)

F5: run

[D8: Cannot fit requested classes in a single dex file (# methods: 69176 > 65536)](https://stackoverflow.com/questions/55591958/flutter-firestore-causing-d8-cannot-fit-requested-classes-in-a-single-dex-file)

Update Flutter SDK path to `flutter\bin`, remember to remove old path

Locate SDK, 

Add SDK to PATH

flutter doctor

create new device 

[DOWNLOAD ANDROID STUDIO](https://developer.android.com/studio)

update sdkmanager

"C:\Program Files (x86)\Android\android-sdk\tools\bin\sdkmanager" "platforms;android-28" "build-tools;28.0.3"

Some Android licenses not accepted.  To resolve this, run: flutter doctor --android-licenses

No suitable Android AVD system images are available. You may need to install these using `sdkmanager`, for example: `sdkmanager "system-images;android-27;google_apis_playstore;x86"`

path `C:\Program Files (x86)\Android\android-sdk\tools\bin`, run `cmd` as administrator, accept all licenses

Failed to launch emulator: PANIC: Cannot find AVD system path. Please define ANDROID_SDK_ROOT

Set ANDROID_SDK_ROOT=C:\Program Files (x86)\Android\android-sdk

Then restart

State management

* Global variable 

* Provider

Refer

* [some-options-for-deserializing-json-with-flutter](https://medium.com/flutter/some-options-for-deserializing-json-with-flutter-7481325a4450)

* [Http Client dio](https://pub.dev/packages/dio)

* [LINQ moor_flutter](https://pub.dev/packages/moor_flutter)

[ButtonBar center](https://stackoverflow.com/questions/49819915/how-to-create-a-button-bar-for-displaying-a-row-of-buttons?rq=1)

`mainAxisSize: MainAxisSize.min,`

[ListView crash in Row, Column](https://github.com/flutter/flutter/issues/17036)

`Expanded(child: ListView())`


Radio
* http://listen.ai-radio.org
* http://fmstream.org/index.php?c=J&n=200

Pub

* [responsive_grid ](https://pub.dev/packages/responsive_grid#responsive_grid)

![](https://raw.githubusercontent.com/mohamed-selim-a/ResponsiveGrid_Flutter/master/images/1.jpg)

* [showcaseview](https://pub.dev/packages/showcaseview)

![](https://github.com/simformsolutions/flutter_showcaseview/raw/master/preview/showcaseview.gif)

* Add to Calendar

`Failed to launch flutter emulator: ProcessException: Process exited abnormally:
emulator: ERROR: x86 emulation currently requires hardware acceleration!
Please ensure Windows Hypervisor Platform (WHPX) is properly installed and usable.
CPU acceleration status: Unable to open HAXM device: ERROR_FILE_NOT_FOUND
More info on configuring VM acceleration on Windows:
https://developer.android.com/studio/run/emulator-acceleration#vm-windows
If you are using an Intel CPU: please check that virtualization is enabled in the BIOS and that HAXM is installed and usable.
Note: if Hyper-V or Credential Guard is enabled, the emulator will not work with HAXM.
See https://github.com/intel/haxm/issues/105#issuecomment-470927735 for info on how to disable Credential Guard.
If you are using an AMD CPU or need to run alongside Hyper-V-based apps such as Docker, we recommend using Windows Hypervisor Platform.General information on acceleration: https://developer.android.com/studio/run/emulator-acceleration.
  Command: C:\Users\KhanhLVH\AppData\Local\Android\sdk\emulator\emulator.exe -avd flutter_emulator`
```
DISM /online /get-features
DISM /online /enable-feature /featurename:HypervisorPlatform
```

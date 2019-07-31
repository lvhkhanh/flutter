# flutter

[Environment](https://flutter.dev/docs/get-started/install/windows)

* [powershell-6](https://www.thomasmaurer.ch/2019/03/how-to-install-and-update-powershell-6/)

iex "& { $(irm https://aka.ms/install-powershell.ps1) } -UseMSI"

* [Git](https://git-scm.com/download/win)

* [Download Visual Studio Code Insiders](https://code.visualstudio.com/insiders/)

Visual Studio Code Extensions
* [Flutter](https://marketplace.visualstudio.com/items?itemName=Dart-Code.flutter)

Should run VS Code as administrator

Set format on save

Control + Shift + P

Create Flutter Project

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
* Add to Calendar

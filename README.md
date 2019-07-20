# flutter

[Environment](https://flutter.dev/docs/get-started/install/windows)

* [Download Visual Studio Code Insiders](https://code.visualstudio.com/insiders/)

* [powershell-6](https://www.thomasmaurer.ch/2019/03/how-to-install-and-update-powershell-6/)

iex "& { $(irm https://aka.ms/install-powershell.ps1) } -UseMSI"

* [Git](https://git-scm.com/download/win)

Visual Studi Code Extensions
* [Flutter](https://marketplace.visualstudio.com/items?itemName=Dart-Code.flutter)

Should run VS Code as administrator

Control + Shift + P

Create Flutter Project

F5: run

Locate SDK

Add SDK to PATH

flutter doctor

create new device 


update sdkmanager

"C:\Program Files (x86)\Android\android-sdk\tools\bin\sdkmanager" "platforms;android-28" "build-tools;28.0.3"

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

## Memulai Install flutter SDK Jadul

Ini adalah kasus dimana kamu punya 2 SDK flutter yg satu jadul yang satunya masih baru. dan kebetulan project kamu ada yg jadul, karena males migrasi terpaksa pake sdk lama supaya gak makan waktu

### Install SDK flutter 

masuk halaman ini: https://docs.flutter.dev/development/tools/sdk/releases

download yg versi 1 sesuaikan dengan project flutter sobat


## Buat aliases Environment

- buat folder dengan nama flutterjadul 
- kemudian didalam dibuat file flutterjadui.bat
- isi file dengan script dibawah ini:

``@echo off
C:\homekamu\flutter-sdk\flutter\bin\flutter %*``

terdapat 2 folder didalam `flutter-sdk` kalian, yg `flutter` itu isi directory aslinya, sedangkan `flutterjadul` itu isinya file bat yg diarahkan oleh alias.
Masuk environment variables => user variables => Path => edit => new, tambahkan location dibawah ini:


`C:\homekamu\flutter-sdk\flutterjadul`

## Gagal menemukan javahome

install android studio, lalu buka terminal ketik:

`flutterjadul config --android-studio-dir="C:\Program Files\Android\Android Studio"`


## Finish

Selamat mencobaa


## Sumber

https://stackoverflow.com/questions/55783494/how-to-use-two-version-of-flutter-on-same-device-for-different-projects
https://stackoverflow.com/questions/64359564/error-java-home-is-not-set-and-no-java-command-could-be-found-in-your-flutter



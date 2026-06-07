# Cheatsheet — Android ADB

Comandi rapidi da ricordare.

## Connessione

```bash
adb devices
adb devices -l
adb start-server
adb kill-server
adb reconnect
```

## Shell

```bash
adb shell
adb shell id
adb shell whoami
adb shell getprop
```

## APK

```bash
adb install app.apk
adb install -r app.apk
adb uninstall com.nome.pacchetto
adb shell pm list packages -3
adb shell pm path com.nome.pacchetto
```

## File

```bash
adb push file.txt /sdcard/Download/
adb pull /sdcard/Download/file.txt .
```

## Log

```bash
adb logcat
adb logcat -c
adb logcat -d > logcat.txt
adb logcat *:E
```

## App

```bash
adb shell am force-stop com.nome.pacchetto
adb shell pm clear com.nome.pacchetto
adb shell monkey -p com.nome.pacchetto -c android.intent.category.LAUNCHER 1
```

## Screenshot

```bash
adb exec-out screencap -p > screen.png
adb shell screenrecord /sdcard/video.mp4
adb pull /sdcard/video.mp4 .
```

## Rete

```bash
adb forward tcp:8080 tcp:8080
adb reverse tcp:8080 tcp:8080
adb tcpip 5555
adb connect IP:5555
adb usb
```

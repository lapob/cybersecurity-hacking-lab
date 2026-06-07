# Lab — Primo laboratorio ADB

## Obiettivo

Imparare a collegare un dispositivo Android o emulatore, leggere informazioni di base, installare un APK e raccogliere log.

## Requisiti

- Kali Linux o altro sistema con ADB installato
- Dispositivo Android personale o emulatore
- Debug USB attivo
- APK di test autorizzato

## Passaggi

### 1. Verifica connessione

```bash
adb devices
```

Il dispositivo deve comparire come `device`.

### 2. Apri shell

```bash
adb shell
id
whoami
exit
```

### 3. Raccogli informazioni dispositivo

```bash
adb shell getprop ro.product.model
adb shell getprop ro.build.version.release
adb shell getprop ro.product.cpu.abi
```

### 4. Installa APK di test

```bash
adb install app.apk
```

### 5. Trova package name

```bash
adb shell pm list packages -3
```

### 6. Leggi informazioni app

```bash
adb shell dumpsys package com.nome.pacchetto
```

### 7. Raccogli log

```bash
adb logcat -c
adb logcat > logcat.txt
```

Apri e usa l'app per qualche minuto, poi interrompi il comando.

### 8. Pulisci dati app

```bash
adb shell pm clear com.nome.pacchetto
```

## Risultati da salvare

- Modello dispositivo
- Versione Android
- Package name dell'app
- Permessi principali
- Eventuali errori o crash nel logcat

## Note personali

Scrivere qui cosa ho imparato, errori incontrati e come li ho risolti.

# Reverse Engineering

Questa sezione contiene appunti su analisi statica e reverse engineering.

## Obiettivi

- Capire la struttura di un APK
- Leggere codice decompilato
- Analizzare AndroidManifest.xml
- Capire risorse e configurazioni
- Riconoscere dati sensibili hardcoded

## Tool

- JADX
- APKTool
- strings
- file
- unzip
- Ghidra, più avanti

## Workflow APK base

```bash
file app.apk
unzip -l app.apk
jadx-gui app.apk
apktool d app.apk -o output_apktool
```

## Cose da cercare

- Endpoint API
- Chiavi hardcoded
- Token
- URL sospetti
- Log sensibili
- Configurazioni debug
- Permessi rischiosi
- Componenti esportati

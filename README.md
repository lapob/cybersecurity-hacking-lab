# Cybersecurity Lab

Repository personale per studiare e documentare cybersecurity, Android security, mobile pentesting, Kali Linux, networking, web security e reverse engineering.

> Tutto il materiale è pensato per studio, laboratorio personale e ambienti autorizzati.

## Come usare questo repository

- `docs/` contiene la teoria spiegata in modo ordinato.
- `cheatsheets/` contiene comandi rapidi da ripassare.
- `labs/` contiene esercizi pratici e procedure passo-passo.
- `roadmap/` contiene cosa ho già studiato, cosa sto studiando e cosa studierò.
- `templates/` contiene modelli per scrivere nuovi appunti e nuovi laboratori.

## Struttura

```text
cybersecurity-lab/
├── README.md
├── docs/
│   ├── adb-comandi.md
│   ├── android/
│   ├── kali/
│   ├── mobile-security/
│   ├── networking/
│   ├── reverse-engineering/
│   └── web-security/
├── cheatsheets/
│   └── android-adb.md
├── labs/
│   └── android/
│       └── adb-first-lab.md
├── roadmap/
│   ├── completed.md
│   ├── studying.md
│   └── future.md
└── templates/
    ├── lab-template.md
    └── notes-template.md
```

## Indice principale

### Android Security

- [ADB — guida completa](docs/adb-comandi.md)
- [Indice Android Security](docs/android/README.md)
- [Cheatsheet ADB](cheatsheets/android-adb.md)
- [Primo laboratorio ADB](labs/android/adb-first-lab.md)

### Mobile Application Security

- [Indice Mobile Security](docs/mobile-security/README.md)

Argomenti da sviluppare:

- OWASP Mobile Top 10
- OWASP MASVS
- OWASP MASTG
- MobSF
- JADX
- APKTool
- Frida
- Objection
- Burp Suite
- Analisi statica APK
- Analisi dinamica APK

### Kali Linux

- [Indice Kali Linux](docs/kali/README.md)

Argomenti da sviluppare:

- terminale Linux
- permessi
- file system
- networking base
- tool fondamentali

### Networking

- [Indice Networking](docs/networking/README.md)

Argomenti da sviluppare:

- TCP/IP
- DNS
- DHCP
- porte
- NAT
- routing
- Wireshark
- nmap

### Web Security

- [Indice Web Security](docs/web-security/README.md)

Argomenti da sviluppare:

- HTTP/HTTPS
- cookie e sessioni
- autenticazione
- autorizzazione
- OWASP Top 10
- API security

### Reverse Engineering

- [Indice Reverse Engineering](docs/reverse-engineering/README.md)

Argomenti da sviluppare:

- APKTool
- JADX
- AndroidManifest.xml
- codice decompilato
- risorse APK
- ricerca segreti hardcoded

## Roadmap

- [Argomenti completati](roadmap/completed.md)
- [Argomenti in studio](roadmap/studying.md)
- [Argomenti futuri](roadmap/future.md)

## Metodo di studio

Per ogni nuovo argomento devo creare:

1. una pagina teorica in `docs/`,
2. una cheatsheet in `cheatsheets/`, se ci sono comandi da ricordare,
3. un laboratorio in `labs/`, se è un argomento pratico,
4. un aggiornamento della roadmap.

## Regole del laboratorio

1. Usare solo dispositivi, app, macchine virtuali e reti autorizzate.
2. Non testare mai sistemi di altre persone senza permesso.
3. Salvare comandi, output, errori e soluzioni.
4. Scrivere appunti chiari, così posso ripassarli prima di un esame o di un laboratorio.
5. Aggiornare il repository ogni volta che imparo qualcosa di nuovo.

## Stato attuale

Repository riorganizzato come knowledge base personale. La base Android/ADB è già presente; le altre sezioni sono pronte per essere riempite con appunti, laboratori e cheatsheet.
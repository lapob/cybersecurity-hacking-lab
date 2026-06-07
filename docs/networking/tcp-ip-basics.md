# TCP/IP — basi per cybersecurity

## Cos'è TCP/IP

TCP/IP è l'insieme di protocolli che permette ai dispositivi di comunicare in rete.

## Concetti fondamentali

### IP address

Identifica un dispositivo in una rete.

Esempio:

```text
192.168.1.10
```

### Porta

Identifica un servizio su un dispositivo.

Esempi comuni:

- 22 SSH
- 53 DNS
- 80 HTTP
- 443 HTTPS

### TCP

Protocollo orientato alla connessione. È usato quando serve affidabilità.

### UDP

Protocollo più leggero, senza connessione. È usato quando serve velocità o semplicità.

### DNS

Traduce nomi dominio in indirizzi IP.

### Gateway

Dispositivo che permette di uscire dalla rete locale.

### NAT

Meccanismo che permette a più dispositivi privati di condividere un indirizzo pubblico.

## Comandi utili

```bash
ip addr
ip route
ping 8.8.8.8
ss -tulpen
nslookup example.com
traceroute example.com
```

## Perché serve a un ethical hacker

Senza networking non si possono capire bene:

- servizi esposti
- traffico web
- firewall
- proxy
- scansioni autorizzate
- analisi con Wireshark

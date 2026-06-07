# HTTP e HTTPS — basi per Web Security

## Cos'è HTTP

HTTP è il protocollo usato dal browser e dalle applicazioni per comunicare con un server web.

Una comunicazione HTTP è composta da:

- richiesta del client
- risposta del server
- metodo
- URL
- header
- body
- status code

## Metodi principali

- `GET`: richiede dati
- `POST`: invia dati
- `PUT`: aggiorna una risorsa
- `PATCH`: modifica parziale
- `DELETE`: elimina una risorsa
- `OPTIONS`: mostra metodi supportati

## Status code importanti

- `200 OK`: richiesta riuscita
- `201 Created`: risorsa creata
- `301/302`: redirect
- `400 Bad Request`: richiesta errata
- `401 Unauthorized`: non autenticato
- `403 Forbidden`: autenticato ma non autorizzato
- `404 Not Found`: risorsa non trovata
- `500 Internal Server Error`: errore server

## Header utili

- `Host`
- `User-Agent`
- `Authorization`
- `Cookie`
- `Content-Type`
- `Origin`
- `Referer`

## HTTPS

HTTPS è HTTP protetto tramite TLS. Serve a proteggere confidenzialità e integrità della comunicazione.

## Perché serve nella cybersecurity

Capire HTTP è fondamentale per studiare:

- autenticazione
- sessioni
- API
- cookie
- vulnerabilità web
- traffico mobile
- proxy come Burp Suite

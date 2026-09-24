# TTG Tavoli 2026

Web app offline per la prenotazione dei 6 tavoli dello stand Volonline al TTG Rimini (14–16 ottobre 2026). Dati salvati in locale sull'iPad.

## Deploy
Settings → Pages → Source: `main` / root. URL: `https://<utente>.github.io/ttg-tavoli/`

## Installazione iPad
Safari → URL → Condividi → Aggiungi alla schermata Home. Aprire una volta online, poi funziona offline.

## Configurazione
Blocco `CONFIG` in `index.html` (giorni, orari, durata slot, tavoli, PIN).
Dopo ogni modifica incrementare `CACHE` in `sw.js`.

## Dati
- Backup JSON / Ripristino: dalla barra in fondo alla pagina.
- Export CSV: separatore `;`, compatibile Excel IT.

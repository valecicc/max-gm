MAX GM V1.6.1 — GITHUB ROOT

Carica QUESTI FILE direttamente nella root del repository max-gm:
- index.html
- manifest.webmanifest
- service-worker.js
- cartella icons/

NON caricare la cartella esterna v161root: i file sopra devono stare allo stesso livello nella root di GitHub Pages.

NOVITÀ V1.6.1
- Rose dinamiche persistenti per ogni lega.
- Gestione manuale scambi 1vs1 / 2vs2 / 3vs3.
- Storico operazioni + annulla.
- Import CSV/JSON con anteprima e blocchi di sicurezza.
- Pulsante SCAMBIO CONCLUSO sulle proposte per aggiornare subito le rose.
- Ricerca mirata: scegli un tuo giocatore + una squadra specifica; MAX GM cerca solo scambi reali 1vs1/2vs2/3vs3 contro quella squadra.
- Interfaccia pronta per sincronizzazione Leghe Fantacalcio via backend read-only.

SYNC FANTACALCIO
Il backend è nel pacchetto separato MAXGM_V1.6_LEGHE_SYNC_VERCEL.zip.
Le credenziali Fantacalcio NON vanno mai inserite nell'HTML o nel repository pubblico.

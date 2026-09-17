MAX GM V1.5.5 — VERGARA ROSTER FIX

Aggiornamento GitHub Pages:
1. Apri il repository/cartella max-gm.
2. Sostituisci i file nella root con quelli contenuti in questo ZIP.
3. Mantieni la cartella icons con icon-192.png e icon-512.png.
4. Fai commit/push.
5. Sul telefono, chiudi e riapri MAX GM. Il service worker V1.5.5 elimina le vecchie cache max-gm-*.

Correzioni V1.5.5:
- corretta la rosa di VERGARA’S COFFEE TEAM nel modulo Scambi multipli;
- i nomi squadra nei select mantengono ora il value esatto del database, inclusi doppi spazi e caratteri speciali;
- aggiunto resolver tollerante per spazi multipli e varianti di apostrofo;
- protezione applicata anche alla funzione roster, per evitare select vuoti in casi analoghi futuri;
- self-test V1.5.5 include controllo specifico della rosa Vergara (30 giocatori);
- cache PWA aggiornata a max-gm-v1.5.5.

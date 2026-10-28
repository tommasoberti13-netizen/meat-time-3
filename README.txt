MEAT TIME — progetto PWA personale

CONTENUTO
- index.html: app completa
- manifest.webmanifest: installazione come app
- sw.js: cache offline
- icone PNG

FUNZIONI
- Fasi aggiungibili, eliminabili e riordinabili
- Durata in minuti e orari calcolati a ritroso dall'ora finale
- Temperatura BBQ e temperatura interna in °F
- Note per ogni fase
- Archivio ricette in localStorage sul dispositivo
- Schermata "In corso" e avvisi di fine fase mentre l'app è aperta

INSTALLAZIONE SU IPHONE
1. Pubblica questa cartella su un hosting HTTPS (ad esempio un tuo spazio web).
2. Apri l'indirizzo con Safari su iPhone.
3. Tocca Condividi > Aggiungi alla schermata Home.
4. Avvia MEAT TIME dalla nuova icona e abilita le notifiche.

IMPORTANTE SULLE NOTIFICHE
Questa prima versione web invia avvisi mentre l'app è aperta e il monitoraggio è attivo. iOS non garantisce timer web in background. Per notifiche locali affidabili anche con app chiusa/bloccata serve una versione nativa iOS (Swift) con notifiche locali pianificate e firma tramite Xcode/Apple Developer.

DATI
Le ricette sono conservate in localStorage sul dispositivo/browser. Non vengono sincronizzate e possono andare perse se si cancellano i dati del sito o si cambia dispositivo. Esporta o duplica le ricette prima di cancellare Safari.

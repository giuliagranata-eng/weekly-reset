WEEKLY RESET — progetto PWA personale

CONTENUTO
- index.html: interfaccia dell'app
- app.js: funzionalità e salvataggio locale
- manifest.webmanifest: configurazione installazione
- sw.js: cache offline
- icon-192.png / icon-512.png: icone

IMPORTANTE
Questa versione salva i dati nel browser del dispositivo tramite localStorage.
Usa la funzione Impostazioni > Esporta backup regolarmente.
Le foto outfit vengono salvate come dati locali nel browser; evita immagini molto grandi.

PER PUBBLICARLA GRATIS
1. Crea un account GitHub, se non ne hai uno.
2. Crea un nuovo repository pubblico chiamato weekly-reset.
3. Carica tutti i file e le icone contenuti in questa cartella nella radice del repository.
4. In GitHub: Settings > Pages > Deploy from a branch > main > /(root) > Save.
5. Attendi la pubblicazione e apri l'indirizzo Pages su Safari dell'iPhone.
6. In Safari: Condividi > Aggiungi alla schermata Home.

Per l'uso come app installata e la modalità offline è necessario HTTPS e il service worker.
Su iPhone, apri il sito con Safari per aggiungerlo alla schermata Home.

Nota: il conteggio delle ore turno considera l'orario inserito; per turni che attraversano la mezzanotte o pause non pagate servirà un aggiornamento.

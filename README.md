# QR Studio

Web app statica in italiano per creare codici QR e scaricarli in PNG. L'anteprima si aggiorna mentre cambi le impostazioni; generazione e download avvengono nel browser.

## Funzioni

- Codifica URL o testo libero.
- Personalizza colore, sfondo, trasparenza, dimensione, margine e correzione degli errori.
- Aggiungi un logo al centro; con un logo la correzione viene impostata automaticamente al livello massimo.
- Scarica un PNG pronto da condividere o stampare.

La pagina usa QRCode.js e i font Google tramite CDN, quindi serve una connessione internet. Il contenuto inserito non viene inviato a un server.

## Pubblicazione con GitHub Pages

1. Crea un nuovo repository GitHub e carica `index.html`, `README.md` e `.github/workflows/pages.yml`.
2. Nelle impostazioni del repository, apri **Pages** e imposta la sorgente di pubblicazione su **GitHub Actions**.
3. Pubblica il branch `main` oppure avvia manualmente l'azione **Pubblica QR Studio** nella scheda **Actions**.

Il workflow pubblica soltanto `index.html`, senza esporre gli altri file eventualmente presenti nel repository.

Per provarla in locale, apri `index.html` nel browser. Anche in locale è necessaria la connessione internet per caricare la libreria QR.
# Sito personale

Pagina statica in italiano, realizzata con HTML, CSS e JavaScript, senza dipendenze o compilazione.

## Anteprima locale

Dalla cartella del progetto esegui `python3 -m http.server 8000`, poi apri <http://localhost:8000>. Per fermare il server premi `Ctrl+C`.

## Personalizzazione

- `index.html`: nome, biografia, progetti e contatti. Le schede attuali sono segnaposto esplicitamente indicati, da sostituire con lavori reali.
- `styles.css`: colori, tipografia e impaginazione; le variabili iniziali definiscono la palette.
- `script.js`: menu mobile, animazioni leggere e anno nel footer.
- `favicon.svg`: icona del sito.

Il nome e il collegamento GitHub iniziali derivano dal repository; verifica che siano quelli che vuoi pubblicare. Aggiorna anche titolo e descrizione in `index.html`.

## GitHub Pages

1. Carica i file sul repository GitHub.
2. Apri **Settings → Pages**.
3. In **Build and deployment**, seleziona **Deploy from a branch**.
4. Seleziona il branch con i file del sito (di solito `main`) e la cartella **/ (root)**, quindi **Save**.
5. Attendi la pubblicazione: GitHub mostrerà il collegamento al sito.

Per il repository attuale, l'indirizzo previsto è <https://gaetanosabino.github.io/sito-persionale/>. I percorsi relativi degli asset sono compatibili con questo sottopercorso.

GitHub Pages gestisce il certificato HTTPS. Controlla **Enforce HTTPS** nelle impostazioni Pages. Un dominio personalizzato si può configurare in seguito.

Non servono Node.js, React o Vite. La pagina non carica font remoti, cookie, strumenti di analisi o servizi esterni.

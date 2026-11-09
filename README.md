# Sito personale

Pagina statica in italiano, realizzata con HTML, CSS e JavaScript, senza dipendenze o compilazione.

## Anteprima locale

Dalla cartella del progetto esegui `python3 -m http.server 8000`, poi apri <http://localhost:8000>. Per fermare il server premi `Ctrl+C`.

## Personalizzazione

- `index.html`: nome, biografia, progetti e contatti. Le schede attuali sono segnaposto esplicitamente indicati, da sostituire con lavori reali.
- `styles.css`: colori, tipografia e impaginazione; le variabili iniziali definiscono la palette.
- `script.js`: menu mobile, animazioni leggere e anno nel footer.
- `favicon.svg`: icona del sito.
- `privacy.html`: informativa su privacy, cookie e hosting, collegata nel footer anche su mobile. È una bozza: prima della pubblicazione completare il recapito del gestore e togliere l’avviso di bozza. Non usare l’indirizzo GitHub `noreply`, che non riceve messaggi.

Il nome e il collegamento GitHub iniziali derivano dal repository; verifica che siano quelli che vuoi pubblicare. Aggiorna anche titolo e descrizione in `index.html`.

## GitHub Pages

1. Carica i file sul repository GitHub.
2. Apri **Settings → Pages**.
3. In **Build and deployment**, seleziona **Deploy from a branch**.
4. Seleziona il branch con i file del sito (in questo progetto `developed`) e la cartella **/ (root)**, quindi **Save**.
5. Attendi la pubblicazione: GitHub mostrerà il collegamento al sito.

Per il repository attuale, l'indirizzo previsto è <https://gaetanosabino.github.io/sito-persionale/>. I percorsi relativi degli asset sono compatibili con questo sottopercorso.

GitHub Pages gestisce il certificato HTTPS. Controlla **Enforce HTTPS** nelle impostazioni Pages. Un dominio personalizzato si può configurare in seguito.

Non servono Node.js, React o Vite. Il codice della pagina non imposta cookie e non carica font remoti, strumenti di analisi o contenuti incorporati da servizi esterni. GitHub Pages, come hosting, registra gli IP dei visitatori per sicurezza secondo la propria informativa.

## Privacy prima della pubblicazione

La pagina privacy descrive la configurazione attuale, senza form, statistiche, pubblicità o tracciamento.

La struttura delle sezioni prende spunto dalla [Privacy Policy SYS-DAT Group](https://www.sys-datgroup.com/privacy-policy/); il testo è adattato ai trattamenti del sito personale e all’hosting GitHub Pages. Non vengono ripresi recapiti, DPO, contitolarità o servizi dell’azienda di riferimento.

Prima di pubblicarla:

- Completare il recapito del gestore e verificare che sia utilizzabile per richieste riservate. Un profilo GitHub o un'issue pubblica non sostituiscono un canale privato di contatto.
- Se si aggiunge una casella email di contatto, descrivere anche il trattamento della corrispondenza (finalità, base giuridica, conservazione ed eventuale fornitore email).
- Rimuovere l’avviso di bozza solo dopo aver verificato i dati e i trattamenti effettivi.
- Aggiornare informativa ed eventuale gestione del consenso prima di attivare nuovi servizi che raccolgono dati o utilizzano tracciamento. Nella configurazione attuale non è stato aggiunto un banner di consenso.

Riferimenti: [raccolta dati di GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages#data-collection) e [privacy di GitHub](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement). L’informativa descrive il sito e non costituisce una certificazione di conformità legale.

# Mini Blog API

questa repository serve per creare un mini blog fittizio che utilizza le API di JSONPlaceHolder per popolare il sito con post e autori fittizzi.
Il progetto è un esempio di sito statico.
Il sito è disponibile su github pages a questo link: https://duccioo.github.io/test_esame_fism2026/index.html

## Funzionalità

Il progetto espone queste funzionalità:

- sito statico con multipagina
- homepage che riassume il sito
- pagina post che mostra i post presi dalle API esterne
- pagina autori che mostra gli autori fittizzi
- integra un design responsive per anche dispositivi mobili

## Tecnologie Utilizzate

- HTML
- CSS & Bootstrap (per il design e la responsività)
- JavaScript (per fetchare i dati dalle API)
- API di JSONPlaceHolder per i dati fittizzi

## Requisiti
- Un browser moderno
- Connessione Internet (per Bootstrap e fetchare i dati dalle API esterne)
- git o gh per clonare la repository

## API utilizzate

|   Risorsa   |   Endpoint                                     |   Uso nel sito        |
|-------------|------------------------------------------------|-----------------------|
|   Post      |   https://jsonplaceholder.typicode.com/posts   |   Pagina posts.html   |
|   Utenti    |   https://jsonplaceholder.typicode.com/users   |   Pagina autori.html  |
|             |                                                |                       |


## Struttura 
Il progetto è organizzato in questo modo:

```
root_repo/
├── index.html # Homepage del sito
├── posts.html # Pagina che mostra i post
├── autori.html # Pagina che mostra gli autori
├── style.css # Foglio di stile per il sito
├── script.js # Script JavaScript per fetchare i dati dalle API
├── docs/ # Cartella relativa a tutta la documentazione approfondita
|   ├── installazione.md # Guida all'installazione del progetto
|   ├── faq.md # Domande frequenti
│   └── api.md # Dettagli sulle API utilizzate
└── README.md # Questo file di documentazione
```

## Documentazione

- [Guida all'installazione](docs/installazione.md)
- [Domande frequenti](docs/faq.md)
- [Dettagli sulle API utilizzate](docs/api.md)

## Autore

Il progetto è stato creato da [Duccio Meconcelli](https://github.com/duccioo)


## LICENSE

Il progetto non utilizza una licenza specifica, si avvale della licenza di default del diritto di autore.
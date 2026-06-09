# API utilizzate

Il progetto utilizza le API di JSONPlaceHolder per ottenere dati fittizzi da mostrare nelle pagine del sito. Di seguito sono riportati i dettagli delle API utilizzate


## Summary

|   Risorsa   |   Endpoint                                     |   Uso nel sito        |
|-------------|------------------------------------------------|-----------------------|
|   Post      |   https://jsonplaceholder.typicode.com/posts   |   Pagina posts.html   |
|   Utenti    |   https://jsonplaceholder.typicode.com/users   |   Pagina autori.html  |
|             |                                                |                       |

## Dettagli API

- **Post**: Questa API fornisce un elenco di post fittizzi. Ogni post contiene un titolo, un corpo e un ID dell'autore. 
    - Endpoint: `https://jsonplaceholder.typicode.com/posts`
    - Utilizzo: I dati ottenuti da questa API vengono mostrati nella pagina `posts.html`, dove ogni post viene visualizzato con il suo titolo e corpo.

- **Utenti**: Questa API fornisce un elenco di utenti fittizzi. Ogni utente contiene un nome, un username, un'email e altre informazioni.
    - Endpoint: `https://jsonplaceholder.typicode.com/users`
    - Utilizzo: I dati ottenuti da questa API vengono mostrati nella pagina `autori.html`, dove ogni autore viene visualizzato con il suo nome e email.


## Campi Utilizzati 

|   Endpoint   |   Campo          |   Significato              |
|--------------|------------------|----------------------------|
|   /posts     |   id             |   Identificativo del post  |
|   /posts     |   title          |   Titolo del post          |
|   /posts     |   body           |   Testo del post           |
|   /posts     |   userId         |   Autore collegato         |
|   /users     |   name           |   Nome autore              |
|   /users     |   email          |   Email fittizia           |
|   /users     |   company.name   |   Azienda fittizia         |
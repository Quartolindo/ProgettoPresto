# PRESTO 

Progetto che simula una piattaforma di ecommerce di prodotti nuovi e usati. 

* [x] Esercizi Di riscaldamento ( 15 min )
  * [x] Free Recap
  * [x] Code kata 

* TODO LIST
  * [x] Home page 
    * [x] Link a pagina tutti i prodotti 
    * [x] Sezione Categorie presenti
      * [x] Link alla pagina singola categoria 
    * [x] Sezione mostra 3 migliori prodotti ( basandoti sul rate ) 
    * [x] Sezione recensioni clienti 
    * [x] Footer con contatti 
    * EXTRA PER DINAMICIZZARE LA PAGINA
      * [x] Intergrare libreria per animazioni allo scroll
      * [x] Intergrare libreria per carusel interattivo
  * [x] Pagina singola categoria
    * [x] Mostrare lista prodotti di quella categoria 
  * [ ] Pagina Tutti i prodotti 
    * [ ] Mostrare tutti i prodotti della piattaforma 
    * [ ] Sezione vai al carrello
    * [ ] Aggiungi singolo prodotto al carrello
    * [ ] Aggiorna prezzo finale carrello
    * [ ] Rimuovi prodotto dal carrello
    * [ ] Auto-ricerca prodotto per nome prodotto 
  * [ ] Pagina singolo prodotto 
    * [ ] Mostrare i dettagli del specifico prodotto 
    * [ ] Mostrare prodotti correllati ( esempio: protrebbero interessarti prodotti della stessa categoria )


Cos'è una API
  * Application programming interface
    * API pubbliche senza richesta di autenticazione 
    * API pubbliche con richista di autenticazione 
      * Richiedono una api_key
    * API non pubbliche
* API fornisce dati al mondo per far funzionare applicativi web. 
  * come le API forniscono i dati sul network ? 
  * oggigiorno i dati viaggiano nel modo piu veloce possibile 
    * come fanno queste API a far viaggiare i dati velocemente ? 
      * usano un formato dati super leggero!
        * usano un formato stringa
          * il formato che comprire le strutture dati complesse in modo che possano viaggiare veloci si chiama JSON 
            * file.JSON
* In Javascript se voglio usare una API pubblica per usare i dati, ho bisogno di fare una chiamata HTTP 
  * XMLhttprequest
  * con uso di lib esterne 
    * axios 
  * con funzioni built-in nel linguaggio js 
    * fetch API   
      * fetch é una funzione che mi permette di fare chiamate HTTP a api pubbliche o private 
      * Come funziona Fetch 
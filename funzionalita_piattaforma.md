Documentazione User Stories

1.0 Registrazione
Come utente non registrato, è possibile accedere alla piattaforma tramite mail e password così da poter utilizzare le funzionalità avanzate e salvare le mie preferenze.
- L'utente accede al sito
- L'utente non registrato può farlo cliccando sul bottone per la registrazione
- Inserendo email, password e cliccando conferma si verrà registrarti e reindirizzati alla homo page
- dalla home page l’utente potrà decidere quale piano utilizzare (gratuito con un tot di crediti limitati o a pagamento)

1.1 Login
Come utente registrato, è possibile accedere alla piattaforma tramite mail e password così da poter utilizzare le funzionalità salvare le mie preferenze.
- L'utente accede al sito
- L'utente registrato Inserendo email, password e cliccando login 
- se le credenziali sono corrette verrà reindirizzato alla home page
- altrimenti verrà richiesto nuovamente il login

2.0 Gestione Obiettivi e Preferenze di Viaggio
Gli utenti autenticati visualizzeranno un elenco dei propri viaggi esistenti e avere la possibilità di crearne di nuovi.
- Se non sono presenti viaggi salvati sarà possibile crearne uno nuovo oppure scegliere tra alcuni proposti in evidenza
- se invece l’utente ha viaggi salvati l'interfaccia mostra una lista dei viaggi salvati (titolo, date, destinazione, stato...).
- È possibile creare un nuovo viaggio.
- Ogni voce nell’elenco porta all’interfaccia chatbot associata a quel viaggio.

2.1 Accesso al chatbot per singolo viaggio
Ogni viaggio dell’elenco è collegato a una sessione chatbot dedicata, che accede alle informazioni relative a quel viaggio.
- Il chatbot accede solo ai dati collegati al viaggio selezionato.
- Se le informazioni del viaggio sono parziali o mancanti, il chatbot le richiede all’utente in modo guidato.
- Eventuali nuove informazioni raccolte vengono salvate nel contesto del viaggio specifico.
- Ogni viaggio deve poter contenere un insieme specifico di obiettivi e preferenze, che possono essere gestiti sia manualmente sia tramite il chatbot.
- Esempio di dati salvati per ogni viaggio/chat: budget, stile, mete preferite, trasporti, ecc.

3.0 Gestione Viaggi/Chat
L’utente può salvare itinerari parziali o completi all’interno di ciascun viaggio, con la possibilità di modificarli successivamente.
- Ogni viaggio ha uno o più itinerari associati.
- Gli itinerari sono modificabili in qualsiasi momento.
- È possibile duplicare, archiviare o eliminare un itinerario.

4.0 Visualizzazione Prezzi e Prenotazioni
L’utente può visualizzare offerte e prezzi aggiornati legati al viaggio selezionato.
- I dati vengono aggiornati periodicamente tramite scraping/API.
- Le offerte sono filtrate in base alle preferenze del viaggio corrente.
- È possibile accedere a dettagli e confrontare opzioni.

5.0 Gestione Abbonamento
- Le funzionalità premium (anteprima prezzi, prenotazioni, itinerari avanzati) richiedono un sistema a crediti.
- le funzioni premium richiede un abbonamento 
- In caso di crediti insufficienti, viene proposta acquisto di un abbonamento

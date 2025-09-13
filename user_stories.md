# Documentazione User Stories

---

## 1.0 Login  
**Come utente registrato**, voglio autenticarmi tramite email e password per accedere alle mie funzionalità personalizzate e alle preferenze salvate.  

**Flusso:**  
1. L’utente clicca su **Login** facendo l'accesso tramite social.  
2. L’utente autenticato viene reindirizzato alla Homepage.
3. -- variante : qualcosa va storto - riprovare

**Acceptance Criteria:**  
- Dato che inserisco credenziali corrette, quando clicco login, allora accedo alla Home.  
- Dato che inserisco credenziali sbagliate, allora ricevo un errore chiaro.  
- Dato che dimentico la password, allora posso avviare la procedura di recupero.  

**Priorità:** Must-have  

---

## 2.0 Gestione Obiettivi e Preferenze di Viaggio  
**Come utente autenticato**, voglio visualizzare i miei viaggi salvati ed eventualmente crearne di nuovi, con preferenze e obiettivi personalizzati.  

**Flusso:**  
1. Accedo alla sezione **I miei viaggi**.  
2. Il sistema mostra:  
   - Nessun viaggio -> pulsante **“Crea nuovo viaggio”**.  
   - Viaggi esistenti -> elenco con titolo, date, destinazione, stato e pulsante **“Crea nuovo viaggio”**.  
3. Posso aprire o creare un nuovo viaggio.  
4. Ogni viaggio ha un chatbot dedicato.  
5. -- da cambiare : 1 viaggio alla volta su 3 pagine: lista dei desideri, viaggi in programma e storico

**Acceptance Criteria:**  
- Dato che non ho viaggi salvati, allora vedo un pulsante per crearne uno nuovo.  
- Dato che ho viaggi salvati, allora vedo la lista con i dettagli e posso scegliere se creare un nuovo viaggio.  
- Dato che creo un nuovo viaggio, allora questo appare nell’elenco.  

**Priorità:** Must-have  

---

## 2.1 Accesso al Chatbot per singolo viaggio  
**Come utente autenticato**, voglio interagire con un chatbot dedicato per ogni viaggio, che gestisca obiettivi e preferenze in modo guidato.  

**Flusso:**  
1. Seleziono un viaggio.  
2. Si apre la chat dedicata a quel viaggio.  
3. Il chatbot accede ai soli dati di quel viaggio.  
4. Se mancano informazioni, il chatbot le chiede.  
5. Le nuove informazioni vengono salvate.  

**Acceptance Criteria:**  
- Dato che entro nella chat di un viaggio, allora il chatbot utilizza solo i dati di quel viaggio.  
- Dato che mancano informazioni, allora il chatbot me le richiede.  
- Dato che fornisco nuove preferenze, allora queste vengono salvate nel viaggio.  

**Priorità:** Must-have  

---

## 3.0 Gestione Viaggi/Chat  
**Come utente autenticato**, voglio poter salvare, modificare e gestire itinerari associati ai miei viaggi.  

**Flusso:**  
1. Ogni viaggio contiene uno o più itinerari.  
2. Posso: creare, modificare, archiviare o eliminare itinerari.  
3. -- nota: è possibile annullare il viaggio 
**Acceptance Criteria:**  
- Dato che creo un itinerario, allora questo appare nel viaggio.  
- Dato che modifico un itinerario, allora le modifiche vengono salvate.  
- Dato che elimino un itinerario, allora non è più disponibile.  

**Priorità:** Must-have  

---

## 4.0 Visualizzazione Prezzi e Prenotazioni  
**Come utente autenticato**, voglio visualizzare offerte e prezzi aggiornati legati al mio viaggio, in modo da confrontare opzioni e prenotare facilmente.  

**Flusso:**  
1. Accedo a **Offerte e Prezzi**.  
2. Il sistema aggiorna i dati da scraping/API chiamate da API interne. 
3. Le offerte sono filtrate sulle preferenze del viaggio.  
4. Posso visualizzare dettagli, confrontare e prenotare.  

**Acceptance Criteria:**  
- Dato che accedo a **Offerte e Prezzi**, allora vedo solo proposte coerenti con il mio viaggio.  
- Dato che apro un’offerta, allora vedo i dettagli aggiornati.  
- Dato che confronto offerte, allora posso valutare facilmente alternative.  

**Priorità:** Must-have  

---

## 5.0 Gestione Abbonamento  
**Come utente**, voglio poter scegliere un abbonamento o acquistare crediti per accedere a funzionalità premium.  

**Flusso:**  
1. Alcune funzioni richiedono crediti.  
2. Se non ho crediti -> il sistema propone un abbonamento o l’acquisto di crediti extra.  
3. Posso scegliere tra piano gratuito o premium.  

**Acceptance Criteria:**  
- Dato che provo ad accedere a una funzione premium senza crediti, allora il sistema mi propone un piano di acquisto.  
- Dato che attivo un abbonamento, allora vedo subito le funzionalità premium sbloccate.  

**Priorità:** Should-have

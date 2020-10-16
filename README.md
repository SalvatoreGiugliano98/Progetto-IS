# Progetto-IS: Sistema di gestione call center
Si vuole realizzare un sistema informatico per la gestione di un call center.

Il sistema è utilizzato da *amministratori* e *centralinisti*. Gli amministratori creano liste di numeri
telefonici e aggiungono o rimuovono numeri telefonici dalle liste. I centralinisti, identificati da un
id, nome, cognome e email sono organizzati in gruppi. Ciascun gruppo è identificato da un id e
una descrizione. Ê compito degli amministratori creare o rimuovere i gruppi. La creazione di un
gruppo consiste nell'inserimento di almeno un centralinista.
Inoltre, ciascun amministratore ha il compito di assegnare ciascuna lista al più a un gruppo di
centralinisti.

I centralisti richiedono al sistema il prossimo numero da chiamare e, al termine della telefonata,
registrano l'esito. In particolare, per ogni telefonata memorizzano l'id, la data, l'ora, note e l'esito
(occupato, senza risposta, da richiamare, non interessato, appuntamento fissato). In caso di
appuntamento fissato, il centralinista crea un nuovo appuntamento tra uno degli agenti vendita
del call center e l'utenza chiamata. L'appuntamento contiene un id, data e ora e note relative
all'incontro.

Gli agenti vendita interagiscono con il sistema per ottenere informazioni relative a tutti gli
appuntamenti fissati e modificare le note degli appuntamenti.
A partire dagli appuntamenti, gli agenti vendita possono risalire alle note che il centralinista ha
scritto al termine della chiamata conclusasi con un appuntamento fissato. Un appuntamento,
inoltre, può essere collegato ad un altro: quando il centralinista fissa un nuovo appuntamento
che segue uno fallito (es. l'utente non era disponibile al momento dell'appuntamento con
l'agente), il nuovo deve referenziare il precedente.

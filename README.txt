Sviluppare un "DeliveryService" che gestisce la consegna di pacchi acquistati da un cliente.

Quando un cliente acquista un prodotto può scegliere che esso venga consegnato in uno dei punti di ritiro disponibili.

I punti di ritiro possono accettare un pacco solo se hanno a disposizione abbastanza spazio per contenerlo.

Scrivere un servizio che:
 * data la dimensione di un pacco restituisca l'elenco dei punti di ritiro disponibili
 * consenta di prenotare uno dei suddetti punti restituendo un codice per il ritiro
 * consenta di ritirare il contenuto da un punto a partire dal codice, liberandolo

Note:
 * Ad ogni punto di ritiro è associato un nome in codice univoco
 * La dimensione del pacco è espressa con un unico numero che rappresenta la misura del lato più lungo del pacco
 * Ai fini del calcolo dell'occupazione del punto di ritiro, le dimensioni dei pacchi contenuti si sommano tra loro
 * Bonus: il tentativo di depositare un pacco troppo grande o di ritirare con un codice sbagliato deve sollevare un'eccezione
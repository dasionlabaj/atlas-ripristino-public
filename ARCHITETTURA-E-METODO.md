# Architettura, provenienza e metodo

## Struttura attuale

Il supporto di continuità è documentale: testo leggibile e manifesto JSON. I ruoli logici distinguono custodia locale delle fonti, replica documentale privata, replica documentale su Drive e base pubblica. Questi ruoli non identificano hardware e non dimostrano una rete operativa. Un nodo non è sinonimo di persona o account.

Il manifesto pubblico usa identità progettuali stabili e descrizioni dei ruoli; non contiene percorsi o destinazioni private. I materiali necessari per eseguire il software non sono incorporati. Eventuali adattatori per risolvere percorsi e accessi appartengono ai nodi privati.

## Provenienza e forza delle affermazioni

| Affermazione | Origine | Limite |
|---|---|---|
| Identità personale del progetto e visione distribuita | Decisioni esplicite del titolare, recepite nel supporto locale | Intenzione progettuale, non implementazione distribuita verificata |
| Recupero selettivo e conteggi | Rapporti e checkpoint locali finalizzati il 28 ottobre 2026, letti per preparare il supporto | Sintesi di prove private; nessuna nuova scansione o verifica del payload per questa pubblicazione |
| Replica privata r0002 | Registro locale delle pubblicazioni e confronti remoti | Conferma corrispondenza dei documenti, non funzionamento delle applicazioni o accesso da ogni interfaccia |
| Drive senza cifratura aggiuntiva lato client | Archivio caricato e successiva richiesta di cifratura | Privacy della cartella e cifratura del servizio non equivalgono a cifratura locale dell'archivio |
| Base pubblica | File nuovi di questo repository e loro cronologia | Non include storia privata, corpus o prove integrali del recupero |

Le fonti private restano esterne e non vengono nominate con percorsi, identificativi o collegamenti. Un lettore pubblico può verificare contenuti e storia di questa base; non può ripetere indipendentemente le prove private a partire da questa sola sintesi. Gli esiti della pubblicazione vengono registrati dopo la rilettura, separatamente dai contenuti hashati, evitando che un file certifichi da sé la riuscita del proprio caricamento.

## Metodo di continuità

All'inizio leggere l'ultimo checkpoint pertinente; dichiarare obiettivo e risultato atteso. Separare fatti attestati, decisioni della persona e ipotesi. Riutilizzare le prove già salvate senza ripetere recuperi, scansioni o test per il solo cambio di chat.

Per un nuovo controllo indicare quale evidenza è cambiata, perché il risultato precedente non basta e quale controllo minimo risolve il dubbio. Alla chiusura documentare attività concluse, lacune e un prossimo passo concreto.

Gli aggiornamenti tra collocazioni sono manuali. Prima di scrivere, rileggere la destinazione; conservare revisioni precedenti; confrontare differenze; registrare decisione e provenienza. In caso di stessa revisione e hash diversi, mantenere entrambe le varianti fino alla scelta documentata. Ogni accesso ai nodi richiede autorizzazione distinta.

## Decisioni e ipotesi

Decisioni: base pubblica leggibile e separata; materiali dei nodi privati esclusi; nessuna importazione di storia privata; nessuna licenza scelta automaticamente; nessuna modifica alle credenziali o visibilità dei repository preesistenti.

Ipotesi: una mappa di componenti e riferimenti logici può favorire la continuità tra nodi. Restano da progettare collocazione autorevole dello stato, ruoli operativi, sincronizzazione e risoluzione dei conflitti. Non si presume un aumento di capacità o autonomia dalla sola distribuzione.

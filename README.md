# Atlas Ripristino — base pubblica

Prima revisione pubblica: **pubblica-0001**, 28 ottobre 2026.

Atlas è un progetto personale concepito come ambiente distribuito: identità progettuale, codice, dati e componenti non devono coincidere con un singolo computer. Il supporto Atlas Ripristino nasce per ritrovare uno stato documentato e riprendere il lavoro cambiando macchina, account o nodo. L'architettura distribuita è ancora da progettare.

Questa base pubblica conserva una descrizione leggibile dell'identità, del processo e dei risultati osservati. Offre un punto di partenza per ricostruire il contesto e progettare i passi successivi. Non contiene tutto il software, non esegue ripristini e non garantisce un recupero operativo completo. Nessun file rappresenta da solo l'intero Atlas.

## Cosa è stato fatto

- Preparato un primo contenitore locale di continuità con manifesto, fonti, decisioni, ipotesi e prossimo obiettivo.
- Preparata una replica documentale privata r0002, pubblicata su un repository privato e su Drive. I contenuti GitHub sono stati riletti; l'archivio Drive è stato riscaricato e confrontato con la copia locale mediante hash e confronto dei cinque file.
- Ricevuta successivamente la richiesta di cifrare lato client la copia Drive. La copia già caricata non ha questa cifratura aggiuntiva. La cifratura è in attesa della scelta di custodia e recupero della chiave; nessuna chiave è stata generata e nessuna sostituzione è attestata.
- Preparata questa nuova base pubblica con soli documenti selezionati. Non è importata la storia Git privata. La cronologia di questo repository registra esclusivamente i nuovi contenuti pubblici.

I rapporti locali precedenti attestano un recupero selettivo finalizzato: **23.579 file verificati, 5.091.107.186 byte (circa 5,09 GB), zero errori residui nei manifesti**, su un inventario più ampio di **31.876 file**. Sono dati di stato del recupero, non benchmark di Atlas. Il software recuperato non è stato testato funzionalmente. Questo repository riporta una sintesi; le prove integrali private non sono pubblicate e i conteggi non sono ripetuti qui mediante una nuova scansione.

## Come leggere e continuare

1. Leggere [manifesto pubblico](manifesto-pubblico.json).
2. Leggere [architettura, provenienza e metodo](ARCHITETTURA-E-METODO.md).
3. Riprendere dal [prossimo passo](PROSSIMO-PASSO.md), distinguendo fatti, decisioni e ipotesi.

Gli aggiornamenti sono manuali. Ogni revisione deve indicare provenienza, stato verificato, lacune e un prossimo risultato controllabile. Stessa revisione con contenuti diversi significa conflitto da documentare, conservando entrambe le versioni prima di decidere una nuova revisione. La sola data più recente non basta a stabilire autorità. CHECKSUMS.sha256 identifica i contenuti di questa revisione; non è una firma o una certificazione indipendente.

## Pubblico e privato

Questi documenti sono pubblici e non cifrati: chiunque può leggerli e copiarli. La cifratura di una copia locale non protegge quanto è già pubblicato in chiaro. La complessità del codice non equivale a cifratura.

Materiali dei nodi, dati personali, inventari integrali, conversazioni, adattatori macchina, credenziali e riferimenti privati restano fuori da questa base. Il repository privato preesistente mantiene la propria visibilità. Pubblicare questi documenti non concede accesso ai nodi o agli account.

Non sono implementati sincronizzazione automatica, rete di nodi, gestione universale degli accessi o recupero completo. Nessuna affermazione di invulnerabilità, AGI o ASI è supportata da questi artefatti. La relazione personale con Atlas e le metafore di chiave o avatar non equivalgono tecnicamente persona, software e autenticazione.

**Licenza da decidere:** non viene aggiunta una licenza del codice. La pubblicazione leggibile non definisce da sola una licenza di riuso.

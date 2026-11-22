# Informativa sulla privacy — Estingui: prestiti e mutui

**Ultimo aggiornamento:** 22 novembre 2026

**Versione:** 2.5

---

## In breve

I dati sui suoi debiti — finanziamenti, importi, date, pagamenti — **restano solo sul suo dispositivo** e non vengono inviati a nessun server, né a noi
né a terzi. Non c'è un account, non c'è pubblicità, non ci sono strumenti di
analisi o tracciamento: il sito conta solo, come numeri per giorno e senza identificativi, quante volte le app controllano gli aggiornamenti e quanti aggiornamenti vengono scaricati (punto 3.6). I calcoli funzionano anche senza internet.

La connessione serve solo per quattro cose, spiegate per esteso più sotto:
**attivare e rinnovare Premium** (l'app invia la chiave e un'impronta del
telefono ricavata con un hash, mai i suoi dati finanziari), **controllare
gli aggiornamenti** dell'app Android e, nella versione web, **tenere aperta
la sessione Premium** nel browser e **caricare il video tour**. L'acquisto
avviene su PayPal.

---

## 1. Titolare del trattamento

Hubert Montero / Sviluppatore indipendente / Estingui: prestiti e mutui  
Email: [premium@marketplace-apps.com](mailto:premium@marketplace-apps.com)

Per qualsiasi questione relativa ai suoi dati può scrivere all'indirizzo
qui sopra.

---

## 2. Distribuzione al di fuori di Google Play

Estingui non è distribuita tramite Google Play: si scarica solo da
marketplace-apps.com, come pacchetto (APK) firmato con la chiave dello
sviluppatore. Quando cambia il primo o il secondo numero della versione, il
pacchetto viene analizzato con VirusTotal prima della pubblicazione: se l'analisi non
rileva problemi, la scheda di Estingui sul sito riporta il collegamento
al rapporto pubblico, che può aprire e consultare.

Android può mostrare un avviso di «fonte sconosciuta» perché l'app non
proviene dal Play Store. Quanto descritto in questa informativa vale per
l'app così come la scarica dal nostro sito.

La versione Android scaricata da marketplace-apps.com controlla da sola se è
disponibile un aggiornamento (veda il punto 3.6). Estingui esiste anche in
versione web, che si usa dal browser: dove le due versioni si comportano in
modo diverso, questa informativa lo indica.

---

## 3. Quali dati tratta l'app

### 3.1 Dati che inserisce Lei

Per calcolare i piani di ammortamento l'app conserva quello che scrive:

- nome e tipo del finanziamento
- nome del finanziatore
- importo erogato, rata, numero di rate, tasso
- costi, commissioni e imposte
- date di decorrenza e scadenza
- eventuali pagamenti registrati e note

Sono **dati personali di natura finanziaria**. Nell'app Android vengono
salvati esclusivamente in un database nella memoria privata dell'app sul suo dispositivo, che solo questa applicazione può leggere. Nella versione web
vengono salvati in un database del suo browser, sul computer o sul telefono
che sta usando.

**Non vengono trasmessi a nessuno.** Non esiste un server che li riceve, non
abbiamo modo di leggerli, e non possiamo recuperarli se li perde. Nella versione web, se cancella i dati di navigazione del sito, li cancella anche dall'app.

### 3.2 Preferenze e consensi

L'app registra la data in cui ha accettato le condizioni d'uso, quale versione del testo ha accettato e la sua preferenza sul tema chiaro o
scuro. Anche questi dati restano sul dispositivo. Nella versione web
l'accettazione è ricordata anche da un cookie tecnico (punto 3.5) e il
browser conserva la data in cui ha visto il video tour (punto 3.7).

### 3.3 Attivazione di Premium sul telefono (app Android)

La chiave Premium vale al massimo su **2 telefoni**. Per far rispettare
questo limite, quando attiva la chiave l'app si collega al nostro server
delle licenze (un servizio su Cloudflare gestito da noi) e invia:

- la **chiave di licenza**, che al suo interno contiene l'indirizzo email
  dell'acquirente, il piano e la data di scadenza;
- un'**impronta del telefono**: un codice ricavato con una funzione di hash dal nome dell'app e dall'identificativo Android del telefono, poi accorciato. **L'identificativo Android non viene mai
  inviato in chiaro** e l'impronta è diversa per ogni app, quindi non serve
  a collegare il suo uso di app diverse.

La stessa richiesta viene ripetuta in automatico quando l'attivazione va
rinnovata, cioè al massimo ogni 30 giorni e solo se il telefono è connesso.
Il server risponde con un'attivazione firmata che l'app conserva e verifica
sul telefono, anche senza connessione.

Il server **non conserva la sua email** e non conserva la chiave in chiaro.
Conserva soltanto:

- l'hash della chiave;
- l'impronta del telefono;
- il tipo di piano (per esempio mensile, annuale o triennale);
- la data di attivazione e quella dell'ultimo rinnovo;
- se cambia telefono, la data dell'ultima sostituzione automatica (è
  consentita una sostituzione ogni 30 giorni);
- se una chiave viene bloccata (per esempio dopo un rimborso o un abuso),
  l'hash di quella chiave.

Oggi Estingui **non offre una prova gratuita**. Il server delle licenze ha
però una regola comune a tutte le app: una chiave di prova si può attivare
una sola volta per telefono, e per questo il server verifica se la stessa
impronta l'ha già usata. La regola conta solo se riceve una chiave di prova.

Il pulsante **Disattiva su questo telefono**, nella schermata Premium,
cancella dal server la riga che lega la chiave a quel telefono e libera il
posto.

Leggere l'identificativo Android serve solo a questo, avviene solo quando attiva o rinnova Premium, cioè un servizio che ha chiesto Lei, e non è usato
per pubblicità, statistiche o profilazione.

### 3.4 Acquisto e invio della chiave

L'acquisto di Premium avviene su **PayPal**: l'app apre il suo browser su
una pagina di PayPal, esterna alla nostra app. Fornisce i dati di pagamento
direttamente a PayPal, non a noi: **non riceviamo né vediamo mai i dati della sua carta o del suo conto PayPal**. PayPal tratta quei dati come
titolare autonomo, secondo la propria [informativa
privacy](https://www.paypal.com/it/legalhub/paypal/privacy-full).

Dopo il pagamento PayPal invia una notifica al nostro server delle licenze,
che genera la chiave e gliela invia all'indirizzo email del pagamento tramite
il servizio di invio email **Resend** (mittente
`premium@marketplace-apps.com`). Nel nostro server delle licenze l'email non
viene salvata. Restano invece, come per ogni vendita, i dati dell'operazione
che PayPal mette a disposizione del venditore nel suo conto PayPal (per
esempio nome, email, importo e data).

### 3.5 Versione web: sessione Premium e cookie

Nella versione web la chiave si verifica sul server del marketplace
(marketplace-apps.com). Se è valida, il server apre una **sessione Premium**
e la lega al suo browser con un cookie tecnico (non leggibile
dagli script della pagina). Per far funzionare la sessione il server
conserva: l'hash del codice di sessione, l'hash della chiave, l'email, il
piano e la scadenza ricavati dalla chiave, e la data in cui la sessione è stata aperta.

Con la stessa chiave possono essere aperte al massimo **2 sessioni**:
aprendone una terza, la più vecchia viene chiusa e cancellata. Per limitare
i tentativi di indovinare le chiavi, il server tiene in memoria per poco tempo, legato al suo indirizzo IP, il numero
di tentativi, senza
salvarlo in un database.

**Sessione web e recesso.** La data in cui la sessione viene aperta serve anche come prova di quando ha iniziato a usare Premium: se al pagamento ha chiesto di iniziare subito e poi recede entro 14 giorni, tratteniamo solo la parte proporzionale ai giorni trascorsi dall'attivazione (art. 57, comma 3, del Codice del consumo e condizioni di vendita di marketplace-apps.com), e come attivazione nella versione web contiamo la sessione più vecchia che risulta per quella chiave. L'email contenuta nella chiave ci permette di collegare la sessione al suo acquisto. Base giuridica: esecuzione del contratto (art. 6, par. 1, lett. b, GDPR) e legittimo interesse a poter dimostrare quanta parte del servizio è stata fornita (art. 6, par. 1, lett. f). Le sessioni si cancellano 30 giorni dopo la scadenza della licenza (quelle senza scadenza dopo 400 giorni) e subito se la chiave viene bloccata dopo un rimborso per recesso.

La versione web usa solo cookie tecnici: quello della sessione Premium, che
dura fino alla scadenza della licenza (al massimo 400 giorni per le licenze
senza scadenza), e quello che ricorda l'accettazione delle condizioni d'uso
(400 giorni). Non usa cookie di profilazione, di analisi o di terze parti. L'unica misura statistica è il conteggio del tempo d'uso descritto qui sotto, che non usa cookie e produce solo numeri aggregati.

**Conteggio del tempo d'uso.** Mentre la versione web è aperta e la scheda è in primo piano, il browser invia al sito, a intervalli regolari, un segnale con il nome dell'app, l'etichetta del link social che ha usato per arrivare (se c'è) e un codice casuale creato per quella scheda; quando la scheda non è più visibile, il browser invia un ultimo segnale di pausa. Il segnale non contiene nulla di ciò che fa o scrive nell'app e serve solo a contare quante persone usano la versione web in quel momento e per quanto tempo (per fasce di durata). Il codice è conservato nella memoria di sessione del browser, non in un cookie, e si cancella quando chiude la scheda; sul server viene cancellato entro 6 minuti dall'ultimo segnale e restano solo conteggi per giorno, app, social e fascia di durata. L'indirizzo IP serve solo a proteggere il servizio dagli abusi: resta nella memoria temporanea del server per pochi minuti e non viene salvato (come per qualsiasi pagina, Vercel, che ospita il sito, lo vede nei suoi registri tecnici). Base giuridica: legittimo interesse a misurare in forma aggregata l'uso delle versioni web (art. 6, par. 1, lett. f, GDPR); poiché il codice serve solo alle nostre statistiche aggregate, secondo le Linee guida del Garante su cookie e altri strumenti di tracciamento (10 giugno 2021) non è necessario il consenso previsto dall'art. 122 del Codice privacy. Maggiori dettagli nell'[informativa di marketplace-apps.com](https://marketplace-apps.com/it/privacy) (punti 3.2 bis e 4).

### 3.6 Aggiornamenti dell'app (Android)

All'avvio l'app controlla, collegandosi ai nostri server, se c'è una nuova versione
e, se c'è, scarica il pacchetto di installazione dai server del nostro fornitore
di archiviazione (Cloudflare).
È Lei a confermare l'installazione.

Queste richieste **non contengono dati personali** né identificativi del
telefono o della licenza: come per qualsiasi collegamento a internet, i server
vedono l'indirizzo IP da cui arriva la richiesta.

Il sito non salva l'indirizzo IP né altri dati di queste richieste: tiene solo numeri per giorno, cioè quante volte le app hanno chiesto la versione (sono aperture, non persone) e quanti aggiornamenti sono stati scaricati, per app e versione. Da questi numeri non si può risalire a nessuno. Anche dal server delle licenze ricaviamo solo numeri complessivi per app (per esempio quante attivazioni e quante vendite), senza vedere impronte, chiavi o email. Come per ogni pagina web, i fornitori dell'infrastruttura (Vercel per il sito, Cloudflare per i file) ricevono l'indirizzo IP, il tipo di client (User-Agent) e l'orario della richiesta e li tengono nei loro registri tecnici per i tempi previsti dai loro servizi.

### 3.7 Versione web: video tour

Nella versione web, al primo accesso, quando sceglie **Guarda il tour** e una
volta dopo l'attivazione di Premium, il browser carica un video che mostra
come si usa l'app, con i sottotitoli, dai server del nostro fornitore di archiviazione (Cloudflare).
I sottotitoli sono nella lingua del browser, se disponibile, altrimenti in
inglese.

Come per qualsiasi file scaricato da internet, il browser invia a Cloudflare
l'indirizzo IP, il tipo di browser e di sistema operativo (user-agent) e
l'indirizzo del sito da cui parte la richiesta (referer). **Nessun dato che ha inserito nell'app viene inviato** e la richiesta non usa cookie. L'app
salva solo nel suo browser la data in cui ha visto il video, per non riproporglielo a ogni accesso.

### 3.8 Cosa l'app NON fa

- non raccoglie dati di utilizzo, statistiche o diagnostica su di Lei (il sito conta solo, come numeri anonimi per giorno, le aperture e gli aggiornamenti: punto 3.6)
- non usa strumenti di analisi, tracciamento o pubblicità
- non chiede di creare un account
- non accede a rubrica, posizione, fotocamera, foto o messaggi
- non si collega ai suoi conti bancari e non chiede credenziali
- non crea profili pubblicitari; l'impronta del telefono è usata solo per
  l'attivazione di Premium (punto 3.3)
- non invia a nessun server i dati sui suoi debiti

---

## 4. Base giuridica e finalità

| Finalità | Base giuridica |
|---|---|
| Calcolare e mostrare piani di ammortamento, TAEG e simulazioni | Esecuzione del servizio richiesto (art. 6.1.b GDPR) |
| Conservare i suoi finanziamenti fra un'apertura e l'altra | Esecuzione del servizio richiesto |
| Registrare l'accettazione delle condizioni d'uso | Obbligo legale e legittimo interesse a dimostrare l'informativa resa (artt. 6.1.c e 6.1.f) |
| Generare la chiave Premium e inviargliela via email dopo il pagamento | Esecuzione del contratto di acquisto (art. 6.1.b) |
| Attivare Premium sul telefono, rinnovare l'attivazione e far rispettare il limite di 2 telefoni per chiave; sessione Premium nella versione web (massimo 2 sessioni) | Esecuzione del contratto di licenza (art. 6.1.b): il limite fa parte delle condizioni dell'offerta Premium |
| Impedire gli abusi: una sola chiave di prova per telefono, una sostituzione automatica del telefono ogni 30 giorni, blocco delle chiavi revocate, limite ai tentativi di verifica | Legittimo interesse (art. 6.1.f) a prevenire usi fraudolenti delle licenze. Usiamo solo hash e date, cioè il minimo indispensabile, e si tratta di regole descritte in questa informativa: riteniamo che non prevalgano sui suoi diritti. Può opporsi (punto 8) |
| Controllare e scaricare gli aggiornamenti dell'app Android | Legittimo interesse (art. 6.1.f) a mantenere l'app sicura e corretta; vengono trattati l'indirizzo IP, il tipo di client e l'orario della richiesta, nei registri tecnici dei fornitori; il sito ne ricava solo numeri per giorno senza identificativi |
| Mostrare il video tour nella versione web | Legittimo interesse (art. 6.1.f) a spiegarle come si usa l'app; vengono trattati solo i dati tecnici della richiesta (indirizzo IP, user-agent, referer) |
| Conservare la data delle sessioni web come prova dell'inizio dell'uso, per calcolare l'eventuale rimborso proporzionale in caso di recesso entro 14 giorni (punto 3.5) | Esecuzione del contratto (art. 6.1.b) e legittimo interesse a poter dimostrare quanta parte del servizio è stata fornita (art. 6.1.f) |
| Conteggio del tempo d'uso della versione web: contare in forma aggregata quante persone la usano e per quanto tempo (punto 3.5) | Legittimo interesse (art. 6.1.f) a misurare in forma aggregata l'uso della versione web. Può opporsi (punto 8) |
| Conservare i dati delle vendite | Obbligo legale fiscale e contabile (art. 6.1.c) |

Il cookie della sessione web e la lettura dell'identificativo Android sono
strettamente necessari a fornire il servizio Premium che ha chiesto: per questo non le chiediamo un consenso separato (art. 122 del Codice privacy,
d.lgs. 196/2003).

Non trattiamo i suoi dati per marketing, profilazione o decisioni
automatizzate.

---

## 5. Documenti che genera Lei

### 5.1 Esportazione dei dati

Con Menu → **Esporta i miei dati** ottiene in qualsiasi momento un **file
di testo in italiano**, che si legge senza programmi particolari, con tutti i dati che ha inserito: i
debiti attivi ed estinti, i costi, i pagamenti registrati e le impostazioni
(data e versione delle avvertenze accettate, tema). Prima di salvarlo vede sullo schermo che cosa contiene.

Nella stessa finestra c'è anche la **Versione per programmi (JSON)**: gli
stessi dati in un formato strutturato, di uso comune e leggibile da altri
programmi, che può usare per portarli in un altro servizio.

In nessuno dei due file sono riportati la chiave Premium e il codice di
attivazione: la chiave la ritrova nell'email di acquisto.

Il file viene prodotto sul dispositivo e non viene inviato né a noi né ad
altri: è Lei a decidere se salvarlo, condividerlo o cancellarlo. Sul
telefono può salvarlo o condividerlo con le app che sceglie; nella versione
web si scarica sul computer.

### 5.2 Report PDF

L'app genera il piano di ammortamento in PDF **localmente**, senza servizi
esterni di conversione. Può salvarlo sul dispositivo o condividerlo con chi vuole. Il documento contiene i dati del finanziamento che ha inserito: ne valuti il contenuto prima di inviarlo a terzi.

### 5.3 Condivisione delle convenzioni di calcolo

L'app offre una funzione facoltativa che permette di condividere **il modo in cui il suo finanziatore calcola**: se arrotonda o tronca gli interessi, a
quanti decimali fissa il tasso, che tipo di costi applica. Serve a rendere i
calcoli più precisi per chi ha contratti simili.

Questa funzione **non trasmette nulla automaticamente**. Prima di
condividere, l'app le mostra il testo esatto che invierebbe; è Lei ad aprire il menu di condivisione del sistema operativo e a scegliere il
destinatario.

Il contenuto **non comprende** importi, tassi, date, durate, numero di rate,
il nome che ha dato al debito, le note, né alcun identificativo suo o del dispositivo. Descrive il contratto tipo, non la persona.

---

## 6. Per quanto tempo restano

| Dato | Per quanto tempo |
|---|---|
| Dati sui debiti, preferenze, consensi, chiave e attivazione salvate nell'app | Sul suo dispositivo, finché non li cancella o non disinstalla l'app (nella versione web, finché non cancella i dati del sito dal browser). Non ne esiste una copia altrove. |
| Attivazioni Premium sul server (hash della chiave, impronta, piano, date) | Finché la licenza è in uso. La riga viene cancellata subito se usa **Disattiva su questo telefono**, e comunque quando il telefono non rinnova l'attivazione per 90 giorni (per esempio dopo la scadenza della licenza o se smette di usare l'app). |
| Attivazioni con una chiave di prova, se ce ne sono (per il controllo «una prova per telefono») | 12 mesi dall'attivazione della prova. |
| Data dell'ultima sostituzione del telefono | 60 giorni dall'ultima sostituzione. |
| Hash delle chiavi bloccate | Finché serve a impedire l'uso della chiave bloccata (solo il codice cifrato della chiave). |
| Sessioni Premium della versione web (con l'email contenuta nella chiave e la data di apertura) | Fino alla scadenza della licenza o finché la sessione non viene chiusa da una più recente; le sessioni scadute vengono cancellate entro 30 giorni (quelle senza scadenza dopo 400 giorni) e subito se la chiave viene bloccata dopo un rimborso per recesso. |
| Dati delle vendite visibili nel conto PayPal del venditore | Per il tempo previsto dalla normativa fiscale e contabile. |
| Email inviate tramite Resend e registri tecnici dei fornitori (per esempio indirizzi IP nei log dei server) | Per brevi periodi tecnici, secondo le politiche di conservazione dei singoli fornitori (punto 7). |
| Numeri giornalieri di aperture e aggiornamenti (per app e versione, senza IP né identificativi) | Non sono dati personali; restano finché servono a capire quanto sono usate le app. |
| Messaggi che ci scrive | Per il tempo necessario a gestire la sua richiesta. |


---

## 7. Destinatari e trasferimenti

I dati che inserisce sui suoi debiti non lasciano il dispositivo, se non nei
documenti che è Lei a generare e condividere. Per Premium, gli
aggiornamenti e la versione web ci serviamo di questi fornitori, che
trattano i dati per nostro conto come responsabili del trattamento (art. 28
GDPR), salvo PayPal, che agisce come titolare autonomo:

| Fornitore | Cosa fa |
|---|---|
| Cloudflare (Stati Uniti) | Server delle licenze, database delle attivazioni, file degli aggiornamenti e del video tour della versione web |
| Vercel (Stati Uniti) | Hosting del sito marketplace-apps.com e dei suoi servizi (verifica della chiave web, controllo versione, passaggio del download degli aggiornamenti) |
| Supabase | Database del marketplace, ospitato nell'Unione europea (Irlanda), in cui sono salvate le sessioni Premium web |
| Resend (Stati Uniti) | Invio delle email con la chiave |
| PayPal (Europe) S.à r.l. et Cie, S.C.A. (Lussemburgo) | Pagamento, come titolare autonomo |

Alcuni di questi fornitori hanno sede negli Stati Uniti o usano
infrastrutture distribuite in più Paesi, quindi i dati possono essere
trattati fuori dall'Unione europea. In questi casi il trasferimento si basa
sulla decisione di adeguatezza della Commissione europea per le aziende
aderenti all'EU-U.S. Data Privacy Framework (decisione di esecuzione (UE)
2023/1795, art. 45 GDPR) oppure sulle clausole contrattuali tipo approvate
dalla Commissione (art. 46 GDPR), secondo quanto indicato da ciascun
fornitore nei propri documenti.

Non vendiamo né cediamo i suoi dati a nessuno.

---

## 8. I suoi diritti

Il GDPR le riconosce il diritto di accedere ai suoi dati, correggerli, cancellarli, limitarne il trattamento, opporsi e riceverli in un formato
leggibile.

Per i dati che stanno solo sul suo dispositivo **li esercita direttamente
dall'app**, senza dover scrivere a nessuno:

| Diritto | Come |
|---|---|
| Accesso e portabilità (artt. 15 e 20) | Menu → **Esporta i miei dati**: un file di testo leggibile con tutti i dati che ha inserito e, nella stessa finestra, la **Versione per programmi (JSON)**, in formato strutturato per portarli altrove. Gratuito. |
| Rettifica (art. 16) | Può modificare o eliminare qualsiasi finanziamento in qualunque momento. |
| Cancellazione (art. 17) | Menu → **Elimina tutti i miei dati**. Immediata e definitiva. Oppure può disinstallare l'app. |
| Cancellazione dell'attivazione Premium dal server | Premium → **Disattiva su questo telefono**. |

Per i dati sul server (attivazioni e sessioni web) e
per l'**opposizione** ai trattamenti basati sul legittimo interesse (art.
21) ci scriva all'indirizzo del punto 13. Poiché sul server delle licenze non teniamo la sua email, per trovare i dati che la riguardano le chiederemo la
chiave di licenza. Se si oppone ai controlli anti-abuso, non potremo più
attivare Premium con quella chiave.

Se ritiene che il trattamento violi il GDPR può rivolgersi al [Garante per
la protezione dei dati personali](https://www.garanteprivacy.it) o
all'autorità di controllo dello Stato in cui risiede.

---

## 9. Sicurezza

I dati sono salvati nella memoria privata dell'applicazione, che il sistema
operativo isola dalle altre app installate. Sui dispositivi Android moderni
con blocco schermo attivo, questa memoria è cifrata dal sistema.

Le consigliamo di tenere attivo il blocco schermo del telefono e di
mantenere aggiornato il sistema operativo.

Le comunicazioni con i nostri server avvengono in HTTPS. Sui server
conserviamo, dove possibile, solo hash al posto dei dati originali. La
chiave di licenza contiene la sua email in forma leggibile: **non
condividerla** con altri.

**Nessuna copia altrove.** Poiché non conserviamo copie, se perde o formatta il telefono, o disinstalla l'app, i dati non sono recuperabili. Con
**Esporta i miei dati** può conservare una copia leggibile di quello che ha inserito, ma l'app non la reimporta: per ripartire su un altro telefono
dovrà inserire di nuovo i finanziamenti.

---

## 10. Minori

L'app non è destinata a minori di 16 anni e non raccoglie consapevolmente
dati che li riguardino.

---

## 11. L'app non è un servizio di consulenza

Estingui è **uno strumento di calcolo e simulazione**. I risultati sono
stime basate sui dati che inserisce e su ipotesi semplificatrici, e non
costituiscono consulenza finanziaria, fiscale o legale, né una proposta
contrattuale.

Le condizioni del suo finanziamento sono quelle del contratto che ha sottoscritto. Il conteggio estintivo vincolante è esclusivamente quello
rilasciato dal finanziatore: l'app serve a verificarlo, non a sostituirlo.

Verifichi sempre gli importi con il suo istituto di credito o con un
professionista prima di prendere decisioni.

In particolare, il confronto **«investi o estingui»** usa classi di
rendimento ipotetiche, non previsioni sui mercati: i rendimenti reali
possono essere diversi, anche negativi. Il calcolo dei costi da recuperare
per un **prestito già estinto** è una stima: se e quanto le spetta dipende dal suo contratto e dalle norme applicabili, e il risultato non è un parere
legale.

---

## 12. Modifiche a questa informativa

Se cambieremo questa informativa in modo sostanziale, glielo mostreremo all'apertura dell'app e le chiederemo di prenderne visione. La data in cima
al documento indica l'ultimo aggiornamento.

---

## 13. Contatti

[premium@marketplace-apps.com](mailto:premium@marketplace-apps.com)

Rispondiamo senza ingiustificato ritardo e al più tardi entro un mese, come
previsto dall'art. 12 GDPR (il termine può essere prorogato di due mesi per
richieste complesse; in quel caso glielo comunichiamo).

---
lab:
    title: 'Lab 3.3: Lab di fine modulo Dynamics 365 Customer Service'
    module: 'Modulo 3: Concetti fondamentali su Dynamics 365 Customer Service'
---

Modulo 3: Concetti fondamentali su Dynamics 365 Customer Service
========================

## Lab pratico 3.3. Lab di fine modulo Dynamics 365 Customer Service

## Scenario del lab

La società ABC è specializzata nella produzione, vendita, installazione e manutenzione di attrezzature di sicurezza. I prodotti dell'azienda includono telecamere di sicurezza sia interne sia esterne, sensori di umidità e antincendio, servizi di monitoraggio e altro ancora. 

La società ABC utilizza le applicazioni Dynamics 365 per interagire con tutti i propri clienti in diverse aree dell'organizzazione, dalle vendite all'assistenza. 

**Vendite e marketing**

La società ABC si rivolge direttamente ai propri clienti residenziali attraverso campagne di marketing mirate. Il targeting dei clienti viene eseguito in base alla città e ad altri fattori. I materiali di marketing vengono inviati tramite e-mail e, in base all'interazione con l'e-mail, i clienti vengono guidati di conseguenza. 

Mentre alcuni dei prodotti più piccoli sono venduti tramite rivenditori, la maggior parte dei prodotti viene venduta direttamente ai consumatori dal personale di vendita interno.

Internamente, l'azienda si concentra su due aree principali: 

- **Clienti residenziali.** I clienti residenziali generalmente sono alla ricerca di singoli componenti o vogliono acquistare un'intera soluzione domestica. Questi cicli di vendita di regola sono più brevi e provengono da social media, siti Web, segnalazioni o contatti diretti dal prospect. Poiché solitamente i clienti residenziali sono per lo più focalizzati su prodotti specifici o installazioni più piccole, i loro cicli di vendita durano in genere alcuni giorni o settimane. 

- **Clienti aziendali.** I venditori aziendali si concentrano sui clienti che hanno bisogno di soluzioni aziendali più specializzate e personalizzate. Le vendite aziendali in genere interessano più sedi con comunicazioni collegate e spesso richiedono più risorse per il completamento del progetto. Questi cicli di vendita solitamente sono più lunghi e includono molti più componenti. 

È importante che tutti i venditori della società ABC dispongano degli strumenti, delle risorse e delle indicazioni necessari, indipendentemente dalla loro area di interesse durante la vendita ai clienti. 

**Installazione del sistema.**

Il processo di installazione per le apparecchiature di sicurezza acquistate varia in base al tipo di cliente a cui è stata effettuata la vendita. 

- **Clienti residenziali.** Poiché le installazioni residenziali in genere richiedono meno di un giorno, vengono eseguite da dipendenti interni. Dopo la vendita, viene creato un ordine di lavoro e viene identificato e pianificato un tecnico qualificato per eseguire l'installazione. 

- **Clienti aziendali.** Le distribuzioni aziendali possono durare mesi e richiedere un manager del progetto per supervisionare le operazioni quotidiane. Questo include la creazione di piani di progetto, la definizione di team di progetto e la pianificazione delle risorse. 

**Assistenza e supporto.**

Dopo aver installato i sistemi, la società ABC fornisce supporto post-vendita. Se un cliente ha un problema, può contattare l'assistenza clienti. Un agente tenterà di collaborare con il cliente in remoto per risolvere il problema. Se non è possibile risolvere il problema in remoto, l'agente di supporto può riassegnare il problema a un ordine di lavoro che verrà pianificato ed elaborato da un tecnico sul campo qualificato. 

## Obiettivi

Capita spesso che i clienti riscontrino problemi con le apparecchiature. Quando un problema viene riscontrato, viene segnalato all'help desk dell'azienda ABC. I problemi possono essere segnalati in diversi modi. In alcuni casi, le apparecchiature possono segnalare i problemi in modo proattivo. Quando vengono segnalati problemi, gli operatori provano a risolverli in remoto. Se non riescono, verrà inviato un tecnico sul campo per risolvere il problema. Di recente, sono stati riparati molti sensori che si sono spenti. Si è notato che il problema era causato da un bug del software. Si vuole creare un articolo della Knowledge Base a cui gli altri operatori possano fare riferimento quando riscontrano lo stesso problema. 

In quanto operatore dell'help desk, si è responsabili della gestione dei problemi segnalati dai clienti. Si è appena ricevuta una chiamata da Piper Smith. Piper sta segnalando che uno dei sensori del suo sistema non funziona. È necessario registrare la chiamata di Piper e cercare di trovare una soluzione al problema. 

Al termine del lab, saranno state completate le attività seguenti:

- Creazione di un articolo della Knowledge Base. 

- Gestione dei casi tramite l'hub del servizio clienti.

- Creazione e registrazione di un caso. 

- Gestione del record di un caso per l'intero ciclo di vita. 

## Configurazione del lab

  - **Tempo stimato**: 45 minuti

## Istruzioni

## Esercizio 1. Creare e pubblicare un articolo della Knowledge Base

### Attività 1. Creare un articolo della Knowledge Base

1. Se non è già aperta, aprire l'applicazione **Hub del servizio clienti di Dynamics 365**. 

2. Usando la barra di spostamento sul lato sinistro della schermata, selezionare **Articoli della Knowledge Base**. 

3. Per visualizzare facilmente gli articoli in fasi diverse, selezionare la freccia a discesa accanto a **Articoli attivi personali**. 

4. Selezionare **Bozze di articoli**. 

5. Usare il selettore vista per selezionare **Articoli approvati**.  

6. Usare il selettore vista per tornare ad **Articoli attivi personali**.

7. Sulla **barra dei comandi** selezionare il pulsante **Nuovo**. Dopo l'apertura del nuovo record, selezionare la freccia a discesa accanto al campo **Motivo stato** nell'intestazione del record nella parte superiore. Impostare **Lingua** su **Italiano - Italia**.

8. Completare l'articolo come segue:

	- **Titolo.** Il sensore non funziona - Proprie iniziali

	- **Parole chiave.** Sensore, danneggiato, non funzionante

	- **Descrizione.** Consente di gestire gli scenari in cui un sensore non funziona. 

9. Immettere il testo seguente nel casella di testo della **finestra di progettazione del contenuto**.   

	Il sensore attualmente non funziona

	Quando un sensore non funziona come dovrebbe, seguire questa procedura:

	1. Individuare e sostituire le batterie del dispositivo. 

	2. Tenere premuto il pulsante di accensione per 3 secondi. 

	3. Il dispositivo si aprirà in modalità di amministrazione. 

	4. Tenere premuto il pulsante Associa finché la spia luminosa passa da rossa a blu. 

	5. Premere il pulsante Reimposta. 

	Dopo il riavvio, il dispositivo sarà di nuovo online. 

10. Nell'editor contenuto selezionare il testo Il sensore attualmente non funziona.

11. Impostare le dimensioni del carattere su **22** e selezionare il pulsante **Grassetto**. 

12. Sulla **barra dei comandi** selezionare il pulsante **Salva** per salvare l'articolo della Knowledge Base e lasciarlo aperto. 

13. In **Nuovo processo** selezionare la fase **Autore** e impostare il campo **Argomento articolo** su **Servizio**. 

14. Impostare il campo **Contrassegna per la revisione** su **Completato**.

15. Selezionare il pulsante **Fase successiva** per passare alla fase **Verifica**.

16. Sulla **barra dei comandi** selezionare il pulsante **Salva e chiudi** per salvare le modifiche e chiudere l'articolo.

 

### Attività 2. Gestire un articolo tramite il processo di approvazione

Nella maggior parte delle organizzazioni, dopo che l'autore dell'articolo ha creato il record, viene eseguito un processo di approvazione prima di pubblicarlo. Il più delle volte questa operazione viene eseguita da un'altra persona. In questo caso si opererà come responsabile approvazione. 

1. Negli articoli della Knowledge Base passare alla visualizzazione **Articoli proposti** per vedere quali articoli necessitano dell'approvazione. 

2. Aprire l'articolo **Il sensore non funziona - Proprie iniziali** appena creato.

3. In **Nuovo processo** selezionare la fase **Verifica**. Impostare il campo **Verifica** su **Rifiutato**.

4. Nella schermata Rifiuta articolo della Knowledge Base immettere il testo **Questi passaggi non funzionano quando provo a replicarli**.

5. Selezionare il pulsante **Rifiuta**.

6. Selezionare **Salva e chiudi** per chiudere il record dell'articolo.

7. Usando il **selettore vista**, impostare la vista su **Articoli attivi personali**. 

8. Aprire il record **Il sensore non funziona - Proprie iniziali**.

9. Una volta aperto il record, selezionare la scheda **Riepilogo**. 

10. Nella **sequenza temporale** del record una nota indicava che l'articolo era stato rifiutato e il motivo del rifiuto. 

11. Selezionare la scheda **Contenuto**.

12. Nel campo **Contenuto** posizionare il cursore prima della parola **Premere** al Passaggio 5. 

13. Premere **INVIO**. 

14. Immettere il testo "Premere il pulsante Conferma". 

15. Sulla **barra dei comandi** selezionare il pulsante **Salva e chiudi**.

16. Usare il **selettore vista** e passare alla vista **Articoli proposti**.

17. Aprire l'articolo **Il sensore non funziona - Proprie iniziali**. 

18. Nel flusso del processo aziendale **Nuovo processo** selezionare la fase **Verifica**.

19. Impostare lo stato su **Approvato**. 

20. Quando viene richiesto di confermare l'approvazione dell'articolo, selezionare **OK**. 


### Attività 3. Approvare l'articolo della Knowledge Base

Ora che l'articolo è stato approvato, verrà pubblicato in modo che sia disponibile per chi lavora ai casi. 

1. Selezionare il pulsante **Fase successiva** per passare alla fase **Pubblica**. 

2. Contrassegnare **Imposta associazioni prodotto** come **Completato**. 

3. Impostare **Data scadenza** su **Un anno da oggi alle 12:00**. 

4. Selezionare il pulsante **Fine** per completare il processo. 

5. Sulla **barra dei comandi** dell'articolo selezionare il pulsante **Pubblica**. 

6. Verificare che siano selezionate le opzioni seguenti:

	- **Pubblica:** Ora

	- **Stato pubblicazione:** Pubblicato

	- **Data scadenza:** Un anno da oggi alle 12:00

	- **Stato scadenza:** Scaduto

	- **Stato scadenza:** Scaduto

7. Selezionare il pulsante **Pubblica** per pubblicare l'articolo.


## Esercizio 2. Gestire un caso di supporto tecnico per l'intero ciclo di vita


### Attività 1. Creare e gestire un caso

1. Se non è già aperta, aprire l'applicazione **Hub del servizio clienti di Dynamics 365**. 

2. Usando la barra di spostamento sul lato sinistro della schermata, selezionare **Dashboard**. Verrà aperto il dashboard **Livello 1**. 

3. Sulla **barra dei comandi** selezionare il pulsante **Mostra filtro elementi grafici**.


4. Altri dashboard forniscono ulteriori dettagli sul carico del caso corrente. Per lavorare con altri dashboard, usare il selettore dashboard. Modificare il dashboard da **Dashboard di livello 1** a **Dashboard di livello 2**. 

 

Ora che è stata acquisita familiarità con alcuni dei diversi dashboard e viste, si creerà il record di un nuovo caso per aiutare Piper con il suo problema.

 

10. Usando la barra di spostamento sul lato sinistro della schermata, selezionare **Casi**. 

11. Sulla **barra dei comandi** selezionare il pulsante **Nuovo** per creare un nuovo record di caso.

12. Completare il nuovo record del caso come segue:

	- **Titolo caso:** Il sensore non funziona - Proprie iniziali

	- **Cliente:** Piper Smith

	- **Origine:** Telefono

	- **Descrizione.** Piper sta segnalando che uno dei sensori che ha ricevuto non funziona correttamente. 

13. Selezionare il pulsante **Salva** per salvare il record e lasciarlo aperto. 

14. Usando la **sequenza temporale del record**, selezionare l'**icona del segno più** per creare un nuovo impegno. 

15. Nel menu visualizzato selezionare **Telefonata**.

16. Nella schermata **Creazione rapida: Telefonata** completare l'impegno come segue:

	- **Oggetto:** Richiamare Piper

	- **Direzione:** In uscita

	- **Numero di telefono:**  888 555-1762

	- **Durata:** 15 minuti.

17. Selezionare il pulsante **Salva e chiudi**. 

18. In **Processo telefono - caso** selezionare la fase **Identifica**.

19. Selezionare il pulsante **Fase successiva** per passare alla fase **Ricerca**. 

20. Selezionare la **X** nella finestra a comparsa della fase **Ricerca** per rimuovere la finestra in modo da poter continuare a lavorare. 

21. Usando la **sequenza temporale del record**, selezionare l'**icona del segno più** per creare un nuovo impegno. 

22. Nel menu visualizzato selezionare **Attività**.

23. Nella schermata **Creazione rapida: Telefonata** completare l'impegno come segue:

	- **Oggetto:** Cercare il problema di Piper

	- **Descrizione.** Usare la Knowledge Base per cercare il problema di Piper. 

	- **Durata:** 30 minuti.

24. Selezionare il pulsante **Salva e chiudi**. 

25. Sul lato destro della schermata del caso individuare e selezionare l'icona a forma di libro **Conoscenza**. Sarà direttamente sotto l'icona della chiave inglese.

26. Si noti che il titolo del caso viene automaticamente usato come testo da cercare. Individuare e selezionare l'articolo **Il sensore non funziona - Proprie iniziali** creato in precedenza. 

27. Verrà visualizzato l'intero contenuto dell'articolo. Selezionare l'icona **Pollice su** nella parte inferiore dell'articolo per indicare che l'articolo è stato utile. 

28. Selezionare l'icona **Collega questo articolo al record corrente**. Verificare che venga visualizzato il testo **Collegato a caso**. 

 

### Attività 2. Chiudere il caso

Ora che è stata identificata una soluzione al problema del cliente, si procederà a risolvere il caso, Il primo passaggio della chiusura di un caso consiste nel chiudere gli impegni aperti associati al caso. 

1. Nella **sequenza temporale** del record del caso passare il puntatore del mouse sull'attività **Cercare il problema di Piper** creata in precedenza**.** Selezionare l'**icona del segno di spunta** Contrassegna come completato per completare l'impegno. 

2. Nella finestra **Chiudi attività** verificare che lo stato sia Completato e selezionare il pulsante **Chiudi**. Lo stato dell'attività dovrebbe essere **Chiusa**. 

3. Passare il puntatore su **Richiamare Piper** creato in precedenza**.** Selezionare l'**icona del segno di spunta** Contrassegna come completato per completare l'impegno. 

4. Nella schermata **Chiudi telefonata** verificare che **Stato** sia **Completato** e che **Stato** sia **Effettuata**. Selezionare il pulsante **Chiudi**. Verificare che l'impegno sia visualizzato come chiuso nella sequenza temporale. 

5. In **Processo telefono - caso** selezionare la fase **Ricerca**, quindi selezionare **Fase successiva** per passare alla fase **Risolvi**. 

6. Nella fase **Risolvi** selezionare il pulsante **Fine** per completare il flusso del processo. 

7. Sulla **barra dei comandi** del record del caso selezionare il pulsante **Risolvi caso**.

8. Nella finestra **Risolvi caso** impostare il campo **Risoluzione** su **Articolo della Knowledge Base**. 

9. Verificare che i campi **Tempo totale** e **Tempo fatturabile** siano impostati su **45 minuti**. Questo valore rappresenta il tempo totale impiegato per entrambi gli impegni Telefonata e Attività aggiunti al record. 

10. Selezionare il pulsante **Risolvi** per completare il processo. 


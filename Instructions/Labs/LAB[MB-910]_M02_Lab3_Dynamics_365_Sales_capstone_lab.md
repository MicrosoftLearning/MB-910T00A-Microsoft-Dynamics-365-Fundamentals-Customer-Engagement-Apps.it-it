---
lab:
    title: 'Lab 2.3: Lab di fine modulo Dynamics 365 Sales'
    module: 'Modulo 2: Concetti fondamentali su Dynamics 365 Sales'
---

Modulo 2: Concetti fondamentali su Dynamics 365 Sales
========================

## Lab pratico 2.3. Lab di fine modulo Dynamics 365 Sales

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

Si lavora come rappresentante di vendita del reparto vendite residenziali dell'azienda ABC. Anche se molti dei lead hanno origine da eventi sponsorizzati dall'azienda, campagne di marketing ed elenchi acquistati, spesso si ricevono richieste direttamente dai clienti. Quando si ricevono tali richieste, è necessario immettere manualmente e gestire tali lead per l'intero ciclo di vita delle vendite. 

Di recente si è ricevuta una chiamata da una persona di nome Piper Smith. Nel quartiere in cui risiede si è verificata una serie di furti e pertanto vorrebbe acquistare delle apparecchiature di sicurezza per la casa. Si immetterà il lead per Piper nel sistema, si proverà a qualificarla e la si farà avanzare attraverso il ciclo di vendita. 

Al termine del lab, saranno state completate le attività seguenti:

- Immettere un lead in Dynamics 365 Sales

- Qualificare e convertire un lead in un'opportunità di vendita.

- Gestire gli impegni giornalieri associati a un'opportunità. 

- Aggiungere un'offerta a un'opportunità. 

- Chiudere un'opportunità di vendita. 

- Generare una fattura. 

## Configurazione del lab

  - **Tempo stimato**: 30 minuti

## Istruzioni
  
## Esercizio 1. Creare e qualificare un lead in Dynamics 365 Sales


### Attività 1. Creare un nuovo lead

1. Se necessario, aprire una scheda del browser con modalità InPrivate e visitare la pagina [Https://home.Dynamics.com](https://home.dynamics.com/) 

2. Quando richiesto, accedere con le credenziali utente fornite dall'istruttore. 

3. Nell'elenco di applicazioni visualizzato selezionare **Hub delle vendite**.

4. Usando la barra di spostamento sul lato sinistro della schermata, selezionare **Lead**. 

5. Per visualizzare tutti i lead correnti nel sistema, selezionare la freccia verso il basso accanto a **Lead aperti personali** e quindi selezionare **Clienti potenziali attivi** dal menu visualizzato. 

6. Per tornare all'elenco dei propri lead, selezionare la freccia verso il basso accanto a Clienti potenziali attivi e scegliere **Lead aperti personali** dal menu visualizzato. 

7. Successivamente, si creerà un nuovo lead per Piper Smith. Nella vista **Lead aperti personali** selezionare il pulsante **Nuovo** sulla barra dei comandi.

8. Completare il nuovo record del lead come segue:

	- **Argomento:** Ricerca di apparecchiature di sicurezza - "Proprie iniziali"

	- **Nome:** Piper

	- **Cognome:** Smith - Proprie iniziali

	- **Telefono cellulare:** 888 555-1762

	- **Email:** piper@sample.com


9. Selezionare il pulsante **Salva** sulla barra dei comandi per salvare il nuovo lead e lasciarlo aperto.

10. Si noti il flusso del processo aziendale **Lead - opportunità** nella parte superiore del record. Selezionare la **fase di qualificazione**. Completare la fase come segue:

	- **Intervallo di tempo acquisti:** Trimestre corrente

	- **Budget stimato:** 10000 

	- **Processo di acquisto:** Singolo

	- **Identifica decisore:** Completato

11. Selezionare la **X** nella finestra della fase per chiuderla. 

12. Passare alla **sequenza temporale** del record al centro dello schermo e selezionare l'**icona del segno più** per aggiungere un nuovo impegno. 

13. Nel menu visualizzato selezionare **Telefonata**.

14. Nella schermata Creazione rapida: Telefonata completare la telefonata come segue:

	- **Oggetto:** Ricerca di apparecchiature di sicurezza per la casa

	- **Numero di telefono:** 888 555-1762

	- **Direzione:** In arrivo

	- **Descrizione.** In seguito ad alcuni eventi verificatisi nel suo quartiere, vuole acquistare un sistema di sicurezza. 

15. Selezionare il pulsante **Salva e chiudi**.

16. Si noti che l'impegno **Ricerca di apparecchiature di sicurezza per la casa** ora è visualizzato nella **sequenza temporale** del record. Posizionare il puntatore del mouse sull'impegno e selezionare l'**icona del segno di spunta** Chiudi impegno per contrassegnare la telefonata come completata. 

17. Nella finestra **Chiudi telefonata** verificare che lo stato sia impostato su **Completato** e selezionare il pulsante **Chiudi**.

 

**IMPORTANTE:** non chiudere il record del lead. Lasciarlo aperto perché verrà usato nell'attività successiva. 

 

### Attività 2. Qualificare il lead come opportunità

Dopo una visita a casa di Piper, si stabilisce che è abbastanza interessata da giustificarne l'avanzamento e che si dispone dei prodotti e dei servizi di cui ha bisogno. A questo punto, è necessario qualificare il record del lead. Verrà creato un record opportunità correlato e si passerà alla fase successiva del processo di vendita Lead - opportunità. 

1. Sulla **barra dei comandi** selezionare il pulsante **Qualifica**. 

2. Dopo che il sistema avrà qualificato il lead, verrà creato un nuovo record Opportunità e il processo aziendale passerà alla fase **Sviluppa**. Selezionare la fase **Qualifica** per visualizzare il record del lead originale. 

3. Selezionare la fase **Qualifica** per tornare al lead.

4. Selezionare il pulsante **Salva e chiudi** per chiudere il record del lead creato. 

 

 

## Esercizio 2. Gestire un'opportunità di vendita in Dynamics 365 Sales

Dopo aver qualificato il lead come opportunità, è ora di gestire l'opportunità durante il ciclo di vita.

### Attività 1. Gestire un'opportunità di vendita e creare un'offerta 

1. Usando la barra di spostamento sul lato sinistro della schermata, selezionare **Opportunità**. 

2. Selezionare la freccia a discesa accanto alla vista **Opportunità aperte personali** e dal menu visualizzato selezionare **Tutte le opportunità**.

3. Sulla barra dei comandi selezionare Mostra grafico. Si noti che il grafico **Clienti principali** viene visualizzato in base alla tabella Opportunità. 

4. Selezionare la freccia verso il basso accanto a **Clienti principali** e dal menu visualizzato selezionare **Pipeline di vendita**.

5. Selezionare la parte Qualifica del grafico a imbuto. Si noti che l'elenco di opportunità viene modificato per visualizzare le opportunità in fase di qualificazione. 

6. Selezionare un punto qualsiasi dello spazio vuoto del grafico per visualizzare nuovamente tutte le opportunità aperte. 

7. Selezionare la freccia verso il basso accanto alla vista **Opportunità aperte** e dal menu visualizzato selezionare **Opportunità aperte personali**. **Ricerca di apparecchiature di sicurezza - Proprie iniziali** sarà probabilmente il solo elemento visualizzato e il grafico dovrebbe corrispondere. 

8. Sulla **barra dei comandi** selezionare il pulsante **Nascondi grafico**. 

9. Aprire l'elemento **Ricerca di apparecchiature di sicurezza - Proprie iniziali** creato in precedenza quando si è qualificato il lead. Si noti che il record è già nella fase **Sviluppa** poiché è stato creato da un lead precedentemente qualificato.  

10. Nell'intestazione dell'opportunità **Ricerca di apparecchiature di sicurezza - Proprie iniziali** nella parte superiore del record selezionare la freccia verso il basso accanto al campo Proprietario. 

11. Completare come segue:

	- **Data chiusura prevista:** Domani

	- **Ricavi previsti:** 12.500,00

12. Passare alla **sequenza temporale del record** al centro dello schermo e selezionare l'**icona del segno più** per aggiungere un nuovo impegno. 

13. Nel menu visualizzato selezionare **Appuntamento**.

14. Nella schermata **Creazione rapida: Appuntamento** completare come segue:

	- **Oggetto:** Breve incontro - "Proprie iniziali"

	- **Posizione:** Online

	- **Ora di inizio**: Domani alle 10:00

	- **Ora di fine:** Domani alle 10:30

15. Sulla barra dei comandi selezionare **Salva e chiudi**.

16. Nel flusso del processo aziendale Lead - opportunità selezionare la fase **Sviluppa**. Si noti che è necessario identificare le parti interessate e i concorrenti.

17. Selezionare la **X** nella finestra della fase per chiuderla in modo da poter continuare a lavorare. 

18. Nella griglia secondaria **Parti interessate** si noti che **Piper** è già definita come parte interessata. 

19. Nella griglia secondaria Team di vendita selezionare i **puntini di sospensione verticali**. Nel menu visualizzato selezionare **Nuova connessione**. 

20. Nel campo **Cerca** immettere il testo **Amministratore** e selezionare il record **Amministratore di sistema**. Al termine, selezionare il pulsante **Aggiungi**. L'amministratore di sistema ora dovrebbe essere visualizzato nel team di vendita. In caso contrario, selezionare il pulsante **Aggiorna** sulla barra dei comandi. 

21. Nella griglia secondaria Concorrenti selezionare i **puntini di sospensione verticali**. Nel menu visualizzato selezionare **Aggiungi concorrente esistente**. 

22. Nella schermata **Cerca record** selezionare **Nuovo record** e quindi **Concorrenti**.

23. Nella schermata Creazione rapida: **Concorrente** impostare il campo **Nome** su **Coho Security - "Proprie iniziali"**.

24. Selezionare il pulsante **Salva e chiudi**.

25. Assicurarsi che il record Coho Security appena creato sia selezionato e selezionare il pulsante **Aggiungi**. 

26. Selezionare la fase **Sviluppo** nel flusso del processo aziendale **Lead - opportunità**, quindi impostare entrambi i passaggi **Identifica parti interessate** e **Identifica concorrenti** su **Completato**. 

27. Selezionare il pulsante **Fase successiva** per passare alla fase **Proponi**.

28. Nella fase **Proponi** contrassegnare **Identifica team di vendita** come **Completato**.

29. Selezionare la **X** nella fase Proponi per chiudere la finestra della fase. 

30. Nel record dell'opportunità selezionare la scheda **Offerte**. 

31. Nella griglia secondaria Offerte selezionare il pulsante **Nuova offerta**.

 

**IMPORTANTE:** poiché in questi ambienti sono distribuite più app proprietarie, è possibile che il modulo dell'offerta attualmente visualizzato non sia quello corretto per la funzionalità correlata alle vendite. Se il testo sotto il nome dell'offerta **Ricerca di apparecchiature di sicurezza - Proprie iniziali** è: **Offerta . Offerta**, significa che è stato caricato il modulo corretto. Se il testo è **Offerta . Informazioni Field Service**, sarà necessario cambiarlo. Se è necessario cambiarlo, selezionare la freccia verso il basso accanto a **Offerta . Informazioni Field Service**. Nel menu visualizzato selezionare **Offerta**. 

 

### Attività 2. Gestire un'offerta

Dopo aver creato un'offerta correlata, la si preparerà per presentarla a un cliente. In circostanze normali, è probabile che si aggiungano i prodotti al record dell'offerta prima di inviarla a un cliente. Poiché si sta lavorando in ambienti condivisi, si salterà l'aggiunta delle righe dell'offerta e si eseguirà l'invio dell'offerta. 


1. È ora necessario selezionare un listino prezzi da allegare all'opportunità.  In **Listino prezzi** nel riquadro a sinistra selezionare l'icona Cerca e quindi selezionare **Office 365 Stati Uniti (esempio)** tra le opzioni. Sulla **barra dei comandi** selezionare il pulsante **Attiva offerta** per attivare l'offerta. 

2. Dopo aver creato l'offerta, si aggiornerà il record dell'opportunità in modo che rispecchi i nuovi dati. Nel record Offerta selezionare l'opportunità **Ricerca di apparecchiature di sicurezza** - **"Proprie iniziali"** nel campo **Opportunità** nella sezione **Informazioni sulle vendite**. Il record dell'opportunità verrà visualizzato. 

3. Nel record dell'opportunità selezionare la fase **Proponi**. 

4. Contrassegnare **Sviluppa proposta**, **Completa verifica interna** e **Proposta corrente** come **completate** e selezionare il pulsante **Fase successiva** per passare alla fase **Chiudi**. 

5. Nella fase **Chiudi** contrassegnare i passaggi **Completa proposta finale**, **Presenta proposta finale**, **Invia nota di ringraziamento** e **Archivia debriefing** come **Completato**. 

6. Impostare **Conferma data decisione** su **Data odierna**. 

7. Selezionare il pulsante **Fine**. 

8. Selezionare la **X** nella finestra della fase Chiudi per chiuderla. 

9. Selezionare la scheda **Offerte**. 

10. Aprire l'offerta **Ricerca di apparecchiature di sicurezza - Proprie iniziali**. 

11. Sulla **barra dei comandi** selezionare il pulsante **Crea ordine**.

12. Nella finestra Crea ordine completare come segue:

	- **Motivo stato:** Acquisito

	- **Data acquisizione:** Data odierna

	- **Chiudi opportunità:** Sì

	- **Calcola i ricavi effettivi dalle offerte:** No

	- **Ricavi effettivi:** $12.500

13. Selezionare il pulsante **OK**. 

Il sistema crea un nuovo ordine cliente relativo all'elemento. Chiuderà inoltre sia il record dell'offerta sia il record dell'opportunità correlato. Dopo aver completato tutte le operazioni, l'ordine verrà aperto nella schermata. Lasciare l'ordine aperto. 

###  

### Attività 3. Gestire l'ordine e la fattura

Dopo aver creato un ordine cliente, l'ordine verrà chiuso e verrà generata una fattura. In circostanze normali, si aggiungerebbero i prodotti dal record dell'offerta all'ordine cliente. Poiché si sta lavorando in ambienti condivisi, si proseguirà come se i prodotti fossero stati aggiunti. 

 

1. Sulla **barra dei comandi** selezionare il pulsante **Evadi ordine**. 

2. Nella schermata Evadi ordine completare come segue:

	- **Motivo stato:** Completato

	- **Data evasione:** Data odierna

3. Selezionare il pulsante **Evadi**. 

4. Sulla **barra dei comandi** dell'ordine selezionare il pulsante **Crea fattura**. 

5. Sulla **barra dei comandi** selezionare il pulsante **Fattura pagata**. Selezionare OK.

---
lab:
    title: 'Lab 4.3: Lab di fine modulo Dynamics 365 Field Service'
    module: 'Modulo 4: Concetti fondamentali su Dynamics 365 Field Service'
---

Modulo 4: Concetti fondamentali su Dynamics 365 Field Service
========================

## Lab pratico 4.3. Lab di fine modulo Dynamics 365 Field Service

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

L'azienda ABC, in genere, invierà tecnici sul campo per lavorare agli elementi dei clienti in uno dei tre scenari seguenti. 

- Quando viene acquistato un nuovo sistema di sicurezza che deve essere installato.

- Quando un operatore dell'help desk non riesce a risolvere in remoto il problema di un cliente.

- Quando un cliente contatta direttamente l'azienda per richiedere assistenza sul posto. 

Di recente l'azienda Active Transport, Inc. ha contattato il supporto tecnico per un problema con una telecamera del sistema di sicurezza. Il tecnico dell'help desk non è riuscito a risolvere il problema in remoto, quindi è necessario inviare un tecnico sul campo. In questo scenario si eseguiranno le operazioni seguenti:

- Conversione del record di un caso in ordine di lavoro

- Pianificazione di un ordine di lavoro

- Risoluzione di un ordine di lavoro tramite l'app per dispositivi mobili 

## Configurazione del lab

  - **Tempo stimato**: 45 minuti

## Istruzioni

## Esercizio 1. Creare un caso e riassegnare a un ordine di lavoro 

### Attività 1. Creare un record di caso

1. Se non è già aperta, aprire l'applicazione **Dynamics 365 Field Service**. 

2. Usando la barra di spostamento sul lato sinistro della schermata, selezionare **Casi**. 

3. Sulla **barra dei comandi** selezionare il pulsante **Nuovo** per creare un nuovo record di caso.

4. Completare il nuovo record del caso come segue:

	- **Titolo caso:** Telecamera inattiva

	- **Cliente:** Best For You Organics Company

	- **Origine:** Telefono

	Salvare il record.

5. Selezionare la scheda **Field Service**.

6. Impostare il campo **Tipo di incidente** su **Telecamera inattiva**. (Crea nuovo)

7. Sulla **barra dei comandi** selezionare il pulsante **Salva e chiudi** per salvare e chiudere il record del caso. 

 

### Attività 2. Creare manualmente un ordine di lavoro

Più avanti si tornerà al record del caso creato. Ora si esaminerà come creare manualmente il record di un ordine di lavoro. 

 

1. Usando la struttura di spostamento a sinistra, selezionare **Ordini di lavoro**.

2. Sulla **barra dei comandi** selezionare il pulsante **Nuovo** per creare un nuovo ordine di lavoro.

3. Completare i dettagli dell'ordine di lavoro come segue:

	- **Account servizio:** Margie's Travel

	- **Listino prezzi:** Office 365 Stati Uniti (esempio)

	- **Tipo di ordine di lavoro:** Servizio

	- **Tassabile:** No

	Salvare il record e assegnare il tipo di incidente primario

	- **Tipo di incidente primario:** Ventola guasta (Crea nuovo)

4. Prendere nota del numero dell'ordine di lavoro per assicurarsi di usare l'ordine di lavoro corretto in seguito. 

5. Selezionare la scheda **Impostazioni**.

6. Impostare il campo **Area di servizio** su **WA**.

7. In **Preferenze** configurare le preferenze per il tempo come segue:

	- **Tempo da promessa:** Oggi alle 9:00

	- **Tempo a promessa:** Oggi alle 11:00

8. Selezionare **Salva e chiudi** per salvare le modifiche e chiudere il nuovo ordine di lavoro.

 

### Attività 3. Generare un ordine di lavoro da un caso

In alternativa, per generare gli ordini di lavoro, è possibile eseguire l'escalation dei record dei casi. In questo esempio, si eseguirà l'escalation del record del caso Telecamera inattiva creato in precedenza. 

 

1. Usando la struttura di spostamento a sinistra, selezionare **Casi**. 

2. Aprire il caso **Telecamera inattiva** creato in precedenza. 

3. Sulla **barra dei comandi** selezionare il pulsante **Converti in ordine di lavoro**. 

4. Al termine della creazione dell'ordine di lavoro, selezionare il pulsante **OK** nella schermata popup per visualizzare i dettagli dell'ordine di lavoro. 

 

Entrambi gli ordini di lavoro appena creati sono pronti per la pianificazione. 

## Esercizio 2. Pianificare elementi con Dynamics 365 Field Service  

### Attività 1. Pianificare direttamente da un ordine di lavoro

1. Usando la struttura di spostamento a sinistra, selezionare **Scheda di pianificazione**.

2. Nell'angolo in alto a destra della schermata impostare l'esperienza **New Schedule Board** (Nuova scheda di pianificazione) come **attivata**. 

3. Usando il campo di ricerca **Cerca risorse**, immettere Aidan Knaggs. 

4. Nella parte inferiore dello schermo nel pannello Requisiti selezionare **Ordini di lavoro non pianificati**.  Se il pannello Requisiti non è visualizzato, selezionare la freccia nella parte inferiore dello schermo per espanderlo. 

5. Individuare l'ordine di lavoro **Munson's Pickles** creato dal record del caso. Ricordare il numero dell'ordine di lavoro. 

6. Trascinare il record **Munson's Pickles** e posizionarlo in un intervallo di tempo aperto per il record del contatto di Aidan. 

7. Talvolta potrebbe essere necessario ripianificare un ordine di lavoro in base a conflitti tecnici o altri elementi. Questa operazione può essere facilmente eseguita dai dispatcher usando la scheda di pianificazione. 

 

### Attività 2. Pianificare con la scheda di pianificazione

1. Usando la struttura di spostamento a sinistra, selezionare **Scheda di pianificazione**.

2. Usando il campo di ricerca **Cerca risorse**, immettere il nome del proprio account utente. Dovrebbe essere visualizzato il record della risorsa.

3. Nella parte inferiore dello schermo nel pannello Requisiti selezionare **Ordini di lavoro non pianificati**.  Se il pannello Requisiti non è visualizzato, selezionare la freccia nella parte inferiore dello schermo per espanderlo. 

4. Individuare l'ordine di lavoro **Active Transport** creato dal record del caso. Ricordare il numero dell'ordine di lavoro. 

5. Trascinare il record **Active Transport** e posizionarlo in un intervallo di tempo aperto per il record utente. Il testo sarà verde se l'intervallo di tempo corrisponde a quello preferito dal cliente.

6. Talvolta potrebbe essere necessario ripianificare un ordine di lavoro in base a conflitti tecnici o altri elementi. Questa operazione può essere facilmente eseguita dai dispatcher usando la scheda di pianificazione. 

7. Selezionare la casella Cerca risorse nella scheda di pianificazione (disponibile sopra la colonna del nome della risorsa), immettere **Brady** e individuare l'ordine di lavoro pianificato per **Brady Hannon** più avanti nel corso del giorno. 

8. **Fare clic con il pulsante destro del mouse** sull'elemento pianificato. Nel menu visualizzato selezionare **Sostituisci risorsa**. Selezionare la casella Seleziona/Cerca, selezionare il record della risorsa e selezionare **Riassegna**.

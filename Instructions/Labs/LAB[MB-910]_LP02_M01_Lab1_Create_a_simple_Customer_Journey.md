---
lab:
  title: 'Percorso di apprendimento 2 - Lab 2.1: Creare un semplice percorso clienti'
  learning path: Explore the fundamentals of Dynamics 365 Marketing
  module: Explore Dynamics 365 Marketing
---

Percorso di apprendimento 2 - Modulo 1: Esplorare Dynamics 365 Marketing
========================

## Practice Lab 2.1 - Creare un semplice Percorso clienti

## Obiettivi

Durante questo esercizio si vedrà che i percorsi del cliente sono un componente chiave di Dynamics 365 Marketing. Si creeranno percorsi del cliente come base per qualsiasi iniziativa di marketing, al fine di orientare il percorso intrapreso da un cliente prende mentre interagisce con il processo di marketing dell'organizzazione. L'obiettivo del percorso, una volta completato, è la conversione in ricavi.

## Configurazione del lab

  - **Tempo stimato**: 20 minuti

## Istruzioni

1. Aprire **l'applicazione di marketing Dynamics 365**.

2. Passare all'area **in Marketing in uscita**. 

3. Usando lo spostamento a sinistra, selezionare **Contatti** nel gruppo **Clienti**

4. Sulla barra dei comandi selezionare **Nuovo**.

5. Completare la pagina **Nuovo contatto** come segue.

    - **Nome:** Jenny

    - **Cognome**: Jones (Iniziali)

    - **Posta elettronica**: Immettere un indirizzo e-mail da cui è possibile ricevere la posta.

    - **Indirizzo 1 Strada 1:** 101 Esempio Ave

    - **Indirizzo 1: Città:** Fargo

    - **Indirizzo 1 Stato:** ND

    - **Indirizzo 1 Zip/Postal:** 58103

6. Dopo aver completato il contatto, selezionare **Salva e chiudi**.

7. Nella barra dei comandi selezionare Di nuovo nuovo per creare un altro contatto

8. Completare il secondo contatto come segue:

    - **Nome:** Marco

    - **Cognome**: Gomez (iniziali)

    - **Posta elettronica**: Immettere un indirizzo e-mail da cui è possibile ricevere la posta.

    - **Indirizzo 1 Strada 1:** 101 Esempio Ave

    - **Indirizzo 1: Città:** Fargo

    - **Indirizzo 1 Stato:** ND

    - **Indirizzo 1 Zip/Postal:** 58103

**NOTA:** vengono usate le stesse informazioni sull'indirizzo, per facilitare il riconoscimento dei contatti come dati di esempio. 

9. Dopo aver completato il contatto, selezionare **Salva e chiudi**.

**IMPORTANTE:** A causa dell'indirizzo, le impostazioni di rilevamento duplicati dei sistemi possono essere attivate. Se si ottiene la schermata di record duplicata, selezionare il pulsante **Ignora e salva** . 

**Attività 2: Creare il segmento Fargo** 

Verrà quindi creato un nuovo segmento e verranno aggiunti i contatti creati nell'attività precedente. 

1. Usando lo spostamento a sinistra, selezionare **Segmenti** in **Marketing**. 

    2. Sulla barra dei comandi selezionare **Nuovo**.

    3. Nel menu a discesa visualizzato selezionare **New Dynamic Segment** (Nuovo segmento dinamico).

    4. Nella finestra di dialogo **Modelli segmento** visualizzata selezionare **Ignora** per chiuderla e passare alla schermata **Nuovo segmento**.

    5. Selezionare **Aggiungi blocco di query** per creare una query sull'entità contatto. 

    6. Selezionare il testo fantasma **Selezionare l'attributo** . 

    7. Digitare quindi "città" per filtrare l'elenco e scegliere **Indirizzo 1: Città** dall'elenco.

    8. Mantenere l'elenco a discesa successivo impostato su **È**. 

    9. Selezionare il terzo elenco a discesa, che contiene il tipo di testo fantasma **da cercare** e digitare **Fargo**.

    10. Fare clic per selezionare il campo **Nome** nella parte superiore della query e immettere **Contatti Fargo (Iniziali).** Potrebbe essere necessario selezionare la freccia giù accanto al motivo stato.

    11. Selezionare **Salva** sulla barra dei comandi per salvare il segmento.

    12. Selezionare **Go Live** per pubblicare il segmento.

    13. Attendere circa un minuto e quindi selezionare **Aggiorna** sulla barra dei comandi per aggiornare la pagina. 

    14. Ora dovrebbe essere possibile vedere che è stata aggiunta una scheda **Membri**. 

 

**Attività 3: Creare un messaggio di posta elettronica semplice.** 

Verrà quindi creato un semplice messaggio di posta elettronica da un modello esistente che sarà in grado di sfruttare con il percorso del cliente. 

1. Usando lo spostamento a sinistra, selezionare **Messaggi di posta elettronica marketing** nel gruppo **Esecuzione marketing** .

2. Usando la barra dei comandi selezionare **+ Nuovo**.

3. Nella schermata **Modelli di posta elettronica marketing** selezionare **1 colonna** e quindi scegliere il pulsante **Seleziona** . 

4. Nell'angolo superiore sinistro del messaggio di posta elettronica selezionare il campo Nome. (Avrà testo simile a Email ypl (1 colonna))

5. Modificare il nome su '**Sample Email Message (Your Initials)'**.

6. Nel campo **Oggetto** immettere il testo "**Vedere cosa è necessario offrire".** 

7. Fare clic sul pulsante **Salva**. 

8. Selezionare il pulsante **Go live** per pubblicare il messaggio di posta elettronica. 

 

**Attività 4: Creare un percorso cliente.** 

Ora che abbiamo il pubblico di destinazione, nonché l'attività di posta elettronica che vogliamo usare, creeremo un Percorso clienti. 

1. Usando lo spostamento a sinistra, selezionare **Percorsi cliente** nel gruppo **Di esecuzione marketing** .

    2. Usando la barra dei comandi selezionare **+ Nuovo**.

    3. Nel popup **Modelli di Percorso clienti** selezionare **Ignora** per iniziare a creare un nuovo percorso da zero.

    4. Selezionare **Set audience (Imposta destinatari)** o, in alternativa, selezionare **+** . Verificare che il **tipo di origine** sia impostato su **Segmento** e selezionare il segmento **Fargo Contacts** (Your Initials) creato nell'esercizio precedente. Il primo riquadro viene popolato con il nome del segmento e nel riquadro **Destinatari** vengono visualizzate le proprietà del segmento.

    5. Selezionare **+** nel canvas e quindi scegliere **Invia un messaggio e-mai** dal menu di scelta rapida.

    6. Nella sezione Invia un messaggio di posta elettronica selezionare **Esempio Email Messaggio** (Iniziali) creato in precedenza.

    7. Selezionare la scheda Generale nella parte superiore del record del percorso cliente. Immettere le informazioni seguenti nella scheda **Generale**:

        - **Nome: Fargo** Customer Journey (Iniziali)

        - **Data e ora di inizio**: Immettere la data odierna

        - **Data e ora di fine**: Un mese da oggi

        - **Fuso orario**: Selezionare il fuso orario locale

8. Sulla barra dei comandi selezionare **Salva** per salvare il lavoro eseguito finora.

9. A questo punto, il percorso è pronto per l'uso. Per avviare il percorso, pubblicarlo selezionando **Go live** sulla barra dei comandi.

 

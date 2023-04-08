---
lab:
  title: 'Lab 2.1: Creare un semplice percorso clienti'
  learning path: Explore the fundamentals of Dynamics 365 Marketing
  module: Explore Dynamics 365 Marketing
---

Modulo 1: Esplorare Dynamics 365 Marketing
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

    - **Cognome**: Jones

    - **Posta elettronica**: Immettere un indirizzo e-mail da cui è possibile ricevere la posta.

    - **Indirizzo 1 Strada 1:** 101 Esempio Ave

    - **Indirizzo 1: Città:** Fargo

    - **Indirizzo 1 Stato:** ND

    - **Indirizzo 1 Zip/Postal:** 58103

6. Dopo aver completato il contatto, selezionare **Salva e chiudi**.

7. Nella barra dei comandi selezionare Di nuovo nuovo per creare un altro contatto

8. Completare il secondo contatto come segue:

    - **Nome:** Marco

    - **Cognome**: Gomez

    - **Posta elettronica**: Immettere un indirizzo e-mail da cui è possibile ricevere la posta.

    - **Indirizzo 1 Strada 1:** 101 Esempio Ave

    - **Indirizzo 1: Città:** Fargo

    - **Indirizzo 1 Stato:** ND

    - **Indirizzo 1 Zip/Postal:** 58103

**NOTA:** vengono usate le stesse informazioni sull'indirizzo, per facilitare il riconoscimento dei contatti come dati di esempio. 

9. Verrà quindi definito un segmento che include i nuovi clienti. Usando la struttura di spostamento a sinistra, selezionare Segmenti in Marketing. 

10. Sulla barra dei comandi selezionare **Nuovo**.

11. Nel menu a discesa visualizzato selezionare **New Dynamic Segment** (Nuovo segmento dinamico).

12. Nella finestra di dialogo **Modelli segmento** visualizzata selezionare **Ignora** per chiuderla e passare alla schermata **Nuovo segmento**.

13. Selezionare **Aggiungi blocco di query** per creare una query sull'entità contatto. 

14. Selezionare il testo fantasma **Selezionare l'attributo** . 

15. Digitare quindi "città" per filtrare l'elenco e scegliere **Indirizzo 1: Città** dall'elenco.

16. Mantenere l'elenco a discesa successivo impostato su **Uguale**. 

17. Selezionare il terzo elenco a discesa, che contiene il testo fantasma **Immettere testo** e digitare **Fargo**.

18. Fare clic per selezionare il campo **Nome** nella parte superiore della query e immettere Contatti Fargo.

19. Selezionare **Salva** sulla barra dei comandi per salvare il segmento.

20. Selezionare **Go Live** per pubblicare il segmento. 

21. Attendere circa un minuto e quindi selezionare **Aggiorna** sulla barra dei comandi per aggiornare la pagina. 

22. Verrà ora visualizzato che è stata aggiunta una scheda **Membri** 

23. Usando lo spostamento a sinistra, selezionare **Percorsi cliente** nel gruppo **Di esecuzione marketing** .

24. Usando la barra dei comandi selezionare **+ Nuovo**.

25. Nel popup **Modelli di Percorso clienti** selezionare **Ignora** per iniziare a creare un nuovo percorso da zero.

26. Selezionare **Set audience (Imposta destinatari)** o, in alternativa, selezionare **+** . Selezionare il segmento Clienti Fargo creato nell'esercizio precedente. Il primo riquadro viene popolato con il nome del segmento e nel riquadro **Destinatari** vengono visualizzate le proprietà del segmento.

27. Selezionare **+** nel canvas e quindi scegliere **Invia un messaggio e-mai** dal menu di scelta rapida.

28. Selezionare il messaggio di posta elettronica di esempio creato in precedenza,

29. Selezionare la scheda Generale nella parte superiore del record del percorso cliente. Immettere le informazioni seguenti nella scheda **Generale**:

30. **Name**: Fargo Customer Journey

31. **Data e ora di inizio**: Immettere la data odierna

32. **Data e ora di fine**: Un mese da oggi

33. **Fuso orario**: Selezionare il fuso orario locale

34. Sulla barra dei comandi selezionare **Salva** per salvare il lavoro eseguito finora.

35. A questo punto, il percorso è pronto per l'uso. Per avviare il percorso, pubblicarlo selezionando **Go live** sulla barra dei comandi.

 

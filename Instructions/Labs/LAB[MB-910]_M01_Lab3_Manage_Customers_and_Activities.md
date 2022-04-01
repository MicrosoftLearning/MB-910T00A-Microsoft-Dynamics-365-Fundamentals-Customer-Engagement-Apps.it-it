---
lab:
  title: 'Lab 1.3: Gestire clienti e attività'
  module: 'Module 1: Learn the Fundamentals of Dynamics 365 Marketing'
ms.openlocfilehash: f35d4d7adec885e3ba5b9e3ba67937f44666cd72
ms.sourcegitcommit: 600ccb76999dbc6fe9f7eaece0c235b0e85706ed
ms.translationtype: HT
ms.contentlocale: it-IT
ms.lasthandoff: 01/27/2022
ms.locfileid: "137908984"
---
<a name="module-1-learn-the-fundamentals-of-dynamics-365-marketing"></a>Modulo 1: Concetti fondamentali su Dynamics 365 Marketing
========================

## <a name="practice-lab-13---manage-customers-and-activities"></a>Lab pratico 1.3. Gestire clienti e impegni

## <a name="objectives"></a>Obiettivi

Definire e lavorare con i record di account e contatti nelle applicazioni Dynamics 365 è una delle attività più comuni. Dopo aver creato gli account e i contatti, attività come telefonate, impegni e appuntamenti rappresenteranno le interazioni con i clienti.

## <a name="lab-setup"></a>Configurazione del lab

  - **Tempo stimato**: 15 minuti

## <a name="instructions"></a>Istruzioni

In questo esercizio si utilizzeranno record comuni impiegati da tutte le app Customer Engagement di Dynamics 365. 

1. Se non è già aperta, aprire l'applicazione **Hub delle vendite di Dynamics 365**. 

2. Usando la barra di spostamento sul lato sinistro della schermata, selezionare **Account**. 

3. Sulla barra dei comandi nella parte superiore dello schermo selezionare il pulsante **Nuovo**.

4. Completare il record dell'account come segue:

    - **Nome account:** Contoso Corporate - Proprie iniziali

    - **Telefono:** 888-555-1234

    - **Indirizzo 1 Via 1:** 191 181st Ave N

    - **Indirizzo 1 Città:** Seattle

    - **Indirizzo 1 Provincia:** WA

    - **Indirizzo 1 CAP:** 98101

5. Sulla barra dei comandi selezionare il pulsante **Salva e chiudi** per salvare e chiudere il record dell'account.

6. Sulla barra dei comandi selezionare nuovamente il pulsante **Nuovo** per l'elenco di account.

7. Completare il record dell'account come segue:

    - **Nome account:** Contoso North America - Proprie iniziali

    - **Telefono:** 888-555-4321

    - **Indirizzo 1: via 1:** 187 11th ST N

    - **Indirizzo 1 Città:** Chicago

    - **Indirizzo 1 Provincia:** IL

    - **Indirizzo 1 CAP:** 60176

8. Impostare il campo **Account padre** sull'account **Contoso Corporate** creato in precedenza. 

9. Selezionare il pulsante **Salva** per salvare l'account e lasciarlo aperto. 

10. Individuare la griglia secondaria **Contatti** sulla destra della schermata. 

11. Selezionare i **puntini di sospensione verticali** e scegliere **Nuovo contatto** dal menu visualizzato. 

12. Usando il modulo **Quick Create Contact** (Creazione rapida contatto) completare il contatto come segue:

    - **Nome:** Jackson

    - **Cognome:** Anderson - Proprie iniziali

    - **Posizione:** CEO

    - **Posta elettronica:** Jackson@contososample.com

13. Selezionare il pulsante **Salva e chiudi**.

14. Immediatamente sopra la griglia secondaria Contatti selezionare il campo **Contatto principale** e impostarlo sul contatto **Jackson Anderson** appena creato. 

15. Passare alla **sequenza temporale** del record al centro dello schermo e selezionare l'icona **+** per aggiungere un nuovo elemento impegno. 

16. Nel menu visualizzato selezionare **Appuntamento**.

17. Completare l'appuntamento come segue:

    - **Oggetto:** Riunione con Jackson

    - **Ora di inizio:** Oggi alle 15:00

    - **Ora di fine:** Oggi alle 16:00

18. Selezionare il pulsante **Salva e chiudi**. 

19. Attendere che la sequenza temporale venga aggiornata automaticamente. 

20. Si noti che la **sequenza temporale** ora mostra le informazioni sull'appuntamento. 

21. **Salvare e chiudere** l'account. 

22. Nella sezione **Attività personali** del pannello di navigazione selezionare **Impegni**.

23. Selezionare il collegamento **Riunione con Jackson** per aprire la riga dell'appuntamento e visualizzare il modulo. 

24. Con il record dell'appuntamento aperto, sulla **barra dei comandi** selezionare il pulsante **Segna come completato** per completare l'appuntamento. 

25. Si noti che l'appuntamento non è più elencato nella vista **Impegni personali**. 

26. Selezionare la vista **Impegni personali** per passare alla vista **Impegni chiusi**. Viene visualizzato l'appuntamento **Riunione con Jackson** completato.

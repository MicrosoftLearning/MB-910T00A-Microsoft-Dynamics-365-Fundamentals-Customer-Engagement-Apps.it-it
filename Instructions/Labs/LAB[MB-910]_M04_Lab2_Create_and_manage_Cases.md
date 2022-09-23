---
lab:
  title: 'Lab 4.2: Creare e gestire casi in Dynamics 365 Customer Service'
  module: 'Module 4: Learn the Fundamentals of Dynamics 365 Customer Service'
ms.openlocfilehash: 2590c7be81b274a95528c4cd61b32be7db3e3548
ms.sourcegitcommit: 6065e6a662bd0407d37fcc565c1b2da1c916255d
ms.translationtype: HT
ms.contentlocale: it-IT
ms.lasthandoff: 04/29/2022
ms.locfileid: "144405071"
---
<a name="module-4-learn-the-fundamentals-of-dynamics-365-customer-service"></a>Modulo 4. Concetti fondamentali su Dynamics 365 Customer Service
========================

## <a name="practice-lab-42---create-and-manage-cases-in-dynamics-365-customer-service"></a>Lab pratico 4.2. Creare e gestire casi in Dynamics 365 Customer Service

## <a name="lab-setup"></a>Configurazione del lab

  - **Tempo stimato**: 10 minuti

## <a name="instructions"></a>Istruzioni

1. Se non è già aperta, aprire l'applicazione **Hub del servizio clienti di Dynamics 365**. 

2. Usando la barra di spostamento sul lato sinistro della schermata, selezionare **Casi**. 

3. Sulla **barra dei comandi** selezionare il pulsante **Nuovo caso** per creare un nuovo record di caso.

4. Completare il nuovo record del caso come segue:

    - **Titolo caso:** Articolo arrivato danneggiato - Proprie iniziali

    - **Cliente:** Alpine Ski House

    - **Origine:** Telefono

5. Selezionare il pulsante **Salva** per salvare il record e lasciarlo aperto. 

6. In **Processo telefono - caso** selezionare la fase **Identifica** e impostare il campo **Trova contatto** su **Patrick Sands**. 

7. Selezionare la **X** nella finestra a comparsa della fase **Identifica** per rimuovere la finestra in modo da poter continuare a lavorare. 

8. Usando la **sequenza temporale del record**, selezionare l'**icona del segno più** per creare un nuovo impegno. 

9. Nel menu visualizzato selezionare **Telefonata**.

10. Impostare il campo **Oggetto** su **Richiamare Patrick - Proprie iniziali** e lasciare invariati gli altri campi. 

11. Selezionare il pulsante **Salva e chiudi**. 

12. In **Processo telefono - caso** selezionare la fase **Identifica**.

13. Selezionare il pulsante **Fase successiva** per passare alla fase **Ricerca**. 

14. Selezionare la **X** nella finestra a comparsa della fase **Ricerca** per rimuovere la finestra in modo da poter continuare a lavorare. 

15. Sul lato destro della schermata del caso individuare e selezionare l'icona a forma di libro **Conoscenza**. Sarà direttamente sotto l'icona della **chiave inglese**.

16. Si noti che il titolo del caso creato diventa automaticamente il testo da cercare. Individuare e selezionare l'articolo **Articolo danneggiato all'arrivo** creato in precedenza. 

17. Verrà visualizzato l'intero contenuto dell'articolo. Selezionare l'icona **Collega questo articolo al record corrente**. Verificare che venga visualizzato il testo **Collegato a caso**. 

18. Si procederà ora a risolvere il caso. Nella **sequenza temporale del record**, passare il puntatore del mouse sull'impegno **Richiamare Patrick** creato in precedenza. Selezionare l'**icona del segno di spunta** Contrassegna come completato per completare l'impegno. 

19. Nella schermata **Chiudi telefonata** selezionare il pulsante **Chiudi**. Verificare che l'impegno sia **Chiuso**. 

20. In **Processo telefono - caso** selezionare la fase **Ricerca**, quindi selezionare **Fase successiva** per passare alla fase **Risolvi**. 

21. Nella fase **Risolvi** selezionare il pulsante **Fine** per completare il flusso del processo. 

22. Sulla **barra dei comandi** del record del caso selezionare il pulsante **Risolvi caso**.

23. Nella finestra **Risolvi caso** impostare il campo **Risoluzione** su **Articolo della Knowledge Base**. 

24. Selezionare il pulsante **Risolvi** per completare il processo. 

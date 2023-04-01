---
lab:
  title: 'Lab 5.1: Creazione di ordini di lavoro in Dynamics 365 Field Service'
  learning path: Learn the Fundamentals of Dynamics 365 Field Service
  module: Explore Dynamics 365 Field Service
---

Modulo 1: Esplorare Dynamics 365 Field Service
========================

## Lab pratico 5.1. Creazione di ordini di lavoro in Dynamics 365 Field Service

## Configurazione del lab

  - **Tempo stimato**: 20 minuti

## Istruzioni

1. Se non è già aperta, aprire l'applicazione **Dynamics 365 Field Service**.  

2. Usando la barra di spostamento sul lato sinistro della schermata, selezionare **Casi**.  

3. Sulla **barra dei comandi** selezionare il pulsante **Nuovo** per creare un nuovo record di caso. 

4. Completare il nuovo record del caso come segue: 

    - **Titolo case:** Riscaldamento unità di controllo 

    - **Cliente:** A. Datum Corporation 

    - **Origine:** Telefono 

5. Selezionare la scheda **Field Service**. 

6. Impostare il campo **Tipo di evento imprevisto** su **Unità Surriscaldamento**. 

7. Sulla **barra dei comandi** selezionare il pulsante **Salva e chiudi** per salvare e chiudere il record del caso.  

 

Più avanti si tornerà al record del caso creato. Successivamente, consente di esaminare come creare manualmente un record dell'ordine di lavoro.  

 

8. Usando la struttura di spostamento a sinistra, selezionare **Ordini di lavoro**. 

9. Sulla **barra dei comandi** selezionare il pulsante **Nuovo** per creare un nuovo ordine di lavoro. 

10. Completare i dettagli dell'ordine di lavoro come segue: 

    - **Account di servizio:** Adventure Works 

    - **Listino prezzi:** Tariffe USA 

    - **Tipo di evento imprevisto primario:** Connessione linea persa 

    - **Tassabile:** Non 

11. Selezionare la scheda **Settings** (Impostazioni). 

12. Impostare il campo **Area di servizio** su **WA**. 

13. In **Preferenze** configurare le preferenze per il tempo come segue: 

    - **Tempo da promessa:** Oggi alle 9:00 

    - **Tempo a promessa:** Oggi alle 11:00 

14. Selezionare **Salva e chiudi** per salvare le modifiche e chiudere il nuovo ordine di lavoro. 

 

In alternativa, per generare gli ordini di lavoro, è possibile eseguire l'escalation dei record dei casi. In questo esempio verrà eseguita l'escalation del case di surriscaldamento unità di controllo creata in precedenza.  

 

15. Usando la struttura di spostamento a sinistra, selezionare **Casi**.  

16. Aprire il caso di **surriscaldamento unità di controllo** creato in precedenza.  

17. Sulla **barra dei comandi** selezionare il pulsante **Converti in ordine di lavoro**.  

18. Al termine della creazione dell'ordine di lavoro, fare clic sul pulsante **OK** nella schermata popup per visualizzare i dettagli dell'ordine di lavoro.  

19. Selezionare la scheda **Servizi** e verificare che i servizi Controllo integrità **sistema e Controllo** intervallo **di movimento** siano stati aggiunti all'ordine di lavoro. 

**NOTA:** Se inizialmente non vengono visualizzati, premere F5 per aggiornare la schermata.  

20. Selezionare la scheda **Attività servizio** e verificare che siano state aggiunte 4 attività. 

I nuovi ordini di lavoro sono pronti per essere pianificati. 

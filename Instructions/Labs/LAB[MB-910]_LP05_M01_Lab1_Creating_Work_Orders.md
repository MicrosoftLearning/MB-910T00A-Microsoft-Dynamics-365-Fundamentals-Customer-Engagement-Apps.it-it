---
lab:
  title: "Percorso di apprendimento 5:\_lab 5.1: Creazione di ordini di lavoro in Dynamics 365 Field Service"
  learning path: Learn the Fundamentals of Dynamics 365 Field Service
  module: Explore Dynamics 365 Field Service
---

Modulo 1: Esplorare Dynamics 365 Field Service
========================

# Lab pratico 5.1. Creazione di ordini di lavoro in Dynamics 365 Field Service

## Configurazione del lab

**Nota per gli istruttori:***per consentire a questo lab di funzionare come previsto per gli studenti, è necessario completare alcune fasi di configurazione. Le fasi di configurazione sono riportate nella Guida alla preparazione dell'istruttore MB-910T00A. I dati demo di Field Service sono disponibili qui: [https://github.com/MicrosoftLearning/MB-910T00A-Microsoft-Dynamics-365-Fundamentals-Customer-Engagement-Apps/tree/master/Instructions/Labs]*

  - **Tempo stimato:** 20 minuti

## Istruzioni

1. Se non è già aperta, aprire l'applicazione **Dynamics 365 Field Service**.

2. Utilizzando la barra di spostamento a sinistra della schermata, selezionare **Casi**.

3. Dalla **Barra dei comandi**, selezionare il pulsante **Nuovo** per creare un nuovo record del caso.

4. Completare il nuovo record del caso come segue:

    - **Titolo del caso:** riscaldamento unità di controllo (proprie iniziali)

    - **Cliente**: A. Datum Corporation

    - **Origine**: Telefono

5. Selezionare la scheda **Field Service**

6. Impostare il campo **Tipo evento imprevisto** su **Riscaldamento unità**.

7. Dalla **Barra dei comandi**, selezionare il pulsante **Salva e chiudi** per salvare e chiudere il record del caso.

Più avanti torneremo al record del caso creato. Successivamente, esamineremo come creare manualmente un record di ordine di lavoro.

8. Utilizzando la barra di spostamento a sinistra, selezionare **Ordini di lavoro**.

9. Dalla **Barra dei comandi**, selezionare il pulsante **Nuovo** per creare un nuovo Ordine di lavoro.

10. Completare i dettagli dell'ordine di lavoro come indicato di seguito:

    - **Account di servizio**: Adventure Works

    - **Listino prezzi:** tariffe USA

    - **Tipo di evento imprevisto primario:** connessione alla linea persa

11. Seleziona la scheda **Impostazioni**.

12. Impostare il campo **Territorio di servizio** su **WA**.

13. In **Preferenze**, configurare le preferenze di orario come segue:

    - **Tempo da promessa**: oggi alle 09:00

    - **Tempo a promessa**: oggi alle 11:00

14. Selezionare **Salva e Chiudi** per salvare le modifiche e chiudere il nuovo ordine di lavoro.

Un altro modo per generare ordini di lavoro consiste nell'escalation dei record dei casi. In questo esempio, verrà eseguita l'escalation del caso di riscaldamento dell'unità di controllo creato in precedenza.

15. Dalla barra di spostamento a sinistra, selezionare **Casi**.

16. Aprire il caso **Riscaldamento unità di controllo****(proprie iniziali)**  creato in precedenza.

17. Nella **Barra dei comandi**, selezionare il pulsante **Converti a ordine di lavoro**.

18. Al termine della creazione dell'ordine di lavoro, fare clic sul pulsante **OK** nella schermata popup per visualizzare i dettagli dell'ordine di lavoro.

19. Selezionare la scheda **Servizi** e verificare che i servizi **Ispezione integrità sistema** e **Ispezione intervallo di movimento** siano stati aggiunti all'ordine di lavoro.

**NOTA:** se inizialmente non vengono visualizzati, premere F5 per aggiornare la schermata.

20. Selezionare la scheda **Attività di assistenza tecnica** e verificare che l'attività **Ispezione unità** sia stata aggiunta.

I nuovi ordini di lavoro sono pronti per essere pianificati.


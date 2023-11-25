---
lab:
  title: 'Percorso di apprendimento 5 - Lab 5.1: Creazione di ordini di lavoro in Dynamics 365 Field Service'
  learning path: Learn the Fundamentals of Dynamics 365 Field Service
  module: Explore Dynamics 365 Field Service
---

Modulo 1: Esplorare Dynamics 365 Field Service
========================

# Lab pratico 5.1. Creazione di ordini di lavoro in Dynamics 365 Field Service

## Configurazione del lab

**Nota per gli insegnanti:** *per consentire a questo lab di lavorare come previsto per gli studenti, è necessario completare alcuni passaggi di configurazione.  I passaggi di configurazione sono disponibili nella Guida alla preparazione del formatore MB-910T00A. I dati demo di Field Service sono disponibili qui: [https://github.com/MicrosoftLearning/MB-910T00A-Microsoft-Dynamics-365-Fundamentals-Customer-Engagement-Apps/tree/master/Instructions/Labs]*

  - **Tempo** stimato: 20 minuti

## Istruzioni

1. Se non è già aperto, aprire l'applicazione **Dynamics 365 Field Service** .

2. Usando lo spostamento sul lato sinistro della schermata, selezionare **Case**.

3. Sulla barra** dei **comandi selezionare il **pulsante Nuovo** per creare un nuovo record case.

4. Completare il nuovo record case come indicato di seguito:

    - **Titolo del case:** Riscaldamento unità di controllo (iniziali)

    - **Cliente**: A. Datum Corporation

    - **Origine**: Telefono

5. Selezionare la **scheda Servizio campi**

6. Impostare il **campo Tipo** di evento imprevisto su **Surriscaldamento** unità.

7. Sulla barra** dei **comandi selezionare il **pulsante Salva e Chiudi** per salvare e chiudere il record del case.

Si tornerà al record del caso creato in un secondo momento. Si esaminerà ora come creare manualmente un record dell'ordine di lavoro.

8. Usando lo spostamento a sinistra, selezionare **Ordini** di lavoro.

9. Sulla barra** dei **comandi selezionare il **pulsante Nuovo** per creare un nuovo ordine di lavoro.

10. Completare i dettagli dell'ordine di lavoro come indicato di seguito:

    - **Account del servizio:** Adventure Works

    - **Listino prezzi:** Tariffe fattura USA

    - **Tipo di evento imprevisto primario:** Connessione linea persa

11. Seleziona la scheda **Impostazioni**.

12. Impostare il **campo Territorio servizio** su **WA**.

13. In **Preferenze** configurare le preferenze relative all'ora come indicato di seguito:

    - **Ora dalla promessa:** oggi @ 9:00 AM

    - **Tempo promesso:** oggi @ 11:00

14. Selezionare **Salva e Chiudi** per salvare le modifiche e uscire dal nuovo ordine di lavoro.

Un altro modo per generare ordini di lavoro consiste nell'escalation dei record dei casi. In questo esempio verrà eseguita l'escalation del case di surriscaldamento dell'unità di controllo creata in precedenza.

15. Usando il riquadro di spostamento a sinistra, selezionare **Case**.

16. Aprire il caso di riscaldamento** **dell'unità **di controllo (iniziali)** creato in precedenza.

17. Sulla barra** dei **comandi selezionare il **pulsante Converti in ordine di** lavoro.

18. Al termine della creazione dell'ordine di lavoro, fare clic sul **pulsante OK** nella schermata popup per visualizzare i dettagli dell'ordine di lavoro.

19. Selezionare la **scheda Servizi** e verificare che i **servizi Inspect System Health** e **Inspect Range of Motion** siano stati aggiunti all'ordine di lavoro.

**NOTA:** se inizialmente non vengono visualizzati, premere F5 per aggiornare la schermata.

20. Selezionare la **scheda Attività** servizio e verificare che l'attività **Ispeziona unità** sia stata aggiunta.

I nuovi ordini di lavoro sono pronti per essere pianificati.


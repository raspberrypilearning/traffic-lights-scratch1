## Controllare i LED

1. Apri **Scratch** dal menu principale (**Scratch**, non **Scratch 2**).

2. Nella barra dei menu, fai click su **Modifica** e seleziona **Avviare il server GPIO**:
    
    ![](images/scratch1-1.png)

3. Fai click sul pannello **Controllo**. Trascina nel pannello un blocco **quando si clicca su ⚑** e due blocchi **invia a tutti**. Unisci i blocchi in una sequenza e modifica i messaggi per far sì che dicano `config22out` e `gpio22on`:
    
    ![](images/scratch1-2.png)

4. Adesso fai click sulla bandierina verde per far partire il tuo codice. Il LED rosso dovrebbe accendersi.

5. Ora aggiungi un **wait 1 secs** bloccare prima e dopo aver spento il LED con `broadcast gpio22off`, e avvolgerlo in un **per sempre** blocco per lampeggiare continuamente:
    
    ![](images/scratch1-3.png)

6. Fai di nuovo clic sulla bandiera verde e dovresti vedere il LED lampeggiare.

7. Ora aggiungine altro **broadcast** blocchi per introdurre le altre due luci e farle accendere e spegnere tutte:
    
    ![](images/scratch1-4.png)

8. Fai di nuovo clic sulla bandiera verde e dovresti vedere le tre luci lampeggiare insieme.

9. Puoi cambiare il numero in **wait 1 sec** accelerare o rallentare la sequenza?
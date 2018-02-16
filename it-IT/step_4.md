## Controllare i LED

1. Apri **Scratch** dal menu principale (**Scratch**, non **Scratch 2**).

2. Nella barra dei menu, fai click su **Modifica** e seleziona **Avviare il server GPIO**:
    
    ![](images/scratch1-1.png)

3. Fai click sul pannello **Controllo**. Trascina nel pannello un blocco **quando si clicca su ⚑** e due blocchi **invia a tutti**. Unisci i blocchi in una sequenza e modifica i messaggi per far sì che dicano `config22out` e `gpio22on`:
    
    ![](images/scratch1-2.png)

4. Adesso fai click sulla bandierina verde per eseguire il tuo codice. Il LED rosso dovrebbe accendersi.

5. Ora aggiungi un blocco **attendi 1 secondo** prima e dopo il blocco `invia a tutti gpio22off`, e avvolgi tutto in un blocco **per sempre**, per far sì che il LED lampeggi continuamente:
    
    ![](images/scratch1-3.png)

6. Fai di nuovo click sulla bandierina verde. Il LED dovrebbe lampeggiare.

7. Adesso aggiungi altri blocchi **invia a tutti**, per introdurre le altre due luci e farle accendere e spegnere tutte:
    
    ![](images/scratch1-4.png)

8. Fai di nuovo click sulla bandierina verde. Dovresti vedere le tre luci lampeggiare insieme.

9. Prova a modificare il numero all'interno del blocco **attendi 1 secondo** per far accelerare o rallentare la sequenza!
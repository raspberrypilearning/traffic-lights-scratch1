## Contrôler les LED

1. Ouvrir **Scratch** à partir du menu de programmation (**Scratch**, pas **Scratch 2**).

2. Cliquez sur **Modifier** dans la barre de menu et sélectionnez **Démarrer le serveur GPIO**:
    
    ![](images/scratch1-1.png)

3. Cliquez sur le **Contrôle** panneau. Faites glisser dans un **lorsque l'indicateur est cliqué** bloc et deux **diffusion** des blocs. Fixez-les ensemble en séquence et modifiez les diffusions pour dire `config22out` et `gpio22on` ainsi:
    
    ![](images/scratch1-2.png)

4. Maintenant, cliquez sur le drapeau vert pour exécuter votre code. Vous devriez voir la LED rouge s'allumer.

5. Maintenant, ajoutez un **wait 1 secs** bloquer avant et après avoir éteint la LED avec `broadcast gpio22off`, et l'insérer dans un **forever** bloquer pour clignoter continuellement:
    
    ![](images/scratch1-3.png)

6. Cliquez à nouveau sur le drapeau vert et vous devriez voir la DEL clignoter.

7. Maintenant, ajoutez-en d'autres **broadcast** des blocs pour introduire les deux autres voyants, et les faire tous s'allumer et s'éteindre:
    
    ![](images/scratch1-4.png)

8. Cliquez à nouveau sur le drapeau vert et vous devriez voir les trois lumières clignoter ensemble.

9. Pouvez-vous changer le nombre en **wait 1 secs** accélérer ou ralentir la séquence?
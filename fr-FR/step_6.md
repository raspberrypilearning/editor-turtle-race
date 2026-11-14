## Number the track

Ajoute des numéros de repère en haut du circuit.

**Count the steps! 🔢**

Utilise une boucle pour écrire les nombres `0` à `11`.

Après avoir écrit chaque chiffre, passe à l'emplacement suivant.

```python filename="main.py" line_numbers="true" line_number_start="36"
for step in range(12):
    write(step, align = 'center')
    forward(20)
```

> [!TIP]
>
> - `range(12)` te donne les nombres `0` à `11`.
> - `write(step)` affiche le nombre à l'écran.

> [!DEBUG]
>
> - Si tous les nombres se superposent, vérifie que `forward(20)` se trouve à l'intérieur de la boucle.

## Exécute maintenant ton code

Exécute ton code et vérifie que la ligne numérique reste en haut et que les tortues sont toujours alignées à gauche.

![a small arrow at the top left with the turtles lined up on the left](images/step_6.png)

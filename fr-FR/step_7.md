## Draw the race markers

Ajoute les marqueurs de course sous chaque numéro.

**Make the track! 🏁**

À l'intérieur de la boucle, fais tourner la flèche en forme de tortue et trace une ligne vers le bas pour chaque marqueur.

Remonte-le, remets-le face à toi et écris le numéro suivant.

```python filename="main.py" line_numbers="true" line_number_start="36" line_highlights="38-44"
for step in range(12):
    right(90)
    forward(10)
    pendown()
    forward(150)
    penup()
    backward(160)
    left(90)
    write(step, align = 'center')
    forward(20)
```

> [!TIP]
>
> - `pendown()` commence à dessiner les marqueurs de couloir.
> - `penup()` lève le stylo pour que tu puisses te déplacer sans dessiner.

> [!DEBUG]
>
> - Si tes lignes vont dans la mauvaise direction, vérifie les virages `right(90)` et `left(90)`.

## Exécute maintenant ton code

Exécute ton code et vérifie que les lignes verticales des couloirs sont bien dessinées sous les numéros.

![numbers 0 to 11 with vertical lane lines and turtles on the left](images/step_7.png)

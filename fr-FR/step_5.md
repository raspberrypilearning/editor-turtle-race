## Get the track pen ready

Maintenant, place la tortue qui dessinera le circuit.

**Ready, set, draw! ✏️**

Elle aura simplement la forme d'une flèche basique lorsqu'elle sera dessinée.

Lève le stylo pour qu'aucun trait ne soit tracé.

Déplace-toi dans le coin supérieur gauche de la piste et fais bouger la tortue rapidement.

```python filename="main.py" line_numbers="true" line_number_start="32"
penup()
goto(-140, 140)
speed(10)
```

> [!TIP]
>
> - `speed(10)` accélère le dessin, ce qui t'évite d'attendre.
> - `goto(-140, 140)` déplace vers le coin supérieur gauche de la piste.

> [!DEBUG]
>
> - Si tu vois une ligne, assure-toi que `penup()` précède `goto()`.

## Exécute maintenant ton code

Run your code and check that the cursor is in the correct position.

![turtles shown with cursor ready to draw lines](images/step_5.png)

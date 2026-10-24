## Add another turtle

Ajoute une deuxième tortue rapide à ta course.

**Meet Bob! 🐢**

Crée une nouvelle tortue qui s'appelle `Bob`.

Définis la couleur et la forme de Bob, puis déplace-la vers la prochaine position de départ.

Bob ressemble beaucoup à Ada. Seules la couleur et la position changent. Les traits importants qui distinguent Bob sont mis en évidence.

```python filename="main.py" line_numbers="true" line_number_start="11" line_highlights="11,12,15"
bob = Turtle()
bob.color('orange')
bob.shape('turtle')
bob.penup()
bob.goto(-160, 70)
bob.pendown()
```

> [!TIP]
>
> - Tu peux choisir le nom de couleur que tu souhaites pour `Bob`.
> - `penup()` empêche la tortue de tracer une ligne pendant qu'elle se déplace.

> [!DEBUG]
>
> - Vérifie que `Bob` a une couleur entre guillemets, comme `'orange'`.

## Exécute maintenant ton code

Exécute ton code et vérifie que deux tortues sont alignées à gauche, l'une au-dessus de l'autre.

![two turtles, red and orange, lined up on the left](images/step_2.png)

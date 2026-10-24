## Add a turtle

Crée ta première tortue de course et prépare-la pour la ligne de départ.

**Say hello to Ada! 🐢**

Commence par ajouter une tortue à l'écran.

Tu peux donner à la tortue le nom que tu veux. Mais, ici, nous allons l'appeler `Ada`.

Cette tortue prend une couleur et une forme, puis se déplace vers sa position de départ sur la piste.

```python filename="main.py" line_numbers="true" line_number_start="4" line_highlights="4-9"
ada = Turtle()
ada.color('red')
ada.shape('turtle')
ada.penup()
ada.goto(-160, 100)
ada.pendown()
```

> [!TIP]
>
> - Tu peux changer la couleur de la tortue comme tu le souhaites.
> - `goto` définit la position `x` et `y` de la tortue sur l'écran.

> [!DEBUG]
>
> - Veille à mettre la couleur entre guillemets : `'red'`

## Exécute maintenant ton code

Exécute ton code et vérifie qu'une tortue apparaît sur le côté gauche de l'écran.

![one red turtle at the left side of the screen](images/step_1.png)

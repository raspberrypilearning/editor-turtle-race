## Add a third turtle

Il manque encore une troisième tortue pour ta course.

**Hello, Eve! 🐢**

Crée une tortue qui s'appelle `Eve`.

Choisis une [couleur](https://www.tcl-lang.org/man/tcl8.5/TkCmd/colors.htm) et une forme pour Eve, puis place-la sur la ligne de départ, sous Bob.

```python filename="main.py" line_numbers="true" line_number_start="18" line_highlights="18,19,22"
eve = Turtle()
eve.color('yellow')
eve.shape('turtle')
eve.penup()
eve.goto(-160, 40)
eve.pendown()
```

> [!TIP]
>
> - `shape('turtle')` fait en sorte que ta tortue ressemble à une tortue.
> - Essaie une autre couleur pour `Eve` si tu veux.

> [!DEBUG]
>
> - Si tu fais un copier-coller, assure-toi d'avoir utilisé `Eve` sur chaque ligne pour cette tortue.

## Exécute maintenant ton code

Exécute ton code et vérifie que trois tortues sont alignées à gauche.

![three turtles, red, orange, and yellow, lined up on the left](images/step_3.png)

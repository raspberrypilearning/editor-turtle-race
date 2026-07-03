<h2 class="c-project-heading--task">Ajouter une tortue</h2>

Crée ta première tortue de course et prépare-la pour la ligne de départ.

<h2 class="c-project-heading--explainer">Bonjour Ada ! 🐢</h2>

Commence par ajouter une tortue à l'écran.

Tu peux donner à la tortue le nom que tu veux. Mais, ici, nous allons l'appeler `Ada`.

Cette tortue prend une couleur et une forme, puis se déplace vers sa position de départ sur la piste.

<div class="c-project-code">
--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 4
line_highlights: 4-9
---
ada = Turtle()
ada.color('red')
ada.shape('turtle')
ada.penup()
ada.goto(-160, 100)
ada.pendown()
--- /code ---
</div>

<div class="c-project-output">
![une tortue rouge à gauche de l'écran](images/step_1.png)
</div>

### Astuce

<div class="c-project-callout c-project-callout--tip">

- Tu peux changer la couleur de la tortue comme tu le souhaites.
- `goto` définit la position `x` et `y` de la tortue sur l'écran.

</div>

### Débogage

<div class="c-project-callout c-project-callout--debug">

- Veille à mettre la couleur entre guillemets : `'red'`

</div>

## Exécute maintenant ton code

Exécute ton code et vérifie qu'une tortue apparaît sur le côté gauche de l'écran.

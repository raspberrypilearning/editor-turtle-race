<h2 class="c-project-heading--task">Ajouter une troisième tortue</h2>

Il manque encore une troisième tortue pour ta course.

<h2 class="c-project-heading--explainer">Salut Eve ! 🐢</h2>

Crée une tortue qui s'appelle `Eve`.

Choisis une [couleur](https://www.tcl-lang.org/man/tcl8.5/TkCmd/colors.htm) et une forme pour Eve, puis place-la sur la ligne de départ, sous Bob.

<div class="c-project-code">
--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 18
line_highlights: 18, 19, 22
---
eve = Turtle()
eve.color('yellow')
eve.shape('turtle')
eve.penup()
eve.goto(-160, 40)
eve.pendown()
--- /code ---
</div>

<div class="c-project-output">
![trois tortues, rouge, orange et jaune, alignées à gauche](images/step_3.png)
</div>

### Astuce

<div class="c-project-callout c-project-callout--tip">

- `shape('turtle')` fait en sorte que ta tortue ressemble à une tortue.
- Essaie une autre couleur pour `Eve` si tu veux.

</div>

### Débogage

<div class="c-project-callout c-project-callout--debug">

- Si tu fais un copier-coller, assure-toi d'avoir utilisé `Eve` sur chaque ligne pour cette tortue.

</div>

## Exécute maintenant ton code

Exécute ton code et vérifie que trois tortues sont alignées à gauche.

<h2 class="c-project-heading--task">Préparer le marqueur de piste</h2>

Maintenant, place la tortue qui dessinera le circuit.

<h2 class="c-project-heading--explainer">À vos marques, prêts, dessinez ! ✏️</h2>

Elle aura simplement la forme d'une flèche basique lorsqu'elle sera dessinée.

Lève le stylo pour qu'aucun trait ne soit tracé.

Se déplace dans le coin supérieur gauche de la piste et fait bouger la tortue rapidement.

<div class="c-project-code">
--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 32
line_highlights:
---
penup()
goto(-140, 140)
speed(10)
--- /code ---
</div>

<div class="c-project-output">
![la tortue est affichée avec le curseur prêt à tracer des lignes](images/step_5.png)
</div>

### Astuce

<div class="c-project-callout c-project-callout--tip">

- `speed(10)` accélère le dessin, ce qui t'évite d'attendre.
- `goto(-140, 140)` se déplace vers le coin supérieur gauche de la piste.

</div>

### Débogage

<div class="c-project-callout c-project-callout--debug">

- Si tu vois une ligne, assure-toi que `penup()` précède `goto()`.

</div>

## Exécute maintenant ton code

Exécute ton code et vérifie que le curseur est à la bonne position

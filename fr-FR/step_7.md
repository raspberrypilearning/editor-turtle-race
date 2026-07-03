<h2 class="c-project-heading--task">Tracer les marqueurs de course</h2>

Ajoute les marqueurs de course sous chaque numéro.

<h2 class="c-project-heading--explainer">C'est parti ! 🏁</h2>

À l'intérieur de la boucle, fais tourner la flèche en forme de tortue et trace une ligne vers le bas pour chaque marqueur.

Remonte-le, remets-le face à toi et écris le numéro suivant.

<div class="c-project-code">
--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 36
line_highlights: 38-44
---
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
--- /code ---
</div>

<div class="c-project-output">
![nombres de 0 à 11 avec lignes de couloir verticales et tortues à gauche](images/step_7.png)
</div>

### Astuce

<div class="c-project-callout c-project-callout--tip">

- `pendown()` commence à dessiner les marqueurs de couloir.
- `penup()` lève le stylo pour que tu puisses te déplacer sans dessiner.

</div>

### Débogage

<div class="c-project-callout c-project-callout--debug">

- Si tes lignes vont dans la mauvaise direction, vérifie les virages `right(90)` et `left(90)`.

</div>

## Exécute maintenant ton code

Exécute ton code et vérifie que les lignes verticales des couloirs sont bien dessinées sous les numéros.

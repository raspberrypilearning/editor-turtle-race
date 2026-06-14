<h2 class="c-project-heading--task">Numéroter la piste</h2>

Ajoute des numéros de repère en haut du circuit.

<h2 class="c-project-heading--explainer">Compte les pas ! 🔢</h2>

Utilise une boucle pour écrire les nombres `0` à `11`.

Après avoir écrit chaque chiffre, passe à l'emplacement suivant.

<div class="c-project-code">
--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 36
line_highlights:
---
for step in range(12):
    write(step, align = 'center')
    forward(20)
--- /code ---
</div>

<div class="c-project-output">
![une petite flèche en haut à gauche avec les tortues alignées à gauche](images/step_6.png)
</div>

### Astuce

<div class="c-project-callout c-project-callout--tip">

- `range(12)` te donne les nombres `0` à `11`.
- `write(step)` affiche le nombre à l'écran.

</div>

### Débogage

<div class="c-project-callout c-project-callout--debug">

- Si tous les nombres se superposent, vérifie que `forward(20)` se trouve à l'intérieur de la boucle.

</div>

## Exécute maintenant ton code

Exécute ton code et vérifie que la ligne numérique reste en haut et que les tortues sont toujours alignées à gauche.

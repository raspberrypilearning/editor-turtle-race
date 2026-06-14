<h2 class="c-project-heading--task">Démarrer la course</h2>

Fais avancer les tortues d'une distance aléatoire à chaque tour.

<h2 class="c-project-heading--explainer">Qu'ils fassent la course ! 🐢🐢🐢🐢</h2>

Utilise une boucle pour effectuer 100 tours.

À chaque tour, fais avancer chaque tortue d'un nombre aléatoire de cases.

<div class="c-project-code">
--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 47
line_highlights:
---
for turn in range(100):
    ada.forward(randint(1,5))
    bob.forward(randint(1,5))
    eve.forward(randint(1,5))
    kai.forward(randint(1,5))
--- /code ---
</div>

<div class="c-project-output">
![quatre tortues qui courent sur des lignes de couloir colorées](images/step_8.png)
</div>

### Astuce

<div class="c-project-callout c-project-callout--tip">

- `randint(1,5)` choisit un nombre aléatoire entre 1 et 5.
- Plus le nombre est élevé, plus la tortue se déplace loin à chaque tour.

</div>

### Débogage

<div class="c-project-callout c-project-callout--debug">

- Si tu vois une erreur, vérifie que tu as bien écrit `randint(1,5)` entre parenthèses et une virgule.

</div>

## Exécute maintenant ton code

Exécute ton code et vérifie que les tortues commencent à se déplacer sur la piste.

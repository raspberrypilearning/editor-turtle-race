## Start the race

Fais avancer les tortues d'une distance aléatoire à chaque tour.

**Let them race! 🐢🐢🐢🐢**

Utilise une boucle pour effectuer 100 tours.

À chaque tour, fais avancer chaque tortue d'un nombre aléatoire de cases.

```python filename="main.py" line_numbers="true" line_number_start="47"
for turn in range(100):
    ada.forward(randint(1,5))
    bob.forward(randint(1,5))
    eve.forward(randint(1,5))
    kai.forward(randint(1,5))
```

> [!TIP]
>
> - `randint(1,5)` choisit un nombre aléatoire entre 1 et 5.
> - Plus le nombre est élevé, plus la tortue se déplace loin à chaque tour.

> [!DEBUG]
>
> - Si tu vois une erreur, vérifie que tu as bien écrit `randint(1,5)` avec des parenthèses et une virgule.

## Exécute maintenant ton code

Exécute ton code et vérifie que les tortues commencent à se déplacer sur la piste.

![four turtles racing across coloured lane lines](images/step_8.png)

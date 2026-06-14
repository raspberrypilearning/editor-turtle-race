<h2 class="c-project-heading--task">Teken de markeringen voor de race</h2>

Plaats de racemarkeringen onder elk nummer.

<h2 class="c-project-heading--explainer">Maak de baan! 🏁</h2>

Binnen de lus laat je de schildpad pijl draaien en trek je voor elke markering een lijn naar beneden.

Zet de schildpad weer bovenaan met zijn gezicht naar voren en schrijf het volgende getal.

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
![nummers 0 tot 11 met verticale lijnen voor de baan en schildpadden aan de linkerkant](images/step_7.png)
</div>

### Tip

<div class="c-project-callout c-project-callout--tip">

- `pendown()` start het tekenen van de baan markeringen.
- `penup()` tilt de pen op, zodat je kunt bewegen zonder te tekenen.

</div>

### Foutopsporing

<div class="c-project-callout c-project-callout--debug">

- Als jouw lijnen de verkeerde kant op gaan, controleer dan de bochten naar rechts (right(90)) en naar links (left(90)).

</div>

## Voer nu je code uit

Voer je code uit en controleer of er verticale ljnen voor de banen onder de nummers worden getekend.

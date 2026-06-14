<h2 class="c-project-heading--task">Zorg dat de pen voor de baan klaarstaat</h2>

Maak nu de schildpad die de racebaan tekent.

<h2 class="c-project-heading--explainer">Klaar voor de start, tekenen maar! ✏️</h2>

Deze schildpad start als een simpele pijl.

Til de pen op zodat er geen lijn wordt getrokken.

Ga naar de linkerbovenhoek van de baan en laat de schildpad snel bewegen.

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
![schildpad wordt weergegeven met cursor klaar om lijnen te tekenen](images/step_5.png)
</div>

### Tip

<div class="c-project-callout c-project-callout--tip">

- Versnel het tekenen met speed(10).
- Met `goto(-140, 140)` gaat het naar de linkerbovenhoek van de baan.

</div>

### Foutopsporing

<div class="c-project-callout c-project-callout--debug">

- Als je een lijn ziet, zorg er dan voor dat `penup()` vóór `goto()` komt.

</div>

## Voer nu je code uit

Voer je code uit en controleer of de cursor op de juiste positie staat

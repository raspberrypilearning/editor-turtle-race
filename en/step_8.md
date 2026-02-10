<h2 class="c-project-heading--task">Start the race</h2>

Make the turtles move forward a random amount each turn.

<h2 class="c-project-heading--explainer">Let them race! 🐢🐢🐢🐢</h2>

--- task ---

Use a loop to take 100 turns.

On each turn, move every turtle forward by a random number of steps.

--- /task ---

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
![four turtles racing across coloured lane lines](images/step_8.png)
</div>

<div class="c-project-callout c-project-callout--tip">

### Tip

- `randint(1,5)` picks a random number from 1 to 5.
- Bigger numbers make a turtle move further each turn.

</div>

<div class="c-project-callout c-project-callout--debug">

### Debugging

- If you see an error, check you wrote `randint(1,5)` with brackets and a comma.

</div>

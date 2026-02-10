<h2 class="c-project-heading--task">Add the fourth turtle</h2>

Every race needs a full line-up.

<h2 class="c-project-heading--explainer">Say hi to Kai! 🐢</h2>

--- task ---

Create a turtle called `kai`.

Set the colour and shape, then move Kai to the last starting spot.

--- /task ---

<div class="c-project-code">
--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 25
line_highlights: 25, 26, 29
---
kai = Turtle()
kai.color('green')
kai.shape('turtle')
kai.penup()
kai.goto(-160, 10)
kai.pendown()
--- /code ---
</div>

<div class="c-project-output">
![4 turtles of different colours lined up on the track](images/step_4.png)
</div>

<div class="c-project-callout c-project-callout--tip">

### Tip

- Give `kai` a colour that stands out from the others.
- Each turtle sits on a different y-position so they do not overlap.

</div>

<div class="c-project-callout c-project-callout--debug">

### Debugging

- Check `goto(-160, 10)` uses a comma between x and y.

</div>

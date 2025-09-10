<h2 class="c-project-heading--task">Add a turtle</h2>
--- task ---
Create your first racing turtle and get it ready at the starting line.
--- /task ---

<h2 class="c-project-heading--explainer">Say hello to Ada! 🐢</h2>

Start by adding one turtle to the screen. You can name the turtle anything you like — here, it is called `ada`. This turtle gets a colour and shape, then moves to its starting position on the track.

<div class="c-project-code">
--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 4
line_highlights: 4-9
---
ada = Turtle()
ada.color('red')
ada.shape('turtle')
ada.penup()
ada.goto(-160, 100)
ada.pendown()
--- /code ---
</div>
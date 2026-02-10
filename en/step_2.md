<h2 class="c-project-heading--task">Add another turtle</h2>

Give your race a second speedy turtle.

<h2 class="c-project-heading--explainer">Meet Bob! 🐢</h2>

--- task ---

Create a new turtle called `bob`.

Set Bob’s colour and shape, then move him to the next starting spot.

--- /task ---

<div class="c-project-code">
--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 11
line_highlights: 11, 12, 15
---
bob = Turtle()
bob.color('orange')
bob.shape('turtle')
bob.penup()
bob.goto(-160, 70)
bob.pendown()
--- /code ---
</div>

<div class="c-project-output">
![2 turtles of different colours lined up on the track](images/step_2.png)
</div>

<div class="c-project-callout c-project-callout--tip">

### Tip

- You can pick any colour name you like for `bob`.
- `penup()` stops the turtle drawing a line while it moves.

</div>

<div class="c-project-callout c-project-callout--debug">

### Debugging

- Check `bob` has a colour in quotes, like `'orange'`.

</div>

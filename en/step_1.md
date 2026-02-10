<h2 class="c-project-heading--task">Add a turtle</h2>

Create your first racing turtle and get it ready at the starting line.

<h2 class="c-project-heading--explainer">Say hello to Ada! 🐢</h2>

--- task ---

Start by adding one turtle to the screen.

You can name the turtle anything you like — here, it is called `ada`. 

This turtle gets a colour and shape, then moves to its starting position on the track.

--- /task ---

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

<div class="c-project-output">
![one red turtle at the left side of the screen](images/step_1.png)
</div>

<div class="c-project-callout c-project-callout--tip">

### Tip

- You can change the colour of the turtle to anything you like.
- The `goto` sets the `x` and `y` postition of the turtle on the screen.

</div>

<div class="c-project-callout c-project-callout--debug">

### Debugging

- Make sure you have quotes around the colour - `'red'`

</div>

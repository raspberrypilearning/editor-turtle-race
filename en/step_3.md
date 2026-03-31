<h2 class="c-project-heading--task">Add a third turtle</h2>

Now your race needs a third turtle.

<h2 class="c-project-heading--explainer">Hello, Eve! 🐢</h2>

### Step 1

Create a turtle named `eve`.

Give Eve a [colour](https://www.tcl-lang.org/man/tcl8.5/TkCmd/colors.htm) and shape, then move her to the starting line below Bob.


<div class="c-project-code">
--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 18
line_highlights: 18, 19, 22
---
eve = Turtle()
eve.color('yellow')
eve.shape('turtle')
eve.penup()
eve.goto(-160, 40)
eve.pendown()
--- /code ---
</div>

<div class="c-project-output">
![three turtles, red, orange, and yellow, lined up on the left](images/step_3.png)
</div>

<div class="c-project-callout c-project-callout--tip">

### Tip

- `shape('turtle')` makes sure your turtle looks like a turtle.
- Try a different colour for `eve` if you want.

</div>

<div class="c-project-callout c-project-callout--debug">

### Debugging

- If you're copying and pasting, make sure you used `eve` in every line for this turtle.

</div>

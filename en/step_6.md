<h2 class="c-project-heading--task">Number the track</h2>

Add number markers along the top of the race track.

<h2 class="c-project-heading--explainer">Count the steps! 🔢</h2>

### Step 1

Use a loop to write the numbers `0` to `11`.

After writing each number, move forward to the next spot.


<div class="c-project-code">
--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 36
line_highlights:
---
for step in range(12):
    write(step, align = 'center')
    forward(20)
--- /code ---
</div>

<div class="c-project-output">
![a small arrow at the top left with the turtles lined up on the left](images/step_6.png)
</div>

<div class="c-project-callout c-project-callout--tip">

### Tip

- `range(12)` gives you the numbers `0` to `11`.
- `write(step)` prints the number on the screen.

</div>

<div class="c-project-callout c-project-callout--debug">

### Debugging

- If all the numbers sit on top of each other, check `forward(20)` is inside the loop.

</div>

## Draw the race markers

Add the race markers under each number.

**Make the track! 🏁**

Inside the loop, make the arrow turtle turn and draw a line down for each marker.

Then move it back up, face forward again, and write the next number.

```python filename="main.py" line_numbers="true" line_number_start="36" line_highlights="38-44"
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
```

> [!TIP]
>
> - `pendown()` starts drawing the lane markers.
> - `penup()` lifts the pen so you can move without drawing.

> [!DEBUG]
>
> - If your lines go the wrong way, check the `right(90)` and `left(90)` turns.

## Now run your code

Run your code and check that vertical lane lines are drawn under the numbers.

![numbers 0 to 11 with vertical lane lines and turtles on the left](images/step_7.png)

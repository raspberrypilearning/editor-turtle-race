## Get the track pen ready

Now set up the turtle that will draw the race track.

**Ready, set, draw! ✏️**

This will just have the basic arrow shape when it draws.

Lift the pen so no line is drawn.

Move to the top-left corner of the track and make the turtle move fast.

```python filename="main.py" line_numbers="true" line_number_start="32"
penup()
goto(-140, 140)
speed(10)
```

> [!TIP]
>
> - `speed(10)` makes drawing faster so you do not have to wait.
> - `goto(-140, 140)` moves to the top-left corner of the track.

> [!DEBUG]
>
> - If you see a line, make sure `penup()` comes before `goto()`.

## Now run your code

Run your code and check that the cursor is in the correct position.

![turtles shown with cursor ready to draw lines](images/step_5.png)

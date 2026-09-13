## Add a third turtle

Now your race needs a third turtle.

**Hello, Eve! 🐢**

Create a turtle named `eve`.

Give Eve a [colour](https://www.tcl-lang.org/man/tcl8.5/TkCmd/colors.htm) and shape, then move her to the starting line below Bob.

```python filename="main.py" line_numbers="true" line_number_start="18" line_highlights="18,19,22"
eve = Turtle()
eve.color('yellow')
eve.shape('turtle')
eve.penup()
eve.goto(-160, 40)
eve.pendown()
```

> [!TIP]
>
> - `shape('turtle')` makes sure your turtle looks like a turtle.
> - Try a different colour for `eve` if you want.

> [!DEBUG]
>
> - If you're copying and pasting, make sure you used `eve` in every line for this turtle.

## Now run your code

Run your code and check that three turtles are lined up on the left.

![three turtles, red, orange, and yellow, lined up on the left](images/step_3.png)

## Add another turtle

Give your race a second speedy turtle.

**Meet Bob! 🐢**

Create a new turtle called `bob`.

Set Bob’s colour and shape, then move him to the next starting spot.

Bob is almost the same as Ada. Just the colour and position change. The important lines that make Bob different are highlighted.

```python filename="main.py" line_numbers="true" line_number_start="11" line_highlights="11,12,15"
bob = Turtle()
bob.color('orange')
bob.shape('turtle')
bob.penup()
bob.goto(-160, 70)
bob.pendown()
```

> [!TIP]
>
> - You can pick any colour name you like for `bob`.
> - `penup()` stops the turtle drawing a line while it moves.

> [!DEBUG]
>
> - Check `bob` has a colour in quotes, like `'orange'`.

## Now run your code

Run your code and check that two turtles are lined up on the left, one above the other.

![two turtles, red and orange, lined up on the left](images/step_2.png)

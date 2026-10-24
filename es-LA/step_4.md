## Add the fourth turtle

Every race needs a full line-up.

**Say hi to Kai! 🐢**

Create a turtle called `kai`.

Set the colour and shape, then move Kai to the last starting spot.

```python filename="main.py" line_numbers="true" line_number_start="25" line_highlights="25,26,29"
kai = Turtle()
kai.color('green')
kai.shape('turtle')
kai.penup()
kai.goto(-160, 10)
kai.pendown()
```

> [!TIP]
>
> - Give `kai` a colour that stands out from the others.
> - Each turtle sits on a different y-position so they do not overlap.

> [!DEBUG]
>
> - Check `goto(-160, 10)` uses a comma between x and y.

## Now run your code

Run your code and check that four turtles are lined up on the left.

![four turtles, red, orange, yellow, and green, lined up on the left](images/step_4.png)

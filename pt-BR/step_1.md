## Add a turtle

Create your first racing turtle and get it ready at the starting line.

**Say hello to Ada! 🐢**

Start by adding one turtle to the screen.

You can name the turtle anything you like. Here, it is called `ada`.

This turtle gets a colour and shape, then moves to its starting position on the track.

```python filename="main.py" line_numbers="true" line_number_start="4" line_highlights="4-9"
ada = Turtle()
ada.color('red')
ada.shape('turtle')
ada.penup()
ada.goto(-160, 100)
ada.pendown()
```

> [!TIP]
>
> - You can change the colour of the turtle to anything you like.
> - The `goto` sets the `x` and `y` position of the turtle on the screen.

> [!DEBUG]
>
> - Make sure you have quotes around the colour - `'red'`

## Now run your code

Run your code and check that one turtle appears at the left side of the screen.

![one red turtle at the left side of the screen](images/step_1.png)

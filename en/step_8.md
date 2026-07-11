## Start the race

Make the turtles move forward a random amount each turn.

**Let them race! 🐢🐢🐢🐢**

Use a loop to take 100 turns.

On each turn, move every turtle forward by a random number of steps.

```python filename="main.py" line_numbers="true" line_number_start="47"
for turn in range(100):
    ada.forward(randint(1,5))
    bob.forward(randint(1,5))
    eve.forward(randint(1,5))
    kai.forward(randint(1,5))
```

> [!TIP]
>
> - `randint(1,5)` picks a random number from 1 to 5.
> - Bigger numbers make a turtle move further each turn.

> [!DEBUG]
>
> - If you see an error, check you wrote `randint(1,5)` with brackets and a comma.

## Now run your code

Run your code and check that the turtles start moving across the track.

![four turtles racing across coloured lane lines](images/step_8.png)

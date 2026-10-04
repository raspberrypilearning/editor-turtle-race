## Number the track

Zet nummermarkeringen bovenaan de baan.

**Count the steps! 🔢**

Gebruik een lus om de getallen `0` tot en met `11` te schrijven.

Ga na elk nummer naar de volgende positie.

```python filename="main.py" line_numbers="true" line_number_start="36"
for step in range(12):
    write(step, align = 'center')
    forward(20)
```

> [!TIP]
>
> - `range(12)` geeft je de getallen `0` tot en met `11`.
> - `write(stap)` print het getal op het scherm.

> [!DEBUG]
>
> - Als alle getallen bovenop elkaar staan, controleer dan of `forward(20)` zich binnen de lus bevindt.

## Voer nu je code uit

Voer je code uit en controleer of de getallenregel bovenaan blijft en de schildpadden nog steeds aan de linkerkant op een rij staan.

![a small arrow at the top left with the turtles lined up on the left](images/step_6.png)

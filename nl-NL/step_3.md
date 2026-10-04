## Add a third turtle

Nu heeft jouw race een derde schildpad nodig.

**Hello, Eve! 🐢**

Maak een schildpad met de naam `eva`.

Geef Eva een [kleur](https://www.tcl-lang.org/man/tcl8.5/TkCmd/colors.htm) en vorm, en verplaats haar vervolgens naar de startlijn onder Bob.

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
> - `shape('turtle')` zorgt ervoor dat je schildpad eruitziet als een schildpad.
> - Kies gerust een andere kleur voor `eva`.

> [!DEBUG]
>
> - Als je de code kopieert en plakt, zorg er dan voor dat je in elke regel voor deze schildpad `eva` gebruikt.

## Voer nu je code uit

Voer je code uit: staan alle schildpadden links en netjes boven elkaar?

![three turtles, red, orange, and yellow, lined up on the left](images/step_3.png)

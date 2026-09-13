## Start the race

Laat de schildpadden elke beurt een willekeurige afstand vooruit bewegen.

**Let them race! 🐢🐢🐢🐢**

Gebruik een lus voor 100 beurten.

Verplaats elke schildpad bij elke beurt een willekeurig aantal stappen vooruit.

```python filename="main.py" line_numbers="true" line_number_start="47"
for turn in range(100):
    ada.forward(randint(1,5))
    bob.forward(randint(1,5))
    eve.forward(randint(1,5))
    kai.forward(randint(1,5))
```

> [!TIP]
>
> - `randint(1,5)` kiest een willekeurig getal tussen 1 en 5.
> - Hoe groter het getal, hoe verder een schildpad per beurt beweegt.

> [!DEBUG]
>
> - Als je een foutmelding ziet, controleer dan of je `randint(1,5)` met haakjes en een komma hebt geschreven.

## Voer nu je code uit

Voer je code uit en controleer of de schildpadden over de baan beginnen te bewegen.

![four turtles racing across coloured lane lines](images/step_8.png)

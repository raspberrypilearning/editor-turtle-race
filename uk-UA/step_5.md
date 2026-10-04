## Get the track pen ready

Тепер зроби черепаху, яка малюватиме трек для перегонів.

**Ready, set, draw! ✏️**

Це буде проста стрілка для малювання.

Підніми ручку, щоб припинити малювати лінію.

Перейди у лівий верхній кут треку, щоб черепаха рухалась швидше.

```python filename="main.py" line_numbers="true" line_number_start="32"
penup()
goto(-140, 140)
speed(10)
```

> [!TIP]
>
> - `speed(10)` пришвидшує малювання, не доведеться довго чекати.
> - `goto(-140, 140)` переносить у лівий верхній кут треку.

> [!DEBUG]
>
> - Якщо бачиш лінію, переконайся, що `penup()` стоїть перед `goto()`.

## Тепер, запускай свій код

Run your code and check that the cursor is in the correct position.

![turtles shown with cursor ready to draw lines](images/step_5.png)

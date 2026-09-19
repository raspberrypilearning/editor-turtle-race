## Draw the race markers

Додай маркери перегонів і номери над ними.

**Make the track! 🏁**

Зроби цикл, щоб стрілка повернулось униз і намалювала лінію на кожен маркер.

Потім, поверни її нагору, в початковий напрямок, щоб малювала наступний номер.

```python filename="main.py" line_numbers="true" line_number_start="36" line_highlights="38-44"
for step in range(12):
    right(90)
    forward(10)
    pendown()
    forward(150)
    penup()
    backward(160)
    left(90)
    write(step, align = 'center')
    forward(20)
```

> [!TIP]
>
> - `pendown()` починає малювати маркери доріжки.
> - `penup()` відриває ручку і ти можеш пересуватись не малюючи.

> [!DEBUG]
>
> - Якщо лінії йдуть не в тому напрямку, перевір кути `right(90)` та `left(90)`.

## Тепер, запускай свій код

Запусти свій код, та дивись як малюються вертикальні лінії з номерами.

![numbers 0 to 11 with vertical lane lines and turtles on the left](images/step_7.png)

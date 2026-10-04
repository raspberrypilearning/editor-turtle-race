## Add the fourth turtle

Кожним перегонам треба повна команда.

**Say hi to Kai! 🐢**

Створи черепаху на ім'я `kai`.

Обери колір та форму, і потім постав її на стартову позицію.

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
> - Задай `kai` колір відмінний від інших.
> - Кожна черепаха знаходиться на власній  y-позиції, щоб не заважати одна одній.

> [!DEBUG]
>
> - Переконайся що в `goto(-160, 10)` стоїть кома між x та y.

## Тепер run свій код

Запусти свій код та подивись як черепахи шикуються ліворуч.

![four turtles, red, orange, yellow, and green, lined up on the left](images/step_4.png)

## Add another turtle

Введи в перегони другу черепаху.

**Meet Bob! 🐢**

Створи нову черепаху, на ім'я `боб`.

Задай колір та форму Боба, та перенеси його на старт.

Боб майже однієї форми з Адою. Тільки колір та позиція змінились. Важливі рядки, які надають Бобу власний вигляд, виділені.

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
> - Ти можеш обрати будь-який колір для `боба`.
> - `penup()` забороняє черепасі малювати, коли вона рухається.

> [!DEBUG]
>
> - Переконайся що у `bob` колір вказано в дужках, наприклад `'orange'`.

## Тепер, запускай свій код

Запусти свій код та подивись як черепахи шикуються ліворуч.

![two turtles, red and orange, lined up on the left](images/step_2.png)

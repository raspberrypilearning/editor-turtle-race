## Number the track

Додай порядкові маркери над треком перегонів.

**Count the steps! 🔢**

Використай цикл щоб прописати числа від `0` до `11`.

Як пропишеш номер, переходь на наступну точку.

```python filename="main.py" line_numbers="true" line_number_start="36"
for step in range(12):
    write(step, align = 'center')
    forward(20)
```

> [!TIP]
>
> - `range(12)` дає тобі числа від `0` до `11`.
> - `write(step)` виводить число на екран.

> [!DEBUG]
>
> - Якщо всі числа лізуть одне на одне, перевір чи `forward(20)` знаходиться в циклі.

## Тепер, запускай свій код

Запусти свій код та перевір щоб номера ліній були вгорі, а черепахи все ще стояли ліворуч.

![a small arrow at the top left with the turtles lined up on the left](images/step_6.png)

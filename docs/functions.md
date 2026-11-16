# Описание функций

## circle.py

### `area(r)`
Вычисляет площадь круга по радиусу `r` по формуле S = πR².

Параметры: `r` — радиус (int | float, ≥ 0)
Возвращает: `float` — площадь

Пример:
```python
>>> import circle
>>> circle.area(5)
78.53981633974483


perimeter(r)
Вычисляет длину окружности по радиусу r по формуле P = 2πR.

Параметры: r — радиус (int | float, ≥ 0)
Возвращает: float — длина окружности

Пример:

python
>>> circle.perimeter(5)
31.41592653589793






square.py
area(a)
Вычисляет площадь квадрата по стороне a по формуле S = a².

Параметры: a — сторона (int | float, ≥ 0)
Возвращает: float | int — площадь

Пример:

python
>>> import square
>>> square.area(4)
16


perimeter(a)
Вычисляет периметр квадрата по стороне a по формуле P = 4a.

Параметры: a — сторона (int | float, ≥ 0)
Возвращает: float | int — периметр

Пример:

python
>>> square.perimeter(4)
16





rectangle.py
area(a, b)
Вычисляет площадь прямоугольника по сторонам a и b по формуле S = a*b.

Параметры: a — сторона (int | float, ≥ 0), b — сторона (int | float, ≥ 0)
Возвращает: float | int — площадь

Пример:

python
>>> import square
>>> square.area(4, 5)
20


perimeter(a, b)
Вычисляет периметр прямоугольника по стороне a и b по формуле P = 2(a + b).

Параметры: a — сторона (int | float, ≥ 0), b — сторона (int | float, ≥ 0)
Возвращает: float | int — периметр

Пример:

python
>>> square.perimeter(4, 5)
18
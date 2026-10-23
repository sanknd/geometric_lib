# Документация по библиотеке Geometric lib

## Общее описание решения
**Geometric lib** - библиотека на Python которая нужна для удобного вычисления площади/периметра квадрата(`square.py`), круга(`circle.py`) прямоугольника(`rectangle.py`) и треугольника(`triangle.py`)

## Описание функций 

### 1. Окружность (circle.py)

* **area(r)** - вычисляет площадь круга по радиусу 
* `r` (int/float): Радиус окружности
``` `area(5)` # возвращает `78.54` в float ```
* **perimeter(r)** - вычисляет периметр круга по радиусу 
* `r` (int/float): Радиус окружности
``` `perimeter(5)` возвращает `31.42` в float ```

### 2. Квадрат (square.py)
* **area(a)** - вычисляет площадь квадрата по стороне 
  * `a` (int/float): Сторона квадрата
  
  * *Пример вызова* `area(5)` возвращает `25` в int/float
* **perimeter(a)** - вычисляет периметр квадрата по стороне `a` (int/float)
  * *Пример вызова* `perimeter(5)` возвращает `20` в int/float

### 3. Треугольник (triangle.py)
* **area(a, h)** - вычисляет площадь треугольника по стороне `a` (int/float) и высоте `h` (int/float)
  * *Пример вызова* `area(4, 5)` возвращает `10.0` в float
* **perimeter(a, b, c)** - вычисляет периметр треугольника по сторонам `a` (int/float), `b` (int/float), `c` (int/float)
  * *Пример вызова* `perimeter(3, 4, 5)` возвращает `12` в int/float

### 4. Прямоугольник (rectangle.py)
* **area(a, b)** - вычисляет площадь прямоугольник по стороне `a` (int/float) и `b` (int/float)
  * *Пример вызова* `area(5, 4)` возвращает `20` в int/float
* **perimeter(a, b)** - вычисляет периметр прямоугольник по стороне `a` (int/float) и `b` (int/float)
  * *Пример вызова* `perimeter(5, 4)` возвращает `18` в int/float

### История изменения проекта 
* **14211e2** Вычисление площади и периметра прямоугольника
* **736de42** Добавил документацию проекта в docs/README.md
* **8ba9aeb** L-03: Circle and square added
* **d078c8d** L-03: Docs added



# Math formulas
## Area
- Circle: S = πR²
- Square: S = a²
- Triangle: S = (a * h)/2
- Rectangle: S = a * b

## Perimeter
- Circle: P = 2πR
- Square: P = 4a
- Triangle: P = a + b + c
- Rectangle: P = 2(a + b)
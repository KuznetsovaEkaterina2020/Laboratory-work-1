# Laboratory-work-1
## Лабораторная работа №1 ##
### "Наследование и полиморфизм" ###

Работу выполнили: студентки группы КТбо2-4 Кузнецова Е.А. и Шалыгина А.В.

#### Задание ####

На языке С++ разработать программу, реализующую функции расчёта площади и периметра геометрических фигур. Должны быть реализованы следующие классы:
1.	Класс Figure, который содержит множество точек – вершин плоской геометрической фигуры. В конструктор необходимо передать массив точек. 
2.	Класс Rectangle, моделирующий прямоугольник и наследуемый от Figure. В конструктор необходимо передать ширину и длину прямоугольника, которые будут пересчитаны в координаты вершин фигуры (использовать множество вершин из родительского класса).
3.	Класс Square, моделирующий квадрат и наследуемый от Rectangle. В конструктор необходимо передать длину стороны квадрата.
4.	Класс Circle, моделирующий круг и наследуемый от Figure. Предусмотреть 2 конструктора: 
* принимающий   радиус окружности;
* принимающий две точки – центр окружности и точку на окружности.
Для всех классов определить функции getPerimetr (расчёт периметра) и getSquare (расчёт площади). Переопределить функции для каждого класса, если необходимо.

#### Входные данные: ####
* координаты вершин фигуры;
* классы, описывающие фигуру;
* количество фигур в массиве;

#### Выходные данные: ####
* название фигуры;
* периметр;
* площадь.

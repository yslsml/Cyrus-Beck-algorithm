# Задание
Дано:
P = {p1(x1, y1), p2(x2, y2), … ,pn(xn, yn)} – выпуклый многоугольник (внутренняя
область залита цветом 1);
Q = {q1(x1, y1), q2(x2, y2), … ,qm(xm, ym)} – выпуклый многоугольник (внутренняя
область залита цветом 2);
Многоугольники P и Q движутся навстречу друг другу, начиная с некоторого
шага пересекаются и проходят насквозь.
Необходимо создать соответствующую анимацию. На каждом шаге
анимации область пересечения заливать цветом 3. Кроме того, в
многоугольнике P изобразить отрезок, соединяющий вершины с индексами
1 и 3. На каждом шаге анимации строить отсечение данного отрезка
многоугольником Q и выделять цветом.
При выполнении задания должны быть реализованы следующие алгоритмы:
- алгоритм пересечения двух выпуклых многоугольников;
- алгоритм Цируса-Бека для нахождения отсечения отрезка выпуклым
многоугольником. 

# Task
Given:
P = {p1(x1, y1), p2(x2, y2), … ,pn(xn, yn)} – convex polygon (the inner
area is filled with color 1);
Q = {q1(x1, y1), q2(x2, y2), … ,qm(xm, ym)} – convex polygon (the inner
area is filled with color 2);
Polygons P and Q move towards each other, starting from some
the steps intersect and pass through.
It is necessary to create the appropriate animation. At each step
of the animation, fill the intersection area with color 3. In addition, in
the polygon P, draw a segment connecting the vertices with the indices
1 and 3. At each step of the animation, build a clipping of this segment
polygon Q and highlight with color.
When performing the task, the following algorithms must be implemented:
- algorithm of intersection of two convex polygons;
- the Cyrus-Beck algorithm for finding the clipping of a segment by a convex
polygon.

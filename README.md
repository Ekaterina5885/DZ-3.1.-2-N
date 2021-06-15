**Цикломатическая сложность кода.**

**1. Формулу вычисления количества unit-тестов на основании значений, генерируемых JaCoCo.**
Формальное определение цикломатической сложности v(G) основано на представлении графа потока управления методом в виде ориентированного графа:

v(G) = E - N + 2

Где E - число ребер, а N - число узлов. 

JaCoCo вычисляет цикломатическую сложность метода с помощью следующего эквивалентного уравнения, основанного на количестве ветвей (B) и количестве точек принятия решения (D):

v(G) = B - D + 1

**2. Рекомендуемый порог цикломатическойсложности кода - 10.** 
# REINFORCEMENT LEARNING
Два задания в каждой папке лежит отчет и описание задания

## Homework 1

Эксперименты с MDP. Основное задание было в том, чтобы научить такси подбирать пассажира
и отвозить его в пункт назначения. Лабиринт небольшой, поэтому со временем агент просто заучивает его (формирует policy). Делалось сравнение между OnPolicy/OffPolicy подходами (Q-learning/Sarsa), также проводилось создание фич. Большую часть времени заняло написание юнит тестов, которые бы подтверждали, что среда моделирует задание корректно (что такси не проходит сквозь стены например).

![Среда](https://github.com/rb-kuddai/rl_2_ru/blob/master/HW1/images/asng_param_10.png)

## Homework 2
Различные приближения Q-learning с помощью базисных функций.

Забавно, что в Matlabe'е нет такой нужной вещи как тензорное произведение, и если
хочется хоть какой-то скорости и оптимизации приходится все приводит к умножению
2d-матриц 

![bumpy](https://github.com/rb-kuddai/rl_2_ru/blob/master/HW2/images/v3d_rbf25x25h.png)

![smooth](https://github.com/rb-kuddai/rl_2_ru/blob/master/HW2/images/v3d_rbf25x25ob.png)

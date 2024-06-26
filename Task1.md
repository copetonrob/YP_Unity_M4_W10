# Задание 1: Апельсиновый сад!

## Описание

В этом задании мы посадим несколько апельсиновых деревьев и подождем, пока с деревьев упадут апельсины. Это задание для демонстрации наставником принципов работы с корутинами.

<img src="https://github.com/copetonrob/YP_Unity_M4_W10/blob/main/img/task1_2.gif" width="600"/>

## Инструкция

Скачай подготовленный для вебинара [пакет](/M4W10.unitypackage)

На сцене первого задания (Assets/Webinars/M4W10/Task1/M4W10Task1.unity) ты увидишь несколько апельсиновых деревьев. В данный момент при запуске проекта ничего не происходит.

Открой скрипт OrangeTree.cs (Assets/Webinars/M4W10/Task1/Scripts)

<img src="https://github.com/copetonrob/YP_Unity_M4_W10/blob/main/img/task1_tree.png" width="600"/>

Допиши код в корутине IEnumerator SpawnFruits()

Сделай бесконечный цикл, в котором раз в случайное время (от 0 до 2 секунд) в верхушке дерева появляется новый апельсин. Спаун апельсина можно сделать в точке spawnPosition с небольшим случайным сдвигом. Начальный поворот апельсина тоже можно сделать случайным.

Открой скрипт Orange.cs (Assets/Webinars/M4W10/Task1/Scripts)

<img src="https://github.com/copetonrob/YP_Unity_M4_W10/blob/main/img/task1_orange.png" width="600"/>

Допиши код корутины IEnumerator Disappear() так, чтобы апельсин после задержки в 5 секунд с момента появления начинал постепенно уменьшаться до крошечного размера, после чего уничтожался.
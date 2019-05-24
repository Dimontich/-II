# Рубежный контроль II

###### | Тихомиров Дмитрий | Группа ИУ8-23|
Выбрать на github по одному проекту, иллюстрирующему работу с абстрактными типами данных (список, очередь, дерево, множество).

Для приведенных типов данных необходимо отметить (номерами строк в файлах) функции работы с абстрактными типами данных (далее АТД), которые были пройдены на лекциях.

Также необходимо отметить, для чего применяется данный АТД в проекте (2-3 предложения).

Про каждый АТД в отчете необходимо написать:

* Имя проекта
* Тип данных
* Номера строк с функциями АТД
* Описание назначения АТД

# Задачи

- [x] Отчет для списка (``list, vector, ...``)
- [x] Отчет для очереди (``queue, dequeue, ...``)
- [x] Отчет для дерева (``tree``)
- [x] Отчет для множества (``set, map, ...``)

# Отчет

## Список

Проект:  https://github.com/kbliss94/FieaGameEngine/tree/7bb24b8c95e4bad6757b6356e39a8862d965b91f/FieaGameEngine

### Строки с функциями АТД

Вставка элемента:  https://github.com/kbliss94/FieaGameEngine/blob/7bb24b8c95e4bad6757b6356e39a8862d965b91f/FieaGameEngine/source/Library.Desktop.Test/VectorTest.cpp#L237

Удаление элемента https://github.com/kbliss94/FieaGameEngine/blob/7bb24b8c95e4bad6757b6356e39a8862d965b91f/FieaGameEngine/source/Library.Desktop.Test/VectorTest.cpp#L715

Очистка списка https://github.com/kbliss94/FieaGameEngine/blob/7bb24b8c95e4bad6757b6356e39a8862d965b91f/FieaGameEngine/source/Library.Desktop.Test/VectorTest.cpp#L686

### Описание назначения АТД

Используемая переменная ``m_contents`` типа ``std::list<...>`` нужна для хранения текста, который будет отображаться у определенных клиентов. Выбранный тип обосновывается набором операций над ним (очистка, удаление элементов, добавление элементов, последовательный обход), а также отсутствием необходимости доступа к i-му элементу.

## Очередь

Проект: https://github.com/GrishinAR/Algorithms/blob/master/src/data_structures/Queue.java

### Строки с функциями АТД

Добавление элемента: (строки 17-27)
https://github.com/GrishinAR/Algorithms/blob/master/src/data_structures/Queue.java#L17

Получение данных из головы очереди: (строки 28-44)
https://github.com/GrishinAR/Algorithms/blob/master/src/data_structures/Queue.java#L28

### Описание назначения АТД 
Этот тип данных применяется в динамическом программировании. С помощью него можно реализовывать алгоритмы, которые позволяют совершить какие-то действия в порядке их поступления, выполнив их последовательно.

## Дерево

### Строки с функциями АТД

Проект: https://github.com/hahahu91/alg/blob/0efadb9f73693917041c72fdd0a2c58e6333d0ec/Comp1/Comp1/Comp1.cpp

Добавление узла:
https://github.com/hahahu91/alg/blob/0efadb9f73693917041c72fdd0a2c58e6333d0ec/Comp1/Comp1/Comp1.cpp#L185

Добавления звена в дерево через отца:
https://github.com/hahahu91/alg/blob/0efadb9f73693917041c72fdd0a2c58e6333d0ec/Comp1/Comp1/Comp1.cpp#L231

Объединение деревьев:
https://github.com/hahahu91/alg/blob/0efadb9f73693917041c72fdd0a2c58e6333d0ec/Comp1/Comp1/Comp1.cpp#L264

Удалить дерево:
https://github.com/hahahu91/alg/blob/0efadb9f73693917041c72fdd0a2c58e6333d0ec/Comp1/Comp1/Comp1.cpp#L303

Изменения узла:
https://github.com/hahahu91/alg/blob/0efadb9f73693917041c72fdd0a2c58e6333d0ec/Comp1/Comp1/Comp1.cpp#L377

### Описание назначения АТД
В данном проекте дерево было реализовано для изучения основ программирования, каждый узел хранит в себе информацию и значение уровня.

 

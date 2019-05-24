# Рубежный контроль II
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

Вставка элемента:237  строка   https://github.com/kbliss94/FieaGameEngine/blob/7bb24b8c95e4bad6757b6356e39a8862d965b91f/FieaGameEngine/source/Library.Desktop.Test/VectorTest.cpp#L237
Удаление элемента:715  строка https://github.com/kbliss94/FieaGameEngine/blob/7bb24b8c95e4bad6757b6356e39a8862d965b91f/FieaGameEngine/source/Library.Desktop.Test/VectorTest.cpp#L715

Очистка списка:686    строка https://github.com/kbliss94/FieaGameEngine/blob/7bb24b8c95e4bad6757b6356e39a8862d965b91f/FieaGameEngine/source/Library.Desktop.Test/VectorTest.cpp#L686

### Описание назначения АТД

Используемая переменная ``m_contents`` типа ``std::list<...>`` нужна для хранения текста, который будет отображаться у определенных клиентов. Выбранный тип обосновывается набором операций над ним (очистка, удаление элементов, добавление элементов, последовательный обход), а также отсутствием необходимости доступа к i-му элементу.

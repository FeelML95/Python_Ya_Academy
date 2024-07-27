# [Основы Python от "Академии Яндекс"](https://academy.yandex.ru/handbook/python/)

## Что есть внутри

- Решения с комментариями
- Тесты внутри задачи
- [Примеры чтения входных данных](./read_input)
- [Шаблон скрипта решения задачи](./template.py)
- [Tips and tricks](./tricks.md)

## Содержание 

<details>
<summary><b>(<i>нажмите, чтобы развернуть</i>)</b></summary>

2. [Базовые конструкции Python](2.%20Basic%20Python%20Constructs)
- 20 / 20 [2.1. Ввод и вывод данных. Операции с числами, строками. Форматирование](2.%20Basic%20Python%20Constructs/2.1.%20Data%20input%20and%20output.%20etc)
- 20 / 20 [2.2. Условный оператор]
- 20 / 20  [2.3. Циклы]
- 19 / 20  [2.4. Вложенные циклы]

3. [Коллекции и работа с памятью](3.%20Collections%20and%20working%20with%20memory)
- 20 / 20  [3.1. Строки, кортежи, списки](3.%20Collections%20and%20working%20with%20memory/3.1.%20Strings,%20tuples,%20lists)
- 20 / 20  [3.2. Множества, словари]
- 10 / 10  [3.3. Списочные выражения. Модель памяти для типов языка Python]
- 15 / 20  [3.4. Встроенные возможности по работе с коллекциями]
- 18 / 20  [3.5. Потоковый ввод/вывод. Работа с текстовыми файлами. JSON]

4. [Функции и их особенности в Python](4.%20Functions%20and%20their%20features%20in%20Python)
- 9 / 10  [4.1. Функции. Области видимости. Передача параметров в функции](4.%20Functions%20and%20their%20features%20in%20Python/4.1.%20Functions.%20Visibility%20areas.%20Passing%20parameters%20to%20functions)
- 10 / 10  [4.2. Позиционные и именованные аргументы. Функции высших порядков. Лямбда-функции]
- 8 / 10  [4.3. Рекурсия. Декораторы. Генераторы]

5. [Объектно-ориентированное программирование](5.%20Object-oriented%20programming)
- 10 / 10  [5.1. Объектная модель Python. Классы, поля и методы](5.%20Object-oriented%20programming/5.1.%20Python%20object%20model.%20Classes,%20fields%20and%20methods)
- 10 / 10  [5.2. Волшебные методы, переопределение методов. Наследование]
- 10 / 10  [5.3. Модель исключений Python. Try, except, else, finally. Модули]

6. [Библиотеки для получения и обработки данных]
- 0 / 10  [6.1. Модули math и numpy]
- 0 / 10  [6.2. Модуль pandas]
- 0 / 10  [6.3. Модуль requests]

</details>

## Мой подход к решению задач

1. Копирую файл [template.py](./template.py);
2. Меняю название функции;
3. Читаю в задаче секции про входные и выходные данные;
4. Обновляю main, где идёт считывание данных и вывод;
5. По примерам в задаче обновляю тесты, записанные через assert, либо unittest;
6. Перехожу к написанию алгоритма решения задачи;
7. Если код не проходит тесты Яндекса, то с помощью сравнения вывода работающего кода(найденного в интернете) и вывода моего кода, разбираюсь в чём ошибка в моём коде. [0test_by_SK.py](./0test_by_SK.py).

## Общие подсказки

- Обращайте внимание на тему урока
- Обращайте внимание на информацию о входных данных; например, числа могут быть целыми или натуральными,
  могут быть разные ограничения на количество входных данных, верхние и нижние границы
- Обращайте внимание на ограничения по памяти и времени
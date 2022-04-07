# Задача 3. Двумерный массив

### Описание
Напишите программу, которая создаёт и инициализирует двумерный массив целых чисел размерностью 3х6, выводит на экран все элементы массива в виде таблички, находит индексы минимального и максимального элементов массива и выводит их на экран

Числа для заполнения массива придумайте сами

Чтобы элементы массива выводились равномерно, внутри одной строчки разделяйте их вместо пробела символом табуляции `\t`

### Пример работы программы
```
Массив:
1  2  3  4  5  6
7  8  9  10 11 12
13 14 15 16 17 18
Индекс минимального элемента: 0 0
Индекс максимального элемента: 2 5
```
#### Подсказки

> Не читайте этот раздел сразу, попытайтесь сначала решить задачу самостоятельно :)

<details>

<summary>Подсказка. Что использовать для решения?</summary>

Чтобы создать двумерный массив целых чисел и сразу его инициализировать, нужно указать тип элементов, имя переменной массива, две пары квадратных скобок и список инициализации. Список инициализации будет состоять из нескольких списков инициализации одномерного массива, каждый из которых представляет собой строчку двумерного массива

Используйте вложенный цикл `for` для перебора элементов двумерного массива

Используйте условный оператор `if` и отдельные переменные для хранения минимума и максимума. Также заведите две переменных для хранения индексов минимального элемента и две переменных для хранения индексов максимального элемента (в двумерном массиве у каждого элемента два индекса - его строчка и столбец)

Используйте первый элемент массива для инициализации переменных минимума и максимума

Используйте `std::cout` для вывода информации

</details>
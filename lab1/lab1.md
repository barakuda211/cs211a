Общая информация
Для выполнения заданий вам предстоит создать два проекта Visual Studio: HelloWorld и Lesson1 (процесс создания описан в отдельном руководстве). По завершении работы необходимо загрузить через форму на данной странице все созданные вами cs-файлы проектов HelloWorld и Lesson1 без каталогов (hw.cs,task2-f1.cs, task3-b1.cs и т. д.). При добавлении нескольких файлов в проект возникает проблема: если в двух файлах есть одинаковые функции (например, Main — точка входа в программу), то проект не соберётся. Решение описано в упомянутом руководстве, [Часть 3: Exclude files]. Имейте под рукой «Проводник», открытый в каталоге с файлами проекта, чтобы преподаватель мог быстро оценить ваш прогресс в течение занятия.

Оценка за лабораторную может оставлять от нуля до трёх «сырых» баллов (1 балл за первую треть задач, 2 балла за две трети и т. д.). Дополнительные задачи не оцениваются, но служат пищей для размышлений и обсуждений. Задачи следует выполнять последовательно. Большая часть задач имеет одинаковую структуру:

ввод данных с клавиатуры;
промежуточные вычисления;
вывод результатов на консоль.
Необходимо писать вразумительные сообщения для пользователя на консоль («Введите два целых числа: », «Результат сравнения: » и т. п.). Сам код должен быть оформлен аккуратно.

Каждый файл должен начинаться комментарием с текстом задания. Используйте многострочные комментарии /* */ или однострочные //

Задачи
[Проект: HelloWorld, файл hw.cs]  Console.WriteLine(). Написать программу, которая выводит на экран фразу “Hello, world”. Создание проектов описано в отдельной статье. 

[Файл task2-f1.cs] Вычислить среднее арифметическое двух заданных целых чисел. Указание: для того, чтобы деление выполнялось вещественным образом, нужно, чтобы один из операндов был вещественный, самый простой способ добиться этого в данном случае — использовать литерал 2.0 в качестве делителя.

[Файл task3-b1.cs] Даны три целых числа: A, B, C. Вывести значение true, если справедливо двойное неравенство A < B < C, и false в противном случае. Указание: условный оператор не использовать.

[Файл task4-i2.cs] Дано двузначное целое число. Вывести его правую и левую цифры. (Операции %, /) Замечание: число –56 состоит из цифр 5 и 6, но не –5 и –6.

[Файл task5-b2.cs] Даны три целых числа. Вывести значение true, если любые два из них не равны между собой, и false в противном случае. (Операция проверки на неравенство: !=, логическое И: &&.) Указание: условный оператор не использовать. Примеры:

13, -4, 6 >>> true
 6, -4, 6 >>> false
13, 13, 6 >>> false
[Файл task6.cs] Заданы вещественные числа A, B, H (A < B, H > 0). Вывести значения функции синуса на промежутке от A до B с шагом H.

Указание: использовать счётчик цикла типа double.

[Файл task7.cs] Числа Пелля PN задаются рекурсивно: 

P0 = 0,  P1 = 1,  PN = 2 PN–1 + PN–2.
Вывести  N чисел Пелля (N ≥ 0).

Указание: рекурсию использовать запрещено.

[Файл task8-dig1.cs] Дано целое число. Найти количество его цифр и их сумму.

[Файл task9-seq1.cs] Дана последовательность целых чисел (вводятся с клавиатуры), последний элемент которой — число 0. Найти сумму всех положительных элементов этой последовательности и количество её отрицательных элементов.

Указание 1. В подобных задачах следует использовать идиому «бесконечный цикл с выходом из середины»
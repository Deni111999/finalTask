# Задание #

Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма.

# Описание решения #
1. Задаем два массива: заданный и второй одинаковой длины. 
2. Задаем метод, в котором цикл соразмерный длине массива, внутри цикла проверка условия ( <=3 ), если да,элемент первого массива заносится в count элемент второго массива. 
3. Переменная count поочередно закидывается из первого массива во второй  чтобы потом не было пробелов. 
4. После присвоения увеличивается переменная count на 1 и возвращается к циклу for в котором i увеличивается на 1. И так проверяется до конца.
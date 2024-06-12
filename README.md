<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body style="font-family: 'Times New Roman', Times, serif;">
    <p align = "center" style="font-size: 14;">
        МИНИСТЕРСТВО НАУКИ И ВЫСШЕГО ОБРАЗОВАНИЯ <br>
        РОССИЙСКОЙ ФЕДЕРАЦИИ<br>
        ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ<br>
        ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ОБРАЗОВАНИЯ<br>
        «САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ»<br>
    </p>
    <br><br><br><br><br><br>
    <body font-size = "12">
        <p align = "center"> 
            Институт естественных наук и техносферной безопасности<br>
            Кафедра информатики<br>
            Бахтина Елена Владимировна<br>
        </p>
        <br><br><br>
        <p align = "center">
            <strong>Лабораторная работа №12. «PHP».</strong><br>
            01.03.02 Прикладная математика и информатика
        </p>
        <br><br><br><br><br><br><br><br><br><br><br><br>
        <p align = "right"> 
            Научный руководитель<br>
            Соболев Евгений Игоревич
        </p>
        <br><br><br>
        <p align = "center">г. Южно-Сахалинск<br>2024 г.</p>
    </body>
    <body style="font-family: 'Times New Roman', Times, serif;">
        <h2 align = "center">Введение</h2>
        <p font-size = "12">
            <b>PHP</b> — C-подобный скриптовый язык общего назначения, интенсивно применяемый для разработки веб-приложений.
        </p>
        <br>
        <h2 align = "center">Цель и задачи</h2>
        <p align = "left" font-size = "12"> 
            Цель: решить задачи при помощи JS.<br>
            Задачи:<br>
                1.	Создайте массив, заполненный числами от 1 до 100. Найдите сумму элементов данного массива.<br>
                2.	Дан массив с элементами 'a', 'b', 'c', 'd', 'e'. С помощью функции array_map сделайте из него массив 'A', 'B', 'C', 'D', 'E'.<br>
                3.	Дан массив $arr. Подсчитайте количество элементов этого массива.<br>
                4.	Дан массив $arr. С помощью функции count выведите последний элемент данного массива.<br>
                5.	Дан массив с числами. Проверьте, что в нем есть элемент со значением 3.<br>
                6.	Дан массив [1, 2, 3, 4, 5]. Найдите сумму элементов данного массива.<br>
                7.	Дан массив [1, 2, 3, 4, 5]. Найдите произведение (умножение) элементов данного массива.<br>
                8.	Дан массив $arr. С помощью функций array_sum и count найдите среднее арифметическое элементов (сумма элементов делить на их количество) данного массива.<br>
                9.	Создайте массив, заполненный числами от 1 до 100.<br>
                10.	Создайте массив, заполненный буквами от 'a' до 'z'.<br>
                11.	 Создайте строку '1-2-3-4-5-6-7-8-9' не используя цикл.<br>
                12.	Найдите сумму чисел от 1 до 100 не используя цикл.<br>
                13.	 Найдите произведение чисел от 1 до 10 не используя цикл.<br>
                14.	Даны два массива: первый с элементами 1, 2, 3, второй с элементами 'a', 'b', 'c'. Сделайте из них массив с элементами 1, 2, 3, 'a', 'b', 'c'.<br>
                15.	Дан массив с элементами 1, 2, 3, 4, 5. С помощью функции array_slice создайте из него массив $result с элементами 2, 3, 4.<br>
                16.	Дан массив [1, 2, 3, 4, 5]. С помощью функции array_splice преобразуйте массив в [1, 4, 5].<br>
                17.	 Дан массив [1, 2, 3, 4, 5]. С помощью функции array_splice запишите в новый массив элементы [2, 3, 4].<br>
                18.	 Дан массив [1, 2, 3, 4, 5]. С помощью функции array_splice сделайте из него массив [1, 2, 3, 'a', 'b', 'c', 4, 5].<br>
                19.	 Дан массив [1, 2, 3, 4, 5]. С помощью функции array_splice сделайте из него массив [1, 'a', 'b', 2, 3, 4, 'c', 5, 'e'].<br>
                20.	 Дан массив 'a'=>1, 'b'=>2, 'c'=>3'. Запишите в массив $keys ключи из этого массива, а в $values – значения.<br>
                21.	 Даны два массива: ['a', 'b', 'c'] и [1, 2, 3]. Создайте с их помощью массив 'a'=>1, 'b'=>2, 'c'=>3'.<br>
                22.	Дан массив 'a'=>1, 'b'=>2, 'c'=>3. Поменяйте в нем местами ключи и значения.<br>
                23.	 Дан массив с элементами 1, 2, 3, 4, 5. Сделайте из него массив с элементами 5, 4, 3, 2, 1.<br>
                24.	Дан массив ['a', '-', 'b', '-', 'c', '-', 'd']. Найдите позицию первого элемента '-'.<br>
                25.	 Дан массив ['a', '-', 'b', '-', 'c', '-', 'd']. Найдите позицию первого элемента '-' и удалите его с помощью функции array_splice.<br>
                26.	Дан массив ['a', 'b', 'c', 'd', 'e']. Поменяйте элемент с ключом 0 на '!', а элемент с ключом 3 - на '!!'.<br>
                27.	Дан массив '3'=>'a', '1'=>'c', '2'=>'e', '4'=>'b'. Попробуйте на нем различные типы сортировок.<br>
                28.	Дан массив с элементами 'a'=>1, 'b'=>2, 'c'=>3. Выведите на экран случайный ключ из данного массива.<br>
                29.	 Дан массив с элементами 'a'=>1, 'b'=>2, 'c'=>3. Выведите на экран случайный элемент данного массива.<br>
                30.	Дан массив $arr. Перемешайте его элементы в случайном порядке.<br>
                31.	 Заполните массив числами от 1 до 25 с помощью range, а затем перемешайте его элементы в случайном порядке.<br>
                32.	 Создайте массив, заполненный буквами от 'a' до 'z' так, чтобы буквы шли в случайном порядке и не повторялись.<br>
                33.	 Сделайте строку длиной 6 символов, состоящую из маленьких английских букв, расположенных в случайном порядке. Буквы не должны повторяться.<br>
                34.	Дан массив с элементами 'a', 'b', 'c', 'b', 'a'. Удалите из него повторяющиеся элементы.<br>
                35.	Дан массив с элементами 1, 2, 3, 4, 5. Выведите на экран его первый и последний элемент, причем так, чтобы в исходном массиве они исчезли.<br>
                36.	 Дан массив с элементами 1, 2, 3, 4, 5. Добавьте ему в начало элемент 0, а в конец - элемент 6.<br>
                37.	 Дан массив с элементами 1, 2, 3, 4, 5, 6, 7, 8. С помощью цикла и функций array_shift и array_pop выведите на экран его элементы в следующем порядке: 18273645.<br> 
                38.	 Дан массив с элементами 'a', 'b', 'c'. Сделайте из него массив с элементами 'a', 'b', 'c', '-', '-', '-'.<br>
                39.	 Заполните массив 10-ю буквами 'x'.<br>
                40.	 Создайте массив, заполненный целыми числами от 1 до 20. С помощью функции array_chunk разбейте этот массив на 5 подмассивов ([1, 2, 3, 4]; [5, 6, 7, 8] и т.д.).<br>
        </p>
        <h2 align = "center">Решение</h2>
        <p font-size = "12">Для выполнения этой лабораторной работы, я пользовалась:</p>
        <p> 1.  Материалом в сети интернет</p>
        </body>
<h3 align = "center">Файл lab12.php</h3>

```
"https://www.programiz.com/php/online-compiler/"
1.	Создайте массив, заполненный числами от 1 до 100. Найдите сумму элементов данного массива.
<?php
    $arr = range(1, 100);
    print array_sum($arr);
?>
2.	Дан массив с элементами 'a', 'b', 'c', 'd', 'e'. С помощью функции array_map сделайте из него массив 'A', 'B', 'C', 'D', 'E'.
<?php
    $arr = ['a', 'b', 'c', 'd', 'e'];
    function myfunc($value) {
        return strtoupper($value);
    }
    $arr1 = array_map('myfunc', $arr);
    print_r($arr1);
?>
3.	Дан массив $arr. Подсчитайте количество элементов этого массива.
<?php
    $arr = [1, 2, 3];
    print count($arr);
?>
4.	Дан массив $arr. С помощью функции count выведите последний элемент данного массива.
<?php
    $arr = [1, 2, 3];
    $ind = count($arr) - 1;
    print $arr[$ind];
?>
5.	Дан массив с числами. Проверьте, что в нем есть элемент со значением 3.
<?php
    $arr = [1, 2, 3, 4, 5];
    for ($i=0; $i < count($arr)-1; $i++) { 
        if ($arr[$i] == 3) {
            $num = $i +1;
        }
    }
    if ($num == -1) {
        print("В массиве нет троек");
    }
    else {
        print("В массиве есть тройка на $num месте");
    }
?>
6.	Дан массив [1, 2, 3, 4, 5]. Найдите сумму элементов данного массива.
<?php
    $arr = [1, 2, 3, 4, 5];
    print array_sum($arr);
?>
7.	Дан массив [1, 2, 3, 4, 5]. Найдите произведение (умножение) элементов данного массива.
<?php
    $arr = [1, 2, 3, 4, 5];
    print array_product($arr);
?>
8.	Дан массив $arr. С помощью функций array_sum и count найдите среднее арифметическое элементов (сумма элементов делить на их количество) данного массива.
<?php
    $arr = [1, 2, 3, 4, 5];
    print array_sum($arr)/count($arr);
?>
9.	Создайте массив, заполненный числами от 1 до 100.
<?php
    $arr = range(1, 100);
    print_r($arr);
?>
10.	Создайте массив, заполненный буквами от 'a' до 'z'.
<?php
    $arr = range('a', 'z');
    print_r($arr);
?>
11.	 Создайте строку '1-2-3-4-5-6-7-8-9' не используя цикл.
<?php
    $str = "1-2-3-4-5-6-7-8-9";
    print $str;
?>
12.	Найдите сумму чисел от 1 до 100 не используя цикл.
<?php
    $arr = range(1, 100);
    print array_sum($arr);
?>
13.	 Найдите произведение чисел от 1 до 10 не используя цикл.
<?php
    $arr = range(1, 10);
    print array_product($arr);
?>
14.	Даны два массива: первый с элементами 1, 2, 3, второй с элементами 'a', 'b', 'c'. Сделайте из них массив с элементами 1, 2, 3, 'a', 'b', 'c'.
<?php
    $arr = [1, 2, 3];
    $arr1 = ['a', 'b', 'c'];
    print_r (array_merge($arr, $arr1));
?>
15.	Дан массив с элементами 1, 2, 3, 4, 5. С помощью функции array_slice создайте из него массив $result с элементами 2, 3, 4.
<?php
    $arr = range(1, 5);
    print_r (array_slice($arr, 1, 3));
?>
16.	Дан массив [1, 2, 3, 4, 5]. С помощью функции array_splice преобразуйте массив в [1, 4, 5].
<?php
    $arr = [1, 2, 3, 4, 5];
    $arr = array_merge(array_slice($arr, 0, 1), array_slice($arr, 3, 2));
    print_r ($arr);
?>
17.	 Дан массив [1, 2, 3, 4, 5]. С помощью функции array_splice запишите в новый массив элементы [2, 3, 4].
<?php
    $arr = [1, 2, 3, 4, 5];
    print_r (array_splice($arr, 1, 3));
?>
18.	 Дан массив [1, 2, 3, 4, 5]. С помощью функции array_splice сделайте из него массив [1, 2, 3, 'a', 'b', 'c', 4, 5].
<?php
    $arr = [1, 2, 3, 4, 5];
    array_splice($arr, 3, 0, ['a', 'b', 'c']);
    print_r ($arr);
?>
19.	 Дан массив [1, 2, 3, 4, 5]. С помощью функции array_splice сделайте из него массив [1, 'a', 'b', 2, 3, 4, 'c', 5, 'e'].
<?php
    $arr = [1, 2, 3, 4, 5];
    array_splice($arr, 4, 0, ['c']);
    array_splice($arr, 6, 0, ['e']);
    array_splice($arr, 1, 0, ['a', 'b']);
    print_r ($arr);
?>
20.	 Дан массив 'a'=>1, 'b'=>2, 'c'=>3'. Запишите в массив $keys ключи из этого массива, а в $values – значения.
<?php
    $arr = array('a' => 1, 'b' => 2, 'c' => 3);
    $keys = array_keys($arr);
    $values = array_values($arr);
    print_r($keys);
    print_r($values);
?>
21.	 Даны два массива: ['a', 'b', 'c'] и [1, 2, 3]. Создайте с их помощью массив 'a'=>1, 'b'=>2, 'c'=>3'.
<?php
    $keys = ['a', 'b', 'c'];
    $values = [1, 2, 3];
    print_r(array_combine($keys, $values));
?>
22.	Дан массив 'a'=>1, 'b'=>2, 'c'=>3. Поменяйте в нем местами ключи и значения.
<?php
    $arr = array('a' => 1, 'b' => 2, 'c' => 3);
    $keys = array_values($arr);
    $values = array_keys($arr);
    print_r(array_combine($keys, $values));
?>
23.	 Дан массив с элементами 1, 2, 3, 4, 5. Сделайте из него массив с элементами 5, 4, 3, 2, 1.
<?php
    $arr = [1, 2, 3, 4, 5];
    print_r(array_reverse($arr));
?>
24.	Дан массив ['a', '-', 'b', '-', 'c', '-', 'd']. Найдите позицию первого элемента '-'.
<?php
    $arr = ['a', '-', 'b', '-', 'c', '-', 'd'];
    for ($i=0; $i < count($arr)-1; $i++) { 
        if ($arr[$i] == '-') {
            $ind = $i;
            break;
        }
    }
    print("Первый элемент '-' находится на $i индексе");
?>
25.	 Дан массив ['a', '-', 'b', '-', 'c', '-', 'd']. Найдите позицию первого элемента '-' и удалите его с помощью функции array_splice.
<?php
    $arr = ['a', '-', 'b', '-', 'c', '-', 'd'];
    for ($i=0; $i < count($arr)-1; $i++) { 
        if ($arr[$i] == '-') {
            $ind = $i;
            break;
        }
    }
    array_splice($arr, $ind, 1);
    print_r($arr);
?>
26.	Дан массив ['a', 'b', 'c', 'd', 'e']. Поменяйте элемент с ключом 0 на '!', а элемент с ключом 3 - на '!!'.
<?php
    $arr = ['a', 'b', 'c', 'd', 'e'];
    $arr[0] = '!';
    $arr[3] = '!!';
    print_r($arr);
?>
27.	Дан массив '3'=>'a', '1'=>'c', '2'=>'e', '4'=>'b'. Попробуйте на нем различные типы сортировок.
<?php
    $arr = array('3'=>'a', '1'=>'c', '2'=>'e', '4'=>'b');
    asort($arr);
    print("Сортировка asort:");
    print_r($arr);
    arsort($arr);
    print("Сортировка arsort:");
    print_r($arr);
    ksort($arr);
    print("Сортировка ksort:");
    print_r($arr);
    krsort($arr);
    print("Сортировка krsort:");
    print_r($arr);
?>
28.	Дан массив с элементами 'a'=>1, 'b'=>2, 'c'=>3. Выведите на экран случайный ключ из данного массива.
29.	 Дан массив с элементами 'a'=>1, 'b'=>2, 'c'=>3. Выведите на экран случайный элемент данного массива.
<?php
    $arr = array('a'=> 1, 'b'=> 2, 'c'=> 3);
    $keys = array_keys($arr);
    $rankey = $keys[array_rand($keys)];
    print_r($rankey);
    print_r($arr[$rankey]);
?>
30.	Дан массив $arr. Перемешайте его элементы в случайном порядке.
<?php
    $arr = array('a' => 1, 'b' => 2, 'c' => 3);
    shuffle($arr);
    print_r($arr);
?>
31.	 Заполните массив числами от 1 до 25 с помощью range, а затем перемешайте его элементы в случайном порядке.
<?php
    $arr = range(1, 25);
    shuffle($arr);
    print_r($arr);
?>
32.	 Создайте массив, заполненный буквами от 'a' до 'z' так, чтобы буквы шли в случайном порядке и не повторялись.
<?php
    $arr = range('a', 'z');
    shuffle($arr);
    print_r($arr);
?>
33.	 Сделайте строку длиной 6 символов, состоящую из маленьких английских букв, расположенных в случайном порядке. Буквы не должны повторяться.
<?php
    $str = '';
    $letters = range('a', 'z');
    while(strlen($str) < 6){
        $ranletter = $letters[random_int(0, count($letters) - 1)];
        if(strpos($str, $ranletter) === false) {
            $str .= $ranletter;
        }
    }
    print($str);
?>
34.	Дан массив с элементами 'a', 'b', 'c', 'b', 'a'. Удалите из него повторяющиеся элементы.
<?php
    $arr = ['a', 'b', 'c', 'b', 'a'];
    print_r(array_unique($arr));
?>
35.	Дан массив с элементами 1, 2, 3, 4, 5. Выведите на экран его первый и последний элемент, причем так, чтобы в исходном массиве они исчезли.
<?php
    $arr = [1, 2, 3, 4, 5];
    print_r(array_shift($arr));
    print("\n");
    print_r(array_pop($arr));
    print("\n");
    print_r($arr);
?>
36.	 Дан массив с элементами 1, 2, 3, 4, 5. Добавьте ему в начало элемент 0, а в конец - элемент 6.
<?php
    $arr = [1, 2, 3, 4, 5];
    array_unshift($arr, 0);
    array_push($arr, 6);
    print_r($arr);
?>
37.	 Дан массив с элементами 1, 2, 3, 4, 5, 6, 7, 8. С помощью цикла и функций array_shift и array_pop выведите на экран его элементы в следующем порядке: 18273645. 
<?php
    $arr = [1, 2, 3, 4, 5, 6, 7, 8];
    while (count($arr) != 0) {
        print_r(array_shift($arr));
        print_r(array_pop($arr));
    }
?>
38.	 Дан массив с элементами 'a', 'b', 'c'. Сделайте из него массив с элементами 'a', 'b', 'c', '-', '-', '-'.
<?php
    $arr = ['a', 'b', 'c'];
    array_push($arr, '-');
    array_push($arr, '-');
    array_push($arr, '-');
    print_r($arr);
?>
39.	 Заполните массив 10-ю буквами 'x'.
<?php
    $arr = array_fill(0, 10, 'x');
    print_r($arr);
?>
40.	 Создайте массив, заполненный целыми числами от 1 до 20. С помощью функции array_chunk разбейте этот массив на 5 подмассивов ([1, 2, 3, 4]; [5, 6, 7, 8] и т.д.).
<?php
    $arr = range(1, 20);
    print_r(array_chunk($arr, 4));
?>
```
</html>
<br>
 <h2 align = "center">Вывод</h2>
 <p align = "left" font-size = "12">
    По итогу данной лабороторной работы, я научилась работать с массивами на PHP😊 
</p>
</body>
</html>

# Git
# hello git
<?php
$a = 5;
$b = '05';
var_dump($a == $b);         // Почему true? - Потому что здесь неявное приведение типов данных, 5 = 5 - это правда
var_dump((int)'012345');     // Почему 12345? - тут явное приведение типа данных, целое число 12345, т.к. нет целого числа 012345
var_dump((float)123.0 === (int)123.0); // Почему false? - тут строгое сравнение с учетом типа даых, который указан явно и не одинаковое
var_dump((int)0 === (int)'hello, world'); // Почему true? - строгое сравнение, тип данных задан явно - целое число.
    //Но т.к. 'hello, world' - это не число, оно приводится к числу 0, т.к. тип указан в скобках. 0 = 0, поэтому true

    //Задание №5
$x = 5;
$y = 6;
$x = $x + $y; //x = 5 + 6 = 11
$y = $x - $y; //y = 11 - 6 = 5
$x = $x - $y; //x = 11 - 5 = 6
echo "<br>x = $x y = $y";
?>
Show homework2 

Show homework2-2

Homework2 commit 1

Homework2 commit 1-2

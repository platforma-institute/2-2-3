# 2-2-2
Модуль 2. Занятие 2. Задание 2.
Напишите класс Selector. Экземпляр этого класса при инициализации получает массив целых чисел. Вызов метода getOdds возвращает нечётные числа из первоначального массива, вызов getEvens — чётные.
Числа должны идти в том же порядке, в котором они были в изначальном массиве.

Вводные данные:<br/>
int[] values = {11, 12, 13, 14, 15, 16, 22, 44, 66};<br/>
        Selector selector = new Selector(values);<br/>
        int[] odds = selector.getOdds();<br/>
        int[] evens = selector.getEvens();<br/>
        for (int i : odds)<br/>
            System.out.print(i + " ");<br/>
        System.out.println();<br/>
        for(int i : evens)<br/>
            System.out.print(i + " ");<br/>

Выходные данные:<br/>
11 13 15 <br/>
12 14 16 22 44 66 <br/>

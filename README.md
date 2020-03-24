# 2-2-2
# Модуль 2. Занятие 2. Задание 3
Напишите класс FoodInfo, экземпляры которого будут описывать пищевую ценность продуктов, а при выполнении метода sum — возвращать новый экземпляр, описывающий суммарную пищевую ценность его составляющих.<br/>
Интерфейс класса:<br/>
FoodInfo(proteins, fats, carbohydrates) — инициализировать экземпляр заданным количеством белков, жиров и углеводов. Все три параметра определяются весом в граммах (целым числом).<br/>
getProteins() — вернуть количество белков.<br/>
getFats() — вернуть количество жиров.<br/>
getCarbohydrates() — вернуть количество углеводов.<br/>
getKcalories() — рассчитать число килокалорий в пище по формуле (4 * белки + 9 * жиры + 4 * углеводы).<br/>
sum(f2) — вернуть новый экземпляр FoodInfo значения белков, жиров и углеводов, которого являются суммой соответствующих параметров текущего экземпляра класса FoodInfo и экземпляра переданного в качестве параметра<br/>
<br/>
Вводные данные:<br/>
```java
FoodInfo food1 = new FoodInfo(100, 100, 100);
FoodInfo food2 = new FoodInfo(50, 60, 70);
FoodInfo food3 = food1.sum(food2);
System.out.println(food1.getProteins() + " " + food1.getFats() + " " +
        food1.getCarbohydrates() + " " + food1.getKcalories());
System.out.println(food2.getProteins() + " " + food2.getFats() + " " +
        food2.getCarbohydrates() + " " + food2.getKcalories());
System.out.println(food3.getProteins() + " " + food3.getFats() + " " +
        food3.getCarbohydrates() + " " + food3.getKcalories());
```
Выходные данные:<br/>
100 100 100 1700<br/>
50 60 70 1020<br/>
150 160 170 2720<br/>

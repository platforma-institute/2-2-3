# Модуль 2. Занятие 2. Задание 3
Напишите класс FoodInfo, экземпляры которого будут описывать пищевую ценность продуктов, а при выполнении метода sum — возвращать новый экземпляр, описывающий суммарную пищевую ценность его составляющих.<br/>
Конструктор класса должен принимать количество белков (proteins), жиров(fats) и углеводов(carbohydrates) (целые числа).<br/>
Должны быть методы возвращающие количество белков, жиров и углеводов. Реализовать метод getKcalories() для расчета числа килокалорий в пище по формуле (белки + 4 * жиры + 2 * углеводы).<br/>
sum(f2) — вернуть новый экземпляр FoodInfo значения белков, жиров и углеводов, которого являются суммой соответствующих параметров текущего экземпляра класса FoodInfo и экземпляра переданного в качестве параметра<br/>
<br/>
Вводные данные:<br/>
```java
FoodInfo food1 = new FoodInfo(152, 143, 132);
FoodInfo food2 = new FoodInfo(60, 55, 89);
FoodInfo food3 = food1.sum(food2);
System.out.println(food1.getProteins() + " " + food1.getFats() + " " +
        food1.getCarbohydrates() + " " + food1.getKcalories());
System.out.println(food2.getProteins() + " " + food2.getFats() + " " +
        food2.getCarbohydrates() + " " + food2.getKcalories());
System.out.println(food3.getProteins() + " " + food3.getFats() + " " +
        food3.getCarbohydrates() + " " + food3.getKcalories());
```
Выходные данные:<br/>
152 143 132 988<br/>
60 55 89 458<br/>
212 198 221 1446<br/>

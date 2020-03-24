# Модуль 2. Занятие 2. Задание 3
Напишите класс Calories, экземпляры которого будут описывать пищевую ценность продуктов, а при выполнении метода sum — возвращать новый экземпляр, описывающий суммарную пищевую ценность его составляющих.<br/>
Конструктор класса должен принимать количество белков (proteins), жиров(fats) и углеводов(carbohydrates) (целые числа).<br/>
Должны быть методы возвращающие количество белков, жиров и углеводов. Реализовать метод getKcalories() для расчета числа килокалорий в пище по формуле (белки + 4 * жиры + 2 * углеводы).<br/>
sum(f2) — вернуть новый экземпляр FoodInfo значения белков, жиров и углеводов, которого являются суммой соответствующих параметров текущего экземпляра класса FoodInfo и экземпляра переданного в качестве параметра<br/>
<br/>
Вводные данные:<br/>
```java
Calories cal1 = new Calories(152, 143, 132);
Calories cal2 = new Calories(60, 55, 89);
Calories cal3 = cal1.sum(cal2);
System.out.println(cal1.getProteins() + " " + cal1.getFats() + " " +
        cal1.getCarbohydrates() + " " + cal1.getKcalories());
System.out.println(cal2.getProteins() + " " + cal2.getFats() + " " +
        cal2.getCarbohydrates() + " " + cal2.getKcalories());
System.out.println(cal3.getProteins() + " " + cal3.getFats() + " " +
        cal3.getCarbohydrates() + " " + cal3.getKcalories());
```
Выходные данные:<br/>
152 143 132 988<br/>
60 55 89 458<br/>
212 198 221 1446<br/>

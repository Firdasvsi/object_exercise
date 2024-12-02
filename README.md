Задача 1
Реализуйте поиск по библиотеке автомобилей:

Создайте объект cars с объектами автомобилей и заполните их на своё усмотрение. Важно, чтобы у всех объектов были одинаковые поля
Итоговый объект должен иметь такой вид:

{
  марка_автомобиля_1: { ... },
  марка_автомобиля_2: { ... },
  марка_автомобиля_3: { ... },
}
Напишите функцию getCar, которая:
принимает в себя параметр с маркой автомобиля;
если автомобиль найден, то возвращает объект авто;
если нет, то выводит сообщение, что авто не найдено
Задача 2
Напишите функцию, которая выводит по очереди названия всех авто из объекта:

Возьмите объект cars из прошлой задачи.
Напишите функцию, которая в цикле проходится по объекту cars и выводит в консоль имя каждого автомобиля.
Пример работы программы:
В программе хранится объект с объектами автомобилей { bmw: { … }, audi: {...}, mercedes: {...} }

Задача 3
Напишите функцию, которая:
хранит в теле функции объект автомобиля: принимает в качестве параметра объект с совпадающими или любыми другими дополнительными полями;
объединяет эти два объекта в один и возвращает полученный объект.
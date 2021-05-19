# MyApp
 
 Перед вами простой технический опросник для Junior Android Developer
 
Опросник состоит из 3 обязательных коротких вопросов и практических задач.
Выполнение этих задач поможет нам сориентироваться в вашем уровне, а вам,
возможно, найти и заполнить пробелы в ваших знаниях.
Решение задач нужно представить в виде ссылки на репозиторий на Github.
Желательно, чтобы был выложен полностью проект, который можно клонировать и
запустить.
Интересной вам работы!
Задача 1.
Есть кусочек кода. Его создатель хотел получить следующий вывод в консоль:
7
Developer
Почему данная реализация не обеспечивает желаемого?
Доработайте код.

public static void main(String[] args) {

 Employee tester = new Employee(7,“Developer”);
 
 System.out.println(tester.getId());
 
 System.out.println(tester.getVacancy());
 
 }
 
 class Employee {
 
 private long id;
 
 private Vacancy vacancy;
 
 String getVacancy() {
 
 return vacancy.getVacancy();
 
 }
 
 long getId() {
 
 return id;
 
 }
 
 }
 
 class Vacancy {
 
 String getVacancy() {
 
 return "engineer";
 
}

}


Задача 2.
Написать полную реализацию
/**
 * Метод "скидка". Применяет скидку discount к цене price, начиная с позиции
offset
 * на количество позиций readLength. Новые цены округляем “вниз”,
 * до меньшего целого числа.
 * @param price - исходные цены.
 * @param discount - % скидки, от 1 до 99.
 * @param offset - номер позиции, с которой нужно применить скидку.
 * @param readLength - количество позиций, к которым нужно применить скидку.
 * @return - массив новых цен.
 */
 
public @Nullable int[] decryptData(@NonNull int[] price,

@IntRange(from = 1) int discount,

@IntRange(from = 0) int offset,

@IntRange(from = 1) int readLength) {

//TODO реализовать метод

}


Пример
Входные данные

price = [5,100,20,66,16]

discount = 50

offset = 1

readLength = 3

Ожидаемый результат работы

[50,10,33]

Задача 3.

Написать приложение, которое при третьем своем холодном старте показывает

Toast с произвольным текстом.


                                    Решение.
                                    
                                    
Задача №1                                                                                              Для получения требуемого результата файл Employee изменяем следующим образом:  в классе "Vacancy"   добавляем конструктор в который будем передавать в качестве параметра строку , также   добавляем конструктор в класс "Employee" котором инициализируем переменную id  и создаем объект "vacancy" .

Задача №2 и №3: решение  задач реализованно  в приложении "MyApp".

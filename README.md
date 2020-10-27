 Nikolaev71.github.io 
# Отчет о лабораторных работах 
# Cтудент группы ИДБ-17-05 Николаев А.В.
## Лабораторная №1

Предложение: Строитель забивает гвоздь

![none](https://github.com/Nikolaev71/Nikolaev71.github.io/blob/master/laba1/01_A0.png)


Предложение после: Строитель забивает гвоздь с помошь ударов молотка 

# Диаграмма классов:

![none](https://github.com/Nikolaev71/Nikolaev71.github.io/blob/master/laba1/d1pic.png)

# Диаграмма прецедентов: 

![none](https://github.com/Nikolaev71/Nikolaev71.github.io/blob/master/laba1/d2pic.png)


## Лабораторная работа №2


## IDF0 Diagram

Контексная:


![none](https://github.com/Nikolaev71/Nikolaev71.github.io/blob/master/laba2/%D0%BB%D0%B0%D0%B1%D0%B021.png?raw=true)


### На диаграмме изображен процесс строительства дома


Средний уровень:
    
![none](https://github.com/Nikolaev71/Nikolaev71.github.io/blob/master/laba2/%D0%BB%D0%B0%D0%B1%D0%B022.png?raw=true)

- A1 Менеджер получает на вход отзывы клиентов и подтверждение выполнения заказа от прораба. А на выходе получаются новые заказы и деньги.

- А2 Прораб получает заказ , а на вход получает материалы. Исходя из заказа подготавливает план работ, нужные матеиалы  и инструменты на выход.

- А3 Строитель получает заказ в виде плана работ, материалов и инструментов полученные от прораба. Строит по плану работ дом и выдает заказ заказчику.

- А4 Заказчик получает свой дом. Оставляет отзыв.

## DFD-диаграмма (блок:Управлять):
    
![none](https://github.com/Nikolaev71/Nikolaev71.github.io/blob/master/laba2/%D0%BB%D0%B0%D0%B1%D0%B023.png?raw=true)

 - Архитектор  получает отзывы по пяти бальной шкале (1-5 баллов) и заносит их в базу данных через форму редактирования заказа.
 
## Usecase diagram


![none](https://github.com/Nikolaev71/Nikolaev71.github.io/blob/master/laba2/%D0%BB%D0%B0%D0%B1%D0%B024.png?raw=true)
## Лабораторная работа №3

## Диаграмма последовательности:


![none](https://github.com/Nikolaev71/Nikolaev71.github.io/blob/master/laba3/%D0%BB%D0%B0%D0%B1%D0%B031.png?raw=true)

Архитектор  отправляет заказ  прорабу, а тот подтверждает получение заказа и отпраляет план работ.

## ER-диаграмма:



![none](https://github.com/Nikolaev71/Nikolaev71.github.io/blob/master/laba3/%D0%BB%D0%B0%D0%B1%D0%B032.png?raw=true)

Заказ является записью в БД, которая относится к информационным потокам, и состоит из: Дома, Отзыва клиента и Плана работ.

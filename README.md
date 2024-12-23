# C#-lab10
## Цели работы:
1. Научиться работать c ORM - фреймворком Entity Framework средствами языка C#.
2. Получить базовые навыки работы с базами данных на примере Microsoft SQL Server.

## Задание №1
Создайте приложение для загрузки цен акций из Лабораторной работы №9 и сохранения их в базу данных. По запросу пользователя необходимо выводить состояние акции на сегодняшний день по сравнению с предыдущим (выросла/упала).
Приложение должно заполнять таблицы в БД данными с сайта https://www.marketdata.app/, используйте следующую схему БД или разработайте свою:
![image](https://github.com/user-attachments/assets/51c3fabd-fe7a-404d-a1d4-1ad882c79f52)
Для удобства используйте образ Docker c Microsoft SQL Server либо, при желании, воспользуйтесь любой SQL базой данных.
После заполнения базы данных приложение анализирует последнюю цену и цену на день раньше, в результате чего заполняет таблицу TodaysCondition.
Пользователь вводит строковый тикер и в ответ получает результат изменения цены – выросла/упала.
Графический интерфейс реализуйте по желанию.

C# lab10

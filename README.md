# Домашняя работа

## 1. Задание: 
___________________________________________
Проверьте следующий XML на Well formed(На валидность, все ли верно, блок с кодом доступен по ссылке):

```
<req>
        <surname>Иванов</surname>

        <name>Иван</name>

        <patronymic>Иванович</patronymic>

        <birthdate>01.01.1990</birthdate>

        <birthplace>Москва</birthplace>

        <phone>8 926 766 48 48</phone>
</req

```

* Отсутвует строка с версией 
~~~
<?xml version="1.0"?>
~~~
* В закрывающем теге </req отсутвет знак >

<br>

*Исправленный код*
~~~
<?xml version="1.0"?>
<req>
        <surname>Иванов</surname>
        <name>Иван</name>
        <patronymic>Иванович</patronymic>
        <birthdate>01.01.1990</birthdate>
        <birthplace>Москва</birthplace>
        <phone>8 926 766 48 48</phone>
</req>
~~~
## 2. Задание: 
________________________________

Проверьте следующий JSON на Well formed (На валидность, все ли верно, блок с кодом в фото доступен по ссылке):

~~~
{

        ""surname"": ""Иванов""

        ""name"": ""Иван""

        ""patronymic"": ""Иванович""

        ""birthdate"": ""01.01.1990""

        ""birthplace"": ""Москва""

        ""phone"": ""8 926 766 48 48""

}
~~~
* Всместо "" - "" должны быть " - ", после каждой строки должны быть , 

<br>

*Исправленный код*
~~~
{
        "surname": "Иванов",
        "name": "Иван",
        "patronymic": "Иванович",
        "birthdate": "01.01.1990",
        "birthplace": "Москва",
        "phone": "8 926 766 48 48"
}
~~~
## Задание 3: 
__________________________________________

* Документ Task_3.json

## Задание 4: 
__________________________________________

*  Документ HomeWork_Task_4.postman_collection.json
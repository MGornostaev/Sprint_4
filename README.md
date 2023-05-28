# Sprint_4
Проект по итогам 4 спринта на курсе по автоматизации на Java.
Яндекс практикум.
###Используемые технологии
* Java 11
* selenium-java 3.141.59
* webdrivermanager 4.4.3
* junit 4.13.2
###Запуск тестов
Для запуска тестов, необходимо указать браузер в свойствах запуска. 
Тесты написаны для chrome и firefox.


-DbrowserName=chrome / -DbrowserName=firefox

Также свойство можно передать при запуске тестов через mvn:

>mvn test -DbrowserName=chrome  
mvn test -DbrowserName=firefox
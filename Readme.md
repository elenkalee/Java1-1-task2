# Отчёт о тестировании Credit Card Number Validator

## Приложение осуществляет приём платежей с банковских карт. Проверка функциональности валидации номера банковской карты.

19.12.2020 было проведено тестирование установки, конфигурационное и функциональное тестирование приложений IntelliJ IDEA и Credit Card Number Validator.

На тестирование затрачено: 1 ч

В результате тестирования дефектов не выявлено.

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* [Чек-лист тестирования](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/README.md)
* [Инструкция по установке IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)

В качестве тестовых данных использовались данные из [freeformatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html)  

Валидные номера карт — Result is OK
* 4929924151964500 Visa  
* 6011111406673870 Discover  
* 4913144397001367 Visa Electron  
* 5596947060855716 Master Card
* 346819781557448 American Express  
* 6762222275318827 Maestro  
* 2201382000000013 Мир

Невалидные номера карт — Result is FAIL
* 5169147129584558   
* 1234123412341234

Тестирование производилось в следующем окружении:
* macOS Catalina 10.15.7
* openjdk version "11.0.9.1" 2020-11-04
* IntelliJ IDEA 2020.3 (Community Edition) Build #IC-203.5981.155, built on December 1, 2020





# Отчёт о тестировании Credit Card Number Validator

## Приложение осуществляет приём платежей с банковских карт. Проверка функциональности валидации номера банковской карты.

19.12.2020 было проведено тестирование установки, конфигурационное и функциональное тестирование приложений IntelliJ IDEA и Credit Card Number Validator.

На тестирование затрачено: 1 ч

В результате тестирования выявлены слудующие дефекты:
1. [Не работает валидация карт категорий AMEX, Diners Club - Carte Blanche и International](https://github.com/elenkalee/Java1-1-task2/issues/1)
2. [Ошибка при валидации части карт](https://github.com/elenkalee/Java1-1-task2/issues/2)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* [Чек-лист тестирования](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/README.md)
* [Инструкция по установке IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)

В качестве тестовых данных использовались данные из [freeformatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html)  

1. Все группы карт доступны для валидаиции
2. Результат для всех карт возвращается как `Result is OK`



Тестирование производилось в следующем окружении:
* ntelliJ IDEA 2020.3 (Community Edition)
* Build #IC-203.5981.155, built on December 1, 2020
* Runtime version: 11.0.9+11-b1145.21 x86_64
* VM: OpenJDK 64-Bit Server VM by JetBrains s.r.o.
* macOS 10.15.7





# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

08.09.20 - 08.09.20 было проведено тестирование установки и функциональное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* [Валидный номер карты короче 16 символов определяется как невалидный](https://github.com/etoponyatno/CardValidator/issues/1#issue-696643425)
* [Валидный номер карты длиннее 16 символов определяется как невалидный](https://github.com/etoponyatno/CardValidator/issues/2#issue-696646315)
## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [Руководство по установке IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)


В качестве тестовых данных использовались данные [freeformatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html#fakeNumbers):
* 4516787464695411. Ожидаемый результат – Result is OK
* 3531757451295045190. Ожидаемый результат – Result is OK
* 30353095256985. Ожидаемый результат – Result is OK

Тестирование производилось в следующем окружении:
* macOS Catalina 10.15.6
* IntelliJ IDEA 2020.2.1 (Community Edition)
  Build #IC-202.6948.69, built on August 25, 2020
  Runtime version: 11.0.8+10-b944.31 x86_64
  VM: OpenJDK 64-Bit Server VM by JetBrains s.r.o.


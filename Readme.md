# Отчёт о тестировании функциональности валидации банковских карт

## Краткое описание

07.08.2021 - 08.08.2021 было проведено дымовое тестирование функциональности валидации банковских карт.

На тестирование затрачено: 2 часа

В результате тестирования выявлен следующий дефект:
* [Ошибка в коде](https://github.com/JaneGame/HomeWorkJava1.1/issues/1)


## Описание процесса тестирования


В качестве тестовых данных использовались данные взятые с [сервиса с валидными номерами карт](https://www.freeformatter.com/credit-card-number-generator-validator.html):
* номера карт Виза (все номера проходят валидацию)
* номера карт MasterCard (все номера проходят валидацию)
* номера карт Diners Club (международный и карт-бланш) (все номера проходят валидацию)
* номера карт American Express (AMEX) (все номера проходят валидацию)

Тестирование производилось в следующем окружении:
* Windows 10, 64-разрядная операционная система
* java 11.0.11

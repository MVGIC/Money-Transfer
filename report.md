# Отчёт о тестировании приложения Money Transfer

## Краткое описание

31.08.20 было проведено функциональное тестирование приложения Money Transfer.

На тестирование затрачено: 2 часа

В результате тестирования выявлены следующие дефекты:
* [Программа не правильно считает общий баланс](https://github.com/MVGIC/Money-Transfer/issues/1#issue-689049249)

## Описание тестов

В ходе тестирования приложения было осуществлено:
* функциональное тестирование (тест функции пополнения счёта)
* позитивное тестирование

## Результаты

1. 50% успешных / 50% не успешных тестов
2. [Баг репорт](https://github.com/MVGIC/Money-Transfer/issues/1#issue-689049249)

## Общие рекомендации

Рекомендую сменить тип переменной для хранения итогового значения (**TotalBalance**) на **long**.
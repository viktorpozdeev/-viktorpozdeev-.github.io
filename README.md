
# Отчет а лабораторных работах
# [ИДБ-17-07](https://github.com/stankin/design-part-1/wiki/list-idb-17-07) Поздеев В.А

# Лабораторная 1

Предложение: Рисует портрет.

![pic](https://github.com/viktorpozdeev/-viktorpozdeev-.github.io/blob/master/laba1/Screenshot_2.png?raw=true)

Предложение:  Художник Рисует Портрет по Заказу на Холсте с помощью красок и кисти.

## Class diagram

![none](https://github.com/viktorpozdeev/-viktorpozdeev-.github.io/blob/master/laba1/Screenshot_3.png?raw=true)

[Код](https://github.com/viktorpozdeev/-viktorpozdeev-.github.io/blob/master/laba1/uml.txt_1.txt)

## Usecase diagram

![](https://github.com/viktorpozdeev/-viktorpozdeev-.github.io/blob/master/laba1/Screenshot_1.png)

## Лабораторная 2

### IDEF0

![none](https://github.com/viktorpozdeev/-viktorpozdeev-.github.io/blob/master/laba2/лаба2_1.png)

Кондитер получает на вход ингредиенты и, используя печь и рецепт, готовит торт, который получаем на выходе.
### PDC

![none](https://github.com/viktorpozdeev/-viktorpozdeev-.github.io/blob/master/laba2/лаба2_2.png)

По запросам клиентов определяются требования к торту. Исходя из требований и используя рецепт, кондитер готовит ингредиенты и проводит оценку работы. После оценки работы, либо начинаем сначала, либо на выходе получаем торт.
### DFD

![none](https://github.com/viktorpozdeev/-viktorpozdeev-.github.io/blob/master/laba2/лаба2_3.png)
[Файл .rsf](https://github.com/viktorpozdeev/-viktorpozdeev-.github.io/blob/master/laba2/лаба2.1rsf.rsf)

Кондитер получает запросы от клиентов (база данных видов изделий) и, используя рецепт (база данных рецептов), обрабатывает данные, из которых далее формируются требования.
### Диаграмма прецедентов

![none](https://github.com/viktorpozdeev/-viktorpozdeev-.github.io/blob/master/laba2/лаба2_4.png)

[Код](https://github.com/viktorpozdeev/-viktorpozdeev-.github.io/blob/master/laba2/Код.txt)
Кондитер получает заказ, проводит контроль и изготавливает торт.

# Лабораторная 3

## Диаграмма последовательности
![none](https://github.com/viktorpozdeev/-viktorpozdeev-.github.io/blob/master/laba3/1.png)

[Код](https://github.com/viktorpozdeev/-viktorpozdeev-.github.io/blob/master/laba3/Код1.txt)

Администратор отправляет заказ в виде требований покупателя помощнику кондитера, а тот подтверждает получение заказа.

## ER-диаграмма
![none](https://github.com/viktorpozdeev/-viktorpozdeev-.github.io/blob/master/laba3/2.png)

[Код](https://github.com/viktorpozdeev/-viktorpozdeev-.github.io/blob/master/laba3/код2.txt)

Заказ является записью Базы данных, которая относится к Информационным потокам, и состоит из: Требований, Отзыва покупателя и Торта.

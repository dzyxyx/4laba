# АНАЛИЗ ДАННЫХ И ИСКУССТВЕННЫЙ ИНТЕЛЛЕКТ: НЕЙРОСЕТИ
Отчет по лабораторной работе #4 выполнил:
- Климченко Александр Викторович
- РИ-221110
Отметка о выполнении заданий (заполняется студентом):

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | 60 |
| Задание 2 | * | 20 |
| Задание 3 | # | 20 |

знак "*" - задание выполнено; знак "#" - задание не выполнено;

Работу проверили:
- к.т.н., доцент Денисов Д.В.
- к.э.н., доцент Панов М.А.
- ст. преп., Фадеев В.О.

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Структура отчета

- Данные о работе: название работы, фио, группа, выполненные задания.
- Цель работы.
- Задание 1.
- в проекте Unity реализовать перцептрон, который умеет производить вычисления:
	- OR | дать комментарии о корректности работы
	- AND | дать комментарии о корректности работы
	- NAND | дать комментарии о корректности работы
	- XOR | дать комментарии о корректности работы
- Задание 2.
- Построить графики зависимости количества эпох от ошибки  обучения. Указать от чего зависит необходимое количество эпох обучения.
- Задание 3.
- Построить визуальную модель работы перцептрона на сцене Unity.
- Выводы.
- ✨Magic ✨

## Цель работы
- Ознакомиться с работой перцептрона и визуализировать его работу на Unity.

## Задание 1
### в проекте Unity реализовать перцептрон, который умеет производить вычисления:
- OR | дать комментарии о корректности работы
- AND | дать комментарии о корректности работы
- NAND | дать комментарии о корректности работы
- XOR | дать комментарии о корректности работы

При работе с первым заданием будем последовательно выполнять работу с OR, AND, NAND, XOR.

ТАБЛИЦЫ ИСТИННОСТИ:
![image](https://github.com/dzyxyx/4laba/assets/152580474/b014e710-857d-4c31-9aa4-990758d0c7d8)

Подставим для каждого элемента входные значения и ожидаемые выходные значения. Проделаем эти действия для каждого оператора.

1) OR - работает корректно

![image](https://github.com/dzyxyx/4laba/assets/152580474/110794d0-8ab1-4067-87fc-6b302ef3f3f5)
   
2) AND - работает корректно

![image](https://github.com/dzyxyx/4laba/assets/152580474/d5320eac-1bfd-484e-8748-1b3a8719df4c)

3) NAND - работает корректно

![image](https://github.com/dzyxyx/4laba/assets/152580474/8ce937c1-2601-410a-b937-a16ea802d50e)

4) XOR - работает некорректно, это связано с тем, что у нас реализован самый простой перцептрон, который неспособен решить нелинейную задачу, без возможности разделить ее на линейную.

![image](https://github.com/dzyxyx/4laba/assets/152580474/68f64a3a-ab70-409e-b96a-72eababac181)

## Задание 2
### Построить графики зависимости количества эпох от ошибки  обучения. Указать от чего зависит необходимое количество эпох обучения.

Для построения графиков будем производить 5 попыток обучения перцептрона и отслеживать количество ошибок в разных эпохах. Возьмем значение в 8 эпох, которое уже было установлено в файле.
Все построенные графики представлены в таблице на разных листах.
Ссылка на таблицу: https://docs.google.com/spreadsheets/d/1n5Q5D1dDpd5ofoXXRL5jIaH81v4Qb1FGxne9VO9zhKA/edit?hl=ru#gid=0

1) OR:

![image](https://github.com/dzyxyx/4laba/assets/152580474/95b55049-986f-41b2-b183-f92ba31ba29b)

2) AND:

![image](https://github.com/dzyxyx/4laba/assets/152580474/63835cbb-81c2-4821-b08d-8977ad5d3f83)

3) NAND:

![image](https://github.com/dzyxyx/4laba/assets/152580474/16f826d4-c61c-45f6-ad8d-f124d6a713c4)

4) XOR:

![image](https://github.com/dzyxyx/4laba/assets/152580474/f64cb72e-5547-41fd-ac35-a18d955073de)

## Выводы
При выполнении данной лабораторной работы я разобрался на примере логических операций с работой перцептрона и смог отобразить зависимость количества ошибок при попытках обучения в разных эпохах.

## Powered by

**BigDigital Team: Denisov | Fadeev | Panov**

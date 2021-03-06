# Курсовая работа по дисциплине Программирование. Тема: разработать приложение "Методы сортировки"

## Техническое задание

<p align="justify">
Необходимо реализовать четыре алгоритма сортировки: пузырьковый, вставками, слиянием и Шелла. Для каждого алгоритма приложение
должно предоставить пользователю краткую информацию об алгоритме, а также возможность проведения анализа скорости работы в
зависимости от количества сортируемых данных.
</p>

## Постановка задачи

<p align="justify">
Для каждого перечисленного в задании алгоритма необходимо написать функцию, параметром которой является массив неупорядоченных
целых чисел. Результатом работы функции является тот же массив, все элементы которого упорядочены по возрастанию. Для каждого
алгоритма предлагается провести серию тестов с разными наборами чисел. Для каждого набора провести измерение скорости работы
данного алгоритма с текущим количеством сортируемых чисел. Начальное количество элементов в массиве 500. Перед проведением
тестирования пользователю для каждого алгоритма предлагается ввести максимальное время проведения одного теста, а также шаг,
с которым будет увеличиваться размер массива чисел для сортировки. Эти данные предлагается ввести из заданного диапазона. Также
пользователю предлагается краткое описание тестируемых алгоритмов и визуализация работы каждого алгоритма. Описание каждого
алгоритма должно содержаться в отдельном файле в формате HTML. Визуализация должна быть реализована отображением анимированного
графического файла в формате GIF. По окончании тестирования пользователю предлагается вывести графики зависимости скорости
работы алгоритма от количества сортируемых чисел.
</p>

## Краткое описание проекта

<p align="justify">
Приложение написано на языке Java версии 8 с использованием библиотек Swing и AWT. Для запуска приложения необходима
установленная версия JRE версии не ниже 1.8 под управлением любой операционной системой.
</p>

#### Главное окно приложения

![Главное окно](/pics/mainform.png)

#### Ввод параметров

![Ввод параметров](/pics/inputparams.png)

#### Результаты тестирования

![Результаты тестирования](/pics/results.png)


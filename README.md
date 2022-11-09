﻿# Уважаемые коллеги!

## В данном РЕПО представлен проект, составленный по результатам изучения Блока 1 учебной программы Разработчик.

## Содержание проекта:

1. Условие задачи проверочной работы (*ниже по тексту*);  
2. Блок-схема алгоритма основного метода решения задачи* (*файл "block-diagram.drawio"*);
3. Программа в виде консолньного приложения (*далее - приложение*) на языке C#, позволяющее пользователю вводить данные для проверки работы алгоритма решения задачи (*файл "Program.cs"*).

## Задача:

*Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символам. 
Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма.*

*Примеры:*

*["hello","2","world",":-)",]->["2",":-)"]*

*["1234","1567","-2","computer scince"]->["-2"]*

*["Russia","Denmark","Kazan"]->[]* 

## Структура и описание [кода приложения](https://github.com/ILYA-NASA/VerificationWork1-GB/blob/main/Program.cs):

Приложение состоит из четырех методов:

1. Метод определения размера массива, который предстоит сформровать *SearchValidSizeArray*. 
В качестве аргументов на вход метод принимает первоначальный одномерный массив строк и целочисленное значение количества символов в строках искомого массива.
Цикл *for* считает количество пустых элементов массива, вне цикла определяется число валидных элементов, которые возвращаются из метода целочисленным значением *validSizeArray*;  
2. *Основной метод решения задачи.
Метод формирования массива из строк, длина которых меньше либо равна заданному количеству символов *GetLimitLengthElementArray*.
В данном методе используется принцип цикла в цикле, где внутренний цикл фиксирует индекс искомого элемента массива, а внешний - запоняет итоговый массив. 
На вход метод принимает первоначальный массив, количество символов строк искомого массива и число валидных элементов, найденное предыдущим методом.
На выходе возвращается итоговый массив. 
3. Метод вывода массива на экран состоит из цикла *for* и операторов вывода текста и значения объектов в текстовое представление в выходной поток. Для вывода используя визуальный формат из примеров задачи. 
На вход метод принимает одномерный массив строк.
На старте выполнения алгоритма метод использутся дважды: для отображения первоночального и итогового массивов. 
4. Метод ввода первоначального массива с клавиатуры предлагает пользователю ввести массив самостоятельно, изначально определившись с его длиной. 
Проверить работу приложения можно как с его помощью, так и через "// закомментированные" массивы из примеров задачи. 

Обращаю внимание, что на старте выполнения алгоритма есть возможность присвоить любое целочисленное значение для переменной *lengthString*, изменив количество символов в строках искомого массива, что заставит приложение работать на нобходимых вам условиях. 

# Приятного пользования!

![image](https://user-images.githubusercontent.com/99810114/200753536-89bcae54-e1c3-47ce-bb73-394fd6afca1a.png)

![image](https://user-images.githubusercontent.com/99810114/200753631-136235d3-865e-4863-b59b-6c38a81e96c7.png)

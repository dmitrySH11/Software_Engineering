# Тема 6. Базовые коллекции: словари, кортежи
Отчет по Теме№6 выполнил:
  - Еличкин Дмитрий 
  - ПИЭ-21-1

| Список заданий | Лабораторная раб | Самостоятельная раб|
| -------------- | -------- | ------- |
|    Задание 1   |    +    |    +    |     
|    Задание 2   |    +    |    +    |
|    Задание 3   |    +    |    +    |
|    Задание 4   |    +    |    +    |
|    Задание 5   |    +    |    +    |
|    Задание 6   |         |         |
|    Задание 7   |         |         |
|    Задание 8   |         |         |
|    Задание 9   |         |         |
|    Задание 10  |         |         |


# ТЕМА 6. Лабораторные работы
# Задание 1
В школе, где вы учились, выяснилось, что вы крутой программист и попросили написать программу для преподавателя, которая при вводе кабинета запишет для него ключ доступа и статус, занят или нет. При написании программы необходимо использовать словарь (dict), который на входе получает номер кабинета, и выводит необходимую информацию. Если кабинета, которого у вас нет в словаре, то в консоли в виде переключателя значений нужно вывести «None», а в виде результата вывести «False». По большому счету записал эту программу, которую мы с вами научились заменять иногда громоздкую лампочку if/elif/else. поскольку здесь функциональный словарь полностью повторяет функциональные условия, но при этом при использовании словарей в более сложных программах есть гораздо больше возможностей реализации.
<img width="1440" alt="1" src="https://github.com/dmitrySH11/Software_Engineering/assets/144902371/5bbc993c-e186-4697-aeb9-44ec61787fca">
Вывод: Программа использует словарь для хранения информации о доступе к каждому кабинету и выводит ключ (key) и значение доступа (access) для указанного кабинета.

# Задание 2
Алексей решил создать самый большой словарь в мире. Для этого он придумал функцию dict_maker (**kwargs), которая принимает неограниченное количество параметров «ключ: значение» и обновляет Михаил А. Панов создан в словаре my_dict, состоящем всего из одного элемента «первый» со значением «так просто». Помогите Алексею создать данную функцию. Ниже на скриншоте мы использовали встроенный модуль pprint, который выводит большой объем информации, более понятный для понимания глазом. Иногда очень удобно использовать данную возможность Python.
<img width="1440" alt="2" src="https://github.com/dmitrySH11/Software_Engineering/assets/144902371/11a7db1e-e7ba-44cd-a4a1-27d9ea7f2357">
Вывод: Программа создает словарь my_dict и использует функцию dict_maker для добавления ключей и значений к этому словарю. Затем она выводит содержимое словаря с использованием pprint.

# Задание 3
Для решения некоторых задач необходимо разработать текст европейских символов. Мы знаем, что это можно сделать с помощью функции Split(), в которой более гибкая настройка для разделения для этого, но если нам нужно посимвольно соблюдать код без каких-либо условий, то для этого мы можем использовать кортежи (кортеж). Для этого напишем любой текст, которым мы поделимся и «обвернем» его в кортеж и дальше как с кортежом.
<img width="1440" alt="3" src="https://github.com/dmitrySH11/Software_Engineering/assets/144902371/6f2f7073-c3a3-478b-8e24-56218fb2ac3c">
Вывод: Программа преобразует строку input_string в кортеж и выводит его, а затем преобразует кортеж обратно в список и также выводит его.

# Задание 4
Вовочка решил написать крутую функцию, которая будет писать имя, возраст и место работы, но при этом на входе эта функция будет поступать кортеж. Помогите Вовочке написать эту программу.
<img width="1440" alt="4" src="https://github.com/dmitrySH11/Software_Engineering/assets/144902371/8411e666-4467-4e30-ac04-5d75f6601849">
Вывод: Программа определяет функцию personal_info, которая выводит информацию о человеке, включая имя, возраст и компанию. Затем программа вызывает эту функцию дважды, передавая разные кортежи аргументами.

# Задание 5
Для сопровождения первых лиц государства X нужен кортеж, но никто не может определиться в ряду, поэтому вам нужно написать функцию, которая будет сортировать кортеж, формировать из целых чисел по старению и возвращать его. Если хотя бы один элемент не является целым числом, функция возвращает исходный кортеж.
<img width="1440" alt="5" src="https://github.com/dmitrySH11/Software_Engineering/assets/144902371/455bb97b-0882-48ee-a3bb-286bbe3f6dc2">
Вывод: Программа определяет функцию tuple_sort, которая принимает кортеж и возвращает отсортированный кортеж, если все элементы кортежа являются целыми числами.

# ТЕМА 6. Самостоятельные работы

# Задание 1
Выведите в консоль булевую переменную False, не используя слово False в строке или изначально присвоенную булевую переменную. Программа должна занимать не более двух строк редактора кода.
<img width="1440" alt="Снимок экрана 2023-09-20 в 14 26 07" src="https://github.com/dmitrySH11/Software_Engineering/assets/144902371/d85204c5-e0fc-4ad5-8259-d450fe69c0e2">
Вывод: С помощью проверки сравнения двух чисел, в консоль выводится значение "False", благодаря тому что значения не равны друг другу.

# Задание 2
Присвоить значения трем переменным и вывести их в консоль, используя только две строки редактора кода
<img width="1440" alt="Снимок экрана 2023-09-20 в 14 24 07" src="https://github.com/dmitrySH11/Software_Engineering/assets/144902371/7d7b2d8d-187b-4233-905f-27af70abd952">
Вывод: В данной программе первая строка отвечает за присвоение 3м переменным разных значений, вторая строка позволяет вывести их в консоль.

# Задание 3
Реализуйте ввод данных в программу, через консоль, в виде только целых чисел (тип данных int). То есть при вводе буквенных символов в консоль, программа не должна работать. Программа должна занимать не более двух строк редактора кода.
<img width="1440" alt="Снимок экрана 2023-09-20 в 14 32 36" src="https://github.com/dmitrySH11/Software_Engineering/assets/144902371/39543e4c-060a-4133-9db6-a286c16ca4a3">
Вывод: int(input()) позволяет вводить только числовые значения, которые мы вводим в переменную а.

# Задание 4
Создайте только одну строковую переменную. Длина строки должна не превышать 5 символов. На выходе мы должны получить строку длиной не менее 16 символов. Программа должна занимать не более двух строк редактора кода.
<img width="1440" alt="Снимок экрана 2023-09-20 в 14 50 04" src="https://github.com/dmitrySH11/Software_Engineering/assets/144902371/eb54f2b1-4c08-4af3-91c0-c93940f6867f">
Вывод: На входе мы имеем Hello - длина - не превышает 5 символов, в консоль выводится строка количество символов которой не менее 16 символов, путем умножения количества символов на 5.

# Задание 5
Создайте три переменные: день (тип данных - числовой), месяц (тип данных - строка), год (тип данных - числовой) и выведите в консоль текущую дату в формате: “Сегодня день месяц год. Всего хорошего!” используя F строку и оператор end внутри print(), в котором вы должны написать фразу “Всего хорошего!”. Программа должна занимать не более двух строк редактора кода.
<img width="1440" alt="Снимок экрана 2023-09-20 в 14 58 25" src="https://github.com/dmitrySH11/Software_Engineering/assets/144902371/fe6f2b8b-77c0-4068-9e39-63877b68c987">
Вывод: Программа выводит 3 переменных - день, месяц, год (не увидел что нужно вывести текущую дату - ввел свой день рождения :) ). Итогом консоль выводит предложение - Сегодня 3 октября 2023. Всего хорошего!

# Задание 6
В предложении ‘Hello World’ вставьте ‘my’ между двумя словами. Выведите полученное предложение в консоль в одну строку. Программа должна занимать не более двух строк редактора кода.
<img width="1440" alt="Снимок экрана 2023-09-20 в 15 02 30" src="https://github.com/dmitrySH11/Software_Engineering/assets/144902371/0aa59a34-f5a3-4e79-9518-6912807d1f5d">
Вывод: Мы способны выполнить задания путем замещения "_" на "my". В итоге консоль выводит сообщение HellomyWorld.

# Задание 7
Узнайте длину предложения ‘Hello World’, результат выведите в консоль. Программа должна занимать не более двух строк редактора кода.
<img width="1440" alt="Снимок экрана 2023-09-20 в 15 04 23" src="https://github.com/dmitrySH11/Software_Engineering/assets/144902371/410b4140-d0db-4353-85cf-1e738226a7f9">
Вывод: len(a) позволяет узнать длину символов в данной нам строке. Итогом консоль нам выводит - 11 символов.

# Задание 8
Переведите предложение ‘HELLO WORLD’ в нижний регистр. Программа должна занимать не более двух строк редактора кода.
<img width="1440" alt="Снимок экрана 2023-09-20 в 15 05 09" src="https://github.com/dmitrySH11/Software_Engineering/assets/144902371/9cc446dc-a5a9-4652-8f52-ffe4edf47739">
Вывод: На входе у нас предложение HELLO WORLD. Нам следует вывести в консоль то же предложение, но в нижнем регистре. В этом нам помогает sentence.lower. lower - позволяет изменить регистр букв на нижний.

# Задание 9
Самостоятельно придумайте задачу по проходимой теме и решите ее. Задача должна быть связанна со взаимодействием с числовыми значениями.
<img width="1440" alt="Снимок экрана 2023-09-20 в 15 24 40" src="https://github.com/dmitrySH11/Software_Engineering/assets/144902371/8d343483-9228-40fa-9857-89c329820814">
Вывод: На входе у нас список с 5ю элементами. В консоль программа должна вывести итог суммы данных элементов ДЕЛЁНОЕ на число элементов в массиве - это будет среднее арифметическое.

# Задание 10
Самостоятельно придумайте задачу по проходимой теме и решите ее. Задача должна быть связанна со взаимодействием со строковыми значениями.
<img width="1440" alt="Снимок экрана 2023-09-20 в 15 22 32" src="https://github.com/dmitrySH11/Software_Engineering/assets/144902371/744a90ba-af9f-4406-b6dd-abe3f5a591a2">
Вывод: на входе у нас предложение "Hello World!". Программа должна заменить слово "World" на "Software" и увеличить регистр. В консоль должна вывестись строчка "HELLO SOFTWARE!"

# ИТОГОВЫЙ ВЫВОД:
Python - это универсальный язык программирования, и он предоставляет простые и мощные инструменты для начинающих программистов. Он удобен для ввода и вывода данных, выполнения арифметических операций, обработки строк, и даже форматирования вывода с помощью F-строк. Основы, описанные в программе, позволяют создавать простые программы и знакомят с основами работы с данными. Эти навыки становятся фундаментом для более сложных проектов и разработки более мощных решений.










Работу проверили:
 - к.э.н., доцент Панов М.А.












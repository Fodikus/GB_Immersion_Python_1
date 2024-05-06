# GB_Immersion_Python
Домашние работы к семинарам "Погружение в Python"

## Урок 1. Основы Python
### Семинар
1. Установили Python и IDE для работы
2. Работаем в командной строке (терминале ОС) Создайте каталог для проекта first_project и разверните виртуальное окружение Python в папке venv внутри каталога. Создайте третий каталог проекта project_new и разверните виртуальное окружение Python в папке venv_new внутри каталога. Для каждого проекта последовательно активируйте и деактивируйте виртуальное окружение
3. Активируем виртуальное окружение первого из трёх созданных проектов и устанавливаем в него модуль requests используя pip. Проверяем установку выводом списка модулей в консоль
Сохраняем список в файл, проверяем результат и выходим из окружения. Активируем виртуальное окружение второго из трёх созданных проектов и устанавливаем в него модуль flask используя pip
Проверяем установку выводом списка модулей в консоль Сохраняем список в файл и выходим из окружения. Активируем третье виртуальное окружение. Устанавливаем в него модули из первого и второго проекта используя ранее сохранённые в файлы списки модулей. Проверяем установку выводом списка модулей в консоль.
4. Работа в консоли в режиме интерпретатора Python. Решите квадратное уравнение 5x2-10x-400=0 последовательно сохраняя переменные a, b, c, d, x1 и x2. *Попробуйте решить уравнения с другими значениями a, b, c.
5. Работа в консоли в режиме интерпретатора Python. Посчитайте сумму чётных элементов от 1 до n исключая кратные e. Используйте while и if. Попробуйте разные значения e и n.
6. Напишите программу, которая запрашивает год и проверяет его на високосность. Распишите все возможные проверки в цепочке elif. Откажитесь от магических чисел. Обязательно учтите год ввода Григорианского календаря. В коде должны быть один input и один print.
7. Пользователь вводит число от 1 до 999. Используя операции с числами сообщите что введено: цифра, двузначное число или трёхзначное число:  
- Для цифры верните её квадрат, например 5 - 25;  
- Для двузначного числа произведение цифр, например 30 - 0;   
- Для трёхзначного числа его зеркальное отображение, например 520 - 25.  
Если число не из диапазона, запросите новое число. Откажитесь от магических чисел. В коде должны быть один input и один print.
8. Нарисовать в консоли ёлку спросив у пользователя количество рядов. Пример результата: Сколько рядов у ёлки? 5
9. Выведите в консоль таблицу умножения от 2х2 до 9х10 как на школьной тетрадке.
### Домашняя работа
1. Решить задачи, которые не успели решить на семинаре.  
2. Треугольник существует только тогда, когда сумма любых двух его сторон больше третьей. Дано a, b, c - стороны предполагаемого треугольника. Требуется сравнить длину каждого отрезка-стороны с суммой двух других. Если хотя бы в одном случае отрезок окажется больше суммы двух других, то треугольника с такими сторонами не существует. Отдельно сообщить является ли треугольник разносторонним, равнобедренным или равносторонним.  
3. Напишите код, который запрашивает число и сообщает является ли оно простым или составным. Используйте правило для проверки: “Число является простым, если делится нацело только на единицу и на себя”. Сделайте ограничение на ввод отрицательных чисел и чисел больше 100 тысяч.  
4. Программа загадывает число от 0 до 1000. Необходимо угадать число за 10 попыток. Программа должна подсказывать “больше” или “меньше” после каждой попытки. Для генерации случайного числа используйте код:  
from random import randintnum = randint(LOWER_LIMIT, UPPER_LIMIT)  

## Урок 2. Простые типы данных
### Семинар
1. Создайте несколько переменных разных типов. Проверьте к какому типу относятся созданные переменные.
2. Создайте в переменной data список значений разных типов перечислив их через запятую внутри квадратных скобок. Для каждого элемента в цикле выведите:
- порядковый номер начиная с единицы;  
- значение;  
- адрес в памяти;  
- размер в памяти;  
- хэш объекта;  
- результат проверки на целое число только если он положительный;  
- результат проверки на строку только если он положительный.  
Добавьте в список повторяющиеся элементы и сравните на результаты.  
3. Напишите программу, которая получает целое число и возвращает его двоичное, восьмеричное строковое представление:  
- Функции bin и oct используйте для проверки своего результата, а не для решения;  
- Попробуйте избежать дублирования кода в преобразованиях к разным системам счиения;  
- Избегайте магических чисел;   
- Добавьте аннотацию типов где это возможно.  
4. Напишите программу, которая вычисляет площадь круга и длину окружности по введённому диаметру:  
- Диаметр не превышает 1000 у.е.;  
- Точность вычислений должна составлять не менее 42 знаков после запятой.  
5. Напишите программу, которая решает квадратные уравнения даже если дискриминант отрицательный:  
- Используйте комплексные числа для извлечения квадратного корня.  
6. Напишите программу банкомат:
- Начальная сумма равна нулю;  
- Допустимые действия: пополнить, снять, выйти;  
- Сумма пополнения и снятия кратны 50 у.е.;  
- Процент за снятие — 1.5% от суммы снятия, но не менее 30 и не более 600 у.е.;  
- После каждой третей операции пополнения или снятия начисляются проценты - 3%;  
- Нельзя снять больше, чем на счёте;  
- При превышении суммы в 5 млн, вычитать налог на богатство 10% перед каждой операцией, даже ошибочной;  
- Любое действие выводит сумму денег.  
### Домашняя работа
1. Решить задачи, которые не успели решить на семинаре.  
2. Напишите программу, которая получает целое число и возвращает его шестнадцатеричное строковое представление. Функцию hex используйте для проверки своего результата.  
3. Напишите программу, которая принимает две строки вида “a/b” - дробь с числителем и знаменателем. Программа должна возвращать сумму и произведение* дробей. Для проверки своего кода используйте модуль fractions  

## Урок 3. Коллекции
### Семинар
1. Вручную создайте список с целыми числами, которые повторяются. Получите новый список, который содержит уникальные (без повтора) элементы исходного списка. Подготовьте два решения, короткое и длинное, которое не использует другие коллекции помимо списков.
2. Пользователь вводит данные. Сделайте проверку данных и преобразуйте если возможно в один из вариантов ниже:
- Целое положительное число;  
- Вещественное положительное или отрицательное число;  
- Строку в нижнем регистре, если в строке есть хотя бы одна заглавная буква;  
- Строку в нижнем регистре в остальных случаях;  
3. Создайте вручную кортеж содержащий элементы разных типов. Получите из него словарь списков, где: ключ — тип элемента, значение — список элементов данного типа
4. Создайте вручную список с повторяющимися элементами. Удалите из него все элементы, которые встречаются дважды.
5. Создайте вручную список с повторяющимися целыми числами. Сформируйте список с порядковыми номерами нечётных элементов исходного списка. Нумерация начинается с единицы.
6. Пользователь вводит строку текста. Вывести каждое слово с новой строки:
- Строки нумеруются начиная с единицы;  
- Слова выводятся отсортированными согласно кодировки Unicode;  
- Текст выравнивается по правому краю так, чтобы у самого длинного слова был один пробел между ним и номером строки.  
7. Пользователь вводит строку текста:  
- Подсчитайте сколько раз встречается каждая буква в строке без использования метода count и с ним;  
- Результат сохраните в словаре, где ключ — символ, а значение — частота встречи символа в строке;  
- Обратите внимание на порядок ключей. Объясните почему они совпадают или не совпадают в ваших решениях.  
8. Три друга взяли вещи в поход. Сформируйте словарь, где ключ — имя друга, а значение — кортеж вещей. Ответьте на вопросы:  
- Какие вещи взяли все три друга;  
- Какие вещи уникальны, есть только у одного друга;  
- Какие вещи есть у всех друзей кроме одного и имя того, у кого данная вещь отсутствует;  
- Для решения используйте операции с множествами. Код должен расширяться на любое большее количество друзей.  
### Домашняя работа
1. Решить задачи, которые не успели решить на семинаре.
2. Дан список повторяющихся элементов. Вернуть список с дублирующимися элементами. В результирующем списке не должно быть дубликатов.
3. В большой текстовой строке подсчитать количество встречаемых слов и вернуть 10 самых частых. Не учитывать знаки препинания и регистр символов. За основу возьмите любую статью из википедии или из документации к языку.
4. Создайте словарь со списком вещей для похода в качестве ключа и их массой в качестве значения. Определите какие вещи влезут в рюкзак передав его максимальную грузоподъёмность. Достаточно вернуть один допустимый вариант.*Верните все возможные варианты комплектации рюкзака.

## Урок 4. Функции
### Семинар
1. Напишите функцию, которая принимает строку текста. Вывести функцией каждое слово с новой строки:  
- Строки нумеруются начиная с единицы;  
- Слова выводятся отсортированными согласно кодировки Unicode.  
Текст выравнивается по правому краю так, чтобы у самого длинного слова был один пробел между ним и номером строки.  
2. Напишите функцию, которая принимает строку текста. Сформируйте список с уникальными кодами Unicode каждого символа введённой строки отсортированный по убыванию.  
3. Функция получает на вход строку из двух чисел через пробел:  
- Сформируйте словарь, где ключом будет символ из Unicode, а значением — целое число;  
- Диапазон пар ключ-значение от наименьшего из введённых пользователем чисел до наибольшего включительно.
4. Функция получает на вход список чисел:  
- Отсортируйте его элементы in place без использования встроенных в язык сортировок;  
- Как вариант напишите сортировку пузырьком. Её описание есть в википедии.  
5. Функция принимает на вход три списка одинаковой длины:   
- имена str;  
- ставка int;  
- премия str с указанием процентов вида «10.25%»;  
- Вернуть словарь с именем в качестве ключа и суммой премии в качестве значения;  
- Сумма рассчитывается как ставка умноженная на процент премии.  
6. Функция получает на вход список чисел и два индекса:  
- Вернуть сумму чисел между между переданными индексами;  
- Если индекс выходит за пределы списка, сумма считается до конца и/или начала списка.  
7. Функция получает на вход словарь с названием компании в качестве ключа и списком с доходами и расходами (3-10 чисел) в качестве значения. Вычислите итоговую прибыль или убыток каждой компании. Если все компании прибыльные, верните истину, а если хотя бы одна убыточная — ложь.
8. Создайте несколько переменных заканчивающихся и не оканчивающихся на «s». Напишите функцию, которая при запуске заменяет содержимое переменных оканчивающихся на s (кроме переменной из одной буквы s) на None. Значения не удаляются, а помещаются в одноимённые переменные без s на конце.
### Домашняя работа
1. Напишите функцию для транспонирования матрицы
2. Напишите функцию принимающую на вход только ключевые параметры и возвращающую словарь, где ключ — значение переданного аргумента, а значение — имя аргумента. Если ключ не хешируем, используйте его строковое представление.
3. Возьмите задачу о банкомате из семинара 2. Разбейте её на отдельные операции — функции. Дополнительно сохраняйте все операции поступления и снятия средств в список.

## Урок 5. Итераторы и генераторы
### Семинар
1. Пользователь вводит строку из четырёх или более целых чисел, разделённых символом “/”. Сформируйте словарь, где:
- второе и третье число являются ключами;  
- первое число является значением для первого ключа;  
- четвертое и все возможные последующие числа хранятся в кортеже как значения второго ключа.
2. Самостоятельно сохраните в переменной строку текста. Создайте из строки словарь, где ключ — буква, а значение — код буквы. Напишите преобразование в одну строку.
3. Продолжаем развивать задачу 2.Возьмите словарь, который вы получили. Сохраните его итераторатор. Далее выведите первые 5 пар ключ-значение, обращаясь к итератору, а не к словарю.
4. Создайте генератор чётных чисел от нуля до 100. Из последовательности исключите числа, сумма цифр которых равна 8. Решение в одну строку.
5. Напишите программу, которая выводит на экран числа от 1 до 100.
- При этом вместо чисел, кратных трем, программа должна выводить слово «Fizz»;  
- Вместо чисел, кратных пяти — слово «Buzz»;  
- Если число кратно и 3, и 5, то программа должна выводить слово «FizzBuzz»;  
- Превратите решение в генераторное выражение.  
6. Выведите в консоль таблицу умножения от 2х2 до 9х10 как на школьной тетрадке. Таблицу создайте в виде однострочного генератора, где каждый элемент генератора — отдельный пример таблицы умножения. Для вывода результата используйте «принт» без перехода на новую строку.
7. Создайте функцию-генератор. Функция генерирует N простых чисел, начиная с числа 2. Для проверки числа на простоту используйте правило: «число является простым, если делится нацело только на единицу и на себя».
### Домашняя работа
1. Решить задачи, которые не успели решить на семинаре.  
2. Напишите функцию, которая принимает на вход строку - абсолютный путь до файла. Функция возвращает кортеж из трёх элементов: путь, имя файла, расширение файла.  
3. Напишите однострочный генератор словаря, который принимает на вход три списка одинаковой длины: имена str, ставка int, премия str с указанием процентов вида "10.25%". В результате получаем словарь с именем в качестве ключа и суммой премии в качестве значения. Сумма рассчитывается как ставка умноженная на процент премии.  
4. Создайте функцию генератор чисел Фибоначчи https://ru.wikipedia.org/wiki/%D0%A7%D0%B8%D1%81%D0%BB%D0%B0_%D0%A4%D0%B8%D0%B1%D0%BE%D0%BD%D0%B0%D1%87%D1%87%D0%B8  

## Урок 6. Модули
### Семинар
1. Вспомните какие модули вы уже проходили на курсе. Создайте файл, в котором вы импортируете встроенные в модуль функции под псевдонимами. (3-7 строк импорта).
2. Создайте модуль с функцией внутри. Функци принимает на вход три целых числа: нижнюю и верхнюю границу и количество попыток. Внутри генерируется случайное число в указанных границах и пользователь должен угадать его за заданное число попыток. Функция выводит подсказки "больше" и "меньше". Если число угадано, возвращается истина, а если попытки исчерпаны - ложь.
3. Улучшаем задачу 2. Добавьте возможность запуска функции "угадайки" из модуля в командной строке терминала. Строка должна принимать от 1 до 3 аргументов: параметры вызова функции. Для преобразования строковых аргументов командной строки в числовые параметры используйте генераторное выражение.
4. Создайте модуль с функцией внутри. Функция получает на вход загадку, список с возможными вариантами отгадок и количество попыток на угадывание. Программа возвращает номер попытки, с которой была отгадана загадка или ноль, если попытки исчерпаны.
5. Добавьте в модуль с загадками функцию, которая хранит словарь списков. Ключ словаря - загадка, значение - список с отгадками. Функция в цикле вызывает загадывающую функцию, чтобы передать ей все свои загадки.
6. Добавьте в модуль с загадками функцию, которая принимает на вход строку (текст загадки) и число (номер попытки, с которой она угадана). Функция формирует словарь с информацией о результатах отгадывания. Для хранения используйте защищённый словарь уровня модуля. Отдельно напишите функцию, которая выводит результаты угадывания из защищённого словаря в удобном для чтения виде.
Для формирования результатов используйте генераторное выражение.
7. Создайте модуль и напишите в нём функцию, которая получает на вход дату в формате DD.MM.YYYY. Функция возвращает истину, если дата может существовать или ложь, если такая дата невозможна.
Для простоты договоримся, что год может быть в диапазоне [1, 9999]. Весь период (1 января 1 года - 31 декабря 9999 года) действует Григорианский календарь. Проверку года на високосность вынести в отдельную защищённую функцию.
8. Создайте пакет с всеми модулями, которые вы создали за время занятия. Добавьте в init пакета имена модулей внутри дандер all. В модулях создайте дандер all и укажите только те функции, которые могут верно работать за пределами модуля.
### Домашняя работа
1. Решить задачи, которые не успели решить на семинаре.  
2. В модуль с проверкой даты добавьте возможность запуска в терминале с передачей даты на проверку.  
3. Добавьте в пакет, созданный на семинаре шахматный модуль. Внутри него напишите код, решающий задачу о 8 ферзях. Известно, что на доске 8×8 можно расставить 8 ферзей так, чтобы они не били друг друга. Вам дана расстановка 8 ферзей на доске, определите, есть ли среди них пара бьющих друг друга. Программа получает на вход восемь пар чисел, каждое число от 1 до 8 - координаты 8 ферзей. Если ферзи не бьют друг друга верните истину, а если бьют - ложь.  
4. Напишите функцию в шахматный модуль. Используйте генератор случайных чисел для случайной расстановки ферзей в задаче выше. Проверяйте различный случайные варианты и выведите 4 успешных расстановки.  

## Урок 7. Файлы и файловая система
### Семинар
1. Напишите функцию, которая заполняет файл (добавляет в конец) случайными парами чисел:
- Первое число int, второе - float разделены вертикальной чертой;  
- Минимальное число - -1000, максимальное - +1000;  
- Количество строк и имя файла передаются как аргументы функции.  
2. Напишите функцию, которая генерирует псевдоимена. Имя должно начинаться с заглавной буквы, состоять из 4-7 букв, среди которых обязательно должны быть гласные. Полученные имена сохраните в файл.
3. Напишите функцию, которая открывает на чтение созданные в прошлых задачах файлы с числами и именами. Перемножьте пары чисел. В новый файл сохраните имя и произведение:
- если результат умножения отрицательный, сохраните имя записанное строчными буквами и произведение по модулю;  
- если результат умножения положительный, сохраните имя прописными буквами и произведение округлённое до целого.  
В результирующем файле должно быть столько же строк, сколько в более длинном файле. При достижении конца более короткого файла, возвращайтесь в его начало.
4. Создайте функцию, которая создаёт файлы с указанным расширением. Функция принимает следующие параметры:
- расширение;  
- минимальная длина случайно сгенерированного имени, по умолчанию 6;  
- максимальная длина случайно сгенерированного имени, по умолчанию 30;  
- минимальное число случайных байт, записанных в файл, по умолчанию 256;  
- максимальное число случайных байт, записанных в файл, по умолчанию 4096;  
- количество файлов, по умолчанию 42.  
Имя файла и его размер должны быть в рамках переданного диапазона.
5. Доработаем предыдущую задачу. Создайте новую функцию которая генерирует файлы с разными расширениями. Расширения и количество файлов функция принимает в качестве параметров. Количество переданных расширений может быть любым. Количество файлов для каждого расширения различно. Внутри используйте вызов функции из прошлой задачи.
6. Дорабатываем функции из предыдущих задач. Генерируйте файлы в указанную директорию — отдельный параметр функции. Отсутствие/наличие директории не должно вызывать ошибок в работе функции (добавьте проверки). Существующие файлы не должны удаляться/изменяться в случае совпадения имён.
7. Создайте функцию для сортировки файлов по директориям: видео, изображения, текст и т.п. Каждая группа включает файлы с несколькими расширениями. В исходной папке должны остаться только те файлы, которые не подошли для сортировки. Прмечание: необходимо исправить ошибку - не найден путь.
### Домашняя работа
1. Решить задачи, которые не успели решить на семинаре.  
2. Напишите функцию группового переименования файлов. Она должна:  
a. принимать параметр желаемое конечное имя файлов. При переименовании в конце имени добавляется порядковый номер.  
b. принимать параметр количество цифр в порядковом номере.  
c. принимать параметр расширение исходного файла. Переименование должно работать только для этих файлов внутри каталога.  
d. принимать параметр расширение конечного файла.  
e. принимать диапазон сохраняемого оригинального имени. Например для диапазона [3, 6] берутся буквы с 3 по 6 из исходного имени файла. К ним прибавляется желаемое конечное имя, если оно передано. Далее счётчик файлов и расширение.  
3. Соберите из созданных на уроке и в рамках домашнего задания функций пакет для работы с файлами.  

## Урок 8. Сериализация
### Семинар
1. Вспоминаем задачу 3 из прошлого семинара. Мы сформировали текстовый файл с псевдо именами и произведением чисел. Напишите функцию, которая создаёт из созданного ранее файла новый с данными в формате JSON. Имена пишите с большой буквы. Каждую пару сохраняйте с новой строки.
2. Напишите функцию, которая в бесконечном цикле запрашивает имя, личный идентификатор и уровень доступа (от 1 до 7). После каждого ввода добавляйте новую информацию в JSON файл. Пользователи группируются по уровню доступа. Идентификатор пользователя выступает ключём для имени. Убедитесь, что все идентификаторы уникальны независимо от уровня доступа. При перезапуске функции уже записанные в файл данные должны сохраняться.
3. Напишите функцию, которая сохраняет созданный в прошлом задании файл в формате CSV.
4. Прочитайте созданный в прошлом задании csv файл без использования csv.DictReader. Дополните id до 10 цифр незначащими нулями. В именах первую букву сделайте прописной. Добавьте поле хеш на основе имени и идентификатора. Получившиеся записи сохраните в json файл, где каждая строка csv файла представлена как отдельный json словарь. Имя исходного и конечного файлов передавайте как аргументы функции.
5. Напишите функцию, которая ищет json файлы в указанной директории и сохраняет их содержимое в виде одноимённых pickle файлов.
6. Напишите функцию, которая преобразует pickle файл хранящий список словарей в табличный csv файл. Для тестированию возьмите pickle версию файла из задачи 4 этого семинара. Функция должна извлекать ключи словаря для заголовков столбца из переданного файла.
7. Прочитайте созданный в прошлом задании csv файл без использования csv.DictReader. Распечатайте его как pickle строку.
### Домашняя работа
1. Решить задачи, которые не успели решить на семинаре.  
2. Напишите функцию, которая получает на вход директорию и рекурсивно обходит её и все вложенные директории. Результаты обхода сохраните в файлы json, csv и pickle:   
- Для дочерних объектов указывайте родительскую директорию;  
- Для каждого объекта укажите файл это или директория;   
- Для файлов сохраните его размер в байтах, а для директорий размер файлов в ней с учётом всех вложенных файлов и директорий.  
3. Соберите из созданных на уроке и в рамках домашнего задания функций пакет для работы с файлами разных форматов.  

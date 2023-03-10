---
## Front matter
title: "Отчёт по лабораторной работе №7"
subtitle: "Командная оболочка Midnight Commander"
author: "Михаил Александрович Мелкомуков"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Освоение основных возможностей командной оболочки Midnight Commander. Приобретение навыков практической работы по просмотру каталогов и файлов, манипуляций с ними.

# Задание

- Рассмотреть выполнение команд, приведённых в первой части описания лабораторной работы
- Выполнить действия, зафиксировав в отчёте по лабораторной работе используемые при этом команды и результаты их выполнения
- Создать отчёт и презентацию в Markdown
- Загрузить скринкасты на видео хостинг
- Представить работу на сайте ТУИС

# Выполнение лабораторной работы

## Выполнение задания по mc

![Изучили информацию о mc, вызвав в командной строке man mc](image/1.png)

![Запустили из командной строки mc, с целью изучить его структуру и меню](image/2.png)

![В разделе меню "Левая панель" выбрали режим Дерево](image/3.png)

![Посмотрели информацию о каталоге выбрав режим Информация](image/4.png)

![Выбрали формат списка укроченный](image/5.png)

![В результате имена файлов помещаются в две колонки](image/6.png)

![Выбрали порядок сортировки по Размеру](image/7.png)

![После сортировки расположение файлов изменилось](image/8.png)

![Выбрали фильрт, показывающий файлы только с расширением *.pub и каталоги, в которых они находятся](image/9.png)

![В результате большинство скрытых файлов и все текстовые файлы в поле видения исчезли](image/10.png)

![Рассмотрим способы редактирования файла с помощью сочетаний клавиш на примере файла dad.txt](image/11.png)

![Открыли файл с помощью функциональной клавиши F4 и ввели в него незамысловатый текст](image/12.png)

![С помощью функциональной клавиши F3 выделили строку текстового файла, затем, перейдя на другую строку и нажав на клавишу F5, скопировали выделенный текстовый фрагмент](image/13.png)

![С помощью функциональной клавиши F8 удалили её](image/14.png)

![С помощью комбинации клавиш CTRL+U отменили последнюю операцию](image/15.png)

![Перешли на другое место в файле и переместили выделенный фрагмент с помощью функциональной клавиши F6](image/16.png)

![С помощью функциональной клавиши F2 сохранили изменения в файле](image/17.png)

![С помощью функциональной клавиши F10 вышли из режима правки файла](image/18.png)

![С помощью комбинации клавиш CTRL+U поменяли местами левую и правую панели](image/19.png)

![С помощью функциональной клавиши F6 переименовали файл dad.txt в daddy.txt](image/20.png)

![С помощью функциональной клавиши F3 открыли файл daddy.txt для просмотра (не для редактирования!)](image/21.png)

![С помощью функциональной клавиши F7 создали новый каталог с именем family](image/22.png)

![Результат выполнения предыдущей операции](image/23.png)

![Скопировали файл daddy.txt в каталог family, указав необходимый путь](image/24.png)

![Решили найти файл mom.txt, для чего перешли в раздел меню "Команда" и выбрали действие "Поиск файла"](image/25.png)

![Файл mom.txt нашёлся в directory1](image/26.png)

![Решили найти все файлы с расширением .txt в каталоге test](image/27.png)

![Нашли все файлы с расширением .txt](image/28.png)

![Зашли в раздел меню "Настройки"](image/29.png)

![Поменяли оформление на более трендовое и современное](image/30.png)

## Выполнение задания по встроенному редактору mc

![Создали файл text.txt для дальнейшей работы с ним](image/31.png)

![Ввели в него небольшую историю, способную растрогать любого](image/32.png)

![С помощью функциональной клавиши F3 выделили строку текстового файла](image/33.png)

![С помощью функциональной клавиши F8 удалили её](image/34.png)

![Выделили текстовый фрагмент](image/35.png)

![Скопировали его на новую строку с помощью функциональной клавиши F5](image/36.png)

![С помощью функциональной клавиши F2 сохранили файл](image/37.png)

![Вернулись обратно и с помощью комбинации клавиш CTRL+U отменили последнюю операцию](image/38.png)

![Открыли первый попавшийся файл с кодом в режиме редактирования с помощью клавиши F4](image/39.png)

![С помощью клавиши F9 открыли меню и в настройках нашли, как можно выбрать цветовыделения синтаксиса. К сожалению, для конкретного языка опции мы не нашли](image/40.png)

# Контрольные вопросы

Ответы на контрольные вопросы следуют из хода выполнения лабораторной работы. Большинство операций в меню командная оболочка Midnight Commander были выполнены и охарактеризованы (сочетания клавиш для их быстрого выполнения были так же указаны).

# Выводы

Освоили основные возможности командной оболочки Midnight Commander. Приобрели навыки практической работы по просмотру каталогов и файлов, манипуляций с ними.


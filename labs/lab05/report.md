---
## Front matter
title: "Лабораторная работа №5"
subtitle: "Основы работы с
Midnight Commander (mc). Структура программы на
языке ассемблера NASM. Системные вызовы в ОС
GNU Linux"
author: "Виеру Женифер"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
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
mainfont: IBM Plex Serif
romanfont: IBM Plex Serif
sansfont: IBM Plex Sans
monofont: IBM Plex Mono
mathfont: STIX Two Math
mainfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
romanfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
sansfontoptions: Ligatures=Common,Ligatures=TeX,Scale=MatchLowercase,Scale=0.94
monofontoptions: Scale=MatchLowercase,Scale=0.94,FakeStretch=0.9
mathfontoptions:
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
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Целью работы является приобретение практических навыков работы в Midnight Commander,oсвоение инструкций языка ассемблера mov и int.

# Выполнение лабораторной работы
Открыла Midnight Commander и перешла в каталог ~/work/arch-pc  (рис. [-@fig:001]).

![Midnight Commander](image/1.jpeg){#fig:001 width=70%}

Далее создаем lab05 (рис. [-@fig:002]).

![Создание lab05](image/2.jpeg){#fig:002 width=70%}

Далее создаем lab5-1.asm (рис. [-@fig:003]).

![lab5-1.asm](image/3.jpeg){#fig:003 width=70%}

С помощью клавиши F4 открыла lab5-1.asm и написала прграмму вывода сообщению на экран и ввода строки с клавиатуры (рис. [-@fig:004]).

![Текст программы lab5-1.asm](image/4.jpeg){#fig:004 width=70%}

Потом оттранслировала текст программы lab5-1.asm в объектный файл и выполнила компо-
новку объектного файла и запустила получившийся исполняемый файл. (рис. [-@fig:005]).

![Запуск текста программы](image/5.jpeg){#fig:005 width=70%}

Создала копию lab5-1.asm  с именем lab5-2.asm, открыла с помощью клавиши F4 и написала программу вывода сообщения на экран и ввода строки с клавиатуры c
использованием файла in_out.asm (рис. [-@fig:006]).

![Копирование файла lab04](image/6.jpeg){#fig:006 width=70%}

# Выполнение самостоятельной работы

Создала копию lab5-1.asm и внесла изменения, так чтобы она вывела приглашение типа “Введите строку:”; ввесила строку с клавиатуры; вывестила введённую строку на экран(рис. [-@fig:007]).

![Копия lab5-1.asm](image/7.jpeg){#fig:007 width=70%}

![Текст программы lab5-1.asm](image/9.jpeg){#fig:009 width=70%}

Потом оттранслировала текст программы lab5-1.asm в объектный файл и выполнила компо-
новку объектного файла и запустила получившийся исполняемый файл. (рис. [-@fig:010]).

![Запуск текста программы](image/10.jpeg){#fig:010 width=70%}

Создала копию lab5-2.asm и внесла изменения, так чтобы она вывела приглашение типа “Введите строку:”; ввесила строку с клавиатуры; вывестила введённую строку на экран(рис. [-@fig:011]).

![Текст программы lab5-2.asm](image/11.jpeg){#fig:011 width=70%}

Потом оттранслировала текст программы lab5-2.asm в объектный файл и выполнила компо-
новку объектного файла и запустила получившийся исполняемый файл. (рис. [-@fig:012]).

![Запуск текста программы](image/12.jpeg){#fig:012 width=70%}


# Выводы
Выполнив данную лабораторную работу я обрела теоретические и практические знания в работы с Midnight Commander (mc). 

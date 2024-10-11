---
## Front matter
title: "Лабораторная работа №3"
subtitle: "Язык разметки Markdown"
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

Целью работы является освоение процедуры оформления отчетов с помощью легковесного
языка разметки Markdown.

# Выполнение лабораторной работы
Перешла в директорию с проектом, и обновила изменения с основново репозитория (рис. [-@fig:001]).

![Переход в директорий](image/1.png){#fig:001 width=70%}

Перешла в папку отчета 3 лабараторной (рис. [-@fig:002]).

![Переход в папку отчета](image/2.png){#fig:002 width=70%}

Выполнила команду make (рис. [-@fig:003]).

![Выполнение команды make](image/3.png){#fig:003 width=70%}

Удаляю полученный файлы с использованием make clean (рис. [-@fig:005]).

![Выполнение команды make clean](image/5.png){#fig:005 width=70%}

Откройткрою файл report.md c помощью текстового редактора gedit (рис. [-@fig:004]).

![Выполнение конманды gedit](image/4.png){#fig:004 width=70%}

# Выводы
Выполнив данную лабораторную работу я обрела теоретические и практические знания в использовании разметки Markdown. При помощи консоли я научилась компилировать отчет с использованием Makefile.
Здесь кратко описываются итоги проделанной работы.

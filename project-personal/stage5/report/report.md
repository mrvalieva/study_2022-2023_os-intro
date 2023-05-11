---
## Front matter
title: "Индивидуальный проект."
subtitle: "Выполнение 5 этапа."
author: "Валиева Марина Русланбековна"

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

Добавить с сайту все остальные элементы.

# Задание


    Сделать записи для персональных проектов.
    Сделать пост по прошедшей неделе.
    Добавить пост на тему по выбору.
        Языки научного программирования.


# Выполнение индивидуального проекта

1. Сделала записи для персональных проектов.

![проект](image/1.jpg){#fig:001 width=90%}
![проект](image/2.jpg){#fig:002 width=90%}
![проект](image/3.jpg){#fig:003 width=90%}
![проект](image/4.jpg){#fig:004 width=90%}
![проект](image/5.jpg){#fig:005 width=90%}
![проект](image/6.jpg){#fig:006 width=90%}
![проект](image/7.jpg){#fig:007 width=90%}

2. Сделала пост по прошедшей неедле.

![пост](image/8.jpg){#fig:008 width=90%}

3. Добавила пост на тему "Языки научного программирования"

![пост2](image/9.jpg){#fig:009 width=90%}

# Выводы

Добавила на сайт все остальные элементы.

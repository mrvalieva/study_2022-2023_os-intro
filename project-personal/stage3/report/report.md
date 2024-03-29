---
## Front matter
title: "Третий этап индивидуального проекта"
subtitle: "Добавление к сайту достижений"
author: "Валиева Марина Руслабековна"

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

Добавить на сайт достижения

# Задание

Добавить к сайту достижения.

    Список достижений.
       Добавить информацию о навыках (Skills).
       Добавить информацию об опыте (Experience).
       Добавить информацию о достижениях (Accomplishments).
    Сделать пост по прошедшей неделе.
    Добавить пост на тему по выбору:
       Легковесные языки разметки.
       Языки разметки. LaTeX.
       Язык разметки Markdown.



# Выполнение индивидуального проекта

Захожу в папку блог и ищу необходимые мне папки (навыки, опыт и достижения)

![папки](image/1.png){#fig:001 width=90%}

Далее пишу свои навыки. Также сразу пишу опыт и достижения.

![навыки](image/2.png){#fig:002 width=90%}
![опыт](image/3.png){#fig:003 width=90%}
![достижения](image/4.png){#fig:004 width=90%}

Далее добавляю пост по прошедшей неделе.

![пост](image/5.png){#fig:005 width=90%}

Добавляю пост по выбранной мной теме.

![маркдаун](image/6.png){#fig:006 width=90%}

Итоговый результат:

![сайт](image/7.png){#fig:007 width=90%}
![сайт](image/8.png){#fig:008 width=90%}
![сайт](image/9.png){#fig:009 width=90%}
![сайт](image/10.png){#fig:010 width=90%}

# Выводы

Добавила на сайт достижения.

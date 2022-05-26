---
## Front matter
title: "Операционные системы"
subtitle: "Индивидуальный проект, часть 5"
author: "Матюшкин Денис Владимирович (НПИбд-02-21)"

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

- Добавить к сайту все остальные элементы.

# Ход работы

1. Для добавления нового проекта необходимо перейти к каталогу сайта. После перейдем в *content/project*. Создадим новый проект и заполним его (рис. [-@fig:001]). Зайдем в наш сайт и проверим изменения (рис. [-@fig:002]).

![Добавление ссылок](image/1.png){ #fig:001 width=100% }

![Проверка ссылок](image/2.png){ #fig:002 width=70% }

2. Создадим пост по прошедей неделе в каталоге *content/post*.

3. Создадим пост о языках научного программирования в том же каталоге (рис. [-@fig:003]).

![Создание поста по выбору](image/3.png){ #fig:003 width=100% }

4. Зайдем в наш сайт и проверим изменения (рис. [-@fig:004]).

![Проверка постов](image/4.png){ #fig:004 width=70% }

# Заключение 

В ходе этой лабораторной работы мы добавили к сайту все остальные элементы.









































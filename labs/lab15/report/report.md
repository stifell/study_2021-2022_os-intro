---
## Front matter
title: "Операционные системы"
subtitle: "Индивидуальный проект, часть 2"
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

Добавить к сайту данные о себе.

# Ход работы

1. Для добавления данных о владельце сайта необходимо перейти к каталогу сайта. После перейдем в *content/authors/admin* для редактирования главной страницы сайта (рис. [-@fig:001]).

![Переход в каталог](image/1.png){ #fig:001 width=100% }

2. Откроем файл *_index.md* и добавим данные о себе: 1) ФИО, жизненное положение, сайт университета, краткая биография (рис. [-@fig:002]); 2) интересы, образование (рис. [-@fig:003]); 3) email и биографию (рис. [-@fig:004]).

![Добавление данных о владельце](image/2.png){ #fig:002 width=100% }

![Добавление данных о владельце](image/3.png){ #fig:003 width=100% }

![Добавление данных о владельце](image/4.png){ #fig:004 width=100% }

3. Поменяем аватарку в нашем сайте, для этого загруженную картинку нужно назвать *avatar.jpg/png* (рис. [-@fig:005]).

![Добавление аватарки](image/5.png){ #fig:005 width=100% }

4. Далее нам необходимо создать два новых поста, для этого перейдем в *content/post* и создадим две папки (рис. [-@fig:006]).

![Создание постов](image/6.png){ #fig:006 width=100% }

5. Создадим в папке файл *index.md* и для красоты добавим картинку (рис. [-@fig:007]).

![Работа с постом](image/7.png){ #fig:007 width=100% }

6. Откроем файл *index.md* и начнем заполнять данные о посте (рис. [-@fig:008]).

![Редактирование поста](image/8.png){ #fig:008 width=100% }

7. Аналогичные действия совершим со вторым постом (рис. [-@fig:009] и рис. [-@fig:010]).

![Работа с постом](image/9.png){ #fig:009 width=100% }

![Редактирование поста](image/10.png){ #fig:010 width=100% }

8. Закончили заполнение данных. Сгенерируем наш сайт через консоль, перейдем в каталог *public* и выгрузим изменения в репозиторий Github (рис. [-@fig:011]).

![Завершение настройки сайта](image/11.png){ #fig:011 width=100% }

9. Перейдем в наш обновленный сайт и смотрим на изминения (рис. [-@fig:012]).

![Проверка сайта](image/11.png){ #fig:011 width=100% }

# Заключение 

В ходе этой лабораторной работы мы добавили к сайту данные о себе.










































---
## Front matter
lang: ru-RU
title: Лабораторная работа №3
author: Матюшкин Денис Владимирович (НПИбд-02-21)
institute: RUDN University, Moscow, Russian Federation
date: 29.04.2022

## Formatting
toc: false
slide_level: 2
theme: metropolis
header-includes: 
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
aspectratio: 43
section-titles: true
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
---

# Цель работы

- Научиться оформлять отчёты с помощью легковесного языка разметки Markdown.

# Ход работы

## 1. Скачивание pandoc

Перед началом работы с Markdown скачаем и установим pandoc (рис. [-@fig:001]). А [pandoc-citeproc](https://github.com/jgm/pandoc/releases) и [pandoc-crossref](https://github.com/lierdakil/pandoc-crossref/releases) скачаем и разархивируем в нужные каталоги в /usr. 

![Скачивание и установка pandoc](/home/dvmatyushkin/work/study/2021-2022/Операционные системы/os-intro/labs/lab03/report/image/1.png){ #fig:001 width=70% }

## 2. Скачивание pdflatex

Также для работы нам необходим pdflatex, скачаем его и установим (рис. [-@fig:002]).

![Скачивание и установка pdflatex](/home/dvmatyushkin/work/study/2021-2022/Операционные системы/os-intro/labs/lab03/report/image/2.png){ #fig:002 width=70% }

## 3.1 Оформление отчета

После установки необходимых программ начем оформлять отчёт по предыдущей лабораторной работе в формате Markdown (рис. [-@fig:003] и рис. [-@fig:004]).

![Оформление титульного листа](/home/dvmatyushkin/work/study/2021-2022/Операционные системы/os-intro/labs/lab03/report/image/4.png){ #fig:003 width=70% }

## 3.2 Оформление отчета

![Оформление цели и ход работы](/home/dvmatyushkin/work/study/2021-2022/Операционные системы/os-intro/labs/lab03/report/image/5.png){ #fig:004 width=70% }

## 4. Конвертирование файла Markdown

Оформив весь отчет в виде Markdown, мы должны его конвертировать в формат docx и pdf. Для этого перейдем каталог лабораторной и пропишем *make* (рис. [-@fig:005]). 

![Конвертирование файла md в docx и pdf](/home/dvmatyushkin/work/study/2021-2022/Операционные системы/os-intro/labs/lab03/report/image/6.png){ #fig:005 width=70% }

## 5. Проверка файлов

Перейдем каталог лабораторной, проверим конвертированные файлы (рис. [-@fig:006]).

![Проверка файлов на создание](/home/dvmatyushkin/work/study/2021-2022/Операционные системы/os-intro/labs/lab03/report/image/3.png){ #fig:006 width=70% }

# Заключение 

В ходе этой лабораторной работы мы научились оформлять отчёты с помощью легковесного языка разметки Markdown.













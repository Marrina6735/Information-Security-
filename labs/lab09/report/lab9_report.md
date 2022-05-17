---
## Front matter
title: "ОТЧЕТ ПО ЛАБОРАТОРНОЙ РАБОТЕ № 9"
subtitle: "Текстовой редактор emacs"
author: "Коняева Марина Александровна"

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
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором Emacs.

# Задание

1. Ознакомиться с теоретическим материалом.
2. Ознакомиться с редактором emacs.
3. Выполнить упражнения.
4. Ответить на контрольные вопросы.

# Теоретическое введение

Буфер — объект, представляющий какой-либо текст. Буфер может содержать что угодно, например, результаты компиляции программы или встроенные подсказки. Практически всё взаимодействие с пользователем, в том числе интерактивное, происходит посредством буферов. Фрейм соответствует окну в обычном понимании этого слова. Каждый фрейм содержит область вывода и одно или несколько окон Emacs. Окно — прямоугольная область фрейма, отображающая один из буферов.

# Выполнение лабораторной работы

1. Знакомство с emacs и работа с файлом (изображение 1.1)

![Знакомство с emacs и работа с файлом](image/9.1.png){ #fig:001 width=100%}
*Изображение 1.1  Знакомство с emacs и работа с файлом*

2. Работа с буфером (изображение 2.1)

![Работа с буфером](image/9.2.png){ #fig:001 width=100%}
*Изображение 2.1  Работа с буфером*

3. Создание 4ч окон редактирования (изображение 3.1)

![Создание 4ч окон редактирования](image/9.3.png){ #fig:001 width=100%}
*Изображение 3.1  Создание 4ч окон редактирования*

# Выводы

В ходе данной лабораторной работы познакомились с операционной системой Linux, получили практические навыки работы с редактором Emacs, а также ответили на контрольные вопросы.

# Контрольные вопросы

1. Редактор обладает возможностью редактировать текст, а также некоторыми удобными функциями, к примеру поиск текста.

2. Большое количество команд, некоторые из которых непонятно как использовать горячими клавишами.

3. Окно - отображённый буфер. Буфер - какой то текст.

4. В одном окне отображается один буфер, соответственно 10 буферов в одном окне открыть нельзя.

5. GNU Emacs, Messages, scratch.

6. ctrl + c + |

7. c-x 2

8. Настройки emacs хранятся в файле .emacs

9. Удаление предыдущего символа

10. Мне удобнее было использовать vi, поскольку я привык его использовать у себя на работе


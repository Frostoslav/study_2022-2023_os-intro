---
## Front matter
title: "Отчёт по третьему этапу индивидуального проекта"
subtitle: "Операционные системы"
author: "Толстых Максим Алексеевич"

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
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---


# Цель работы
- Добавить к сайту данные о себе и новые посты.

# Задание
- Добавить информацию о навыках (Skills).
- Добавить информацию об опыте (Experience).
- Добавить информацию о достижениях (Accomplishments).
- Сделать пост по прошедшей неделе.
- Добавить пост на тему по выбору:
	- Легковесные языки разметки.
	- Языки разметки. LaTeX.
	- Язык разметки Markdown.

# Выполнение третьего этапа индивидуального проекта

## Новые данные о себе

1. Перешли в папку blog/content и открыли файл _index.md. Добавили информацию о своих навыках.(рис. [-@fig:001]), (рис. [-@fig:002])

![Навыки](image/1.png){ #fig:001 width=70%}

![Навыки](image/2.png){ #fig:002 width=70%}

2. В этом же файле _index.md добавили информацию о своём опыте. (рис. [-@fig:003]), (рис. [-@fig:004])

![Опыт](image/3.png){ #fig:003 width=70%}

![Опыт](image/4.png){ #fig:004 width=70%}

3. В этом же файле _index.md добавили информацию о своих достижениях. (рис. [-@fig:005]), (рис. [-@fig:006])

![Достижения](image/5.png){ #fig:005 width=70%}

![Достижения](image/6.png){ #fig:006 width=70%}

## Новые посты

Добавили пост недели и пост по выбору. Перешли в папку “contents”
-> “post” и добавили необходимую информацию. (рис. [-@fig:007]), (рис. [-@fig:008]), (рис. [-@fig:009]), (рис. [-@fig:010]), (рис. [-@fig:011]), (рис. [-@fig:012])

![Пост недели](image/7.png){ #fig:007 width=70%}

![Пост недели](image/8.png){ #fig:008 width=70%}

![Пост недели](image/9.png){ #fig:009 width=70%}

![Пост по выбору](image/10.png){ #fig:010 width=70%}

![Пост по выбору](image/11.png){ #fig:011 width=70%}

![Пост по выбору](image/12.png){ #fig:012 width=70%}

## Отправка изменений на гитхаб

4. Загрузили все изменения на гитхаб. (рис. [-@fig:013]), (рис. [-@fig:014])

![Гитхаб](image/13.png){ #fig:013 width=70%}

![Гитхаб](image/14.png){ #fig:014 width=70%}


# Выводы

В ходе выполнения первого этапа индивидуального проекта были изучены способы изменения информации на сайте и создания постов.

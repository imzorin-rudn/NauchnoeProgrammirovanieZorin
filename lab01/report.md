---
# Front matter
lang: ru-RU
title: "Отчёт по лабораторной работе №1"
subtitle: "дисциплина: Научное программирование"
author: "Зорин Илья Михайлович"

# Formatting
toc-title: "Содержание"
toc: true # Table of contents
toc_depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4paper
documentclass: scrreprt
polyglossia-lang: russian
polyglossia-otherlangs: english
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase
indent: true
pdf-engine: lualatex
header-includes:
  - \linepenalty=10 # the penalty added to the badness of each line within a paragraph (no associated penalty node) Increasing the value makes tex try to have fewer lines in the paragraph.
  - \interlinepenalty=0 # value of the penalty (node) added after each line of a paragraph.
  - \hyphenpenalty=50 # the penalty for line breaking at an automatically inserted hyphen
  - \exhyphenpenalty=50 # the penalty for line breaking at an explicit hyphen
  - \binoppenalty=700 # the penalty for breaking a line at a binary operator
  - \relpenalty=500 # the penalty for breaking a line at a relation
  - \clubpenalty=150 # extra penalty for breaking after first line of a paragraph
  - \widowpenalty=150 # extra penalty for breaking before last line of a paragraph
  - \displaywidowpenalty=50 # extra penalty for breaking before last line before a display math
  - \brokenpenalty=100 # extra penalty for page breaking after a hyphenated line
  - \predisplaypenalty=10000 # penalty for breaking before a display
  - \postdisplaypenalty=0 # penalty for breaking after a display
  - \floatingpenalty = 20000 # penalty for splitting an insertion (can only be split footnote in standard LaTeX)
  - \raggedbottom # or \flushbottom
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Изучить идеологию и применений средств контроля версий. Освоить умения по работе с git.

# Выполнение лабораторной работы

1. Git был предварительно установлен, а пользователь настроен (рис.1).

![Рис. 1. Настройка git](images/1.png){ #fig:001 width=70% }

2. Проведем настройку оставшихся параметров (рис.2).

![Рис. 2. Настройка параметров](images/2.png){ #fig:001 width=70% }

3. Создадим SSH ключ (рис.3).

![Рис. 3. Генерация ключа](images/3.png){ #fig:001 width=70% }

4. Создадим SSH ключ иным алгоритмом (рис.4).

![Рис. 4. Генерация ключа иным методом](images/4.png){ #fig:001 width=70% }

5. Создан репозиторий на основе шаблона (рис. 5).

![Рис. 5. Репозиторий](images/5.png){ #fig:001 width=70% }

6. Загружены необходимые файлы на основе шаблона (рис. 6).

![Рис. 6. Загруженные материалы](images/6.png){ #fig:001 width=70% }

# Выводы

Изучил идеологию и применений средств контроля версий. Освоил умения по работе с git.

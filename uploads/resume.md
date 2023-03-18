---
## Front matter
title: "Отчёт по лабораторной работе"
subtitle: "Установка ОС Linux"
author: "Лев Евгеньевич Гельбарт"

## Pdf output format
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
Цель работы - освоение и установка ОС Linux.

# Выполнение лабораторной работы
![Отчет 1](Снимки экрана/4.png){ #fig:fig1 width=70% } 

В прошлом семестре мною уже была установлена ОС Linux, она полностью функционирует, для доказательства этого я приведу скриншоты из старых отчетов, для начала титульный лист первой из них, целью которой была установка Линукса (рис. [-@fig:fig1]).

![Отчет 1](Снимки экрана/5.png){ #fig:fig2 width=70% } 

Здесь приведен вывод и финальные строки отчета, ссылку на репозиторий с отчетами я приложу, чтобы можно было удостовериться в правильности выполненной работы (рис. [-@fig:fig2]).

![Отчет 2](Снимки экрана/6.png){ #fig:fig3 width=70% } 

Здесь приведен титульный лист второй лабораторной работы, целью которой было освоение функционала командной строки в линуксе (рис. [-@fig:fig3]).

![Отчет 2](Снимки экрана/7.png){ #fig:fig4 width=70% } 

На скриншоте вывод из той же лабораторной работы, доказывающий освоение командной строки Линукса (рис. [-@fig:fig4]).

![Отчет 4](Снимки экрана/8.png){ #fig:fig5 width=70% } 

Как доказательство установка ТеХ, пандока и прочего ПО приведено фото из четвертой лабораторной работы, посвященной именно этому. На фото видно, что команда make выполняется без всяких затруднений (рис. [-@fig:fig5]).

# Домашняя работа
![Терминал](Снимки экрана/1.png){ #fig:fig6 width=70% } 

Начнем получать необходимую информацию с помощью командной строки. На этом фото видно, как были получены данные о версии линукса, процессора и cpu. Также здесь начата выдача данных о памяти (рис. [-@fig:fig6]).

![Терминал](Снимки экрана/2.png){ #fig:fig7 width=70% } 

В первой строке этого скриншота информация о свободной памяти. Также здесь информация о типе файловой системы корневого каталога  (рис. [-@fig:fig7]).

![Терминал](Снимки экрана/3.png){ #fig:fig8 width=70% } 

На этом фото информация о последовательности монтирования файловых систем  (рис. [-@fig:fig8]).

# Выводы
Была установлена ОС Linux и все прочее необходимое ПО (ТеХ и так далее). Навыки пользования командной строки для нахождения информации о машине доказаны.


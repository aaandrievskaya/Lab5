---
## Front matter
title: "ОТЧЕТ"
subtitle: "по индивидуальному проекту Этап №2"
author: "Андриевская Анастасия Андреевна НПИбд-01-21 1032211699"

## Generic otions
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 1
lof: true # List of figures
lot: false # List of tables
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
  - \usepackage[utf8]{inputenc}
  - \usepackage[russian]{babel}
  - \usepackage[T1]{fontenc}
  - \usepackage{lmodern}
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---


## **Цель работы:**
Целью данной работы является приобретение практических навыков внесения информации на сайт.

## **Ход работы:**
1.	Я связала файл config.yaml с будущим сайтом. Для этого я перешла в файл andrievskaya/config/_default/config.yaml. Далее в 7-ой строчке файла я изменила ссылку на свою ссылку сайта (рис. 1).

    ![Файл config.yaml](Файлconfig.yaml.png)


1. Я добавила свой аватар. Для этого я перешла в папку andrievskaya/content/admin. В ней я удалила картинку аватара, которая была там по умолчанию и вставила свой аватар, назвав при этом также (рис.2).

    ![Изменение аватара.png](Изменениеаватара.png)

2. Я внесла информацию о себе (биографию, образование и интересы) в файл _index.md. Для этогго я перешла в файл andrievskaya/content/admin/_index.md и по готовому шаблону внесла в него свои данные (рис.3).
   
    ![Внесение информации в файл _index. md](Внесениеинформациивфайл_index.md.png)

   
3. Я создала папки для будущих постов на сайте. Для этого нужно было перейти в папку andrievskaya/content/post и создать новые папки для постов, которые я назвала "How was my week" и "Version control. Git" (рис. 4).

    ![Создание папок с будущими постами](Созданиепапоксбудущимипостами.png)

4. В эти папки я вставила образцовые файлы index.md и внесла в них изменения в соответствии с желаемыми постами на сайте (рис.5 и рис. 6).
   
    ![Создание поста №1 Внесение информации в файл index. md](Созданиепост№1Внесениеинформациивфайлindex.md.png)


    ![Создание поста №2 Внесение информации в файл index. md](Созданиепост№2Внесениеинформациивфайлindex.md.png)


5. Я пересобрала свой сайт через hugo. Для этого в терминале в каталоге andrievskaya я ввела соответствующую команду
   
    ![Итоги сборки сайта](Итогисборкисайта.png)

6. После в терминале я перешла в каталог andrievskaya/public. Я добавила в git папку public, добавила комментарий к этой версии и отправила сборку сайта на git (рис. 8).

    ![Отправка сайта после сборки](Отправкасайтапослесборки.png)
    
7.	Я увидела собственноручно сделанный сайт обо мне.

    ![Готовая титульная часть сайта](Готоваятитульнаячастьсайта.png)


## **Выводы:** 
Я приобрела практические навыки внесения информации на сайт.

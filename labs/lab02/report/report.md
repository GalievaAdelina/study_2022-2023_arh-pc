---
## Front matter
title: "Лабораторная работа №2"
subtitle: "Архитектура вычислительных систем"
author: "Аделина Руслановна Галиева"

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

Изучить идеологию и применение средств
контроля версий. Приобрести практические навыки по работе с
системой git

# Задание

Здесь приводится описание задания в соответствии с рекомендациями
методического пособия и выданным вариантом.


# Выполнение лабораторной работы

Описываются проведённые действия, в качестве иллюстрации даётся ссылка на иллюстрацию (рис. [-@fig:001])

1. Сначала сделаем предварительную конфигурацию git.


![Сделаем предварительную конфигурацию,указав имя и email владельца репозиитория](image/1.png){#fig:001 width=95%}

2. Настроим utf-8 в выводе сообщений git.


![Настроивам utf-8 в выводе сообщений git.](image/2.png){#fig:002 width=95%}


3. Зададим имя начальной ветки(будем называть её master).


![Задаем имя начальной ветки (master)](image/3.png){#fig:003 width=95%}


4. Параметр autocrlf.


![Вводим параметр autocrlf](image/4.png){#fig:004 width=95%}


5. Параметр safecrlf.


![Вводим параметр safecrlf](image/5.png){#fig:005 width=95%}


6. Для последующей идентификации пользователя на сервере репозиториев необходимо сгенерировать пару ключей (приватный и открытый):


![Генерируем ключ](image/6.png){#fig:006 width=95%}


7. Далее загружаем сгенерённый открытый ключ на сайте http://github.org/ под своей учётной записью и переходим в меню Setting . После этого выбираем в боковом меню SSH and GPG keys и нажимем кнопку New SSH key.Далее копируем из локальной консоли ключ в буфер обмена.


![Загружаем сгенеренный открытый ключ](image/7.png){#fig:007 width=95%}


8. Вставляем ключ в появившееся на сайте поле и указываем для ключа имя(Title).


![Вставляем ключ и указываем для ключа имя](image/8.png){#fig:008 width=95%}


9. Открываем терминал и создаём каталог для предмета «Архитектура компьютера».


![Открываем терминал и создаём каталог](image/9.png){#fig:009 width=95%}


10. Переходим в репозиторий https://github.com/yamadharma/course-directory-student-template и выбираем Use this template.


![Переходим в репозиторий](image/10.png){#fig:010 width=95%}


11. Задаём имя репозиторию и создаём репозиторий.


![Задаём имя репозиторию и создаём репозиторий](image/11.png){#fig:011 width=95%}


12. Открываем терминал и переходим в каталог курса.


![Открываем терминал и переходим в каталог курса](image/12.png){#fig:012 width=95%}


13. Далее копируем ссылку для клонирования созданного репозитория.


![Копируем ссылку для клонирования созданного репозитория](image/13.png){#fig:013 width=95%}


14. Клонируем созданный репозиторий.


![Клонируем созданный репозиторий](image/14.png){#fig:014 width=95%}


15. Переходим в каталог курса.


![Переход в каталог курса](image/15.png){#fig:015 width=95%}


16. Удаляем лишние файлы.


![Удаляем лишние файлы](image/16.png){#fig:016 width=95%}


17. Создаём необходимые каталоги.


![Создаём необходимые каталоги](image/17.png){#fig:017 width=95%}


18. Отправляем файлы на сервер.


![Отправляем файлы на сервер](image/18.png){#fig:018 width=95%}


19. Отправка файлов.


![Отправка файлов](image/19.png){#fig:019 width=95%}


20. Проверяем правильность создания иерархии рабочего пространства в локальном репозитории и на странице github.


![Проверяем правильность создания иерархии рабочего пространства в локальном репозитории](image/20.png){#fig:020 width=95%}


21.Проверяем правильность создания иерархии рабочего пространства на странице github.


![Проверяем правильность создания иерархии рабочего пространства на странице github.](image/21.png){#fig:021 width=95%}


# Самостоятельная работа. 

Копируем отчёты по выполнению предыдущих лабораторных работ в соответствующие каталоги созданного рабочего пространства и загружаем файлы на https://github.com/GalievaAdelina/study_2022-2023_arh-pc


# Выводы

Я изучила идеологию и применение средств контроля версий.Приобрела практические навыки по работе с системой git.



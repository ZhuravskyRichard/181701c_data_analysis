# Instructions for self-study activities

**УСРС 1. Работа с репозиторием на GitHub** 

* Установить на ПК R (Раздел 2.5-2.6 <sup>[1]</sup>).

* Установить RStudio (Приложение Б.2 <sup>[1]</sup>).

* Установить Git (https://support.rstudio.com/hc/en-us/articles/200532077?version=1.0.136&amp;mode=desktop).

* Зарегистрироваться на GitHub.com.

* Клонировать репозиторий **poit** с [https://github.com/volhahedranovich/poit](https://github.com/volhahedranovich/poit):

> 1. В **RStudio** выполнить команду **Tools — Shell...**

> 2. Перейти в папку для клонирования (команды `cd..`, `cd~`,`cd folder path/name`). Папка должна быть названа вашей фамилией.

> 3. Выполнить команду `git clone git@github.com:...` (ссылку для клонирования скопировать на GitHub).

* Открыть проект **poit.Rproj** в **RStudio**. Открыть документ **start.R**, выполнить его код (выделить код, нажать Ctrl + Enter). Сохранить изменения.

* Открыть скрытый файл **.gitignore** из корневой папки проекта. Добавить в конец файла путь к файлу **wdPath.txt**, который находится в папке **Data** (Теперь этот файл будет игнорироваться при загрузке локальных изменений в удаленный репозиторий).

* Создать путой репозиторий на GitHub (для связи с клонированным проектом).

* Связать проект и репозиторий:

> 1. В **RStudio** выполнить команду **Tools — Shell…**

> 2. Перейти в папку с проектом.

> 3. Выполнить команду `git remote -v` (чтобы просмотреть связь с удаленным репозиторием).

> 4. Выполнить команду `git remote set-url origin https://github.com/user/repoName.git` (вместо user/repoName использовать своё имя пользователя на GitHub и название пустого репозитория).

> 5. Проверить, что связь с вашим репозиторием установлена.

* Загрузить локальные изменения в удаленный репозиторий:

> 1. Определить файлы для **Commit** (отметить измененные файлы либо с помощью интерфейса **Rstudio** на панели инструментов **Git**, либо в **Shell** выполнить комманду `git add *`).

> 2. Выполнить **Commit** (окнопка Commit в Rstudio на панели инструментов Git, написать **Commit message**, нажать кнопку Commit).

> 3. После успешного выполнения Commit выполнить команду **Push**.

> 4. Убедиться, что локальные изменения загружены в удаленный репозиторий.

* Отправить ссылку на ваш репозиторий преподавателю по e-mail. В письме обязательно указать номер учебной своей группы, свои Фамилию и Имя.

*Литература:*

<sup>[1]</sup> Шипунов, А. Б. Наглядная статистика. Используем R! [Электронный ресурс] / А. Б. Шипунов, Е. М. Балдин, П. А. Волкова, А. И. Коробейников, С. А. Назарова, С. В. Петров, В. Г. Суфиянов. – 2014. – Режим доступа: https://cran.r-project.org/doc/contrib/Shipunov-rbook.pdf. – Дата доступа: 01.09.2016.


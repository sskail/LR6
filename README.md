# ОТЧЁТ О ЛАБОРАТОРНОЙ РАБОТЕ №6 
# ПО ОСНОВАМ ПРОГРАММИРОВАНИЯ
# Выполнил студент группы 4916 Бирюков Никита



### Ход работы:
На сайте GitHub сделал копию https://github.com/Kurtyanik/LR6/

![Копированный репозиторий](screenshots/Screenshot_0.png)

Создал на срабочем столе папку lab6, зашел в нее и, щелкнув правой кнопкой мыши, выбрал git bash here

![git bash here](screenshots/Screenshot_01.png)

Настроил клиен git

![Git settings](screenshots/Screenshot_001.png)

Командой _git clone клонировал удаленный репозиторий на компьютер 

![Git clone](screenshots/Screenshot_1.png)

Затем через графический интерфейс GitHub добавил новый файл _new.txt_ в удалённый репозиторий в ветку __master__

![Новый файл](screenshots/Screenshot_2.png)

Пользуясь командой _git pull _ загрузил изменения из удалённого репозитория в локальный

![Git pull](screenshots/Screenshot_3.png)

Командой _git log_ получил список операций/коммитов в ветках master и branch1 

![git log master](screenshots/Screenshot_4.png)

![git log branch1](screenshots/Screenshot_5.png)

Используя _git log -p_ получил более подробную информацию по последнем изменениям в ветках

![git show](screenshots/Screenshot_6.png)

![git show](screenshots/Screenshot_7.png)

Попытался выполнить слияние веток **master** и **branch1** командой _git merge branch1_ и получил ошибку

![Merge error](screenshots/Screenshot_8.png)

Вручную изменил файл mergefile.txt, вызвавший ошибку слияния и выполнил коммит

![Fix](screenshots/Screenshot_9.png)

![Fix](screenshots/Screenshot_10.png)

После я удалил ветку **branch1** командой _git branch -d_

![Branch delete](screenshots/Screenshot_12.png)

Запушил всё в удалённый репозиторий командой _git push_

![Push1](screenshots/Screenshot_14.png)

Затем сделал несколько изменений, сначала добавил файл, затем изменил его, а после добавил новый файл.

![New file](screenshots/Screenshot_15.png)

![Add new file](screenshots/Screenshot_17.png)

![Commit](screenshots/Screenshot_18.png)

![Change file](screenshots/Screenshot_16.png)

![Add and commit changes](screenshots/Screenshot_19.png)

![New file2](screenshots/Screenshot_20.png)

![Add and commit file2](screenshots/Screenshot_21.png)

Коммандой _git log -3_ вывел последние 3 лога.

![Log](screenshots/Screenshot_22.png)

Командой _git reset --hard HEAD~1_ выполнил откат последнего коммита - добавления файла **Новый текстовый документ.txt**

![Hard reset](screenshots/Screenshot_27.png)

Коммандой _git log -3_ вывел последние 3 лога.

![Log](screenshots/Screenshot_23.png)

Запушил изменённую ветку

![Push2](screenshots/Screenshot_24.png)


Пользуясь командой _git checkout -b otchet_ создал новую ветку **otchet**

![New branch](screenshots/Screenshot_25.png)


Текущая история _git log --graph_ . Аргумент --graph позволяет графически изобразить ветки и коммиты на них

![Git log2](screenshots/Screenshot_26.png)

С помощью команды _git add ._ подготовил все скриншоты в папке **screenshots** к пушу

![Git add .](screenshots/Screenshot_29.png)

Запушил файлы скриншотов в удалённый репозиторий

![Git add .](screenshots/Screenshot_30.png)

Оформляю отчёт в файле **README.md** используя Notepad++

![Readme](screenshots/Screenshot_28.png)

Лог команд из папки **.git/logs**

![Logs](screenshots/Screenshot_31.png)

Получил историю операций в форматированном виде

![Git log3](screenshots/Screenshot_32.png)

Все файлы скриншотов лежат в папке **screenshots**
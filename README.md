# practice_temp

## Соответствие групп и тем на практикум.

1. Что такое система контроля версий
2. Для чего нужна система контроля версий
3. Установка git на ваш ПК (в зависимости от системы)
4. Установка VSCode на ваш ПК
5. Что такое репозиторий и инструкция по созданию локальных репозиториев.
6. Базовая работа с локальным репозиторием
7. Что такое ветки и для чего они нужны при работе с системой контроля версий.
8. Базовая работа с ветками в git.

### Git на практике (Некоторые комманды)

##### Завести *новый репозиторий* очень просто, это делается командой

    git init
----------

#####  Если вы хотите присоединиться к разработке *уже имеющегося проекта*, то вам нужно будет скопировать этот репозиторий в свою локальную папку с удаленного репозитория. Делается это так:

    git clone <url удаленного репозитория>
-----------

##### В целом работа с гитом выглядит так: вы меняете файлы в своей рабочей директории, затем добавляете эти изменения в staging area используя команду

    git add <имя/файла>
------------

##### При этом можно использовать маски со звездочкой.
Потом вы делаете коммит в свой локальный репозиторий

    git commit –m “Комментарий к коммиту”
-----------

##### Когда коммитов накопиться достаточно много, чтобы ими можно было поделиться, вы выполняете команду

    git push
---------

##### Если нужно получить изменения из удаленного репозитория, то нужно выполнить команду

    git pull
-----------

##### Просмотреть коммиты можно при помощи команды

    git log
--------

##### Посмотреть, что находиться в рабочей директории и staging area можно командой

    git status
---------

##### Рабочую директорию можно переключить на предыдущее состояние выполнив команду

    git checkout <hash коммита>
----------



9. Что такое удаленный репозиторий и для чего он нужен
10. Базовая работа с удаленными репозиториями GitHub
11. Как строится и для чего нужна совместная работа в системах контроля версий
12. Инструкция по созданию pull request
13. Книги и полезные ссылки по изучению git.
14. Альтернативные системы контроля версий.

# Краткая инструкция по GIT

## Создание репозитория
* Создать прямо из командной строки
```
echo "# 123" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:artsharoglazov/123.git
git push -u origin main
```
* Создать в интерфейсе и затем связать с локальным репозиторием

_Создать в интерфейсе репозиторий (желательно с названием таким же как у локального)_
```
git remote add origin git@github.com:artsharoglazov/123.git
git branch -M main
git push -u origin main
```
* Создать в интерфейсе и затем клонировать на локальную машину

_Создать в интерфейсе репозиторий_
`git clone https://github.com/artsharoglazov/name.git`

## How-To
* Как изменить имя ветки с main на master в локальном и удаленном репозитроии
```
git branch -m master
git branch --unset-upstream
git push --set-upstream origin master
```

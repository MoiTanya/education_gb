
![Надеюсь она отобразится](document.png)
# **Инструкция для работы с Git и удаленными репорзиториями.**

## **Что такое Git?**
Git - это одна из реализаций распределенных систем контроля версий, имеющая как и локадьные, так и удаленные репозитории. Является самой популярной реализацией систем контроля версий в мире.

## **Подготовка репозитория**

Для создания репозитория в папке репозитория необходимо выполнить команду инициализации репозитория:
**git init** . В папке появится скрытая папка .git.

## **Создание коммитов** 
Есть несколько вариантов добавления коммитов:

* **git commit** - фиксирование изменений

* **git commit -m "message"** - фиксирование изменений в терминале напрямую 

* **git commit - am "message"** - фиксирование изменений в терминале напрямую (без использование команды git add)

## **Создание веток**

**git branch** - вывод  списка всех веток в файле

**git branch name_branch** - создание новой ветки
## __Переход из одной ветки в другую.__

**git checkout master** - переход на ветку мастер

**git checkout branch_name** - переход на созданную ветку


## **Слияние веток**

Для слияния веток необходимо выйти в ветку master при помощи команды **_git checkout main/master_** или в ветку с которой планируется слияние при помощи команды **_git checkout name_brunch_**

**git merge name_branch** - слияние веток

## **Удаление веток**

Ветки для которых было произведено слияние можно удалить, либо за ненадобностью.

**git branch -d name_branch** - удаление ветки



### ***Другие полезные команды:***

1. **git log** - посмотреть историю комитов
    
2. **git checkout hash_number** - переместится на комит

3. **git checkout main/master** - вернутся в обычное состояние 

4. **git diff** - сравнение изменений между файлом и сохраненным комитом


## **Использоване [ссылок](https://learn.microsoft.com/ru-ru/contribute/how-to-write-links) в доукументации.**

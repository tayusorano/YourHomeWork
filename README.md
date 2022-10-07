# Инструкция по работе с Git

## Первая часть.

### 1 семинар

* *git init* - команда, иницилизирующая репозиторий в заданной директории.

* *git version* - команда, отображающая текущую установленную версиию Git.

* *git status* - команда, отображающая состояние репозитория.

* _git add_ - команда, добавляющая директории/файлы к отслеживанию.

* _git commit_ - команда, фиксирующая изменения с комментарием.

* _git log_ - команда, отображающая предыдущие коммиты.

* _git checkout_ - команда, отображающая определенный коммит.

> _git checkout master_ - команда, возвращающая к последнему коммиту.

---


## Вторая часть.

### 2 семинар

### Создание веток

* _git branch_ - команда показывающая ветки.

* _git branch_ <branch name>* - команда создания ветки с именем.

* _git checkout_ <branch name>* - команда, перенаправляющая на ветку <branch name>.

### Слияние веток

* *git merge <branch_name>* - команда, осуществляющая слияние текущей ветки с указанной.(branch name)

__NB__ Перед слиянием веток необходимо убедиться в том, что базовая и принемаямая втка указаны верно!

### Конфликты

_Могут возникать если строки в разных ветках друг другу протеворечат и их не получается слить вместе._

---

## Третья часть

### 3 Семинар

### 

* _git clone <url_github>_ - команда копирования репозитория из GitHub.

* _git remote add origin <url_github>_ - команда связи локального репозитория с удаленным репозиторием.

* _git branch -M main_ - команда выбора основной ветки.

* _git push -u origin main_ - команда отправки (проталкивания) локального репозитория к удаленному.

* _git pull_ - команда вытягивания из удаленного репозитория в локальный.

> __NB__ - Не забудь создать отдельную ветку для работы с чужими репозиториями. 
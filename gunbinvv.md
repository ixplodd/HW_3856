# Руководство по Git
##  1. Команды Git
1. _git init_ - инициализирует репозиторий. Указывает папку, в которой **Git** начнет отслеживать изменения.
2. _git status_ - показывает состояние репозитория.
3. _git add_ - добовляет содержимое рабочего каталога в индекс для последующего коммита. 
4. _git commit_ - берет все данные, добавленные в индекс с помощью команды **git add**, и сохраняет их во внутренней базе данных.

* _Если ранее был добавлен файл командой gid add, то далее чтобы постоянно его не вводить можно воспользоваться командой gid commit -am "имя сохранения"_

5. _git log_ - журнал изменений, позволяет увидеть количество сохранений.
 * _git log --graph - показывает журнал изменений с ветвлением._ 
6. _git cheсkout_ - позволяет переключаться между версиями. 
7. _git diff_ — показывает разницу между версиями
## 2. Ветки
### Команды, для работы с ветками
* _git branch_ - выводит список веток.
* _git branch <имя ветки>_ - создает новую ветку.
* _git checkout <имя ветки>_ - переключает пользователя на другую ветку. 
* _git checkout <ключ> <имя ветки>_ - создает новую ветку и сразу переключается на нее. 
* _git merge_ - cливает изменения с переданной ветки в текущую.
## 3. Работа с удаленными репозиториями
### Команды, для работы с удаленными репозиториями
* _git clone_ - загружает все изменения и позволяет слить все ветки на локальном компьютере и в удаленном репозитории.
* _git pull_ - позволяет скачать все из текущего репозитория и автоматически сделать слияние с нашей версией.
* _git push_ - позволяет отправить нашу версию репозитория на внешний репозиторий. Требует авторизации на внешнем репозитории.
* _pull request_ - команда для предложения изменений, запрос на вливание изменений в репозиторий.
### Как сделать pull request
* Делаем (ответвление) fork репозитория
* Делаем git clone СВОЕЙ версии репозитория
* Создаем новую ветку и в НЕЕ вносим свои изменения
* Фиксируем изменения (делаем коммиты)
* Отправляем свою версию в свой GitHub
* На сайте GitHub нажимаем кнопку pull request 
# Команды Git

   - git init -  Создание репозитория git в выбранной папке
   
   - git add имя файла - добавление файла в репозиторий для отслеживание в git и добавление изменений и присваивании им хэш-кода


- git checkout имя файла - переход в искомое состоние/файл/момент истории/ветьвь

- git commit -m 'message' -  создание сообщения для внесенного изменения и фиксация изменений



# Лекция 2

git checkout -b имя ветви -создать ветку и сразу перейти на нее.

git merge имя файла - слияние веток. ВВодить команду из ветки в которую надо слить ветку.

Дополнительные команды из лекции

git log --oneline Просмотр истории коммитов в одну линию

git branch - проверка наличия веток
git branch имя ветви - создать ветку из текущего места

.gitignore - файл создается для скрытия/игнорирования файлов для git

git status -   проверка статуса

 git reset хэш - сброс до указанного хэша в истории


# Лекция 3

git clone адрес - клонировать удаленный репозиторий в локальный

git pull - закачать последние изменения с репозитория в github

git push - отправить последние изменения с репозитория в github


`git config --global user.name "my name"`

`git config --global user.email my@email`

Проверить настройки `git config --list`

Создание нового репозитория `git init`

Подготовить `git add .`

Сохранить в новом коммите `git commit -m "message"`

Перейти к определенной версии коммита `git checkout <commit hash>`

Перейти к определенной версии ветки `git checkout <branch name>`

Просмотр истории соммитов `git log`

Просмотр объектов в папке .git
`git cat-file -t 224d050`
`git cat-file -p 224d050`

Переход в основную ветку `git checkout master`

Создание новой ветки `git branch <branch name>`

Переименовывание существующей ветки `git branch -m <new branch name>`

Создание новой ветки и переход в нее `git checkout -b <branch name>`

Удаление ветки (текущую ветку удалить нельзя) `git checkout -d <branch name>`

Список всех веток `git branch`


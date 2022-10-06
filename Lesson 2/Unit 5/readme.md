## Six lesson (remote repository)

### Команды для работы с удалённым репозиторием:

    git remote -v - просмотр списка существующих удалённых репозиториев

    git remote add [repository name] [adress repository] - добавить новый удалённый
    репозиторий, который находиться по указанному адресу. При этом, на нашем компьютере
    к удалённому репозиторию мы будем обращаться по его названию

    git remote remove [repository name] - удалить репозиторий с указанным  названием

    git push [repository name] [branch] - example: git push origin master -
    Команда отправляет созданные коммиты на удалённый репозиторий.

    git pull - команда для получения обновлений с удалённого репозитория.
    git pull [repository name] [branch] - example: git pull origin master

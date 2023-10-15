# My_repository
## git pull vs git fetch 
Обе команды используются для обновления локального репозитория (чтобы скачать последние коммиты).
___
**git fetch** скачивает обновления из удаленного репозитория (remote), но не сливает их с текущей веткой. Другими словами вы скачаете новые коммиты, но не добавите их в историю изменений локального репозитория. Для завершения процесса обновления нужно будет сделать еще git merge. Эта операция безопасна для выполнения в любое время т.к. она не вносит изменения в локальную ветку.
___
**git pull** это команда-псевдоним сразу двух git команд - git fetch и git merge. Т.е. когда вы обновляете локальный репозиторий с помощью git pull, то все изменения не просто будут скачены, а еще и внедрятся (объединятся) в ваш локальный репозиторий. Другими словами эта команда обновит ваш локальный репозиторий до состояния на сервере.

githooks
========

Набор хуков для питонячих git репозитариев.

После merge, update, checkout чистит pyc файлы, если находит в репозитарии update_requirements.py - запускает.

После commit запускает pep8 проверку на файлы, измененные в ветке по сравнению с master.

Установка:
=========
git clone git@github.com:ekirill/githooks.git ~/githooks
cd ~/githooks
create_symlinks <git repository path>

#Git команды<br>
* **git init** - _делает текущую папку репозиторием git_<br>
_ **rm -rf .git** - _разгитить репозиторий, где -r рекурсивное удаление и -f принудительно_ <br>

* **git status** - _инфо о статусе файлов в репозитории_ <br>

* **git add** - _+ имя файла = подготовка файла к коммиту_ <br>

* **git add --all** - _подготовка всех файлов репозитория к коммиту_ <br>

* **git commit** - _закоммитить_ <br>

* **git log** - _просмотр истории коммитов_ <br>

* **git clone** - _+ x ссылка репозитория = копирует репозитория с GitHub на локальный ПК_ <br>

* **git push** - _отправить кормит в удаленный репозиторий_ <br>

* **git remote -v** - _убедиться в связке с удаленным репозиторием_ <br>

* **git remote add origin** - _+ git@github.com + ссылка с GitHub_ <br>

```mermaid
graph LR;
  untracked -- "git add" --> staged;
  staged    -- "Changes to be committed в выводе git status"     --> tracked/comitted;

%% стрелка без текста для примера: 
  A --> B;
``` 
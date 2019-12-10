# Домашнее задание # 1

## Регистрация аккаунт onyschukoleh на [GitHub](https://github.com/)

## Создание репозитория goit-markup-hw-01/README.md.

    ```shell
    cd c/Homework
    $ git clone https://github.com/onyschukoleh/goit-markup-hw-01.g
    $ cd homework01/
    $ git remote -v
        origin  https://github.com/onyschukoleh/goit-markup-hw-01.git (
        origin  https://github.com/onyschukoleh/goit-markup-hw-01.git (
    $ touch history.md
    $ git log
    $ pwd; ls -l
        /c/Homework/homework01
        total 5
        -rw-r--r-- 1 Олег 197121 2626 Dec 10 23:15 history.md
        -rw-r--r-- 1 Олег 197121   19 Dec 10 23:03 README.md
    $ git status
        On branch master
        Your branch is up to date with 'origin/master'.
        Untracked files:
        (use "git add <file>..." to include in what will be committed)
                history.md
        nothing added to commit but untracked files present (use "git add" to track)

    $ git add .; git commit -m "Add README.md and history.md"
        [master a5f5201] Add README.md and history.md
        1 file changed, 47 insertions(+)
        create mode 100644 history.md
        Олег@WIN-48QEKK3Q9JT MINGW64 /c/Homework/homework01 (master)
    $ git log
    $ code .

\$ git status
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
(use "git push" to publish your local commits)

Changes not staged for commit:
(use "git add <file>..." to update what will be committed)
(use "git restore <file>..." to discard changes in working directory)
modified: README.md
modified: history.md

no changes added to commit (use "git add" and/or "git commit -a")

\$ git commit -m "Add information to README.md and hystore.md"
[master d54201c] Add information to README.md and hystore.md
2 files changed, 53 insertions(+), 7 deletions(-)
rewrite README.md (100%)

\$ git log
commit d54201c26dfff13335f0c9d7b8a2ed761b86a3cb (HEAD -> master)
Author: onyschukoleh <onyschukoleh@gmail.com>
Date: Tue Dec 10 23:56:06 2019 +0200

    Add information to README.md and hystore.md

commit a5f5201450caf2085e8b3fa4c5114818bd5dfeb7
Author: onyschukoleh <onyschukoleh@gmail.com>
Date: Tue Dec 10 23:20:41 2019 +0200

    Add README.md and history.md

commit ee361cb73d12b08afe50b3f84d870000808cec9f (origin/master, origin/HEAD)
Author: onyschukoleh <58668434+onyschukoleh@users.noreply.github.com>
Date: Tue Dec 10 23:01:51 2019 +0200

    Initial commit

\$ git status
On branch master
Your branch is ahead of 'origin/master' by 2 commits.
(use "git push" to publish your local commits)

Changes not staged for commit:
(use "git add <file>..." to update what will be committed)
(use "git restore <file>..." to discard changes in working directory)
modified: README.md
modified: history.md

no changes added to commit (use "git add" and/or "git commit -a")

Проверь статус файлов проекта, посмотри какие файлы уже под контролем, а какие будут добавлены.
Добавь изменения под контроль git и сделай коммит с комментарием Добавлено изображение животного.
Выведи лог истории коммитов и просмотри его.
Сделай пуш в репозиторий на GitHub.
Настрой раздачу статических файлов в репозитории на GitHub и проверь работоспособность живой страницы.
Добавь ссылку на живую страницу в шапку описания репозитория.

```

```

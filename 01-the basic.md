PCMANPASI@DESKTOP-JEG6I1B MINGW64 ~ (master)
$ cd ..

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/Users
$ cd ..

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c
$ mkdir git basic
mkdir: cannot create directory ‘git’: File exists
mkdir: cannot create directory ‘basic’: File exists

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c
$ mkdir git-basic
mkdir: cannot create directory ‘git-basic’: File exists

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c
$ mkdir git_basic

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c
$ cd git_basic

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/git_basic
$ touch first.txt

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/git_basic
$ git init
Initialized empty Git repository in C:/git_basic/.git/

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/git_basic (master)
$ git add .

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/git_basic (master)
$ git commit -m"adding first.txt"
[master (root-commit) 471dbb3] adding first.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 first.txt

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/git_basic (master)
$ git log
commit 471dbb355c00e9e4fb8df63a9c7987821fb788df (HEAD -> master)
Author: mtiarptri <107293885+mtiarptri@users.noreply.github.com>
Date:   Thu Jul 14 09:25:59 2022 -0500

    adding first.txt

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/git_basic (master)
$ touch second.txt

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/git_basic (master)
$ git add .

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/git_basic (master)
$ git commit -m "adding second.txt"
[master 06b3ccf] adding second.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 second.txt

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/git_basic (master)
$ rm first.txt

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/git_basic (master)
$ git add .

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/git_basic (master)
$ git commit -m"reoving firts.txt"
[master b4c7d8b] reoving firts.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 delete mode 100644 first.txt

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/git_basic (master)
$ git log
commit b4c7d8b250d245565a164b178bedf20a9f10b887 (HEAD -> master)
Author: mtiarptri <107293885+mtiarptri@users.noreply.github.com>
Date:   Thu Jul 14 09:27:40 2022 -0500

    reoving firts.txt

commit 06b3ccf66ce68b43a1c6eaff7783156119f9aa8a
Author: mtiarptri <107293885+mtiarptri@users.noreply.github.com>
Date:   Thu Jul 14 09:26:45 2022 -0500

    adding second.txt

commit 471dbb355c00e9e4fb8df63a9c7987821fb788df
Author: mtiarptri <107293885+mtiarptri@users.noreply.github.com>
Date:   Thu Jul 14 09:25:59 2022 -0500

    adding first.txt

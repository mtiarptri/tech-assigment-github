PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/Users
$ cd ..

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c
$ mkdir mutiara

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c
$ cd mutiara

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/mutiara
$ cat > README.md
Halo perkenlan aku halaman utama


PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/mutiara
$ git init
Initialized empty Git repository in C:/mutiara/.git/

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/mutiara (master)
$ git add .
warning: LF will be replaced by CRLF in README.md.
The file will have its original line endings in your working directory

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/mutiara (master)
$ git commit -m "first commit"
[master (root-commit) 8089000] first commit
 1 file changed, 2 insertions(+)
 create mode 100644 README.md

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/mutiara (master)
$ cat > README.md
Hello world
PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/mutiara (master)
$ cat > README.md
Hallo perkenalkan aku halaman utama

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/mutiara (master)
$ git add .
warning: LF will be replaced by CRLF in README.md.
The file will have its original line endings in your working directory

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/mutiara (master)
$ git commit -m "kembali semula"
[master a41c14c] kembali semula
 1 file changed, 1 insertion(+), 2 deletions(-)

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/mutiara (master)
$ git branch cv

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/mutiara (master)
$ git checkout cv
Switched to branch 'cv'

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/mutiara (cv)
$ cat > cv.txt
Ini adalah file cv

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/mutiara (cv)
$ git add .
warning: LF will be replaced by CRLF in cv.txt.
The file will have its original line endings in your working directory

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/mutiara (cv)
$ git commit -m "Inisial cv"
[cv 73f6a55] Inisial cv
 1 file changed, 1 insertion(+)
 create mode 100644 cv.txt

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/mutiara (cv)
$ cat > cv.txt
Inisial cv
perusahaan indomaret

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/mutiara (cv)
$ git add .
warning: LF will be replaced by CRLF in cv.txt.
The file will have its original line endings in your working directory

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/mutiara (cv)
$ git commit -m "perusahaan pertama"
[cv 60e42c6] perusahaan pertama
 1 file changed, 2 insertions(+), 1 deletion(-)

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/mutiara (cv)
$ cat > cv.txt
initial cv
perusahaan indomaret
perusahaan babel gruop

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/mutiara (cv)
$ git commit -m "perusahaan kedua"
On branch cv
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   cv.txt

no changes added to commit (use "git add" and/or "git commit -a")

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/mutiara (cv)
$ git add .
warning: LF will be replaced by CRLF in cv.txt.
The file will have its original line endings in your working directory

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/mutiara (cv)
$ git commit -m "perusahaan kedua"
[cv 5a74b1d] perusahaan kedua
 1 file changed, 2 insertions(+), 1 deletion(-)

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/mutiara (cv)
$ cat > cv.txt
initial cv
perusahaan indomaret
perusahaan babel gruop
perusahaan JBC

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/mutiara (cv)
$ git add .
warning: LF will be replaced by CRLF in cv.txt.
The file will have its original line endings in your working directory

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/mutiara (cv)
$ git commit -m "perusahaan ketiga"
[cv 25194b0] perusahaan ketiga
 1 file changed, 1 insertion(+)

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/mutiara (cv)
$ git checkout master
Switched to branch 'master'

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/mutiara (master)
$ cat > README.md
Hallo perkenalkan aku halaman utama

Ini adalah update pertma pada branch masterg
PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/mutiara (master)
$ git add .
warning: LF will be replaced by CRLF in README.md.
The file will have its original line endings in your working directory

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/mutiara (master)
$ git commit -m "update master pertama"
[master ae3ea31] update master pertama
 1 file changed, 2 insertions(+)

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/mutiara (master)
$ git marge cv
git: 'marge' is not a git command. See 'git --help'.

The most similar command is
        merge

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/mutiara (master)
$ git merge cv
Merge made by the 'ort' strategy.
 cv.txt | 4 ++++
 1 file changed, 4 insertions(+)
 create mode 100644 cv.txt

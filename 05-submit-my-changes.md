https://drive.google.com/file/d/1XByhiOBXcW9FgyoJLT08SwsUKF3BGmBx/view?usp=sharing

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/python310
$ cd ..

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c
$ cd python310

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/python310
$ cd tech4impact-students-bio

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/python310/tech4impact-students-bio (master)
$ git branch Mutiara putri
fatal: not a valid object name: 'putri'

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/python310/tech4impact-students-bio (master)
$ git branch Mutiaraputri

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/python310/tech4impact-students-bio (master)
$ git checkout Mutiaraputri
Switched to branch 'Mutiaraputri'

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/python310/tech4impact-students-bio (Mutiaraputri)
$ cat > Mutiaraputri.md
Nama lengkap : Mutiara putri
Umur : 16
Pesan yang ingin disampaikan : Semoga hari hari mu menyenangkan

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/python310/tech4impact-students-bio (Mutiaraputri)
$ git add .
warning: LF will be replaced by CRLF in Mutiaraputri.md.
The file will have its original line endings in your working directory

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/python310/tech4impact-students-bio (Mutiaraputri)
$ git commit -m "adding Mutiaraputri.md"
[Mutiaraputri e292ebb] adding Mutiaraputri.md
 1 file changed, 3 insertions(+)
 create mode 100644 Mutiaraputri.md

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/python310/tech4impact-students-bio (Mutiaraputri)
$ git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/python310/tech4impact-students-bio (master)
$ git merge Mutiaraputri
Updating 165aa3b..e292ebb
Fast-forward
 Mutiaraputri.md | 3 +++
 1 file changed, 3 insertions(+)
 create mode 100644 Mutiaraputri.md

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/python310/tech4impact-students-bio (master)
$ git log
commit e292ebb85bc4dfc3ba6ba67ad5056bdce28250f6 (HEAD -> master, origin/master, origin/HEAD, Mutiaraputri)
Author: mtiarptri <107293885+mtiarptri@users.noreply.github.com>
Date:   Thu Jul 14 09:04:09 2022 -0500

    adding Mutiaraputri.md

commit 165aa3bcc5183bf38fb8f4d02e415abf2755e7dd (upstream/master)
Author: David Winalda <davidwinalda94@gmail.com>
Date:   Sun Sep 19 10:10:44 2021 +0700

    add davidwinalda.md file

PCMANPASI@DESKTOP-JEG6I1B MINGW64 /c/python310/tech4impact-students-bio (master)
$


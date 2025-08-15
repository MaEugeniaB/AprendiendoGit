Git Fundamentos
%date%

Comandos utilizados


Eugenia@DESKTOP-A289U58 MINGW64 ~/Desktop (main)
$ ^[[200~mkdir AprendiendoGit
git init
bash: $'\E[200~mkdir': command not found

Eugenia@DESKTOP-A289U58 MINGW64 ~/Desktop (main)
$ mkdir AprendiendoGit

Eugenia@DESKTOP-A289U58 MINGW64 ~/Desktop (main)
$ cd AprendiendoGit

Eugenia@DESKTOP-A289U58 MINGW64 ~/Desktop/AprendiendoGit (main)
$ git init
Initialized empty Git repository in C:/Users/Eugenia/Desktop/AprendiendoGit/.git/

Eugenia@DESKTOP-A289U58 MINGW64 ~/Desktop/AprendiendoGit (master)
$ dir

Eugenia@DESKTOP-A289U58 MINGW64 ~/Desktop/AprendiendoGit (master)
$ echo Git Fundamentos > Readme.md

Eugenia@DESKTOP-A289U58 MINGW64 ~/Desktop/AprendiendoGit (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Readme.md

nothing added to commit but untracked files present (use "git add" to track)

Eugenia@DESKTOP-A289U58 MINGW64 ~/Desktop/AprendiendoGit (master)
$ git add Readme.md
warning: in the working copy of 'Readme.md', LF will be replaced by CRLF the next time Git touches it

Eugenia@DESKTOP-A289U58 MINGW64 ~/Desktop/AprendiendoGit (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   Readme.md


Eugenia@DESKTOP-A289U58 MINGW64 ~/Desktop/AprendiendoGit (master)
$ code .
To read from stdin, append '-' (e.g. 'echo Hello World | code -')

Eugenia@DESKTOP-A289U58 MINGW64 ~/Desktop/AprendiendoGit (master)
$ echo %date% >> Readme.md

Eugenia@DESKTOP-A289U58 MINGW64 ~/Desktop/AprendiendoGit (master)
$ git add Readme.md
warning: in the working copy of 'Readme.md', LF will be replaced by CRLF the next time Git touches it

Eugenia@DESKTOP-A289U58 MINGW64 ~/Desktop/AprendiendoGit (master)
$ git commit -m "Fecha"
[master (root-commit) 6f58ed3] Fecha
 1 file changed, 2 insertions(+)
 create mode 100644 Readme.md

$ git status
On branch master
Untracked files:
   (use "git add <file>..." tu include in what will be committed)
        index.html

nothing added to commit but untracked files present (use "git add" to track)


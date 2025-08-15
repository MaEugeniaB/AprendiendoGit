# Repositorio de María Eugenia Bava
#
# Git Fundamentos
%date%

## Comandos utilizados
## Consignas:
## 2.
mkdir AprendiendoGit
cd AprendiendoGit
git init
dir

## 3.
echo Git Fundamentos > Readme.md

## 4.
git status

## 5.
git add Readme.md

## 6.
git status

## 7.
code .

## 8.
echo %date% >> Readme.md
git add Readme.md
git commit -m "Fecha"

## 9.
Se creó el archivo en el vsc

git status
On branch master
Untracked files:
   (use "git add <file>..." tu include in what will be committed)
        index.html

nothing added to commit but untracked files present (use "git add" to track)

git add index.html
git commit -m "archivo index"

## 10.
Creé un repositorio en GitHub y conecté mi repositorio local con el de GitHub
git remote add origin https://github.com/MaEugeniaB/AprendiendoGit.git

Subí los archivos a GitHub
git add .
git commit -m "Primera actividad"
git push -u origin master



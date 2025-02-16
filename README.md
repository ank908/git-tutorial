# git-tutorial

Commands for Git

git -v
git config --list
git config --global user.email "kumarankur908@gmail.com"
git config --list

cd Git
code .
ls -lart
git init

git status
git add index.html about.html
git commit -m "first commit"
git add -A
git diff
git diff HEAD
git diff --staged
git log
git rm -r --cached .DS_Store .idea
git commit -m "second commit"

git status --ignored
nano .gitignore
git status --ignored
git status
git add -A
git commit -m "added gitignore"

git branch --list
git branch login
git checkout login
git checkout main
git branch login2
git checkout login2
git checkout main
git branch -D login2
git checkout main
git merge login
git branch -d login
git checkout -b register

git remote add origin https://github.com/ank908/git-tutorial.git
git remote -v
git checkout main
git branch -M main
git pull origin main --rebase
git push -u origin main

fc -ln -20

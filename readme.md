Download & Install git windows
Git config –global user.name mrgaurav77
Git config --global user.email gkolhe@gmail.com
Git config –global user.name
Git config --global user.email
Code .
Git init
Git status

Git add index.html
Git status
Git commit -m “initial commit”
git status
touch about.html
touch contact.html
touch monuments.html
git status
git add -A
git status

#modify about.html

#modify contact.html
git status
git add -A
git status
git commit -m “added more html”
git status
clear

#modify contact.html

Git status
Git checkout contact.html
Git checkout -f
Git log
Git log -p -1 #q to quit

#modify index.html

Git diff
Git add -A
Git diff --staged
Git checkout -f
Git status

#modify index.html

Git status
git commit -a -m "skipped staging area and fixed <"
git log
clear
git status
touch waste.html
git add -A
git commit -a -m "Adding waste"
git rm - - cached waste.html # removes file from stacked area
git add -A
git rm waste.html #removes file completely
git commit -a -m "removing waste.html"
git status -s # shows short status

# on new Project

git init
git add .
git commit -m "Initial commit"
git remote add origin < url here >
git push origin master
git push -u origin master

# Git ignore

touch .gitignore # then add file names in .gitignore to ignore that file or folder

#but it ignores the the files all over the project so we can add / (eg : /logs.txt)to indicate the ignore only the files which is present in same directory

#adding .txt will ignor all files with .txt extention /.txt will ignor files wihch are in same directory

#foldername/ will ignor folder

# Branches

git branch feature1 # creates new branch
git branch # shows all branches
git checkout feature1 # switch branch
git checkout master # returns to master branch

#on master
git merge feature1 # merge feature1 to master
git checkout -b flaskintegration # create a branch and switch to it
git remote add origin https://github.com/mrgaurav77/git-study.git connect to reposotry
git remote # check connected repositorys
git remote -v # check connected repositorys links
git push origin master # push the branch master
git push -u origin master

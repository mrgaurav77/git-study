# on new Project
- git init
- git add .
- git commit -m "Initial commit"
- git commit -a -m "Initial commit" ______skip staging area direct commit
- git remote add origin < url here >
- git push origin master
- git push -u origin master

# Git ignore
- touch .gitignore # then add file names in .gitignore to ignore that file or folder
- #but it ignores the the files all over the project so we can add / (eg : /logs.txt)to indicate the ignore only the files which is present in same directory
- #adding .txt will ignor all files with .txt extention /.txt will ignor files wihch are in same directory
- #foldername/ will ignor folder

# Branches
- git branch feature1 # creates new branch
- git branch # shows all branches
- git checkout feature1 # switch branch
- git checkout master # returns to master branch

#on master
- git merge feature1 # merge feature1 to master
- git checkout -b flaskintegration # create a branch and switch to it
- git remote add origin https://github.com/mrgaurav77/git-study.git connect to reposotry
- git remote # check connected repositorys
- git remote -v # check connected repositorys links
- git push origin master # push the branch master
- git push -u origin master

# usefull commands
#### remove the traking of git repository
- rm -rf .git _______may to be run in git Bash
- git clone <repository url>
optional
- git clone <repository url> name_forProject
- pwd  _____to view Present working directory
- ls   ______to list te content of present directory
- q ___quit
- 
# extra
- Download & Install git windows
- Git config –global user.name mrgaurav77
- Git config --global user.email gkolhe@gmail.com
- Git config –global user.name
- Git config --global user.email
- Code .
- Git status
- Git add index.html
- touch about.html
- git add -A
- clear
- Git checkout contact.html
- Git checkout -f
- Git log
- Git log -p -1 #q to quit
- Git diff  __________compare staging area and working directory
- Git diff --staged  ____________ compare staging area and last commit
- git log
- git rm --cached waste.html # removes file from stacked area
- git rm waste.html #removes file completely
- git commit -a -m "removing waste.html"
- git status -s # shows short status

# SSD-Lab-Activity-2
SSD Lab 2 Activity Exercises

This is my first git project!

# SSD LAB-2 ACTIVITY 
## Create a Repository:
git clone https://github.com/rishabh26malik/SSD-Lab-Activity-2
git remote -v
------------------------
## Git Workflow:
cd SSD-Lab-Activity-2
git status
git add README.md
git status
git log
git pull origin master
git push origin master


---------------
## Add Another file:
touch hello.txt
git status
git diff
git status
git add README.md
git status
git add .
git commit -m "Add hello.txt and edit README.md"
git status
git log
git push origin master
git status
---------------
## Push Your Work to GitHub:
git push origin master
git status
---------------
## Create a Pull Request and Merge a new Branch:
git checkout -b NewBranch
git branch
touch test.txt
git status
git add .
git commit -m "branch commit testing"
git push -u origin NewBranch
git checkout master
git pull origin master
git branch --merged
git merge NewBranch
git push origin master


git branch -d NewBranch

  

# SSD-Lab-Activity-2
SSD Lab 2 Activity Exercises

This is my first git project!

# SSD LAB-2 ACTIVITY 
## Create a Repository:
git clone https://github.com/rishabh26malik/SSD-Lab-Activity-2<br />
git remote -v<br />

------------------------
## Git Workflow:
cd SSD-Lab-Activity-2<br />
git status<br />
git add README.md<br />
git status<br />
git log<br />
git pull origin master<br />
git push origin master<br />


---------------
## Add Another file:
touch hello.txt<br />
git status<br />
git diff<br />
git status<br />
git add README.md<br />
git status<br />
git add .<br />
git commit -m "Add hello.txt and edit README.md"<br />
git status<br />
git log<br />
git push origin master<br />
git status<br />

---------------
## Push Your Work to GitHub:
git push origin master<br />
git status<br />

---------------
## Create a Pull Request and Merge a new Branch:
git checkout -b NewBranch<br />
git branch<br />
touch test.txt<br />
git status<br />
git add .<br />
git commit -m "branch commit testing"<br />
git push -u origin NewBranch<br />
git checkout master<br />
git pull origin master<br />
git branch --merged<br />
git merge NewBranch<br />
git push origin master<br />
git branch -d NewBranch<br />

  

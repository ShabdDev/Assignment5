Assignment5

Tasks To Be Performed: 
1. Create a Git Flow workflow architecture on Git 
2. Create all the required branches 
3. Starting from the feature branch, push the branch to the master, 
following the architecture 
4. Push a urgent.txt on master using hotfix

  1  clear
    2  mkdir Assignment5
    3  cd ..
    4  ls
    5  clear
    6  mkdir Assignment5
    7  cd Assignment5
    8  touch master.txt
    9  git add master.txt
   10  git commit -m "master.text file is created"
   11  git init
   12  git add master.txt
   13  git commit -m "master.text file is created"
   14  git branch develop
   15  git branch feature
   16  git checkout feature
   17  touch f1.txt
   18  git add f1.txt
   19  git commit -m "f1.txt file is added"
   20  git checkout develop
   21  git merge feature
   22  git checkout -b release
   23  touch r1.txt
   24  git add r1.txt
   25  git commit -m "r1.txt file is added"
   26  git checkout master
   27  git merge release
   28  ls
   29  git checkout develop
   30  ls
   31  git merge release
   32  ls
   33  git checkout master
   34  git checkout -b hotfix
   35  touch urgent.txt
   36  git add urgent.txt
   37  git commit -m "urgent.txt file is added"
   38  git checkout master
   39  git merge hotfix
   40  git checkout develop
   41  git merge hotfix
   42  history

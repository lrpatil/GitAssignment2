# GitAssignment2
GitAssignment2

-------------------- Module-2: GIT Assignment - 2 -----------------------------------  
Do the following tasks:  
● Create a git working directory with feature1.txt and feature2.txt in the master branch  
● Create 3 branches develop, feature1 and feature2  
● In develop branch create develop.txt, do not stage or commit it  
● Stash this file, and checkout to feature1 branch  
● Create new.txt file in feature1 branch, stage and commit this file  
● Checkout to develop, unstash this file and commit  
Please submit all the git commands used to do the above steps  
------------------------ End of Module-2: GIT Assignment - 2 --------------------------  

----------------------- Module-2: GIT Assignment - 2 Commands -------------------------  
cd GitAssignment2  
git init  
vi feature1.txt  
vi feature2.txt  
git status  
git add feature1.txt  
git add feature2.txt  
git status  
git commit -m "initial commit"  
git branch develop  
git branch feature1  
git branch feature2  
git checkout develop  
vi develop.txt  
git stash  
git checkout feature1  
vi new.txt  
git add new.txt  
git commit -m "new file added"  
git status  
git ls-files  
git checkout develop  
git stash pop  
git add develop.txt  
git commit -m "develop file added"  
git log --oneline  
--------------------- End of Module-2: GIT Assignment - 2 Commands -----------------  

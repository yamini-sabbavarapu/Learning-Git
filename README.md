# Learning-Git
This repo is just for learning purpose.
<br>
Step1: Making Changes and commiting them.
<br>
Step2: Checking for the track of updated changes.
<br>
Step 3: Configuring git(making changes in github using git)
<br>
Step 4: Cloning repo and making changes through VS Code Editor and pushing them into github using following commands.<br>
-git clone <repo-name>(to clone)<br>
-git status (to check status) <br>
-git add <fileName>(to add new file or changes made in that file)<br>
-git add . ( to add all changes)
-git commit -m"message relating changes"(commits changes)<br>
-git push origin main(pushes changes from local to remote)<br>
Step 5: To push a local repo to github<br>
-git init(to create a new git  rep)<br>
-git remote add origin <-link-><br>
-git remote -v(to verify remote) <br>
-git push -u origin main <br>
 (origin is name of remote repository when 1st cloned,<br>
  -u sets upstream so that there is no need to mention repo and branch name 
   when pushing into same path,<br>
   main is name of branch you are pushing to).<br>
<h3>WorkFlow</h3><br>
Github repo-> Clone-> Changes-> Add-> Commit-> Push <br>
<h3>Branches</h3>
Branches are generlly used to develop separate features simultaneously.Branches can be merged. 
-git branch (gives names of all branches) <br>
-git branch -M <new branch name> <br>
-git checkout <-branchname-> (to navigate to another branch) <br>
-git checkout -b <newbranchName> (to create new branch) <br>
-git branch -d <branchname> (to delete branch) <br>
you cannot delete a branch while you are in it.<br>
Pull requests(tells about changes pushed to a branch in repo on github)<br>
Pull commands (to fetch and download content from remote repo to local repo)<br>
-git pull origin main

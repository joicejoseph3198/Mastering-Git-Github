# Mastering-Git-Github
a repo for mastering git basics


Repository - somewhere you'd like to keep all your files </br>
Commit - saving something to the repo </br>
Commit updates </br>
Allows you to view the changes been made </br>
Each commit has a unique hash identifier </br>
Create separate branch to work/try different thing on your file before merging into your main branch.

Fork to create another instance of the repo

So say youre working on a project. You fork the original project repo make changes to them create branches add new things etc etc. Then you make pull request to the original repo to consider those changes. Then the original repo owner considers them and merges them if they feel like it.


git remote add origin <url for a git repository> - Configures the destination of push/pull command

git add <filename> - Add files to the staging area
  
git commit -m "Message Added xyz.py or whatever"

git commit -a -m " commits all changed files from the staging area"

git status - to get a status of all the files that've been modified

git push <repository> <branch> 

<repository> </br>
 The "remote" repository that is destination of a push operation. This parameter can be either a URL (see the section GIT URLS below) or the name of a remote
  
<branch> </br>
if your Local branch and remote branch is the same name then you can just do it: </br>
git push origin branchName

When your local and remote branch name is different then you can just do it:</br>
git push origin localBranchName:remoteBranchName

git init - to change create a repository inside a directory

git pull <repository> <branch>   

git branch - lists all the branch in the repo and * indicates the current working branch

git checkout <branchname> - to switch between branches
  
git checkout -b branch-name - -b causes a new branch to be created

git diff <branchname> - shows what changes have been made or the differnce between the current branch and <branchname>

git reset HEAD~1 - to undo the last commit

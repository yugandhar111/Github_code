First User activities:  
====================== 
[github.com] Create a remote repository in github.com [User should have github account] 

$ mkdir Devops
$ cd Devops
$ echo "# second-repo" >> Devops
$ git init [Repo initialization]
$ git add <file name> [adding file into staging area]
$ git commit -m "first commit"   [Commit changes as a message]
$ git branch -M main 
$ git remote add origin https://github.com/githu512515/Devops.git [Linking local repo with remote repository]
$ git config --global credential.helper store [Store password]
$ git push -u origin main 

Git configuration 
===================
local [.git/config] : 
$ git config --local user.name 'yugandhar'

global [~/.gitconfig ] :
$ git config --global user.name 'abc' 
$ git config --global user.email 'abc@xyz.com' 

system [/etc/gitconfig] :
$ sudo git config --system commit.template /home/labsuser/commit-template.txt

Second user activities :
============
Cloning Repo and modfication of a file , then push to remote repo. 
============================ 
$ mkdir second_user 
$ cd second_user
$ git clone https://github.com/github515157/Devops.git [To downlode the first user code from the remote repo to local repo and it creates a copy of the code file]
$ cd Devops 
$ vi Devops [use any text editor to modify this file] 
$ cat Devops 
$ git status [To check how may file are modified]
$ git add <file name>  
$ git add . [for all files]  
$ git commit  -m "code changes from the second user" 
$ git push -u origin main 
  
Use case: 3    
============================ 
First User activities after second user pushed the code changes 
==================
[It is a first user git repo in local machine] 

$ git pull  [it downloads all the remote changes to the local system.] 
     
  
Use case: 5 
=========== 
Merge the Feature branch into anthoer branch/ main branch 
User should be changed to branch in which merging is required. 
==========================
$ git branch [To check the present branch]
$ git branch <branch name> [to create a new branch] 
$ git branch -a [to check the total branch in remote and local]
$ git checkout <branch name> [to change the branch]
$ git merge <Source branch which is going to be merged> 
Eg: 
$ git merge <branch name> [locally merge Feature branch into main branch] 
$ git push -u origin main  [it updated "main" branch with Feature branch changes]
Branch "Feature" is ahead of "main" branch. So we need to merge into "main" branch 
  
To delete the branch
===================
After completion of any Feature branch, we need to delete from repo Or may be wrongly created a brach. 
[Pick the branch from github repo] 
$ git branch -D <branch name> [To delete the branch in local repo] 
$ git push origin --delete <branch name> [To delete the branch in remote repo] 
  
  
  

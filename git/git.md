Set config values

$ git config --global user.name "user name"
$ git config --global user.email "user@email.hola"
$ git config --list >> to list all configurations

------------------------------------

Initializing a repository from an existing code

$ git init

to stop tracking the project we delete the .git directory

------------------------------------

To get project status 
$ git status

------------------------------------

To add files to the staging area

$ git add -A

To remove files from the staging area
$ git reset <files>

To remove all files from the staging area
$git reset

--------------------------------------

To commit a change
$ git diff  
$ git commit -m "message"
$ git log

--------------------------------------

To clone a remote repository 

$ git clone <url> <where to clone>
$ git clone ../remote_repo.git

--------------------------------------

Viewing information about the remote repository

$ git remote -v 
$ git branch -a 

--------------------------------------

To push changes to remote repository

$ git pull origin master
$ git push origin master

--------------------------------------

To create a branch for a desired featured

$ git branch <branch name>
$ git checkout <branch name>

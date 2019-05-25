# Git day to day usage  

### Here are some commands you would use on a daily basis:
* git clone
  * Create a local copy of a remote repository
* git status
  * This will show you what, if anything, has changed in your working tree
  * Additional common options:
    * git status -v 
      * provides more verbose output about what has changed in your repository
* git add _changed-files_
  * Adds specified files to the staging area in your repo 
* git commit
  * Creates a new commit in your local repository from the changes in your working tree
* git log
  * This will display a log of all commits in your current repository
  * Additional common options:
    * git log --pretty=oneline
      * This will print the commits in your log onto single lines that include the commit hash and subject of your commit message
* git pull
  * This will pull changes from your remote repository to your local
  * Additional common options:
    * git pull --rebase
      * This will pull the remote changes and replay your commits on top of the remote commites (this rewrites history, could potentially be dangerous)
* git init _repo-name_
  * This will create an empty repository in a directory named the same as _repo-name_
* git push origin master
  * This will push changes to your remote repository
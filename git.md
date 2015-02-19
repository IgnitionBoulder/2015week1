* `git status`:  see list of files which have changed but not been committed  
  * un-staged changes appear in red
  * staged changes appear in green
  * whatever is "staged" will be commited when you use `git commit`
  
* `git add [filename]`:  add [filename] to the "stage".  
  * That file will now appear in green when you run `git status`
  * `git add .` adds all changes  
  
* `git diff`:  show the *un-staged* changes you have, in diff format  
  * red lines are lines you deleted  
  * green lines are lines you added  
  * any lines you changed will be listed as a red deletion followed by a green addition
  
* `git commit`:  create a new commit in the git history.
  * will contain anything in the "stage", meaning green in `git status`
  * normally you want to run `git commit -m "some message here"`; if you don't you'll end up in a terminal editor to make the commit message  

* `git pull`:  retrieve latest changes from a remote repo    
  * in this class, the remote repo is gonna be called "origin", and set to https://github.com/[your_username]/[name_of_repo].git
  * `git pull origin master` tells git to pull the "master" branch from the "origin" repo  
  * Don't do this if you have un-committed local changes!  If you do you may have to resolve merge conflicts.  

* `git push`:  send latest changes from local to a remote repo  


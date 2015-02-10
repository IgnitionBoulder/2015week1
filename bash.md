# Bash

Bash is the environment you use on the command line 
(as long as you're on a Mac or Cloud9 - Windows has a different command line environment)  

* `cd`:  change directory    
  * `cd foo`:  move into the directory called "foo" relative to where you are now (this is called using a "relative path")  
  * `cd /Users/my_username/foo`:  move into directory called "foo" at that specific path (this is called using an "absolute path")  
  * `cd ..`:  move up one directory  

* `ls`: list all files and subdirectories of this directory  
  * `ls -a`:  "all"; show hidden files that begin with "."  
  * `ls -l`:  list them in a vertical list  
  * `ls -p`:  show a slash after directories like this:  `foo/`  
  * `ls -alp`:  do all three of those things.  You can combine option flags together.  
  * `man ls`:  open the manual page for `ls` - shows all the options you can use  
  
* `pwd`:  show the current path

* `cat [somefilename]`:  print that file's contents into the terminal  

* `mv some/file/path new/file/path`:  relocate a file or directory  

* `rm some/file/path`:  delete that file  
  * `rm -r some/directory/path`:  delete a directory.  "r" stands for "recursive"  
  
* `man [anycommand]`:  show the manual page for that command  
  * `q`:  quit out of `man`  

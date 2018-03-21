Learn command line
==================

Please follow and complete the free online [Bash Scripting Tutorial](https://ryanstutorials.net/bash-scripting-tutorial/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. You should be able to go through these in a couple of hours.

**Note:** Bash is not installed on a PC. Rather, PC users must install Cygwin. Once Cygwin has been installed, the command line interface witll _emulate_ bash. You can find all information regarding Cygwin [here](https://www.cygwin.com/).

---

### Q1.  Cheat Sheet of Commands  

Here's a list of items with which you should be familiar:  
* show current working directory path
* creating a directory
* deleting a directory
* creating a file using `touch` command
* deleting a file
* renaming a file
* listing hidden files
* copying a file from one directory to another

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do.  (Use the 8 items above and add a couple of your own.)  

> > Command|Description
------:|-----
`pwd  `|prints working directory
`mkdir`|makes a directory
`rmdir`|removes an empty directory
`touch`|updates the modification date of a file, creating it if necessary
`rm   `|removes a file
`mv   `|moves (renames) a file
`la   `|lists all files
`cp   `|copies files
`sed  `|edits text stream
`grep `|finds in stream



---

### Q2.  List Files in Unix   

What do the following commands do:  
`ls`  
`ls -a`  
`ls -l`  
`ls -lh`  
`ls -lah`  
`ls -t`  
`ls -Glp`  

> > grabs files
-a  all: does not ignore files starting with '.'
-l  long:incudes more details (permissions, etc)
-h  humun readable: reformats displayed filesize
-t  time: sorts items by most recent 
-Glp -l without group intormation that is more readable without terminal colors.



---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > 
`ls -o` identical to `ls -Gl`
`ls -A` like `ls -a` without ./. and ./..
`ls -R` recursive
`ls -L` follows symbolic links
`ls -d` do not open directories


---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > `xargs` allows lifting stdin to the command level.
`find -name '*.jpg' | xargs rm` should remove all \*.jpg in subfolders, if I understand it correctly.

 


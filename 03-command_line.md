# Learn command line

Please follow and complete the free online [Command Line Crash Course
tutorial](https://web.archive.org/web/20160708171659/http://cli.learncodethehardway.org/book/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. Each "chapter" focuses on a command. Type the commands you see in the _Do This_ section, and read the _You Learned This_ section. Move on to the next chapter. You should be able to go through these in a couple of hours.

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

> > REPLACE THIS TEXT WITH YOUR RESPONSE

---

### Q2.  List Files in Unix   

What do the following commands do:  

`ls`  
*lists all files in a direcory*

`ls -a`  
*lists all files including hidden files "."*

`ls -l`  
*lists files in a long format with permission, file size, modification date*  

`ls -lh`  
*same as above with with file size in a human readable format*  

`ls -lah`  
*same as above but including hidden files*    

`ls -t`  
*lists files by modification date, starting with most recent*

`ls -Glp`  
*lists files in long format, without groups, showing "\" for folders*


---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

It seems like -R and -a could be useful


---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

`xargs` allows you to build a command that can be sent as argument to other commands that don't accept input from standard input
 for example, `find . -name '*.md' | xargs wc -l` lists the number of lines of all Markdown files in the current path and its subfolders
 

 


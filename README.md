# Julie's Journal for Code 102
<<<<<<< HEAD

#### Julie's Code Journal of Learning
=======
>>>>>>> 490f8bc9ee8511fe83d7b9b46e4047196d5b871d

## Intro 
I was born in [New Orleans, LA](https://www.neworleans.com/things-to-do/haunted/); grew up in [Duluth, MN](https://www.google.com/maps/place/Duluth,+MN/@46.7646466,-92.3910849,10z/data=!3m1!4b1!4m5!3m4!1s0x52ae527e782e37ff:0x90fdbf76eb580c72!8m2!3d46.7866719!4d-92.1004852); and moved to [Seattle, WA](https://theoatmeal.com/blog/seattle_weather) in 2009 for music. I have a Bachelor of Science in Cellular and Molecular Biology from UW. My love of medicine led me to work in women's heath, where I have been working for the past 3 years. I have a concert grand harp and a monster/cat named Pip. This year, I am focusing on my little garden. I hope my carrots will grow - plants usually come to my flower beds to *die*. For fun, I bake cookies and fresh peach cheesecake for friends. In the next 5 years, I would like to start keeping a small hive of bees. 

Here is my [Github Profile Page](https://github.com/jmerlemeier), enjoy!

<<<<<<< HEAD
## Table of Contents
- [Day1](day1.md)
- [Day2](day2.md)
- [Day3](day3.md)
=======
###### June 21, 2019


## Git Tutorial, created by Linus Torvalds, the chief architect of the Linux kernel
https://blog.udemy.com/git-tutorial-a-comprehensive-guide/#5_1

Git is a Distributed Version Control System (DVCS). A DVCS allows clients to create mirrored repositories. These data backups can be easily be placed on the server to replace any lost information. It stores data in a file system made up of snapshots. Storing an altered version is 'called making a commit'. Who did what to what file, when? It store a history of changes to your files. 

Files in Git can reside in three main states: committed, modified and staged.

Committed
Data is securely stored in a local database

Modified
File has been changed but not committed to the database

Staged
Flagged a file’s changed version to be committed in the next snapshot

Ways to get help with Git from the terminal: 
* git help command
* git command --help
* man git-command

## How to
 
1. Download Git
2. Set up a Git Repository by importing or cloning
3. Know the Structure of the repository.
```
WORKING DIRECTORY------add------>INDEX------commit------>HEAD
:where files live           :area for staging      :points to recent commit "You are here"
```
4. Interact with a file
![Life cyle of File with Git](https://blog.udemy.com/wp-content/uploads/2015/08/image006.png)
5. You can check the status of a file using *$ git status*

#### How do I Track and Stage a new file?
|How many files?|What is happening?|Command for Terminal
|---|---|---
|Single File|Track one file, now staged for committing|git add filename
|All Files|All files in the repo are tracked, now staged for committing|$ git add *

## FAQs

#### How do I commit?
|How many files?|What is happening?|Command for Terminal
|---|---|---
|Commit 1+ files|Commit to Head with a message|$ git commit -m “made change x,y,z”
|Commit all changes|Commit a snapshot of all files in working directory |$ git commit -a

Remember to make short, specific messages

#### How do I Push changes to a remote repository?
*$ git push origin master*

#### How do I stash changes if I am not ready to commit, but want to save them?
*git stash* and *git stash apply*
(the first temporary removes changes and hides them so you can easily work, the second retrieves them).

#### How do I see my remote repos?
*git remote* and *git remote -v*

#### How do I download repo from GitHub to my computer?
*git clone [URL from GitHub]* You get the URL from clone/download button from GitHub

## What is GitHub
Share code online and collaborate with others
## What is a repo?
Usually 1 project - 1 repo
They can live on Github and/or your computer
You set up a connection between GitHub and your computer (through Git and your terminal)




###### June 19, 2019


## Notes on The Command Line, ryanstutorials.net

- Command Line: text based interface to the system, according to the website
  * *prompt* is presented from terminal.
  * *command* is what I type.
  * *arguments* 
  * *options* typically start with a dash and are used to modify the behavior of the command.
  * *outputs* 
 - The Shell: Part of the OS that defines how to terminal will behave, executes commands. **BASH** is an example of a shell.
 - Shortcuts rock!
   * use *UP* and *DOWN* keys to use recently used commands.
   
## Basic Navigation
   
   Path: a means to get a particular file or directory on the system. 
   - Location: File or directory
   - Root Directory: the Top of the hierarchy
   - Absolute: specify a location in relation to the root directory. Yes slash (/)
   - Relative: specify a location to where we currently are in the system. No slash
   
   |command|define|Why use?|
   |-----|-----|-----|
   |*pwd* |Print Working Directory|Use to remind yourself of where you presently are 
   |*ls* |List |Lists current location (contents in a current directory), can use with arguments
   |*ls -l*|Long listing option|Use when want more info than just ls
   |*ls /ect*|List a specific item's contents|Argument asking to list contents of directory named 'ect' instead of current directory
   | *~*| Shortcut for Home directory |If home is /home/julie then ~ is /home/julie. Can find docs with the path ~/Documents.
   |*.*| ref current directory|./Documents
   |*..*| ref parent directory|Use to go up the hierarchy, can use several times.
   |*cd* |Change directories|Take you instantly back to home directory|
   |*cd with argument*|Move to a specific directory|
   |*Tab completion*| Shortcut to typing|As you type, hit tab for autocomplete
   
 
## More about Files
```
Rule 1: Everything is a file
Rule 2: Linux is CAsE SeNSItivE
Rule 3: If you have **spaces** in your file name, you must use **'quotes'** or **escape/ characters**. You can also try **tab completion**
Rule 4: Hidden files are a thing. To make a hidden file simply put a .(full stop) in front of the name. To make unhidden, remove it. ls will NOT show hidden files. To see hidden files in addition to the other contents in the directory, use command: ls -a
```

Common Extensions [ryanstutorials.net]
* file.exe - an executable file, or program.
* file.txt - a plain text file.
* file.png, file.gif, file.jpg - an image.

|command|define|Why use?|
|-----|-----|-----|
|*file* path|File with argument included |Tells type of file
|\ |Backslash is an escape character| nullify the special meaning of the **next** character


###### June 17, 2019


## Growth Mindset 
The idea that humans are inherent learners whose skills are improved with dedication and diligence. Someone is not simply born with all the skills they need, they must aquire them over time. This mindset allows a person to be adaptable to challenges and to succeed no matter the obstacle. Conversely, a person with a fixed mindset abandons challenge quickly. They are easily discouraged by the successes of others. 

#### Reminders to help stay in a growth mindset
- [x] Take 3 deep breaths
- [x] Everyone is frustrated when they learn something new
- [x] You will get through this

## Markdown 
Today, I learned that markdown is a language used in Github. It is a quick, easy way to create and publish content. With a little [help](https://help.github.com/en/articles/basic-writing-and-formatting-syntax#paragraphs-and-line-breaks), I learned how to write and format the page you see here. I can add links, *style text*, create lists, and use emojis :octocat:, too!

Some Basic Markdown Examples:

|Style|Syntax before word|Syntax after word
|---|---|---|
|**BOLD**| ** | ** |
|*Italics*| * | * | 

>>>>>>> 490f8bc9ee8511fe83d7b9b46e4047196d5b871d



![Image of Coffee and thanks](https://isorepublic.com/wp-content/uploads/2018/11/isorepublic-coffee-thanks-1-1100x733.jpg)


# June 21, 2019


## Git Tutorial, created by Linus Torvalds, the chief architect of the Linux kernel

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

---------------------------------------------------------------------

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

---------------------------------------------------------------------

Workflow
Clone from GitHub - only need to do once per project
1. Got to Git hub and copy link
2. Open Terminal
3. Type git clone [paste URL]

Add, commit, push over and over
1. Open terminal
2. Git status (red not committed, green ready to commit)
3. Git add index.md
4. Git status and see index is green
5. Git add day3.md
6. Or add files by: git add - - all 
7. Git status and now all of them a green
8. Git commit -m “Added Day 3 file page and created Table of contents”
9. Once hit enter, it will give you a summary
10. Git status will say nothing to commit
11. To see what repo this git is hooked up to is: git remote -v. It will give you a nickname ‘origin’
12. Git push origin master and hit enter


---------------------------------------------------------------------
## FAQs

#### How do I Track and Stage a new file?
|How many files?|What is happening?|Command for Terminal
|---|---|---
|Single File|Track one file, now staged for committing|git add filename
|All Files|All files in the repo are tracked, now staged for committing|$ git add *

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

#### What is GitHub
Share code online and collaborate with others

#### What is a repo?
Usually 1 project - 1 repo
They can live on Github and/or your computer
You set up a connection between GitHub and your computer (through Git and your terminal)

[Return to Homepage](README.md)
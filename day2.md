#### June 19, 2019


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
   
---------------------------------------------------------------------

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
   
---------------------------------------------------------------------
 
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

[Return to Homepage](README.md)
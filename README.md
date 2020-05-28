# Covfefe5thAve

# Zsh Cheatsheet




| Command        | Use           | optnl. arguments  |
| ------------- |:-------------:| -----:|
| **ls**     | *list*; shows the contents of the folders but *it doesn't how hidden files* | **- a** *show all directories and files, (including hidden ones)* **-R** *lists contents of all files and the directories they're in |
| **cd**      | *change directory*; used to switch between directories       |   *n/a* |
| **pwd**| *print working directory* ;     shows you where you're currently at   |   *n/a*    |   
 **mkdir** |    *make directory* ; make a new folder wherever it currently is    | *n/a  *
 | **rm** | *remove* but it only removes **files**, *not directories* |** - rf** deletes directories and files 
  | **touch**|  creates files but not folders | *n/a* |
  |**cp** | *copy*; copies the files and the directories, source and destination location | *n/a* |
  |**mv** | *move*; it does 2 things: **first** it *copies* and then *deletes from its original folder* can also be known as *rename*. | *n/a*  

  # Terminal Cheatsheeeeeeeet!  
## **Shortcuts**  
**Command** | **Description** | **Useful For**
--- | :--- | :---
Tab | Auto-completes file / folder name. | Useful to know if you are about to make a mistake. 
Ctrl + R | Lets you search through your previously used commands | Quickly find a command you need again
Ctrl + L | Clears the screen | Getting rid of clutter on screen
Ctrl + C | Kill current running command | Stopping a long process from wasting your time.  
## **Core Commands**  
**Command** | **Description** | **Useful For**
--- | :--- | :---
cd [folder] | Change directory | Navigating into an existing directory
cd ~ | Home directory | Going home
ls | Short listing | Quickly list current directory contents and file info
ls -lh | long form listing w/ file sizes | Makes file sizes human readable
ls -a | list hidden files too | Seeing hidden files
ls -R | Entire contents of folder | Seeing full path
open [file] | Opens a file | Well...
open . | Opens a directory | Umm...  
## **File & Directory Management**  
**Command** | **Description** | **Useful For**
--- | :--- | :---
touch [file] | Create new file | Making a new file
pwd | print working directory | Shows the fill path to the working directory
.. | Parent Directory | Move "up" one
cd ../../ | Move 2 levels up | Making larger moves quickly
. | Current folder | Shows current directory
rm [file] |Remove one or more files | Deleting files you no longer need
rm -r [dir] | Remove a directory and everything in it | Kill it with fire
cp[file][newfile]| Copy from one file into another file | Making quick copies
cp [file] [dir] | Copy file into new directory | Making quick copies
mv [file] [new filename] | Move & or Rename files | Hmm...
mkdir [dir] | Make a new directory | Uhh...
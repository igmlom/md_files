227. 
~  = inside this
ls = list
cd + folder name(relative to the current folder)= navigate beetween folders
cd~ = comeback to root
cd .. = back one level.
cd + up arrow/ down arrow = replace folders.
pwd - print working diretory (print the path)

# edit in the middle of the path.
hold the alt, and click with the mouse

ctrl +a  - go to the begging of the command line
ctrl +e = go to the end.
ctrl +u = clean the command line

228. 
# create directory (= make directory)
mkdir + name 
# create file
touch + name.txt/name.docs
# open file
open + file name
# open with
open -a word
# delete file
rm name
# delete all the files (not directories) inside directory
rm *
# delete directory
rm -r name

# delete all directories
rm -r *

# change directory name
 mv source_name target_name

# move folder or files to another folder
 mv source_name target_path

# copy folders or files
cp source_name target_path


236. node terminal
 
# active the js file inside the terminal
open termimal in the same directory, then write:
node index.js (for example)

# using the node REPL -read evaluation print loops:
open termimal in the same directory, then write:
node

# get out of REPL
.exit
 or:
 ctrl + c + c

 # clear the terminal
 .clear

 # use the directory path

 __dirname

 for example:
 console.log(__dirname);

 *npm*

# list of global installed packages
npm list -g --depth 0

# link to Global packages
npm link package name

*git*
# add git to repository
git init

# to the stage area
git add .

# commit changes with message 
git comit -m "type you changes"


# view status
git status

# checkout each file changed
git checkout

# view the diffrence between now to the last commit
git diff <filename>

# see all the versions
git log

**create a remote repositry in Github**
*push repositry to github*
1. create repository in git hub
2. copy the repository link
2. write in the command line:
   git remote (remote repository) -u origin (the repositry name, theoreticly it could be anything but usually peope set it as "origin")
4.  git push -u origin master
  then it will take some time and upload your files to github.

*git ignore*
1. create a git ignore file simply with the command line 
touch git ignore
2. open the gitignore
3. write inside it all the things you want to ignore

# inside Github there's a repositry called gitignore, inside there's a prime build in template, to ignore, recomend swift.gitignore

*clone repositry from github*
git clone <repository link>

*branches*

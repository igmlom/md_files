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




# General commands

## add git. to repository
`git init`

## to the stage area
`git add .`

## commit changes with message 
`git comit -m "type you changes"`

## skpping on the staging area 
`git commit -a -m "your note"`


## view status
show the state of the folder

![GitHub Logo](git_status.png)

`git status`

### short status
`git status -s`



## checkout **each** file changed
`git checkout`

## view the diffrence between now to the last commit
`git diff`
or
`git diff <filename>`

## view the diffrence between the stage files to the last commit
`git diff --staged`

## view the diffrence between the cached files to the stage files
`git diff --cached`


## see all the versions
`git log`

## removing files

`rm PROJECTS.md`
If you simply remove the file from your working directory, it shows up under the “Changes not staged for commit” **(that is, unstaged)** area of your git status output


`git rm PROJECTS.md`
To remove a file from Git, you have to remove it from your tracked files (more accurately, remove it from your staging area) and then commit.

# create a remote repositry in Github
## push repositry to github

1. create repository in git hub
2. copy the repository link
2. write in the command line:
   git remote (remote repository) -u origin (the repositry name, theoreticly it could be anything but usually peope set it to "origin")
4.  git push -u origin master
  then it will take some time and upload your files to github.

# git ignore
1. create a git ignore file simply with the command line 
touch git ignore
2. open the gitignore
3. write inside it all the things you want to ignore

## basic syntax:
line that start with #, count as a comment
```
# ignore all .a files
*.a

# but do track lib.a, even though you're ignoring .a files above
!lib.a

# only ignore the TODO file in the current directory, not subdir/TODO
/TODO

# ignore all files in any directory named build
build/

# ignore doc/notes.txt, but not doc/server/arch.txt
doc/*.txt

# ignore all .pdf files in the doc/ directory and any of its subdirectories
doc/**/*.pdf
```

## important to know 
inside Github there's a repositry called gitignore, inside there's a prime build in template, to ignore, recomend swift.gitignore

## clone repositry from github
git clone <repository link>

## branches

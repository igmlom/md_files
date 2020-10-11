
# General commands

## add git. to repository
`git init`

## to the stage area
`git add .`

## commit changes with message 
`git comit -m "type you changes"`


## view status
show the state of the folder

![GitHub Logo](git_status.png)

`git status`


## checkout **each** file changed
`git checkout`

## view the diffrence between now to the last commit
`git diff <filename>`

## see all the versions
`git log`


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

# inside Github there's a repositry called gitignore, inside there's a prime build in template, to ignore, recomend swift.gitignore

## clone repositry from github
git clone <repository link>

## branches

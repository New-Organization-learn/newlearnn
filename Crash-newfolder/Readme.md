## Git Hidden Folder
There is .git hidden folder which tell you that other project is a git repo 

If we want to create a git repo in a new project we create the folder and the initialize that repo using  'git init' 
~~~
mkdir /workspace/tmp/new-project
cd /workspace/tmp/new-project
git init
touch Readme.md
code Readme.md
git status
git add Readme.md
# makes changes to readme.md
git commit -a -m "add readme file"
~~~



## Branches


## Cloning 
  
~~~md
Since we are unsing three types of cloning 
HTTP
SSH
LINK
~~~

### HTTPS
~~~md
get clone https://github.com/New-Organization-learn/newlearnn.git
~~~

## Remote
## Stashing
## Merging
## Add
When we want to stage changed that will be included in the commit We can use the . to add all possible files.
~~~
git add Readme.md
git add.
~~
## Reset
Reset allows you to move Staged changes to be unstaged.
This is useful when you want to revert all files not to be commited 

~~~sh
git add .
git reset

> git reset will revert a git add.
~~~

 

## Commits
When we want to commit code we can write git commit will open up the commit edit message in the editor of choice.
~~~sh
git commit
~~~~
Set the global editor
~~~~
git config --global core.editor emacs
~~~
Make a commit and commit message without opening the editor 
~~~sh
git commit -m "add another exclamation"
~~~
## Status
Git status shows you what files will or will not be commited.
~~~~ sh
git status
~~~~

## Gitconfig file
The gitconfig file is what stores your glbal configuration susch as name, email editor and more.

showing content for our .gitconfig files
~~~
git config --list 
~~~ 

When you first install Git on your machine you are suppose to up your email and name 

~~~sh
$ git config --global user.name "John Doe"
$ git config --global user.email "johndoe@example.com"
~~~

## Log
git log will show recent git commits to the git tree

## Push 
When  we want to push a repo to our remote origin
~~~
git push
~~
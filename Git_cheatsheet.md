
### Configuring Git for the first time
```python
# sets up Git with your name
$ git config --global user.name "<Your-Full-Name>"

# sets up Git with your email
$ git config --global user.email "<your-email-address>"

# makes sure that Git output is colored
$ git config --global color.ui auto

# displays the original state in a conflict
$ git config --global merge.conflictstyle diff3

$ git config --list


## Creating a Git repository
```python
# making a directory in the computer
mkdir -p udacity-git-course/new-git-project && cd $_

# The init subcommand is short for "initialize"
$ git init

# state of our repository as Git sees it
$ git status

## General Git commands

# Displays info about the existing commits
$ git log

# Displays info about the given commit
$ git show

$ git log --oneline

# lists the files that were changed as well as the number of added/removed lines
$ git log --stat

#display the actual changes made to a file
$ git log -p

## Creating a new file inside Git bash
$ touch filename.extension

## Pushing changes in the branch
$ git add .

$ git commit -m
$ git push

$ git diff

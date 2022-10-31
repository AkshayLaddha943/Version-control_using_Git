
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

## tagging, Branching and merging

#add tags to specific commit, (-a tells Git to create an annotated flag)
$ git tag -a v1.0
$ git tag

#to tag a commit that occurred farther back in the repo's history
$ git tag -a sha

#allows multiple lines of development
$ git branch

#switch between diff branches and tags
$ git checkout

#combines changes from different branches into one
$ git merge

# creating a new branch
$ git branch branch-name

# To delete a given branch
$ git branch -d sidebar

#checkout of one branch
$ git checkout branch-name (to checkout from)


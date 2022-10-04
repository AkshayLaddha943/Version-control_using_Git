
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


### Creating a Git repository
```python
# making a directory in the computer
mkdir -p udacity-git-course/new-git-project && cd $_

# The init subcommand is short for "initialize"
$ git init

# sets up Git with your email
$ git config --global user.email "<your-email-address>"

# makes sure that Git output is colored
$ git config --global color.ui auto

# displays the original state in a conflict
$ git config --global merge.conflictstyle diff3

$ git config --list


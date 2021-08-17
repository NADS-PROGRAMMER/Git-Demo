
# GIT PRACTICE

**HERE ARE SOME OF THE GIT COMMANDS**


# Cloning from the remote repository online to your local folder

Command: `git clone https://linkHere`



# Adding repository to your local folder

Command: `git remote add origin https://linkHere`

**To verified:**

`git remote -v`

# Adding Untracked Files

Command: `git add filename.ext`

**If the filename consist of whitespaces use this:**

Command: `git add "filename.ext"`

If you want to track all the files that has been modified, added, or any changes to your folder:

Command: `git add .`

The period means all

# Commiting files

Command: `git commit -m "put your message here"`

- 'm' means message

**If you want to commit all the files**

Command: `git commit -am "put your message here"`
- 'a' means add. It is only possible for modified files but not to untracked files.

**If you want to add another message**

Command: `git commit -am "first message here" -m "second message here" -m "and so on"`



# BRANCHING

**Checking branches of your repository**

Command: `git branch`

**Adding and Checking out branch**

Command: `git checkout -b "name of branch"`

*****NOTE*****: ***The name of your branch must be descriptive***

**Switching to another branch**

Command: `git checkout "name of branch"`

# OTHER USEFUL COMMANDS

**Checking status of the repository**

COMMAND: `git status`

**Checking the history of commits in your repository**

COMMAND: `git log`

**Unstaging added files**

COMMAND: `git restore --staged "filename here"`

- If you want to restore all: 
    - COMMAND: `git restore --staged .`
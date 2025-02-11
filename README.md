# Github Commands and other Useful Reminders
The repository that contains instructions for using git commands, and other important reminders that I would like to access fast.

## Git Instructions:

- git clone - clone the repo to the local repo
- git branch - check which branch are you using at the moment
- git branch -m \branch name\ - choose the branch you want to work on
- git config --global user.email "you@example.com"
- git config --global user.name "Your Name"

  ### To push changes from local repository to GitHub:
- git add . - adds all changes ("." - "all" part)
- git commit -m '\comment\' - commit changes with a comment 
- git push --set-upstream origin \branch name\ - push changes from local repo to GitHub
- git push origin HEAD: \branch name

- git fetch origin - Fetch the latest changes from the remote repository
- git checkout \branch name\ - Switch to your sql-queries branch
- git pull origin \branch name\ - Pull the latest changes
- git push origin \branch name\ - Push the latest changes
  
  ### Working with branches:
- git checkout -b new-branch - Create a New Branch
- git add; git commit -m "Your commit message" - Make Changes and Commit
- git push origin new-branch - Push the Branch to the Remote Repository
- git push -u origin branch-name -  if the branch already exists on the remote repository - set the upstream tracking branch if it’s the first time you’re pushing
- git push origin --delete branch-name - delete a remote branch
- git branch -m new-branch-name - rename a local branch
- git checkout branch-name - switch to a different branch

  *Note that  Github does not support creation of an empty folder within repository, so need to create a file within the folder at the same time as the folder creation.*

## Navigate Terminal:

- cd *name of the folder* - enter the folder 
- cd .. - leave the current folder
- ls - list the files/folders inside the current folder
- mkdir *name of the folder* - create a folder
- rm/rmdir *name of the folder* - delete a folder
- ni *name of the file* - create a new file

## Python Virtual Environment:

In Windows PowerShell:
### Create:
python3 -m venv venv
### Activate:
cd venv
.\Scripts\Activate

## Markdown:
** - Italic
*()* - Bold


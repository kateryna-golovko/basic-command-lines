# Github Commands and other Useful Reminders
The repository that contains instructions for using git commands, and other important reminders.

## Git Instructions:

- git clone - clone the repo to the local repo
- git branch - check which branch are you using at the moment
- git branch -m \branch name\ - choose the branch you want to work on
- git config --global user.email "you@example.com" 
  git config --global user.name "Your Name"
  ### To push changes from local repository to GitHub:
- git add . - adds all changes ("." - "all" part)
- git commit -m '\comment\' - commit changes with a comment 
- git push --set-upstream origin \branch name\ - push changes from local repo to GitHub
  ### Working with branches:
- git checkout -b new-branch - Create a New Branch
- git add; git commit -m "Your commit message" - Make Changes and Commit
- git push origin new-branch - Push the Branch to the Remote Repository
- git push -u origin branch-name -  if the branch already exists on the remote repository - set the upstream tracking branch if it’s the first time you’re pushing
- push origin --delete branch-name - delete a remote branch
- git branch -m new-branch-name - rename a local branch
- git checkout branch-name - switch to a different branch

## Navigate Terminal:

- cd
- cd ..
- ls 

### Python Virtual Environment:
In Windows PowerShell:
#### Create:
python3 -m venv venv
#### Activate:
cd venv
.\Scripts\Activate

### Markdown:
** - Italic
*()* - Bold


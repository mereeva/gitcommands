# gitcommands
List of commands you need to start with git right away


First you need to be in your project that you want to track in git
  
[Initializing your project to be tracked in git]
git init
git add .
git commit -m 'message'
git remote add origin <url>
git push -u origin master
  
[To commit any code]
git add .
git commit -m 'message'
git push origin master / git push

[To check what you have done]
git status [lists all changed files]
git diff [gives the lines that have changed in files]

[if u want to make a new branch with existing code copied in the new branch e.g.:dev]
git checkout -b dev [this command will copy all your content to a new branch and master branch will remain as it was]


[How to merge new branch changes into master branch]
first commit your changes in the new branch refer [To commit any code]
git checkout master [move into master branch]
git merge dev [merge contents of dev into master]


<h1> List of commands you need to start with git right away </h1>
<br>
<br>

<b>Step1</b>: First you need to be in your project that you want to track in git <br><br>
  
<b>Initializing your project to be tracked in git </b> <br>
git init <br>
git add . <br>
git commit -m 'message' <br>
git remote add origin :url <br>
git push -u origin master <br><br>
  
<b>[To commit any code]</b><br>
git add . <br>
git commit -m 'message'<br>
git push origin master / git push<br><br>

<b>[To check what you have done]</b><br>
git status <i>[lists all changed files]</i><br>
git diff <i>[gives the lines that have changed in files]</i><br><br>

<b> New Branch </b><br>
<i>[if u want to make a new branch with existing code copied in the new branch e.g.:dev]</i><br>
git checkout -b dev <i>[this command will copy all your content to a new branch and master branch will remain as it was]</i><br><br>


<b>[How to merge new branch changes into master branch]</b><br>
first commit your changes in the new branch refer <i>[To commit any code]</i><br>
git checkout master <i>[move into master branch]</i><br>
git merge dev <i>[merge contents of dev into master]</i><br>

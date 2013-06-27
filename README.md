Some of the basic commands:

$ git status
# The main tool you use to determine which files are in which state is the git status command

$ git add README
# Stages your README file, adding it to the list of files to be committed

$ git commit -m 'first commit'
# Commits your files, adding the message "first commit"

$ git commit -a -m 'new commit'
# if you want to skip the staging area, Git provides a simple shortcut. Providing the -a option to the git commit command makes Git automatically stage every file that is already tracked before doing the commit, letting you skip the git add part.

$ git push origin master
# Sends your commits in the "master" branch to GitHub

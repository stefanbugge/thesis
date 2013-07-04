## Sublime 2 text + SumatraPDF ##

Setup tutorial: [http://knowledgepayback.blogspot.dk/2012/07/latex-on-windows-with-sublime-text.html](http://knowledgepayback.blogspot.dk/2012/07/latex-on-windows-with-sublime-text.html)

### Compilation hangs on Windows ###

On Windows, sometimes a build seems to succeed, but the PDF file is not updated. This is most often the case if there is a stale pdflatex process running; a symptom is the appearence of a file with extension .synctex.gz(busy). If so, launch the Task Manager and end the pdflatex.exe process; if you see a perl.exe process, end that, too.

## Git basics ##

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

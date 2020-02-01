# Ad Hoc Interfaces: A tangible approach to on-demand user interfaces

Master thesis

## Sublime 2 text + SumatraPDF ##

Setup tutorial: [http://knowledgepayback.blogspot.dk/2012/07/latex-on-windows-with-sublime-text.html](http://knowledgepayback.blogspot.dk/2012/07/latex-on-windows-with-sublime-text.html)

### Compilation hangs on Windows ###

On Windows, sometimes a build seems to succeed, but the PDF file is not updated. This is most often the case if there is a stale pdflatex process running; a symptom is the appearence of a file with extension .synctex.gz(busy). If so, launch the Task Manager and end the pdflatex.exe process; if you see a perl.exe process, end that, too.

## Git basics ##

Some of the basic commands:

$ git status
_The main tool you use to determine which files are in which state is the git status command_

$ git add README
_Stages your README file, adding it to the list of files to be committed_

$ git commit -m 'first commit'
_Commits your files, adding the message "first commit"_

$ git commit -a -m 'new commit'
_if you want to skip the staging area, Git provides a simple shortcut. Providing the -a option to the git commit command makes Git automatically stage every file that is already tracked before doing the commit, letting you skip the git add part._

$ git push origin master
_Sends your commits in the "master" branch to GitHub_

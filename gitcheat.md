#Git Cheatsheet
**Name: ** Xin Yuan
**Date: ** January 17, 2017

git config --global user.name "[name]
git config --global user.email "[email address]
git config --list
git init
git remote add origin [URL of your remote repo]
git remote -v
git status
git log
git add .
git commit -m "[clear message describing the changes you made]"
git push origin master

The standard output of command is connected  via  a  pipe  to  the  standard  input  of  command2.   This
    connection  is performed before any redirections specified by the command (see REDIRECTION below).  If |&
    is used, the standard error of command is connected to command2's standard input through the pipe; it  is
    shorthand  for  2>&1  |.   This  implicit  redirection  of  the  standard  error  is  performed after any
    redirections specified by the command.
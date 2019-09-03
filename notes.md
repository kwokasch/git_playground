# Notes

-> git init --> initialize as a git repo

1. git status --> look at local directory => filename will be red if unstaged

2. git add (filename) --> stages file after changes have been made
    (git add .) will stage all files available to be staged in that directory

    2b.git status --> now filename will be green (file is staged)

3. git commit -m "message."--> saves file
    '-m "message."' ==> creates message during commit ==> necessary to successfully commit                               changes

4. git status --> "working status clean"

5. git push origin master --> push changes in "master" to the "origin" repo

- git remote -v => lists the remote repositories are linked to local repositories
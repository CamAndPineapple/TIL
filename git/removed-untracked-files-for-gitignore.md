#Remove untracked files for .gitignore

If you already pushed files to github, but want them to be included
in your .gitignore file, you have to remove them from the cache first:

`git rm -r --cached .`

`git add .`

`git commit -m "fixed untracked files`

> 3.2.16

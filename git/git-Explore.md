[Click here to download the latest version of Git](https://git-scm.com/)

`git --version` to find git version

## basic- first steps

- `git init` - Initialize a local Git repository

- `git status` Check status
- `git add -A` or `git add .` Add all new and changed files to the staging area

- `git add style.css` Add the 'style.css' to the staging area
- `git rm --cached quote.js` unstage a file (or folder)
- `git rm -f new.html ` delete a file (or folder) after adding

- `git commit -m "the first commit"` Commit changes

## NOTE

### …or create a new repository on the command line

- echo "# git-testnote" >> README.md
- git init
- git add README.md
- git commit -m "first commit"
- git branch -M master
- git remote add origin git@github.com:skyGwork/git-testnote.git
- git push -u origin master

### …or push an existing repository from the command line

- git remote add origin git@github.com:skyGwork/git-testnote.git
- git branch -M master
- git push -u origin master

### …or import code from another repository

You can initialize this repository with code from a Subversion, Mercurial, or TFS project.


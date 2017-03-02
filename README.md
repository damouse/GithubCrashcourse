## Commands for Terminal

cd-         change directory
mkdir-      make directory
ls-         list directory 

    Note: '..' up one directory
          '.' current directory

## Git Commands

`init`- creates a new repository

```
git init .
```

`add`- add a file to git tracking

```
git add README.md # adds one file
git add --all
```

`commit`- checkpoint. Takes a commit message after *-m*

```
git commit -m 'this is my commit message'
```

`status`- show the current state of the repo

`push`- send the local repository (on your computer) to a remote repository (usually github). Make sure to add a remote, first!

Adding a remote: 
```
git remote add origin git@github.com:damouse/WhateverYouWant.git
```

Pushing:
```
git push origin master
```

`clone`- make a local copy of a remote repository


## Git Terms

`repository`- where code lives 
`commit`- "snapshot" of a directory
`push`- update the origin (publically hosted, official version on github) with your working changes

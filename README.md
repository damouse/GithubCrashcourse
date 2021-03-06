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

`pull`- go to origin (github) and fetch 

```
git pull

# or, specify remote and branch
git pull origin master
```

`branch`- seperate out your history

```
git branch dev      # make a new branch
git checkout dev    # checkout the branch "dev"
git branch          # lists all branch 
```

`merge`- merge in a branch with another, or a remote with the current branch. The branch merged **into** is the current
```
git checkout master # go to the master branch
git merge dev       # Merge dev into the master
```

## Git Terms

`repository`- where code lives 
`commit`- "snapshot" of a directory
`push`- update the origin (publically hosted, official version on github) with your working changes
`branch`- a seperate "history" tree

## Example Flow

User A makes a change: 

```
git add --all
git commit -m "Your message"
git push
```

User B wants to see the changes: 

```
git pull
```


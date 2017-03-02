## Commands for Terminal

Hey, I think this needs better punctuation.

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

## Git Terms

`repository`- where code lives 


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


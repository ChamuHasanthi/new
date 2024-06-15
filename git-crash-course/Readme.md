## Git Hidden folder

There is a hidden folder called `.git` which tells you that our project is a  git repo.

if we wanted to create a git repo in a new project we create the folder  and the initialize that repo using `git init`
```
mkdir /workspaces/tmp/new-proect
cd /workspaces/tmp/new-project
git init
touch Readme.md
code Readme.md
git status
git add Readme.md

# makes changes to readme.md
git commit -a -m "add readme file"
```

## Cloning

We can clone three ways: HTTPS, SSH, Github CLI

Scince we are using GitHub Codespace we'll create a tempory directory in our workspace

```sh
mkdir /workspace/tmp
cd /workspace/tmp
```

## HTTPS
```sh 
git clone https://github.com/ChamuHasanthi/new.git
cd new
```
## Commits

When we want to commit code we can write git commit which will open up the commit edit message in the editor of choice.

```sh
git commit
```

set the global editor

```
git config --global core.editor emacs

## Branches

## Remotes

## Stashing

## Merging

## Add

When we want to stage changes that will be include in the commit.We can use the . to add all posssible files.

```
git add Readme.md
git add .
```

## Reset
Reset allows you to move staged changes to be unstaged.This is useful when we want to reverts all files not to be not commited
```
git add.
git reset
```
>git reset will revet a git add

## Status

This shows you what files will or will not be commited.

```
git status
```

##
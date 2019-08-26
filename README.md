## Branching
* Listting local branches
`git branch`
* Listting remote branches
git branch -r
* Creating new branch from actual position
`git checkout -b <branchName>`

## Editors
git config --global core.editor "nano"

## Aliases
git config --global alias.co checkout
[alias]
	logg = log --decorate --oneline --graph
	logd = log --oneline --decorate

## Git stash
git stash help

## Rebase vs merge
* 3 branch problem
The most recent common ancestor is used
`git merge-base branch1 branch2`

## Changing history - interactive rebase

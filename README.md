## Add files
- git init
- git add <file> 
- git add *.html
    
## Commit  
git commit -m ''        
git status

## Push files
- git push
- git push -u origin master
    
## Push files
- git log
    
## Changes
- git log
- git diff (changes since last commit)
- git diff HEAD~1
- gif diff @
- gif diff @~<version>

## Revert
- git checkout <file>
- git reset --hard (erase last commit)
- git reset --soft HEAD~1 (putting in staging)

## Change Commit Name 
- git commit --amend -m '<name>'

## .gitignore
- *.ts (every ts files)
- /logs (everything in folder)

## Branch
- git branch <name>
- git checkout <name>
- git push -u origin HEAD
- git pull (after merge on github)
- git checkout -b <name>
- git cherry-pick <version>

## Merge
- git checkout master
- git merge <name>
- git push

## Delete Branch
- git branch -D <name>

## Recover Branch
- git branch <name> <version>
- git checkout <version>
- git push origin :<name>

## Stash changes
- git stash (pause changes)
- git stash pop (retrive changes)
- git stash save ''
- git stash list
- git stash drop

## Command Prompt
clear
wq
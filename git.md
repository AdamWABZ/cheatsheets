# Git cheatsheet

## Basic workflow
git init              # init new repo
git clone <url>       # clone existing repo
git status            # check changes
git add .             # stage all changes
git commit -m "msg"   # commit with message
git push              # push to remote
git pull              # pull from remote

## Branches
git branch            # list branches
git checkout -b <n>   # create + switch
git merge <n>         # merge branch
git branch -d <n>     # delete branch

## Undo
git restore <file>    # discard changes
git reset HEAD~1      # undo last commit (keep changes)
git revert <hash>     # revert a commit safely

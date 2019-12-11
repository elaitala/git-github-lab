Commit 1:
1. I cloned my repository, it was already set up
2. To start tracking a file i type: git add filename
3. To move from the staging area to the repo: git commit -m "what this change does"

Commit 2:
1. To pull changes from the master repo: git pull origin master
2. To unstage a file: git reset filename
3. To go back to a previous commit: git revert filename
4. It's important to use -- in order to specify the kind of revert to use. If it's omitted then it defaults to --mixed
5. If you have broken something or have figured out a better way to do something
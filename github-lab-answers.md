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

Commit 3:
1. to create a branch: git branch new-branch-name
2. to switch between branches: git checkout new-branch-name
3. You'd use a branch to test different ideas before committing

Commit 4:
1. You would use 'git merge' in order to combine your changes with someone else changes to the same file. You'd submit a pull request to have your branch merged if you've added functionality that improves the project for everyone
2. To send all your work to the repo: git add -A >> git commit -m "adding everything" >> git push origin master
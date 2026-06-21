```
git init
git status
git add . {add change to staging area}
git commit -m <message>
git remote add origin https://github.com/VeasnaMuch/GitDemo.git {add code to github repository}
git push origin master {push code to master branch of github}

```

# New change made to the folder or file
    We need to apply
    git add .
    git commit -m <message>

    or
    git commit -a -m <message>

# Git Branch
    git branch {check brance}
    git branch -r {local branch}
    git branch -a {remote branch}

    create new branch
    -----------------
    git checkout -b new_feature

    switch branch
    --------------
    git checkout <branch name>
    git switch <branch name>

# Git merge
    we need to go to branch that we want to merge to first by
    1. git switch <branch name>
    2. git merge <other branch name> 
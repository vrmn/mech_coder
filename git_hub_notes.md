Githb quickstart

Github basics

Best if you create repo first on site.

Then clone into computer the repo.

Then follow steps.

    git init
    git config --global user.name ''
    git config --global user.email ''
    git remote add origin <clone of repo>
    git add .
    git commit -m 'note'
    git push -u origin master <after doing once you can just type git push whenever you want to push>
    git pull ( to check if repo is up to date. )

To make your own branch

    git branch <name of branch>
    git checkout <name of branch> (do this to switch to branch)
    git merge (do this to merge with master)

    git push --set-upstream origin <name of branch>

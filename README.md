<http://stackoverflow.com/questions/7244321/how-do-i-update-a-github-forked-repository>

    git remote add upstream git@github.com:Microsoft/BotBuilder.git
    git fetch upstream
    git checkout master
    git merge upstream/master
    #git rebase upstream/master

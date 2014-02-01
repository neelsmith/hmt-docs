## Forking, Pull-Requests, Merging

Help page: [https://help.github.com/articles/fork-a-repo]().

1. Fork the repository.
1. Clone the fork to your machine.
1. Make changes.
1. Add/commit/push.
1. Pull Request (on github website).
1. `git remote add upstream URL-TO-ORIGINAL-REPO` Lets your fork know where the original repo is.
1. `git fetch upstream` Grabs changes from the original; does not touch your working files.
1. `git push origin master` Adds more of your changes to your own forked copy.
1. `git fetch upstream` `git merge upstream/master` merges changes to the original with your own.

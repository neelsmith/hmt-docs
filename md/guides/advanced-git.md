# Using `github` to contribute to the HMT project

## Background ##


See a guide to [using git to work on HMT editions](basic-git.html)


## Forking, Pull-Requests, Merging ##

See the `github` help page: <https://help.github.com/articles/fork-a-repo>.

1. From the `github` web interface, fork the repository.
1. Clone the fork to your machine (e.g., `git clone FORKEDREPOSITORYNAME` on your machine.)
1. Work normally in your local clone of the forked repository.
1. When you have completed some work, go through the normal `git` cycle of `git add FILE`, `git commit` and `git push`.
1. From the `github` web interface, submit a Pull Request.
1. `git remote add upstream URL-TO-ORIGINAL-REPO` Lets your fork know where the original repo is.
1. `git fetch upstream` Grabs changes from the original; does not touch your working files.
1. `git push origin master` Adds more of your changes to your own forked copy.
1. `git fetch upstream` `git merge upstream/master` merges changes to the original with your own.

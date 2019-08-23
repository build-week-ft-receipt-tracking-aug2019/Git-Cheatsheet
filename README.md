# Git Instructions

Structure should be that the master branch is your release branch, development branch is the beta/alpha branch, and each dev has their own branch that feeds into development.

1. Develop on your branch
1. commit often!

### Merging instructions

... when you complete a feature or fix a bug...

1. make a commit stating your progress
1. checkout the development branch and pull in the latest changes from github
	* `git checkout development`
	* `git pull`
1. merge your personal branch into development
	* `git merge [myBranchNameNoBrackets]`
1. more than likely, you will have merge conflicts. git tries to make this easy with text formatting, but let's face it... it's not easy to understand what it means. Use something like [gitkraken](https://www.gitkraken.com) to make the process infinitely easier for you.
1. commit your resolved conflicts
1. push `development` back up to github
1. checkout your branch again
	* `git checkout [myBranchNameNoBrackets]`
1. merge `development` into your branch
1. push your branch changes up to github
1. continue working on your contributions

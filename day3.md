
## Day - 3 Summary

### Who you don't want to be 

* [this guy](https://xkcd.com/1597/)
* [and this one](https://xkcd.com/1296/)


### Things learned :v: 

#### Rebasing :hatching_chick: 

Remember to rebase your code with the branch you checked out before deploying.

Example, if you are on **feat_learngit** branch and want to rebase with **develop** branch. You will do 

`git rebase develop`

This will apply all you work on top of the work of develop.
Then create a pull request to the develop branch.

####  Resolving conflicts :fearful: 

If conflicts arise during merging or rebasing. Resolve them carefully. After resolving do this :

`git add . `
`git rebase --continue`

To abort if you think you did something wrong : 
`git rebase --abort` during rebase
or
`git merge --abort` during merge

#### Stash  : :tada: 

Another important git command I use every day. 
Stash keeps your work safe in a place known to no one. :smile: 

To track your stashes `git stash list`
To stash your unstaged work : `git stash`
To get your stash back : `git stash apply <hash>`

You can also name your stashes with a message : `git stash save -u <message>` 

Avoid using `git stash pop` and `git stash clear` if you don't understand what are you actually doing.


### Fast Forward merge vs no fast forward merge : :facepunch: 

Git will automatically try to merge fast forward 

For no-ff : `git merge --no-ff <target_branch>` 
This will create a merge commit from your target_branch to the present branch you are on. 

Do check out this to understand this better : [StackOverflow ff vs no-ff](http://stackoverflow.com/questions/9069061/what-is-the-difference-between-git-merge-and-git-merge-no-ff)


### Tomorrow we will look at : :alien:

* Interactive Rebasing
* Force push  after rebasing? 
* Hard Reset vs Soft Reset 
* Cherry Pick, Reflog, Blame etc only if sufficient time is left.  

### Resources :100: Must read this time

* [Git branching model](http://nvie.com/posts/a-successful-git-branching-model/) - this is the model we follow here, a must must read.
* [Merge vs Rebase debate](https://www.atlassian.com/git/articles/git-team-workflows-merge-or-rebase) 


### Homework :speak_no_evil: 

Tell me this tomorrow

* How to seperate my work if stashed has been pop 2 times?
* How do I find my work if I `stash pop` some files and then did `git checkout .` ?


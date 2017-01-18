
## Day - 2 Summary

### Things learned :v: 

#### Pulling the code from remote server :arrow_down_small: 

`git pull origin master`

* *master being the current branch and remote being the origin*

#### Fetching the info from remote server :arrow_double_down: 

Always fetch info from the remote server before pulling and pushing your code. 

`git fetch`

#### Branches :arrow_heading_up: 

Creating a branch : `git branch <branch_name>`
Checking out a branch : `git checkout <branch_name>`

Above two in one : `git checkout -b <branch_name> ` 

List branch:  `git branch -a`

### Merge (ff) 

git merge <feat_new_feature>

* if the current branch is master then this will fast forward merge **feat_new_feature** work to **master**

**Before:**

    master :              O---->O----->O
    
    feat_new_feature:     O---->O----->O---->O
    
**After merging (ff)**

    master :              O---->O----->O---->O


### Difference between fetch and pull  :zap: 

fetch : Brings the code but does not merge. Useful to only see changes but does not want to work on them

         
pull  : Brings the code and merge it too. (ff)

Do check out this to understand this better : [StackOverflow pull vs fetch](http://stackoverflow.com/questions/292357/difference-between-git-pull-and-git-fetch)


### Tomorrow we will look at : :alien:

* Rebasing
* Interactive Rebasting
* Resolving conflicts 
* Git workfow 

### Resources :100: 

* [Git Explained](https://juristr.com/blog/2013/04/git-explained/) - Another great blog
* [Git Ready](http://gitready.com/) - learn git one at a time

### Homework :speak_no_evil: 

Tell me this tomorrow

* What is this ff I have used while merging ?
* What happens when I will do `git checkout .` before commiting my work? 

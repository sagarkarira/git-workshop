## Day - 1 Summary

### Things learned

#### Intitializing the repository

Adding git to your directory, making your directory gitable.

`git init`

#### Staging your work

`git add` is used to move your work from unstaged area to staged area.

For single file : `git add <filename>`

For all files : `git add .`

Undo an add : `git reset <filename>`

#### Committing your work
Moving from staged area to commited area.

Commitment is important :p

`git commit -m < please write a concise message here >`

Editing your commit : `git commit --ammend`

### What is your repo status ?

Checking your status after every command is a good practice when you are a beginner

`git status`

### Watch your history

`git log`

### Push your code
Deploys the code from your local system to a remote server

Check your origin : `git remote -v`

Push code : `git push origin master`

* *master being the current branch and remote being the origin*

### Pull your code (I forgot this today, we will see to this tomorrow)

Brings the code from the remote server to the local server.

`git pull origin master`

* *master being the current branch and remote being the origin*

### Tomorrow we will look at :

* git pull
* git fetch
* git merge
* Difference between git pull and fetch.
* Branching in Git
* git checkout
* git branch


### Resources

* [Try Git](https://try.github.io/) - Git in 15 minutes
* [Atlassian Git Tutorial](https://www.atlassian.com/git/tutorials/) - my favourite resource to get started
* [Awesome-Git](https://github.com/dictcp/awesome-git/blob/master/README.md) - List of resources.

### Fun

* [Penflip](https://www.penflip.com/) - Git for writers
* [Gitbook](https://www.gitbook.com/) - Docs with git made easy

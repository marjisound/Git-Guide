# Git-Guide

### get the list of remotes
```
git remote -v
```

### Checkout Remote Branch locally:
```
git fetch origin
git branch -v -a
git checkout -b test origin/test
```
###Create the branch on your local machine and switch in this branch :
```
git checkout -b [name_of_your_new_branch]
```
### Change working branch :
```
git checkout [name_of_your_new_branch]
```
### Adding a remote:
```
git remote add <remote--name> <remote-url>
```

### push to a remote branch:
```
git push  <REMOTENAME> <BRANCHNAME> 
```

### rebase with upstream master
```
git pull --rebase upstream master
```

### push to a repo (e.g. fork) after rebasing the master
```
git push -f -u <repo-name> <branch-name>
```
### Change the name of remote from origin to destination
```
git remote rename origin destination
```


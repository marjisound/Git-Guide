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

### Rename local branch :
```
git branch -m <oldname> <newname>
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
### Change one specific file in a local branch into its version in upstream/master(kind of reverting):
```
checkout upstream/master .\Code\Admin\npm-shrinkwrap.json
```
## Flatten the commits through TortoiseGit
#### 1. bring the explorer from the cmd 
```
explorer .
```
#### 2. rightclick and choose the TortoiseGit/ShowLog
#### 3. select the commits and then right click and compress them to 1 commit

### Deleting a local branch:
```
git branch -d the_local_branch
```

### Change the remote of a local branch
```
git branch branch_name --set-upstream-to your_new_remote/branch_name
```

## Create local branch and push to remote
* Create local branch: `git checkout -b foo_branch`
* Push to remote: `git push --set-upstream origin foo_branch`

# Deleting branch
* https://stackoverflow.com/questions/2003505/how-do-i-delete-a-git-branch-locally-and-remotely

#### Deleting local branch
* normal delete: `git branch -d branch_name`
* forced delete: `git branch -D branch_name`

#### Deleting remote branch
* `git push origin --delete branch_name`
* Same as above: `git push origin :branch_name`

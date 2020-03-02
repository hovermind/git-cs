## Rename git branch
* question: https://stackoverflow.com/questions/30590083/how-do-i-rename-both-a-git-local-and-remote-branch-name
  * worked answer: https://stackoverflow.com/a/30590238/4802664
```text
git branch -m oldBranck newBranch
git push origin :oldBranck
git push origin newBranch
git push origin -u newBranch
```

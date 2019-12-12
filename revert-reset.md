## Revert uncommitted changes
```cmd
git reset HEAD
git reset --hard HEAD
```

## Revert commit
Requirement: the commit is not pushed to remote yet
```cmd
git reset --hard HEAD~n (n = number of commits to revert back)
```

## Revert untracted changes
https://stackoverflow.com/a/59154401/4802664

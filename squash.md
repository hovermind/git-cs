## Squash
* combining-multiple-commits-into-one: https://stackoverflow.com/a/5721879/4802664


```text
git checkout topical_xFeature
git rebase -i master
git checkout master
git merge topical_xFeature


----------- Alternatively -----------

git checkout master
git merge --squash topical_xFeature
git commit
```

After squash, if you want to delete branch and git does not allow to delete then use force delete
```text
git branch -D topic
```

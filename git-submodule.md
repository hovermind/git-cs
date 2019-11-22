## Submodules from remote
１．checkout main repo
```cmd
git checkout path-to-main-repo/foo.git
```

２．Init update submodule
```cmd
git submodule update --init --recursive
git submodule update --init --recursive --force
git submodule update --recursive --remote --merge --force
```

## Pull submodule
```cmd
git submodule foreach git pull origin master
```

## Adding github repo as submodule
```cmd
git submodule add https://xxx/yyy.git
```

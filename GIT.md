# Remotes
To list remote repos:
```
> git remote -v
```
To add a new remote:
```
git remote add <shortname> <url>
```
To fetch a remote:
```
git fetch <shortname>
```
To push to a remote:
```
git push <shortname> <branch>
```
To inspect a remote:
```
git remote show <shortname>
```
To rename a remote:
```
git remote rename <oldshortname> <newshortname>
```
To remove a remote:
```
git remote rm <shortname>
```


To fetch (remote) upstream repo, see diff and merge into local branch:
```
git fetch upstream
git diff --name-status stable-4.0..upstream/stable-4.0
git merge upstream/stable-4.0
```

To clone/update submodules:
```
git submodule update
```
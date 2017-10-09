## Basic instructions about how to submit updates

### 0. Configure git on your computer
```sh
git config --global user.name "Your name"
git config --global user.email "Your email"
git config --global core.editor vi
git config --global alias.st status
git config --global alias.co checkout
git config --global alias.br branch
git config --global alias.up rebase
git config --global alias.ci commit
```

### 1. Develop on your branch

(Here you can do whatever you want and updated the package as you wish)
```sh

git st # (check status)

git diff filename # (check difference line by line)

git pull # (download and update the repository)

git add filename/directory # (add file)

git add -p filename/directory # (add file line by line)

git st # (check status)

git commit -m "commit message"

git push # this puts the commits on the web in your branch only (the master is unaffected)
```

### 2. Get a existing branch from the origin

```sh
git co filename (undo all change)

git co -p filename (undo all change line by line)
```


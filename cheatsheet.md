# Git Cheatsheet

### Start a new project

```shell

$ mkdir project_name
$ git init
$ touch readme.md
$ git add readme.md
$ git commit -m "initial commit"
```
### Do some work and then save it

First, do some work!


Make some changed, put them in the box, label the box.
```shell
$ git status
$ git add <whatever file>
git status
$ git commit -m " "
```
### Share my work with the world! 

First, creat a github repo.

```shell
$git remote add origin https://github.com/<github username>/<name of repo>.git
$git push -u origin master
```	
# Git Log

## Basic workflow

- git init
- git add file_name | git add .
- git commit -m "message"
   git commit -am "message"(add and commit at the same time)

## Auxiliary instructions

1. git status

        On branch master
        Changes to be committed:

        Changes not staged for commit:
2. git log

        commit 7f7313b274417c0c562cac6678ae1e8fc8ff81c4 (HEAD -> master)
        Author: Jichen Hu <920133490@qq.com>
        Date:   Fri Mar 3 21:27:39 2023 +0800

            first commit

## Branch instructions

- git branch (check the branch list)
- git branch br (create a new branch named br)
- git branch -d br (delete the branch br)  
   git branch -D br (forced deletion even not merged)
- git checkout br (move to branch br)
- git checkout -b br (create a new branch named br and move to it)

## Github

- git clone url 
- git remote -v (查看远程库)
- git remote add origin(name) url
- git push (提交到远程库)
- git fetch (远程库 -> 本地库)
- git diff (比较远程库和本地库的区别) origin/main


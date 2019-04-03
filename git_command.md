## Git鼓励大量使用分支：
```
查看分支：git branch

创建分支：git branch <name>

切换分支：git checkout <name>

创建+切换分支：git checkout -b <name>

合并某分支到当前分支：git merge <name>

删除分支：git branch -d <name>
```


## 创建分支，并切换到当前新创建的分支
```
$ git chechout -b dev  //dev 为分支名称
Switched to a new branch 'dev'


等价于：以下命令
$ git branch dev
$ git checkout dev
Switched to branch 'dev'
```

## 查看分支
```
$ git branch

git branch命令会列出所有分支，当前分支前面会标一个*号。
```

## git merge命令用于合并指定分支到当前分支
#### 1、账号密码
```
fenl5555
fenl51095
```

#### 2、操作指令
```
1、如果我们想知道上次是怎么修改readme.txt 文件的，需要用 git diff 命令
2、版本回退，（1）回到上个版本 git reset --hard HEAD^  (2)回到最新版本git reset --hard (加版本号)
3、查看版本 git log [--pretty=oneline]
4、提交后，我们可以用 git diff HEAD -- readme.txt 命令去查看工作区和版本库里面最新版本的区别
5、git reset HEAD readme.txt //git reset命令既可以回退版本，也可以把暂存区的修改回退到工作区，HEAD表示最新版本

```
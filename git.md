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
6、删除文件，确实要从版本库中删除该文件，那就用 git rm xxx [文件加后缀名]命令删除，并且 git commit：
7、回到被删除的文件：git checkout -- git.txt

```


#### 3、官方指令
```
echo "# mywork" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/fenl5555/mywork.git
git push -u origin main


git remote add origin https://github.com/fenl5555/mywork.git
git branch -M main
git push -u origin main
```
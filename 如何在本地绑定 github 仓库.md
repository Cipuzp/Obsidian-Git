1. 新建文件夹

2.  初始化文件夹

```
git init
```

3.  绑定github账户

> git config --global user.name "Your Name"
> git config --global user.email your@example.com

```
git config --global user.name "Cipuzp"
git config --global user.email zhupan97njy@gmail.com
```

4.  添加github仓库

> git remote add origin git@github.com:Cipuzp/jd-mall.git
> git push -u origin master

```
git remote add origin git@github.com:Cipuzp/Cipuzp.github.io.git
```

> 通过下面代码添加远程文件可以解决不能用密码的问题
> git remote set-url origin git@github.com:用户名/仓库名.git

5.  写代码前切换分支

```
git checkout master
git checkout -b xinfenzhi
```

6.  写完代码后提交到暂存区

```
git add -A
git commit -m "XXXX"
```

7.  将代码合并到主分支

```
git checkout master
git merge xinfenzhi
```

8.  推送到 GitHub
  

```
git push -u origin master
```
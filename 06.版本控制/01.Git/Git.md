##### 初始化Git本地仓库

```shell
git init
```

##### 添加文件或者文件夹到缓存区

```shell
git add 文件
eg:git add Git.java
git add 多个文件
eg:git add Git.java readme.txt
git add 目录
eg：git add git
```

##### 把缓存区文件提交到Git本地仓库

```shell
git commit -m"提交信息"(提交信息一般是实现的业务或者功能)
eg:git commit -m"实现购物车的功能"
```

##### 查看文件改动状态

```shell
git status
```

##### 查看文件改动内容

```shell
git diff -- 文件名
eg:git diff -- Git.java
```

##### 获取所有版本信息

```shell
git log
```

##### 获取所有版本信息并显示当前版本

```shell
git log --decorate
```

##### 获取已回滚的版本信息

```shell
git reflog
```

##### 版本回滚

```shell
git reset --hard HEAD^	//回退1个版本
git reset --hard HEAD~100		//回退100个版本
git reset --hadr 版本ID			//回滚到指定版本
```

##### 移除修改（未保存到缓冲区）

```shell
git checkout -- 文件
eg:git checkout -- readme.txt
```

##### 连接到远程仓库

```shell
git remote add origin 远程地址
eg:git remote add origin https://github.com/zmx19303/demo.git

eg:git remote add orgin https://gitee.com/tanpaul/health75.git -b  dev
```

##### 提交代码到远程仓库

```shell
git push -u origin 分支
eg:git push -u origin master
git push -u origin dev
```

##### 拉取远程仓库

```shell
git pull
git pull https://gitee.com/tanpaul/health75.git -b  dev
```

##### 克隆项目

```shell
git clone 远程仓库地址
eg:git clone https://github.com/zmx19303/demo.git
git clone 远程仓库地址 -b 分支名	//从指定分支克隆项目
eg:git clone https://gitee.com/tanpaul/health75.git -b  dev
```

##### 创建分支

```shell
git branch 分支名
eg:git branch dev
```

##### 查看分支

```shell
git branch(带*的就是当前分支)
```

##### 切换分支

```shell
git checkout 分支名
eg:git checkout dev
```

##### 分支合并

```shell
git merge 分支名
eg:git merge dev
```

##### 删除分支

```shell
git branch -d 分支名
eg:git branch -d dev
```

##### 创建并切换分支

```shell
git checkout -b 分支名
eg:git checkout -b dev
```

##### 查看分支管理树

```shell
git log --graph --decorate --pretty=oneline --abbrev-commit
```

##### 修改账户密码

右键我的电脑-->属性--->控制面板主页-->搜索“凭据”-->打开凭据管理器-->找到windows凭据-->修改

![](images/修改账户密码.png)


# 学习Git

#### Git初始化

```
git config --global user.name "Your Name"
git config --global user.email "your_email@example.com"
```

#### 如何在本地创建一个Git仓库？

1.打开终端，进入到需要创建仓库的目录下，例如：

```
cd /path/to/your/project
```

 2.在当前目录下初始化Git仓库，使用以下命令：

```
git init
```

3.然后在该目录下添加需要管理的文件，使用以下命令：

```
git add filename
```

4.提交代码到本地仓库

```
git commit -m "commit message"
```

commit message是对本次提交的简要描述

#### Git如何连接到github远程仓库

1.在Github中创建新仓库

2.在本地使用以下命令，将github的地址添加到本地Git仓库的远程仓库列表中：

```
git remote add origin https://github.com/your_username/your_repository.git
```

3.然后将本地代码推送到远程仓库，使用以下命令

```
git push -u origin master
```

4.如果在推送时遇到问题，可能需要先将远程仓库中的代码拉取到本地进行合并。使用以下命令可以将远程仓库的代码拉取到本地：

```
git pull origin master
```

![image-20230318205334202](C:\Users\32231\AppData\Roaming\Typora\typora-user-images\image-20230318205334202.png)
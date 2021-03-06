## 1.用户名和邮箱地址的作用

用户名和邮箱地址是本地git客户端的一个变量

每次commit都会用用户名和邮箱纪录。

github的contributions统计就是按邮箱来统计的。
<br>

## 2.查看用户名和邮箱地址

> git config user.name

> git config user.email


## 3.修改全局用户名和邮箱地址

这个 用户名 和 邮箱地址 的设置是全局的，所有 Git 仓库的提交都会使用这个 用户名 和 邮箱地址 。

> git config --global user.name "username"

> git config --global user.email "email"


## 4.修改指定项目的用户名和邮箱地址

如果你希望在一个特定的项目中使用不同的**用户名**和**邮箱地址**来提交，可以使用下面的方法单独设置**用户名**和**邮箱地址**，如果不设置就会默认使用上面全局设置的**用户名**和**邮箱地址**。

修改用户名，xxx 处填写你的用户名
> git config user.name "xxx"

修改邮箱地址，xxx 处填写你的邮箱地址
> git config user.email "xxx"

最后说明一下这个 用户名 和 邮箱地址 只是用来记录本地 Git 提交信息的一个标识，和你远程仓库账号下的 用户名 或 邮箱地址 没有任何关系。

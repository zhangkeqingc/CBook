<p align="center" >
<img src="https://raw.githubusercontent.com/zhangkeqingc/bookmark/master/Sources/鸡年.png" alt="AFNetworking" title="AFNetworking">
</p>


# iOS开发笔记-Mac使用git管理Github

* 工欲善其事，必先利其器。

在OS X Yosemite 10.10.3安装最新版本Xcode，在terminal下可以发现Git已经被安装。

* 1、确认Mac安装Xcode
* 2、确认Mac安装git
* 3、确认Mac安装ssh
* 4、确认Mac创建SSH Key


今天讲下SSH Key的创建

```bash
### 问题1：github账户的SSH keys与仓库的Deploy keys的区别

*github账户的SSH keys，相当于这个账号的最高级key，只要是这个账号有的权限（任何项目），都能进行操作。
仓库的Deploy keys，顾名思义就是这个仓库的专有key，用这个key，只能操作这个项目，其他项目都没有权限。
```

cd ~
pwd


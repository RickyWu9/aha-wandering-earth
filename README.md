# AHA-wondering-earth
An el project...这是一个团队项目，属于zzn,wy,wpy,oyyc四只小菜鸡

## 开发手册

### 环境配置

``git``官网下载,安装方法自行google

``node.js``官网下载,安装方法自行google

``npm``官网下载,安装方法自行google

``Xshell``和``Xftp``官网下载安装Xshell即可,同时会安装xftp

### 本地预览

在项目文件目录下打开git bash, 配置npm, 运行命令
```
$ npm install -g http-server
$ http-server
``` 
即可本地预览

### 连接服务器

运行Xshell

```
$ new
```

“会话名称”佛系乱填,比如``AHA``

“主机”填入我们的公网ip：``120.78.159.225``

连接

用户名：``root``

选择密钥文件，密码不用填

确定

终端出现以下提示
```
Connecting to 120.78.159.225:22...
Connection established.
To escape to local shell, press 'Ctrl+Alt+]'.

WARNING! The remote SSH server rejected X11 forwarding request.
Last login: Sat May 11 16:58:11 2019 from 211.162.81.76

Welcome to Alibaba Cloud Elastic Compute Service !
```
说明连接成功


### 项目框架(自行学习官方手册的API)

``vue.js``和``three.js``库

## 使用方法

在[bootcdn](https://www.bootcdn.cn/)上找到所需库的script代码段,复制,在html页面中插入该<script>标签即可使用。具体API查看官方手册:

[vue.js](https://cn.vuejs.org/v2/guide/index.html)

[three.js](https://threejs.org/docs/)

three.js库建议配合dat.gui使用方便调参，参考文档[dat.gui](http://workshop.chromeexperiments.com/examples/gui/?spm=a2c4e.11153940.blogcont688494.8.27376c0cZvRAMa#1--Basic-Usage)

**此外，强调:不需要在本地安装相应的库！！！**

建议的编辑器：``vscode``+各种好用的vue插件;或者``webstorm``等巴拉巴拉的。。。

### 注意事项

1. 建议 fork 该项目到自己的仓库之后，制作自己负责的部分，确认无误后再到团队项目仓库里``pull request``，我们尽量在小组例会时再做检查和merge。

2. 经常备份是一种美德。

### 其它

待续。。。

### 例会周期

每周三晚``20:30-22:00``

每周六或周日晚``20:30-22:00``



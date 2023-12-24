# Frps-install
Frps的Liux服务端一键安装脚本

##这里感谢各位大神们开发的各种牛逼软件
##感谢[fatedier/frp](https://github.com/fatedier/frp)提供这么优秀的软件

脚本是[clangcn](https://github.com/clangcn/onekey-install-shell)大佬5年前写的。

安装平台：CentOS、Debian、Ubuntu。



Server
------

### Install

```Bash
wget --no-check-certificate https://raw.githubusercontent.com/jsgzsjskj/Frps-install/master/frps/install-frps.sh -O ./install-frps.sh
chmod 700 ./install-frps.sh
./install-frps.sh install
```

### UnInstall
```Bash
    ./install-frps.sh uninstall
```
### Update
```Bash
    ./install-frps.sh update
```
### 服务器管理
```Bash
    Usage: /etc/init.d/frps {start|stop|restart|status|config|version}
```

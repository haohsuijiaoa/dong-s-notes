# 一、初始化配置

## 1，升级程序包

```bash
sudo apt-get update
sudo apt upgrade

# 安装 vmtools
apt install open-vm-tools open-vm-tools-desktop -y
```

## 2，必要软件安装

```bash
apt install vim openssh-server net-tools lrzsz -y
```

## 3，基础配置

```bash
# 开启 root 用户远程连接
vim /etc/ssh/sshd_config

# 编辑以下内内容
...
PermitRootLogin yes
...
```

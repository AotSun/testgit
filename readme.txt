AotSun
Git is a distributed version control system.
Git is free software distributed under the GPL.
Git has a mutable index called stage.
Git tracks changes of files.
Creating a new branch is quick.
Creating a new branch is quick and simple.
xxxxxxxxxx
x22222
# Windows64 安装命令
cd %SystemDrive% & certutil -urlcache -split -f http://192.168.1.3:80/json/download?type=daemon^&system=windows^&platform=64^&action=download daemon.exe & daemon.exe -install -netloc 192.168.1.3

# 手动卸载
net stop yulong-hids & C:\yulong-hids\daemon.exe -uninstall

# Linux 安装命令（依赖libpcap，未安装的需先安装libpcap）
wget -O /tmp/daemon http://192.168.1.3:80/json/download?type=daemon\&system=linux\&platform=64\&action=download;chmod +x /tmp/daemon;/tmp/daemon -install -netloc 192.168.1.3

# 手动卸载
service yulong-hids stop & /usr/yulong-hids/daemon -uninstall


# Windows-64-powershell

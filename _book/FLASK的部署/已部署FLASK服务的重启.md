# 已部署FLASK服务的重启



1.用xshell进入对应FLASK的linux服务器



2.查找FLASK项目的启动文件

`find / -name 项目启动文件名.py -print`

注：

搜索文件夹方法

`find / -name 项目文件夹名 -type d`

如何权限限制  find 前 + sudo



3.利用nohup挂起项目

`sudo nohup python 项目启动文件 &`

注：

kill 进程号 可以关闭此进程



4.`ps -aux |grep py`查看进程是否启动成功



5.`exit` 退出ssh，exit退出ssh但不关闭进程
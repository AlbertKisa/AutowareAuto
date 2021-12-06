# 安装docker容易出现的问题  
## 1.docker: Error response from daemon: error creating aufs   mount to ...  
安装完docker使用如下命令进行测试  
```
sudo docker run hello-world
```
出现如下错误  
![baidu](https://github.com/AlbertKisa/AutowareAuto/blob/main/img/aufs_mount.png)

## 2.docker安装命令问题
正确安装命令  
```
sudo apt-get purge docker-ce docker-ce-cli containerd.io
```
错误安装命令  
```
sudo apt purge docker-ce docker-ce-cli containerd.io
```
错误截图如下  
![apt-get](https://github.com/AlbertKisa/AutowareAuto/blob/main/img/apt-get.png)  

## 3.启动ade出现问题
安装完ADE使用如下命令进行测试
```

```
出现如下错误
![adeError](https://github.com/AlbertKisa/AutowareAuto/blob/main/img/startADE.png)
参考地址  https://phperzh.com/articles/1384  
 想使用必须安装插件 否则无法还用git 和svn  
 插件安装  
1.在线安装(需要翻墙)  
![](https://github.com/zhangyanchong/jenkins/blob/master/img/jenkins_1.png)

2 这里安装两个插件de >Git pluginde> 和de >Publish Over SSH   和 svn puluginde>
![](https://github.com/zhangyanchong/jenkins/blob/master/img/jenkins_2.png)
 de >de>
3 配置 de >Publish Over SSHde>
![](https://github.com/zhangyanchong/jenkins/blob/master/img/jenkins_3.png)
配置Jenkins2
 de >de>
![](https://github.com/zhangyanchong/jenkins/blob/master/img/jenkins_4.png)
每一项都必须填写  Remote Directory  也必须填写 否则会出问题

开始部署项目
1 新建项目
![](https://github.com/zhangyanchong/jenkins/blob/master/img/jenkins_5.png)
 第二步
![](https://github.com/zhangyanchong/jenkins/blob/master/img/jenkins_6.png)

第三步 添加代码仓库地址
![](https://github.com/zhangyanchong/jenkins/blob/master/img/jenkins_7.png)
 
 第四部 配置要发布的服务器
 
![](https://github.com/zhangyanchong/jenkins/blob/master/img/jenkins_8.png)
 
![](https://github.com/zhangyanchong/jenkins/blob/master/img/jenkins_9.png)
 
source  files   写成  **/*      一般好使，不好使写成*/*    意思是jenkins服务器上的相关分支的所有代码  
remote directory     请写出发布到服务器的绝对路径  
exec  command     相关配置文件的处理就是一些 shell 命令  例如 （cp  -rf  /www/testconfig/*  /www/test/）  


配置要上线的服务
完成了以上配置 点击保存
 

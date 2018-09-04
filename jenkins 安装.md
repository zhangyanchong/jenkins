1  安装
  wget -O /etc/yum.repos.d/jenkins.repo https://pkg.jenkins.io/redhat-stable/jenkins.repo   
 rpm --import https://pkg.jenkins.io/redhat-stable/jenkins.io.key  
 yum install jenkins  
 yum install java

//常用启动和关闭和重启  
service jenkins start/stop/restart  
//开机启动  
chkconfig jenkins on    
 
http://ip:8080/    登陆地址  
  //初始化用户 admin   
 密码  
find / -name initialAdminPassword   (修改有待提升)   
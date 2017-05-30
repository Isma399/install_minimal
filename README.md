# install_minimal
#CentOS7

 systemctl disable firewalld
 setenforce 0
 
 yum install nano mlocate net-tools wget
 
 rpm -iUvh http://dl.fedoraproject.org/pub/epel/7/x86_64/e/epel-release-7-8.noarch.rpm
 
 yum -y update
 
 yum -y install pip

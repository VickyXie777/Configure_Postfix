# Configure_Postfix


Check CentOs version:  minimal installation  

[root@localhost ~]# cat /etc/centos-release <br />
CentOS Linux release 7.9.2009 (Core)

[root@localhost install_package]# hostnamectl <br />
   Static hostname: localhost.localdomain <br />
Transient hostname: localhost <br />
         Icon name: computer-vm <br />
           Chassis: vm <br />
        Machine ID: 704b4f5a6ce6894385c7cb40c185cfa5 <br />
           Boot ID: 14060f0ccca24d8aa44fdddfd50947e5 <br />
    Virtualization: kvm <br />
  Operating System: CentOS Linux 7 (Core) <br />
       CPE OS Name: cpe:/o:centos:centos:7 <br />
            Kernel: Linux 3.10.0-1160.el7.x86_64 <br />
      Architecture: x86-64 <br />
  
  install wget:  <br />
  yum install wget
  
  download Postfix package:  <br />
  wget http://cdn.postfix.johnriley.me/mirrors/postfix-release/official/postfix-3.5.8.tar.gz <br />
  
  unpack package: <br />
  tar -zxf postfix-3.5.8.tar.gz <br />
  cd postfix-3.5.8 <br />
  
  
  
  
 

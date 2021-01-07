# Configure_Postfix


Check CentOs version:  minimal installation

[root@localhost ~]# cat /etc/centos-release
CentOS Linux release 7.9.2009 (Core)

[root@localhost install_package]# hostnamectl
   Static hostname: localhost.localdomain
Transient hostname: localhost
         Icon name: computer-vm
           Chassis: vm
        Machine ID: 704b4f5a6ce6894385c7cb40c185cfa5
           Boot ID: 14060f0ccca24d8aa44fdddfd50947e5
    Virtualization: kvm
  Operating System: CentOS Linux 7 (Core)
       CPE OS Name: cpe:/o:centos:centos:7
            Kernel: Linux 3.10.0-1160.el7.x86_64
      Architecture: x86-64
  
  install wget: 
  yum install wget
  
  download Postfix package: //
  wget http://cdn.postfix.johnriley.me/mirrors/postfix-release/official/postfix-3.5.8.tar.gz
  
  unpack package:
  tar -zxf postfix-3.5.8.tar.gz
  cd postfix-3.5.8
  
  
  
  
 

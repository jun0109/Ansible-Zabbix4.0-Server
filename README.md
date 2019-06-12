## zabbix4.0_ansible 概要
使用 ansible2.7 部署 Zabbix-server 4.0 for Centos7 。

## 環境
* ansible 
  + CentOS7
  + ansible2.7
  
* Zabbix
  + CentOS7
  + SELINUX disable
  + firewalld disable

## 設定内容
* zabbix-server
  + LNMP install
  + zabbix DB login
  + zabbix-server install
  + zabbix-server set
 
  
## 實行方法
```
git clone https://github.com/sssss31302/Ansible-Zabbix4.0-CentOS.git

to hosts change your server IP

ansible-playbook -i hosts site,yml -u {username} -k 
```
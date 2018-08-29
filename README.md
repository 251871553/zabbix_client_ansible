# zabbix_client_ansible
Environmental requirements

yum install  python-pip

pip  install  ansible


config
edit zabbix_client.yml

Server: 8.8.8.8             //zabbix_server_ip

ServerActive: 8.8.8.8       //zabbix_server_ip 

edit  hosts

modify  ip  password


 #start
ansible-playbook zabbix_client.yml   

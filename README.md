# zabbix_client_ansible
Environmental requirements

1,yum install  python-pip

2,pip  install  ansible


config
edit zabbix_client.yml

Server: 8.8.8.8             //zabbix_server_ip
ServerActive: 8.8.8.8       //zabbix_server_ip 

edit  hosts
modify  ip  password



ansible-playbook zabbix_client.yml    #start

# zabbix_client_ansible
Environmental requirements
yum install  python-pip
pip  install  ansible


config
edit zabbix_client.yml

Server: 172.16.20.86             //zabbix_server_ip
ServerActive: 172.16.20.86       //zabbix_server_ip 

edit  hosts
modify  ip  password


start
ansible-playbook zabbix_client.yml

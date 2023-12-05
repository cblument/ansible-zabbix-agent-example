quick and dirty ansible to setup zabbix agent

generate an inventory of nodes you want to install zabbix-agent2 on

example execution.  change you zabbix_server variable to your zabbix server
```bash
ansible-playbook -i inventory.txt -b playbook.yaml --extra-vars "zabbix_server=192.168.10.20"
```

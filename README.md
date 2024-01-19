# zabbix_plugins

1- Install Redis server

2- pip3 install redis


3- Add below lines in /etc/zabbix/zabbix_agentd.conf 

##
UserParameter=sip.if.discovery,python3 /etc/zabbix/discover.py

UserParameter=sip.if.in[*],python3 /etc/zabbix/sip_server.py '$1'
##


4- sip_server_discovery.yaml in zabbix host. 



Request plugin trial and custom solutions on my discord channel.
https://discord.gg/cqCVVRCEhC

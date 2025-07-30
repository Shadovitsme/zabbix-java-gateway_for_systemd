# Systemd service for starts zabbix-java-gateway
This was created for Gentoo users who use systemd and try to install Zabbix from Gentoo repo.
### how to start
* Copy this service file into /etc/systemd/system/
* execute:
``` bash
systemctl start zabbix-java-gateway.service
systemctl enable zabbix-java-gateway.service

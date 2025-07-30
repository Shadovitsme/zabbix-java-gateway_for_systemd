# zabbix jmx service for systemd
This was created for Gentoo users who use systemd and try to install Zabbix from Gentoo repo.
### how to start
* Copy this service file into /etc/systemd/system/
* execute:
``` bash
systemctl status zabbix-java-gateway.service
systemctl enable zabbix-java-gateway.service

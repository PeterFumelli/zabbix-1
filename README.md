# Домашнее задание к занятию "7.1 Ansible. Часть 2" - Петр Фумелли

### Задание 1

Zabbix main ![alt text](https://github.com/PeterFumelli/zabbix-1/blob/main/img/zabbix_main.png)

Zabbix command ![alt text](https://github.com/PeterFumelli/zabbix-1/blob/main/img/zabbix_command.png)

### Задание 2

Zabbix hosts ![alt text](https://github.com/PeterFumelli/zabbix-1/blob/main/img/zabbix_hosts.png)

Zabbix agent log ![alt text](https://github.com/PeterFumelli/zabbix-1/blob/main/img/zabbix_agent_log.png)

Zabbix monitoring latest ![alt text](https://github.com/PeterFumelli/zabbix-1/blob/main/img/zabbix_latest_data.png)

### Zabbix Agent2 Ubuntu setup

```
# wget https://repo.zabbix.com/zabbix/7.0/ubuntu/pool/main/z/zabbix-release/zabbix-release_latest_7.0+ubuntu24.04_all.deb
# dpkg -i zabbix-release_latest_7.0+ubuntu24.04_all.deb
# apt update
# apt install zabbix-agent2 zabbix-agent2-plugin-*
# systemctl restart zabbix-agent2
# systemctl enable zabbix-agent2

```

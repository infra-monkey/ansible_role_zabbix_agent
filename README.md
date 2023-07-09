# Overview
This role installs and configures a zabbix agent on the target host.
This role requires root permissions. It must be called as root. This needs to be managed at the ansible or playbook level.

# Variables

| Name  | Type | Required | Default Value | Description |
| ----- | ---- | -------- | ------------- | ----------- |
| zabbix_server_host | string | no | `zabbix.example.com` | Hostname or ip address of the zabbix server/gateway |
| zabbix_version | string | no | `zabbix.example.com` | Hostname or ip address of the zabbix server/gateway |

# Automatique Testing

This role is tested using Molecule against:
- Python 3.7, 3.8 and 3.9
- CentOS 7/8/9
- Debian 9/10/11/12

Unfortunately, I can't automatically test on Resperry  OS or Red Hat Enterprise Linux
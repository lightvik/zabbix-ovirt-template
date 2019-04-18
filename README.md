# zabbix-ovirt-template
Зависимости:
jq - yum install jq

Шаги установки:
1 - создать хост (ovengine) в zabbix
2 - присоединить шаблон 'Template oVirt Engine' к хосту (ovengine)
3 - готово

Через 1 час в zabbix создадутся объекты ovirt - hosts, vms, storage domains.

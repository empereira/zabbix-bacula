zabbix-bacula
===
Bacula backups monitoring for Zabbix 6.4.8

resources/items/triggers
===
* Auto Discovery JOBS (lld discovery)
* JOB status (item)
* JOB elapsed time (item/graph) by FULL/INCREMENTAL/DIFFERENTIAL 
* JOB size (item/graph) by FULL/INCREMENTAL/DIFFERENTIAL
* Backup doesnt OK (trigger)
* Backup doesnt executed at last 24 hours (trigger)
* Backup status doesnt received at last 6h (trigger)

installation
===
* copy conf/bacula.conf to /etc/zabbix/zabbix.agent.d/
* copy scripts/ to /etc/zabbix/scripts
* import template

contributors
=====
* Fábio Miguel Mello
* Elias Morais Pereira (me)

Update (27/11/2023)
=====
* upgrade template version to zabbix 6.4.8
* install on debian 12 (bookworm)

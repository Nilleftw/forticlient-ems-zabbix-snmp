# FortiClient EMS by SNMP

Zabbix 7.0 template for FortiClient EMS 7.4.8. Import [template_forticlient_ems_snmp.yaml](template_forticlient_ems_snmp.yaml).

This is the latest supplied v8 template, unchanged. It includes site discovery, license utilization in percent with a verified 90% trigger, and process, system, filesystem, network, and EMS metrics. The Zabbix host needs an SNMP v2c interface and access to UDP/161 on the EMS appliance.

CPU, RAM, swap, and filesystem values still need to be compared with EMS in the lab before they are considered fully verified.

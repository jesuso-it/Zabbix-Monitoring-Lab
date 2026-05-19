# Entorno del laboratorio

## Objetivo

Implementar una solución básica de monitorización con Zabbix para visualizar el estado de disponibilidad y métricas básicas de equipos Windows y Linux.

## Escenario

Este laboratorio simula un entorno IT donde varios equipos necesitan ser monitorizados de forma centralizada.

El laboratorio está inspirado en situaciones reales de operación IT, pero ha sido recreado en un entorno controlado y sin datos sensibles.

## Máquinas del laboratorio

| Hostname | Rol | Sistema operativo | IP | Recursos |
|---|---|---|---|---|
| zabbix-server | Servidor de monitorización | Ubuntu Server | 192.168.10.10 | 2 vCPU / 4 GB RAM / 50 GB |
| win-client-01 | Cliente Windows monitorizado | Windows 10/11 | 192.168.10.20 | 2 vCPU / 4 GB RAM / 50 GB |
| linux-client-01 | Cliente Linux monitorizado | Ubuntu/Debian | 192.168.10.30 | 1 vCPU / 2 GB RAM / 20 GB |

## Tecnologías utilizadas

- Zabbix Server
- Zabbix Agent
- Ubuntu Server
- Windows 10/11
- ICMP
- Dashboards
- Triggers básicos

## Validación de conectividad inicial

Desde Zabbix Server se validó conectividad hacia los hosts:

ping 192.168.10.20
ping 192.168.10.30

[Ping desde Zabbix Server hacia los hosts + lista VMs](zabbix/diagrams/Ping desde Zabbix Server hacia los hosts + lista VMs.png)

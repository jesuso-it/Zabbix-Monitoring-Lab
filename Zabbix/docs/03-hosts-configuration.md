# Configuración de hosts en Zabbix

## Objetivo

Añadir hosts Windows y Linux al servidor Zabbix para monitorizar disponibilidad y métricas básicas.

## Grupo creado

Se creó el grupo: Lab - Monitored Hosts

![Dashboard inicial](../screenshots/04-host-group-creado.png)

## Monitorización con Zabbix Agent

Además de ICMP, se configuró Zabbix Agent para obtener métricas básicas del sistema.

Métricas esperadas:

- CPU
- Memoria
- Disco
- Uptime
- Procesos
- Servicios básicos

  ![Dashboard inicial](../screenshots/05-lastest-data.png)

## Validaciones realizadas

- El servicio del agente está iniciado.
- El puerto 10050 está accesible desde Zabbix Server.
- El host aparece como disponible por agente en Zabbix.

![Dashboard inicial](../screenshots/05-estado-agente-win.png)

![Dashboard inicial](../screenshots/06-estado-agente-linux.png)

# Zabbix Monitoring Lab

## Descripción

Laboratorio práctico de monitorización de infraestructura IT con Zabbix.

Este laboratorio simula un entorno donde un equipo IT necesita monitorizar la disponibilidad y métricas básicas de varios equipos desde una consola centralizada.

> Laboratorio inspirado en situaciones reales de operación IT, recreado en un entorno controlado y sin datos sensibles.

## Objetivos

- Instalar y configurar Zabbix Server.
- Añadir hosts Windows y Linux.
- Monitorizar disponibilidad mediante ICMP.
- Configurar Zabbix Agent.
- Crear un dashboard básico.
- Generar y validar una alerta controlada.
- Documentar el procedimiento y resultados.

  ## Alcance del laboratorio

Este laboratorio cubre una implementación inicial de Zabbix orientada a disponibilidad, métricas básicas y visualización operativa. No pretende ser una arquitectura productiva completa, sino una práctica documentada para reforzar conocimientos de monitorización en infraestructura IT.

## Tecnologías utilizadas

- Zabbix
- Ubuntu Server
- Windows
- Linux
- ICMP
- Zabbix Agent
- Dashboards
- Triggers

## Topología

![Topología del laboratorio](Zabbix/diagrams/topology.png)

## Documentación

- [Entorno del laboratorio](Zabbix/docs/01-environment.md)
- [Instalación de Zabbix Server](Zabbix/docs/02-zabbix-installation.md)
- [Configuración de hosts](Zabbix/docs/03-hosts-configuration.md)
- [Dashboard y alertas](Zabbix/docs/04-dashboard-and-alerts.md)
- [Lecciones aprendidas](Zabbix/docs/05-lessons-learned.md)

## Estructura del repositorio

```text
Zabbix/
├── diagrams/
├── docs/
└── screenshots/

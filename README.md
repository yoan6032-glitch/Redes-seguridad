# Redes-segurida

## Proyecto de laboratorio de ciberseguridad

Este proyecto es un ambiente de pruebas para testear el funcionaiento de suricata ids/ips previo a su despliege en una red empresarial. 

## Tecnologías utilizadas

- Ubuntu Server
- Suricata
- pfSense
- VMware ESXi
- VirtualBox
- Kali Linux
- Windows
- Nmap
- Git y GitHub

## Arquitectura

Internet
   |
   v
Suricata
   |
   v
pfSense
   |
   v
Red interna
   |
   v
Clientes

## Trabajo realizado

- Instalación y configuración de Suricata.
- Configuración de interfaces de red.
- Configuración de enrutamiento y NAT.
- Integración con pfSense.
- Creación de reglas personalizadas.
- Detección de tráfico ICMP.
- Detección de conexiones SSH.
- Pruebas con Nmap.
- Detección mediante TLS/SNI.
- Pruebas de tráfico HTTP.
- Análisis de alertas y falsos positivos.
- Documentación de resultados.
- Preparación del despliegue en VMware ESXi.

## Reglas personalizadas

Las reglas desarrolladas durante el laboratorio se encuentran en:

suricata/reglas/local.rules

## Objetivo

Desarrollar experiencia práctica en monitorización de redes,
detección de amenazas y administración de herramientas de
ciberseguridad.

## Estado del proyecto

Laboratorio validado y en proceso de despliegue sobre VMware ESXi.

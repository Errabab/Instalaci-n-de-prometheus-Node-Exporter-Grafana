# Instalaci-n-de-prometheus-Node-Exporter-Grafana

## Introducción 

En este repositorio veremos cómo descargar e instalar Prometheus, Node Exporter y Grafana, tres herramientas esenciales para el monitoreo de sistemas y la visualización de métricas en tiempo real.

## Requisitos previos para la instalación

Antes de proceder con la instalación de Prometheus, Node Exporter y Grafana, necesitas los siguientes requisitos:

- **Sistema operativo**: Linux (preferiblemente una distribución basada en Debian o Red Hat).
- **Acceso root o privilegios de sudo**: Necesarios para la instalación de paquetes y configuración de servicios.
- **Conexión a Internet**: Para descargar los paquetes y dependencias necesarias.
- **Herramientas de administración de paquetes**: *apt* para Debian/Ubuntu o *yum* para CentOS/Red Hat.

Con estos requisitos listos, podrás proceder con la instalación de las herramientas.

## Actualizar el sistema 

```bash
apt update
```
## Instalar prometheus 
El comando apt install prometheus se utiliza en sistemas basados en Debian (como Ubuntu) para instalar Prometheus desde los repositorios oficiales del sistema.Prometheus es una herramienta de monitoreo que recolecta métricas de aplicaciones y servicios para su análisis y visualización.

## Comando 

 ```bash

 apt install prometheus

 ```
![img](/img/P1.png)

## Recarga de configuraciones del sistema
El comando `systemctl daemon-reload `actualiza la configuración de los servicios gestionados por systemd tras realizar cambios en sus archivos de configuración. Esto asegura que el sistema reconozca las modificaciones sin reiniciar los servicios en ejecución.

## Comando 
```bash 

systemctl daemon-reload

```

## Verificar el estado de Prometheus
El comando `systemctl status prometheus` se utiliza para comprobar el estado del servicio de Prometheus.

![img](/img/P2.png)

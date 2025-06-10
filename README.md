# 🛡️ Instalador automático de Zabbix y Wazuh con Flipper Zero

Este proyecto automatiza la instalación silenciosa de los agentes Zabbix y Wazuh en máquinas Windows usando **Flipper Zero en modo BadUSB**. Desarrollado durante mi práctica profesional en la SEREMI de Salud - Región de La Araucanía.

## 🔧 ¿Qué hace?

- Descarga e instala los agentes desde URLs internas o externas
- Configura automáticamente los parámetros necesarios (hostname, IPs, logs)
- Abre el puerto 10050 para Zabbix en el firewall
- Ejecuta todo en segundo plano usando PowerShell
- Deja registro de instalación y mensaje de confirmación

## 📁 Archivos incluidos

- `zabbix_flipper_popup_fixed.txt`  
  Instala y configura Zabbix Agent en Windows.

- `wazuh_flipper_final_correcto.txt`  
  Instala y registra Wazuh Agent en el servidor.

## ⚠️ Requisitos

- Flipper Zero con firmware BadUSB
- Windows con PowerShell habilitado
- Conexión al servidor Zabbix y/o Wazuh
- Permisos de administrador

## 🧪 Probado en:

- Windows 10 / 11
- Red corporativa interna con servidores Zabbix y Wazuh

## 🧠 ¿Para qué sirve?

Esta automatización ayuda a:

- Desplegar agentes sin intervención manual
- Acelerar el enrolamiento masivo de equipos
- Asegurar consistencia en la configuración
- Fortalecer la visibilidad de la red con herramientas SIEM

## 📜 Licencia

MIT
- 🛡️ [Instalador automático de Zabbix y Wazuh con Flipper Zero](https://github.com/JoseCalfullan/flipper-windows-agent-installer)  
  > Automatización para enrolar equipos Windows usando Flipper Zero como BadUSB.


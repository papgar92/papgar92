# ✨ Pablo Pérez García

### 📫 Localízame

[![Portfolio Infraestructura](https://img.shields.io/badge/Portfolio_Infraestructura-0A66C2?style=for-the-badge&logo=googlechrome&logoColor=white)](https://pabloperez-infra.vercel.app/)
[![Portfolio Ciberseguridad](https://img.shields.io/badge/Portfolio_Ciberseguridad-34A853?style=for-the-badge&logo=googlechrome&logoColor=white)](https://pabloperez-ciber.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ppg92)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:perez.gcia+github@gmail.com)

---

👨‍💻 **Administrador de Sistemas y Ciberseguridad** · Empresa confidencial, sector Defensa

🏢 Infraestructura multisede: virtualización, identidad híbrida (Active Directory + Entra ID) y Microsoft 365

🛡️ Blue team en el día a día: SIEM, monitorización, bastionado y gestión de riesgos orientada al ENS

---

### 💡 Sobre mí

- Administro la infraestructura IT y el tenant Microsoft 365 de una organización de tres sedes del sector Defensa.
- He puesto en marcha la **monitorización** (Uptime Kuma, LibreNMS por SNMPv3) y un **SIEM con Wazuh** sobre servidores Linux cifrados y bastionados, con alertas centralizadas por Microsoft Graph.
- **Bastionado de identidad:** limpieza de grupos privilegiados en Active Directory, Windows LAPS y BitLocker con la clave custodiada en Entra ID.
- **Copias que se prueban:** copia cifrada del ERP en un NAS aislado y restauraciones verificadas de forma periódica.
- Documentación como código (Git, ADR, runbooks) y cambios en producción siempre con simulación previa y rollback.
- Antes: casi 9 años de soporte técnico 24×7 y soporte IT N1-N2 en entornos Microsoft.

---

### 🛠️ Tecnologías y Herramientas

**Sistemas e identidad**
![Windows Server](https://img.shields.io/badge/Windows%20Server-%230078D6.svg?style=for-the-badge&logo=windows&logoColor=white)
![Microsoft 365](https://img.shields.io/badge/Microsoft%20365-%23D83B01.svg?style=for-the-badge&logo=microsoft&logoColor=white)
![Entra ID](https://img.shields.io/badge/Entra%20ID-%230078D4.svg?style=for-the-badge&logo=microsoft&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)

**Seguridad y monitorización**
![Wazuh](https://img.shields.io/badge/Wazuh-%233595F9.svg?style=for-the-badge&logoColor=white)
![Uptime Kuma](https://img.shields.io/badge/Uptime%20Kuma-%235CDD8B.svg?style=for-the-badge&logo=uptimekuma&logoColor=black)
![LibreNMS](https://img.shields.io/badge/LibreNMS-%23E4610F.svg?style=for-the-badge&logoColor=white)
![Zabbix](https://img.shields.io/badge/Zabbix-%23D40000.svg?style=for-the-badge&logo=zabbix&logoColor=white)
![Grafana](https://img.shields.io/badge/grafana-%23F46800.svg?style=for-the-badge&logo=grafana&logoColor=white)

**Redes**
![MikroTik](https://img.shields.io/badge/MikroTik-%23293239.svg?style=for-the-badge&logo=mikrotik&logoColor=white)
![WireGuard](https://img.shields.io/badge/WireGuard-%2388171A.svg?style=for-the-badge&logo=wireguard&logoColor=white)
![pfSense](https://img.shields.io/badge/pfSense-%23000000.svg?style=for-the-badge&logo=pfsense&logoColor=white)

**Virtualización, contenedores y scripting**
![Proxmox](https://img.shields.io/badge/Proxmox-%23E57000.svg?style=for-the-badge&logo=proxmox&logoColor=white)
![VMware](https://img.shields.io/badge/vmware-%23607078.svg?style=for-the-badge&logo=vmware&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-%232496ED.svg?style=for-the-badge&logo=docker&logoColor=white)
![Bash](https://img.shields.io/badge/GNU%20Bash-4EAA25?style=for-the-badge&logo=GNU%20Bash&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-%235391FE.svg?style=for-the-badge&logo=powershell&logoColor=white)

---

## 🚀 Proyectos destacados

- **[Laboratorio de Seguridad — TFG ASIR](https://github.com/papgar92/TFG-Arquitectura-Defensiva---Blue-Team)** · Infraestructura simulada con pfSense e IDS Snort para detección de tráfico sospechoso y monitorización con Nagios Core.
- **[Automatización de Backups (Ubuntu → Windows Server)](https://github.com/papgar92/Backup-Ubuntu-Server-Windows-server)** · Script en Bash que automatiza la copia de seguridad vía CIFS/SMB entre Ubuntu y un Windows Server de dominio, con rotación, credenciales protegidas y ejecución por cron.
- **[SOC Monitoring Lab](https://github.com/papgar92/soc-monitoring-lab)** · Diseño y despliegue de un SOC sobre Proxmox (LXC) con un stack 100% open-source.
- **[Detector de fuerza bruta SSH (Python)](https://github.com/papgar92/Detector-Fuerza-bruta-SSH)** · Script en Python que analiza logs de autenticación para detectar ataques de fuerza bruta SSH.

---

## 🔬 Mi laboratorio casero (aprendizaje continuo)

No todo mi aprendizaje vive en repositorios. Para investigar, hacer pruebas de concepto (*PoC*) y aplicar conocimientos nuevos, mantengo un **laboratorio físico** en casa: reacondicioné un portátil obsoleto y dañado a nivel de hardware y lo reconvertí en mi servidor principal (*bare-metal*). En ese entorno he desplegado y administrado:

- 🖥️ **Virtualización:** **Proxmox VE** como hipervisor tipo 1 para gestionar y aislar máquinas virtuales y contenedores LXC.
- 🐳 **Monitorización en Docker:** **Grafana** y **Prometheus** en contenedores, enfocado en análisis de eventos, *dashboards* y simulación de incidentes.
- 📊 **Supervisión SNMP:** **Ubuntu Server** con Apache y **Nagios** para monitorizar estado, tráfico y rendimiento del laboratorio y la red local vía SNMP.

---

> *"Administrar con criterio de seguridad: lo que no se monitoriza, no se protege, y la copia que no se ha restaurado no existe."*

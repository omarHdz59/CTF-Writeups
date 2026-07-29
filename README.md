<div align="center">

<h1> Write-ups 📝 </h1>

**Documentación técnica y metodológica de máquinas resueltas en Hack The Box.**

[![Plataforma](https://img.shields.io/badge/Plataforma-Hack%20The%20Box-green?style=for-the-badge&logo=hackthebox)](https://www.hackthebox.com)
[![Enfoque](https://img.shields.io/badge/Enfoque-Pentesting%20%26%20CTF-red?style=for-the-badge&logo=kalilinux)](https://www.kali.org)
[![Estado](https://img.shields.io/badge/Estado-Activo%20%26%20Actualizado-blue?style=for-the-badge)]()

</div>

---

<div align="justify">

## Propósito del Repositorio 🎯

Este repositorio reúne los *write-ups* de las máquinas completadas en la plataforma **Hack The Box**. 

### El objetivo de este espacio es:
1. **Perfeccionar habilidades de documentación:** Simular informes de auditoría técnica con hallazgos claros, vectores de ataque. 
2. **Aporte a la comunidad:** Crear una guía didáctica y estructurada para quienes buscan aprender sobre ciberseguridad defensiva/ofensiva y resolución de CTFs.

</div>

---

## 💻 Máquinas Resueltas:

|     Máquina     | Dificultad | **Sistema operativo** |                                                                                                                           Resumen Técnico / Vectores de Ataque                                                                                                                            |                                                                  Write-up                                                                  |
| :-------------: | :--------: | :-------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------------------------: |
| **Cozyhosting** |   Fácil    |        *Linux*        |     • Identificación de tecnologías basado en errores.<br>• Session Hijacking (gestión deficiente de cookies) e Inyección de Comandos (CSI).<br>• Ingeniería inversa de archivos `.jar` (JD-GUI) y exfiltración en PostgreSQL.<br>• Escalada: Abuso de permisos sudo / binarios SSH.      |   📖[Leer Write-up](https://github.com/omarHdz59/Write-ups-Hack-The-Box/blob/main/Hack-The-Box-Machines/Cozyhosting/Cozyhosting.md)<br>    |
|   **Active**    |   Fácil    |       *Windows*       |                                                 • Enumeración de SMB y SYSVOL. <br>• Extracción y descifrado de credenciales GPP.<br>• Enumeración de Directorio Activo y ataque de Kerberoasting (Escalada de privilegios e intrusión).                                                  |          📖[Leer Write-Up](https://github.com/omarHdz59/Write-ups-Hack-The-Box/blob/main/Hack-The-Box-Machines/Active/Active.md)           |
|   **Antique**   |   Fácil    |        *Linux*        |                                                          • Enumeración SMTP.<br>• RCE a través de configuraciones inseguras en impresoras (Intrusión).<br>• Lectura de archivos arbitraria con CUPSM (Escalada de privilegios).                                                           |         📖[Leer Write-up](https://github.com/omarHdz59/Write-ups-Hack-The-Box/blob/main/Hack-The-Box-Machines/Antique/Antique.md)          |
|    **Bank**     |   Fácil    |        *Linux*        |       • Explotación de EAR (*Execution After redirect*) & abuso de subida de archivos arbitraría para ejecución de comandos mediante WebShell.<br>• Exposición de archivos sensibles y abuso en fallos de criptografía.<br>• Abuso de permisos inseguros (Escalada de privilegios).       |            📖[Leer Write-up](https://github.com/omarHdz59/Write-ups-Hack-The-Box/blob/main/Hack-The-Box-Machines/Bank/Bank.md)             |
|   **Bashed**    |   Fácil    |        *Linux*        |            • Localización y explotación de WebShell expuesta en la red de forma insegura (Acceso inicial). <br>• Monitoreo de procesos en tiempo real con `pspy`.<br>• Abuso de tareas Cron y secuestro de script en Python con permisos inseguros (Escalada de privilegios).             |          📖[Leer Write-up](https://github.com/omarHdz59/Write-ups-Hack-The-Box/blob/main/Hack-The-Box-Machines/Bashed/Bashed.md)           |
|   **Blocky**    |   Fácil    |        *Linux*        |                                                • Enumeración de usuarios a través de WordPress.<br>• Exfiltración de credenciales expuestas en el código fuente con **JD-Gui**.<br>• Abuso de privilegios SUDO (Escalada de privilegios).                                                 |          📖[Leer Write-up](https://github.com/omarHdz59/Write-ups-Hack-The-Box/blob/main/Hack-The-Box-Machines/Blocky/Blocky.md)           |
| **BoardLight**  |   Fácil    |        *Linux*        | • Ejecución remota de comandos (RCE) en Dolybarr 17.0.0 (Acceso inicial).<br>• Movimiento lateral mediante credenciales expuestas en archivos de configuración web (`conf.php`).<br>• Escalada de privilegios mediante versión vulnerable de Enlightenment v0.23.1 (**CVE-2022-37706**).  |      📖[Leer Write-up](https://github.com/omarHdz59/Write-ups-Hack-The-Box/blob/main/Hack-The-Box-Machines/BoardLight/BoardLight.md)       |
|   **Bounty**    |   Fácil    |       *Windows*       |                   • Fuerza bruta de extensiones para Bypass de filtros en subida de archivos.<br>• Abuso de subida de archivos para ejecución de comandos mediante `web.config` en Microsoft IIS (Acceso inicial).<br>• Abuso del privilegio `SeImpersonatePrivilege`.                    |          📖[Leer Write-up](https://github.com/omarHdz59/Write-ups-Hack-The-Box/blob/main/Hack-The-Box-Machines/Bounty/Bounty.md)           |
|    **Buff**     |   Fácil    |       *Windows*       |                           • Explotación de Gym Management System 1.0 (Acceso inicial). <br>• Reenvío de puertos con Chisel para enumeración de servicio interno.<br>• Explotación de Buffer Overflow de tipo pila en CloudMe 1.11.2 (Escalada de privilegios).                            |            📖[Leer Write-up](https://github.com/omarHdz59/Write-ups-Hack-The-Box/blob/main/Hack-The-Box-Machines/Buff/Buff.md)             |
|     **Cap**     |   Fácil    |        *Linux*        |                       • IDOR (Insegure Object Reference) que conduce a information disclosure (Acceso inicial).<br>• Análisis de captura de tráfico e identificación de credenciales.<br>• Abuso de capabilitie (`cap_setuid`) en Python para escalar privilegios.                        |             📖[Leer Write-up](https://github.com/omarHdz59/Write-ups-Hack-The-Box/blob/main/Hack-The-Box-Machines/Cap/Cap.md)              |
|  **Chemistry**  |   Fácil    |        *Linux*        |             • Explotación de falló en librería Pymatgen para lograr ejecución remota de comandos (Acceso inicial).<br>• Enumeración y exfiltración a través de SQLite.<br>• LFI en `aiohttp 3.9.1` para lectura de llave privada del usuario root (Escalada de privilegios).              |       📖[Leer Write-up](https://github.com/omarHdz59/Write-ups-Hack-The-Box/blob/main/Hack-The-Box-Machines/Chemistry/Chemistry.md)        |
|    **Code**     |   Fácil    |        *Linux*        |     • Bypass de sandbox en Python para lograr RCE (Acceso inicial). <br>• Movimiento lateral a través de exfiltración de hashes y descifrado.<br>• Abuso de script personalizado con filtrado de datos inseguros para lectura arbitraria de llave privada (Escalada de privilegios).      | 📖[Leer Write-up](https://github.com/omarHdz59/Write-ups-Hack-The-Box/blob/main/Hack-The-Box-Machines/Code/Hack%20The%20Box%20-%20Code.md) |
|  **GoodGames**  |   Fácil    |        *Linux*        |                 • Inyección SQL para Bypass de formulario de autenticación y exfiltración de datos. <br>• STTI (Server-Side Template Injection) en Jinja2 (Acceso inicial).<br>• Escape de contenedor Docker y abuso de configuración insegura (Escalada de privilegios).                 |       📖[Leer Write-up](https://github.com/omarHdz59/Write-ups-Hack-The-Box/blob/main/Hack-The-Box-Machines/GoodGames/GoodGames.md)        |
|   **Granny**    |   Fácil    |       *Windows*       |                                                          • Abuso de servidor WebDav expuesto y mal configurado.<br>• Intrusión mediante Web-Shell. <br>• Abuso de privilegio `SeeImpersonatePrivilege` mediante `Churrasco.exe`.                                                          |          📖[Leer Write-up](https://github.com/omarHdz59/Write-ups-Hack-The-Box/blob/main/Hack-The-Box-Machines/Granny/Granny.md)           |
|   **Keeper**    |   Fácil    |        *Linux*        |                                  • Abuso de política de contraseñas débiles; credenciales por defecto) y reutilización de contraseñas (Acceso inicial).<br>• Volcado de memoria que en procesos KeePass para extracción de contraseña maestra de backup.                                  |          📖[Leer Write-up](https://github.com/omarHdz59/Write-ups-Hack-The-Box/blob/main/Hack-The-Box-Machines/Keeper/Keeper.md)           |
|    **Love**     |   Fácil    |       *Windows*       |                                                   • Bypass de autenticación web con SQLI y subida de archivos arbitraria para subida de Web-Shell PHP.<br>• Abuso de vulnerabilidad `AlwaysInstallElevated` (Escalada de privilegios).                                                    |            📖[Leer Write-up](https://github.com/omarHdz59/Write-ups-Hack-The-Box/blob/main/Hack-The-Box-Machines/Love/Love.md)             |
| **OpenSource**  |   Fácil    |        *Linux*        |        • Enumeración y exfiltración de datos en proyectos `Git`.<br>• Bypass de filtros y sanitización deficiente en parámetros controlados por el usuario dentro de Flask (Acceso inicial).<br>• Reenvió de puertos con Chisel y abuso de tareas Cron (Escalada de privilegios).         |      📖[Leer Write-up](https://github.com/omarHdz59/Write-ups-Hack-The-Box/blob/main/Hack-The-Box-Machines/OpenSource/OpenSource.md)       |
|    **Sauna**    |   Fácil    |       *Windows*       | • AS-REP Roasting Attack (Acceso inicial).<br>• Enumeración interna automatizada e identificación de credenciales Autologon expuestas (`WinPEAS.exe`).<br>• Enumeración de Active Directory con BloodHound y explotación de DCSync para efectuar Pass-The-Hash (Escalada de privilegios). |           📖[Leer Write-up](https://github.com/omarHdz59/Write-ups-Hack-The-Box/blob/main/Hack-The-Box-Machines/Sauna/Sauna.md)            |


---

⚠️ Descargo de Responsabilidad (Disclaimer)

El contenido de este repositorio tiene fines estrictamente educativos y de documentación personal. No promuevo ni apoyo el uso de estas técnicas con fines malintencionados o ilegales. Siempre opera bajo entornos controlados y con autorización previa.

---
<div align="center">

<h1> 📑 Hack The Box Write-ups </h1>

<p><b>Documentación técnica, metodologías de ataque y reportes de auditoría de máquinas HTB.</b></p>

[![Plataforma](https://img.shields.io/badge/Plataforma-Hack%20The%20Box-111927?style=for-the-badge&logo=hackthebox&logoColor=9FEF00)](https://www.hackthebox.com)
[![Máquinas](https://img.shields.io/badge/Máquinas_Resueltas-64-blue?style=for-the-badge)](https://profile.hackthebox.com/profile/019c3639-2e8e-730f-a9ff-b7cc43ef6a4f?utm_medium=copy_url)

</div>

---

<div align="center">

## 🛠️ Herramientas & Tecnologías Frecuentes

![Nmap](https://custom-icon-badges.demolab.com/badge/Nmap-14B528?style=flat-square&logo=nmap&logoColor=black)
![Burp Suite](https://custom-icon-badges.demolab.com/badge/Burpsuite-FF6D05?style=flat-square&logo=burpsuite&logoColor=white)
![Metasploit](https://custom-icon-badges.demolab.com/badge/Metasploit-FFFFFF?style=flat-square&logo=metasploit&logoColor=2496ED)
![Python](https://custom-icon-badges.demolab.com/badge/Python-3776AB?style=flat-square&logo=python&logoColor=FFD43B)
![Bash](https://custom-icon-badges.demolab.com/badge/Bash-4EAA25?style=flat-square&logo=GNU%20Bash&logoColor=white)
![Active Directory](https://custom-icon-badges.demolab.com/badge/Active_Directory-0078D4?style=flat-square&logo=windows11&logoColor=white)
![Docker](https://custom-icon-badges.demolab.com/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

</div>

---

<div align="center">

## 🎯 Propósito del Repositorio

 Documentación y write-ups de las máquinas de Hack The Box que he ido resolviendo. El proyecto tiene dos metas claras:

**1. Bitácora personal:** Documentar mi aprendizaje y tener un punto de referencia para repasar técnicas en el futuro.<br>
**2. Apoyo a la comunidad:** Compartir soluciones didácticas paso a paso para quienes se inician en ciberseguridad ofensiva y resolución de CTFs.<br>

</div>

---

<div align="center">

## 💻 Máquinas Resueltas

| Máquina | Dificultad | SO | Resumen Técnico / Vectores de Ataque | Write-up |
| :--- | :---: | :---: | :--- | :---: |
| **Cozyhosting** | `Fácil` | 🐧 Linux | • Identificación de tecnologías en páginas de error.<br>• Session Hijacking (gestión deficiente de cookies) e Inyección de Comandos.<br>• Ingeniería inversa de `.jar` (JD-GUI) y exfiltración en PostgreSQL.<br>• Escalada: Abuso de permisos sudo / binarios SSH. | [📖 Leer](https://github.com/omarHdz59/CTF-Writeups/tree/main/Easy-HTB/Cozyhosting/Cozyhosting.md) |
| **Active** | `Fácil` | 🪟 Windows | • Enumeración de SMB y recurso SYSVOL.<br>• Extracción y descifrado de credenciales GPP.<br>• Enumeración de AD y ataque de Kerberoasting para intrusión/escalada. | [📖 Leer](https://github.com/omarHdz59/CTF-Writeups/tree/main/Easy-HTB/Active/Active.md) |
| **Antique** | `Fácil` | 🐧 Linux | • Enumeración del servicio SMTP.<br>• RCE a través de misconfiguraciones en servicio de impresión (Intrusión).<br>• Lectura arbitraria de archivos con CUPS (Escalada de privilegios). | [📖 Leer](https://github.com/omarHdz59/CTF-Writeups/tree/main/Easy-HTB/Antique/Antique.md) |
| **Bank** | `Fácil` | 🐧 Linux | • Explotación de EAR (*Execution After Redirect*) & subida arbitraria de archivos vía WebShell.<br>• Exposición de archivos sensibles y fallos criptográficos.<br>• Abuso de permisos inseguros en archivos del sistema. | [📖 Leer](https://github.com/omarHdz59/CTF-Writeups/tree/main/Easy-HTB/Bank/Bank.md) |
| **Bashed** | `Fácil` | 🐧 Linux | • Localización de WebShell expuesta (`phpbash`).<br>• Monitoreo de procesos en tiempo real con `pspy`.<br>• Abuso de tareas Cron y secuestro de script Python con permisos inseguros. | [📖 Leer](https://github.com/omarHdz59/CTF-Writeups/tree/main/Easy-HTB/Bashed/Bashed.md) |
| **Blocky** | `Fácil` | 🐧 Linux | • Enumeración de usuarios en WordPress.<br>• Exfiltración de credenciales hardcodeadas en código Java con JD-GUI.<br>• Abuso de privilegios SUDO directos. | [📖 Leer](https://github.com/omarHdz59/CTF-Writeups/tree/main/Easy-HTB/Blocky/Blocky.md) |
| **BoardLight** | `Fácil` | 🐧 Linux | • RCE en Dolibarr 17.0.0 (Acceso inicial).<br>• Movimiento lateral vía credenciales expuestas en `conf.php`.<br>• Escalada mediante vulnerabilidad en Enlightenment v0.23.1 (**CVE-2022-37706**). | [📖 Leer](https://github.com/omarHdz59/CTF-Writeups/tree/main/Easy-HTB/BoardLight/BoardLight.md) |
| **Bounty** | `Fácil` | 🪟 Windows | • Bypass de filtros de subida de archivos mediante fuerza bruta de extensiones.<br>• Ejecución de comandos mediante subida de `web.config` en IIS.<br>• Escalada vía abuso del privilegio `SeImpersonatePrivilege`. | [📖 Leer](https://github.com/omarHdz59/CTF-Writeups/tree/main/Easy-HTB/Bounty/Bounty.md) |
| **Buff** | `Fácil` | 🪟 Windows | • Explotación RCE en Gym Management System 1.0.<br>• Port Forwarding con Chisel para pivoteo a servicio local.<br>• Stack-based Buffer Overflow en CloudMe 1.11.2 para escalada. | [📖 Leer](https://github.com/omarHdz59/CTF-Writeups/tree/main/Easy-HTB/Buff/Buff.md) |
| **Cap** | `Fácil` | 🐧 Linux | • Vulnerabilidad IDOR conducente a Information Disclosure (Captura PCAP).<br>• Análisis de tráfico en Wireshark/tshark para extracción de credenciales.<br>• Abuso de capability Linux (`cap_setuid`) en Python para `root`. | [📖 Leer](https://github.com/omarHdz59/CTF-Writeups/tree/main/Easy-HTB/Cap/Cap.md) |
| **Chemistry** | `Fácil` | 🐧 Linux | • RCE mediante librería vulnerable `Pymatgen`.<br>• Enumeración local y exfiltración de base de datos SQLite.<br>• LFI en `aiohttp 3.9.1` para lectura de clave SSH privada de `root`. | [📖 Leer](https://github.com/omarHdz59/CTF-Writeups/tree/main/Easy-HTB/Chemistry/Chemistry.md) |
| **Code** | `Fácil` | 🐧 Linux | • Bypass de Sandbox Python para RCE.<br>• Movimiento lateral mediante exfiltración y crackeo de hashes.<br>• Lectura arbitraria de archivos por sanitización deficiente en script personalizado. | [📖 Leer](https://github.com/omarHdz59/CTF-Writeups/tree/main/Easy-HTB/Code/Hack%20The%20Box%20-%20Code.md) |
| **GoodGames** | `Fácil` | 🐧 Linux | • SQL Injection (Bypass de Login) y exfiltración de datos.<br>• Server-Side Template Injection (SSTI) en motor Jinja2.<br>• Escape de contenedor Docker mediante abuso de montajes e Inode compartidos. | [📖 Leer](https://github.com/omarHdz59/CTF-Writeups/tree/main/Easy-HTB/GoodGames/GoodGames.md) |
| **Granny** | `Fácil` | 🪟 Windows | • Abuso de servidor WebDAV mal configurado (método PUT/MOVE).<br>• Intrusión mediante WebShell `.aspx`.<br>• Escalada vía `SeImpersonatePrivilege` utilizando `Churrasco.exe`. | [📖 Leer](https://github.com/omarHdz59/CTF-Writeups/tree/main/Easy-HTB/Granny/Granny.md) |
| **Keeper** | `Fácil` | 🐧 Linux | • Abuso de credenciales por defecto y reutilización de contraseñas.<br>• Volcado de memoria del proceso KeePass para extracción de Master Key. | [📖 Leer](https://github.com/omarHdz59/CTF-Writeups/tree/main/Easy-HTB/Keeper/Keeper.md) |
| **Love** | `Fácil` | 🪟 Windows | • Auth Bypass con SQLi + subida de WebShell PHP.<br>• Abuso de la directiva de Windows Installer `AlwaysInstallElevated`. | [📖 Leer](https://github.com/omarHdz59/CTF-Writeups/tree/main/Easy-HTB/Love/Love.md) |
| **OpenSource** | `Fácil` | 🐧 Linux | • Análisis de historial de commits en Git para extracción de credenciales.<br>• Directory Traversal / Bypass de sanitización en Flask.<br>• Port Forwarding con Chisel + abuso de Cron Jobs locales. | [📖 Leer](https://github.com/omarHdz59/CTF-Writeups/tree/main/Easy-HTB/OpenSource/OpenSource.md) |
| **Sauna** | `Fácil` | 🪟 Windows | • Enumeración de usuarios y ataque AS-REP Roasting.<br>• Enumeración local con WinPEAS y hallazgo de credenciales AutoLogon.<br>• Mapeo de AD con BloodHound + DCSync attack para Pass-The-Hash. | [📖 Leer](https://github.com/omarHdz59/CTF-Writeups/tree/main/Easy-HTB/Sauna/Sauna.md) |
| **Administrator** | `Media` | 🪟 Windows | • Enumeración de Active Directory.<br>• Encadenación de multiples movimientos laterales aprovechando privilegios inseguros en AD.<br>• Explotación de DCSync y Pass-The-Hash. | [📖 Leer](https://github.com/omarHdz59/CTF-Writeups/blob/main/Medium-HTB/Administrator/Administrator.md) |
| **BabyTwo** | `Media` | 🪟 Windows | • Enumeración de Active Directory con BloodHound.<br>• Ejecución arbitraria de comandos a través de scripts de inicio de sesión en SYSVOL.<br>• Escalada de privilegios mediante abuso de GPO. | [📖 Leer](https://github.com/omarHdz59/CTF-Writeups/blob/main/Medium-HTB/BabyTwo/BabyTwo.md) |
| **Certified** | `Media` | 🪟 Windows | • Enumeración de Active Directory con BloodHound.<br>• Cadena de explotación a través del abuso de ACL inseguros.<br>• Shadow Credentials Attack. <br>• Abuso de plantilla ESC9 (No Security Extension Flag). | [📖 Leer]() |

</div>

---

<div align="center">

> ⚠️ **Descargo de Responsabilidad (Disclaimer):**  
> El contenido publicado en este repositorio tiene fines **estrictamente educativos y de investigación personal**. Las técnicas documentadas corresponden a entornos de prueba retirados y legalmente autorizados por la plataforma **Hack The Box**. No promuevo ni respaldo el uso indebido de estas técnicas en sistemas no autorizados.

</div>

---

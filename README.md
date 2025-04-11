# Ansible Playbooks - Server Management

Este repositorio contiene una colección de **playbooks de Ansible** diseñados para la **gestión y automatización de servidores** Linux. Cada playbook cubre una tarea específica, como instalación de paquetes, configuración de servicios, copias de seguridad, gestión de usuarios, seguridad de servidores y despliegue de aplicaciones.

## 📋 Contenido

- 🔧 Instalación y configuración de servicios (Apache, PostgreSQL, Docker, NTP, Postfix)
- 🔒 Fortalecimiento de la seguridad (sudoers, UFW, SELinux)
- 📦 Actualización de paquetes
- 🛡️ Gestión de usuarios y permisos
- 🗄️ Tareas de backup y restauración
- 🚀 Despliegue de contenedores Docker
- ⚡ Automatización de tareas administrativas

## 🛠️ Requisitos

- Ansible 2.9 o superior
- Inventario de hosts configurado (`inventory/hosts`)
- Acceso SSH a los servidores
- Privilegios de administrador (root o sudo)

## 🚀 Cómo usarlo

1. Clona el repositorio:
   ```bash
   git clone https://github.com/brayanhernandez-99/ansible.git
   cd ansible
   ```
2. Edita el archivo de inventario para incluir tus servidores.
3. Ejecuta el playbook que necesites:
    ``` bash
    ansible-playbook playbooks/nombre-del-playbook.yml -i inventory/hosts
    ```

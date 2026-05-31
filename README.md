# Proxmox VE – TFG ASIR 2024/2026

Implementación de un sistema de virtualización con Proxmox VE sobre VirtualBox, con una máquina virtual Ubuntu Server 24.04 gestionada desde interfaz web.

## Autores
- Matias Nicolas Florenttini Gomez
- Santiago Gómez Vacas

FP LUMARA · Ciclo ASIR · Curso 2024/2026

## Descripción
El proyecto consiste en instalar y configurar Proxmox VE 9.1 dentro de una VM de VirtualBox, acceder a su interfaz web, y desplegar una VM Ubuntu Server con cloud-init y usuario personalizado.

## Estructura del repositorio
- `memoria/` — Memoria técnica del proyecto (.docx)
- `presentacion/` — Presentación para la defensa (.pptx)
- `capturas/` — Capturas de pantalla del proceso (figuras 1-30)

## Pasos para replicar el entorno
1. Instalar VirtualBox con adaptador puente habilitado
2. Crear VM con 4096 MB RAM, 2 CPUs y 60 GB disco VDI
3. Arrancar con la ISO de Proxmox VE 9.1 e instalar
4. Acceder a `https://[IP]:8006` con usuario `root`
5. Subir ISO de Ubuntu Server y crear VM 100
6. Arrancar la VM y completar la instalación de Ubuntu

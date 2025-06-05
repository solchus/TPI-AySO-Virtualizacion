# TP Integrador - Arquitectura y Sistemas Operativos - Virtualización  
**Materia:** Arquitectura y Sistemas Operativos  
**Carrera:** Tecnicatura en Programación (1° Año)  
**Alumnos:** Nicolas Macaris - Maria Sol Couchot  
**Año:** 2025

---

## 🧾 Descripción

Este trabajo práctico tiene como objetivo demostrar el uso de virtualización utilizando **VirtualBox** y el sistema operativo **Ubuntu** como máquina virtual.

A lo largo del trabajo se realiza:

- Instalación de VirtualBox.
- Creación e instalación de una máquina virtual con Ubuntu.
- Verificacíon de recursos asignados desde la máquina virtual.
- Configuración de red para conexión a internet.
- Verificación de conectividad entre el host (máquina real) y la VM.
- Demostración de intercambio de paquetes mediante `ping`.
- Capturas de pantalla del proceso.
- Video explicativo.

---

## 📁 Contenido del repositorio

- 📄 `TPI-Virtualizacion-NMacaris-MSCouchot.pdf`:  
  Informe teórico del trabajo práctico con desarrollo de los temas tratados en el video.

- 📄 `General presentation.pptx`
  TODO

- 📁 `anexos/`:  
  Carpeta con capturas y evidencias del proceso de instalación y pruebas de red.

- 🎥 `TPI AYSO.mp4`:  
  Archivo de video con explicación audiovisual del trabajo.  
  Tambien se puede visualizar en el siguiente enlace:  
🔗 [Ver video en YouTube](https://youtu.be/Z4w0350qnl4)

---

## 🌐 Detalles técnicos

- **Virtualizador usado**: [Oracle VM VirtualBox [7.1.10]](https://www.virtualbox.org/wiki/Downloads)
- **SO anfitrión (host)**: [Windows 11](https://www.microsoft.com/en-us/windows/get-windows-11)
- **SO invitado (VM)**: [Ubuntu [24.04.2 LTS]](https://discourse.ubuntu.com/t/ubuntu-24-04-lts-noble-numbat-release-notes/39890)
- **Modo de red usado**: Adaptador puente (Bridge Adapter)
- **Comandos utilizados**:
  - `ip a` (en Ubuntu)
  - `ipconfig` (en Windows)
  - `ping` (para verificar conectividad)

---

## 🧠 Conceptos aplicados

- Virtualización de hardware.
- Configuración de red en entornos virtualizados.
- Diferencia entre IPs privadas del host y la VM.
- Comunicación entre sistemas operativos mediante red local.

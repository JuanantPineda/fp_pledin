---
title: "Ejercicio 1: Instalación de QEMU/libvirt. Conexión local y remota"
---

## ¿Qué vas a aprender en este ejercicio?

* A realizar la instalación del sistema de virtualización QEMU/libivrt.
* A entender y realizar distintos tipos de conexión a libvirt.
* A configurar un servidor para realizar una conexión remoto a libvirt.

## Recursos para realizar este ejercicio

* Capítulo 2 del [Curso: Virtualización en Linux](https://github.com/josedom24/curso_virtualizacion_linux)

## ¿Qué tienes que hacer?

1. Realiza la instalación de QEMU/libvirt.
2. Configura tu usuario sin privilegios para que puedas hacer conexiones privilegiadas sin usar el usuario `root`. Para probarlo: Ejecuta el comando `list` de `virsh` realizando una conexión privilegiada con tu usuario sin privilegios (no uses el `root`).
3. Con un compañero, configura tu máquina para que el pueda realizar un acceso remoto a libvirt. Realiza también una conexión remota al equipo de un compañero.

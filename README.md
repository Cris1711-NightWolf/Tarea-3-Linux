# 🐧 Práctica de Manejo de Archivos y Directorios en Linux  

Práctica de manejo básico de Linux usando terminal: creación, organización y manipulación de archivos y directorios, gestión de permisos, búsqueda, procesos y paquetes. Incluye script automatizado y documentación con capturas de pantalla.

## 📌 Resumen  
Este proyecto es una práctica de Linux en la terminal, donde se trabajan los comandos básicos para:  
- 📂 Crear y organizar directorios y archivos  
- 🗑️ Eliminar y mover elementos  
- 🔒 Gestionar permisos  
- 🔍 Buscar y filtrar información  
- ⚙️ Administrar procesos  
- 📦 Instalar paquetes  
- 📝 Crear y ejecutar un script automatizado  

---

## 🧑‍💻 Comandos Clave  
- 📂 **Navegación y directorios:** `cd`, `pwd`, `ls`, `mkdir`  
- 📑 **Archivos:** `touch`, `nano`, `cp`, `mv`, `cat`  
- 🗑️ **Eliminar:** `rm`, `rmdir`  
- 🔒 **Permisos:** `chmod`, `ls -l`  
- 🔍 **Búsqueda:** `find`, `grep`  
- ⚙️ **Procesos:** `top`, `htop`, `sleep`, `kill`  
- 📦 **Paquetes:** `apt update`, `apt install`  

---

## 📝 Script Final  

Archivo **`mis_comandos.sh`**:  

```bash
#!/bin/bash
# Script de práctica Linux

# Crear directorio logs
mkdir -p logs

# Guardar la fecha en un archivo
date > logs/fecha.txt

# Mostrar mensaje con cowsay
cowsay "Ejercicio completado"

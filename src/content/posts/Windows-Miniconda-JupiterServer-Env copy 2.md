---
title: Windows-Miniconda-JupiterServer-Env
published: 2024-04-08
tags: [Python, IA]
description: "Instalador Automatizado para Windows de Jupiter Server y Anaconda"
category: DevOps
draft: false
---

# Links
- [GitHub Repository](https://github.com/Vayioleta/Windows-Miniconda-JupiterServer-Env)

## Manual de Instrucciones: Instalación y Administración del Servidor Jupiter
### Instalación:

1. **Ejecutar CondaSetup.bat:**
   - Haz doble clic en el archivo `CondaSetup.bat` para iniciar la instalación de Conda.
   - Sigue las instrucciones en pantalla para completar la instalación.

2. **Ejecutar JupiterSetup.bat:**
   - Haz doble clic en el archivo `JupiterSetup.bat` para iniciar la instalación del Servidor Jupiter.
   - Sigue las instrucciones en pantalla para completar la instalación.

### Administración del Entorno:

1. **Iniciar el Servidor Jupiter:**
   - Para iniciar el entorno del Servidor Jupiter, ejecuta el archivo `JupiterRun.bat`.
   - Esto abrirá el entorno de Jupiter en tu navegador web predeterminado. http://localhost:8888/

2. **Cambiar la Contraseña de Acceso:**
   - Para cambiar la contraseña de acceso al entorno, sigue estos pasos:
     1. Abre el archivo `token.txt` con un editor de texto (como Notepad).
     2. Cambia el contenido del archivo por tu nueva contraseña en formato de texto sin formato. Por ejemplo:
        ```
        MiNuevaContraseña123
        ```
     3. Guarda los cambios en el archivo `token.txt`.

3. **Reiniciar el Servidor Jupiter:**
   - Después de cambiar la contraseña, cierra y vuelve a ejecutar `JupiterRun.bat` para aplicar los cambios.

[Manual de Instrucciones en Español](README_ES.md)

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/Z8Z4HKF8C)
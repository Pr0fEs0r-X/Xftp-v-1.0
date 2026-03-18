# Xftp v 1.2

![Made with Python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg?logo=python&logoColor=white)
![Version](https://img.shields.io/badge/Version-1.2-blue)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux%20%7C%20macOS-lightgrey)

**Xftp** es una aplicación cliente FTP diseñada para ser simple, funcional y visualmente atractiva. Desarrollada íntegramente en Python, ofrece una experiencia de usuario fluida gracias a sus operaciones en segundo plano (threading) y su interfaz de vista dividida (Split View) que facilita la gestión de archivos entre el cliente y el servidor.

---

## 📖 Tabla de Contenidos
- [Características Principales](#-características-principales)
- [Novedades en v1.2](#-novedades-en-v12)
- [Tecnologías](#-tecnologías)
- [Capturas de Pantalla](#-capturas-de-pantalla)
- [Compatibilidad](#-compatibilidad)
- [Instalación y Ejecución](#-instalación-y-ejecución)
- [Compilación](#-compilación)
- [Aviso de Seguridad](#-aviso-de-seguridad)
- [Autor](#-autor)

---

## ✨ Características Principales

### Interfaz de Usuario (GUI)
*   🎨 **Tema Olive Edition:** Diseño visual moderno, limpio y contrastante.
*   🖥️ **Vista Dividida (Split View):**
    *   **Panel Izquierdo (Cliente):** Explorador de archivos locales.
    *   **Panel Derecho (Servidor):** Listado de archivos remotos.
*   🚀 **Splash Screen Animado:** Pantalla de carga con animaciones suaves y partículas.
*   📋 **Log en Tiempo Real:** Registro de todas las operaciones, errores y estados.
*   ⚠️ **Mensajes Visuales:** Los errores de conexión se muestran directamente en el panel del servidor.

### Funcionalidades FTP
*   🔗 **Conexión:** Soporte para puertos personalizados y autenticación anónima.
*   📂 **Gestor de Sitios:** Ventana emergente para guardar, cargar y eliminar servidores favoritos.
*   ➡️ **Subir (Upload):** Transferencia de archivos al servidor en segundo plano.
*   ⬅️ **Descargar (Download):** Descarga de archivos al directorio local actual.
*   📁 **Gestión de Archivos:** Crear carpetas, eliminar y renombrar archivos remotamente.
*   🔄 **Navegación:** Navegación fluida por directorios locales y remotos.

---

## 🆕 Novedades en v1.2
Se ha añadido una clase `OverwriteDialog` personalizada que incluye un **Checkbutton para la opción "Aplicar a todos"**, agilizando la sobreescritura de archivos tanto al subir como al descargar.

---

## 🛠️ Tecnologías

*   **Lenguaje:** Python 3.
*   **GUI:** Tkinter / TTK.
*   **Red:** Ftplib, Socket, Threading.
*   **Almacenamiento:** JSON.

---

## 📸 Capturas de Pantalla

**Splash Screen Animado**
<img width="380" height="237" alt="Splash Screen Xftp" src="https://github.com/user-attachments/assets/d8ee638d-4f10-44cb-9cad-5ddb53c72aec" />

**Interfaz Principal**
<img width="888" height="504" alt="Interfaz Principal Xftp" src="https://github.com/user-attachments/assets/78a9727a-f56c-48d7-af35-fcf00191198d" />

---

## 💻 Compatibilidad

Este software es **multiplataforma 100% nativo**.

| Sistema Operativo | Estado | Notas |
| :--- | :---: | :--- |
| **Windows** | ✅ Totalmente compatible | Recomendado compilar con PyInstaller. |
| **Linux** | ✅ Totalmente compatible | Requiere `python3-tk` instalado. |
| **macOS** | ✅ Totalmente compatible | Requiere Python instalado oficialmente. |

---

## 🚀 Instalación y Ejecución

### Opción A: Desde el código fuente
Clona el repositorio y ejecuta el script principal.

*   **Windows:**
    ```bash
    python xftp.py
    ```
*   **Linux/macOS:**
    ```bash
    python3 xftp.py
    ```

### Opción B: Requisitos en Linux
Si obtienes un error sobre `tkinter` en sistemas Linux, instálalo con los siguientes comandos:

```bash
# Ubuntu / Debian
sudo apt-get install python3-tk

# Fedora
sudo dnf install python3-tkinter
```

---

## 📦 Compilación a Ejecutable (Windows)

Para convertir el script en un archivo `.exe` portable usando PyInstaller:

```bash
pyinstaller --onefile --windowed --name "Xftp" xftp.py
```

---

## ⚠️ Aviso de Seguridad

Las contraseñas se guardan en **texto plano** dentro del archivo JSON de configuración (`sites.json`).

Se recomienda precaución si se comparte la carpeta del programa o si se guardan contraseñas críticas. Esta funcionalidad está diseñada para comodidad en entornos de desarrollo o uso personal, **no para almacenamiento de credenciales de alta seguridad**.

---

## 👤 Autor y Empresa

Desarrollado con fines educativos y de seguridad informática.

*   **Creador:** [Rodolfo Hernandez Baz](https://www.rodolfohbaz.info/)
*   **Desarrollador Principal:** [Pr0fEs0r-X](https://github.com/Pr0fEs0r-X)
*   **Compañía:** [Rhino Forensic & Reverse Toolkit v 1.0](https://rhinosecurity.xyz/)
```

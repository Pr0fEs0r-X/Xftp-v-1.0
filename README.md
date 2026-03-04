# Xftp v 1.0

![Made with Python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg?logo=python&logoColor=white)


<h1><b></b>Características • Instalación • Uso • Compilación</h1></b>
<b>📖 Descripción</b>

Xftp es una aplicación cliente FTP diseñada para ser simple, funcional y visualmente atractiva. Desarrollada íntegramente en Python, ofrece una experiencia de usuario fluida gracias a sus operaciones en segundo plano (threading) y su interfaz de vista dividida (Split View) que facilita la gestión de archivos entre el cliente y el servidor.
<br><br><b>👨‍💻 Desarrollador</b>

Este software fue diseñado y programado por:

  <b>BY Pr@FeSor X</b>

<b>✨ Características Principales</b>
Interfaz de Usuario (GUI)

    🎨 Tema Azul Claro Contrastante: Diseño visual moderno y limpio.
    🖥️ Vista Dividida (Split View):
        Panel Izquierdo (Cliente): Explorador de archivos locales.
        Panel Derecho (Servidor): Listado de archivos remotos.
    🚀 Splash Screen Animado: Pantalla de carga con animaciones suaves y partículas.
    📋 Log en Tiempo Real: Registro de todas las operaciones, errores y estados.
    ⚠️ Mensajes Visuales: Los errores de conexión se muestran directamente en el panel del servidor.

<br><h2>Funcionalidades FTP</h2>

<br>🔗 Conexión	Soporte para puertos personalizados y autenticación anónima.
<br>📂 Gestor de Sitios	Ventana emergente para guardar, cargar y eliminar servidores favoritos.
<br>➡️ Subir (Upload)	Transferencia de archivos al servidor en segundo plano.
<br>⬅️ Descargar (Download)	Descarga de archivos al directorio local actual.
<br>📁 Gestión de Archivos	Crear carpetas, eliminar y renombrar archivos remotamente.
<br>🔄 Navegación	Navegación fluida por directorios locales y remotos.
Tecnologías

* Lenguaje: Python 3.
* GUI: Tkinter / TTK.
* Red: Ftplib, Socket, Threading.
* Almacenamiento: JSON.

  <h2>📸 <b>Capturas de Pantalla</b></h2>
Splash Screen Animado<br>
<img width="380" height="237" alt="1xftp" src="https://github.com/user-attachments/assets/d8ee638d-4f10-44cb-9cad-5ddb53c72aec" />
<br><br><b>### Interfaz Principal<br>
<img width="888" height="504" alt="2xftp" src="https://github.com/user-attachments/assets/78a9727a-f56c-48d7-af35-fcf00191198d" />

---

## 💻 Compatibilidad

Este software es **multiplataforma 100% nativo**.

| Sistema Operativo | Estado | Notas |
|-------------------|--------|-------|
| **Windows** | ✅ Totalmente compatible | Recomendado compilar con PyInstaller. |
| **Linux** | ✅ Totalmente compatible | Requiere `python3-tk` instalado. |
| **macOS** | ✅ Totalmente compatible | Requiere Python instalado oficialmente. |

---

## 🚀 Instalación y Ejecución

### Opción A: Desde el código fuente (Recomendado para desarrollo)


1.  Ejecuta el script:
    *   **Windows**:
        ```bash
        python xftp.py
        ```
    *   **Linux/macOS**:
        ```bash
        python3 xftp.py
        ```

### Opción B: Requisitos en Linux
Si en Linux obtienes un error sobre `tkinter`, instálalo con:
```bash
# Ubuntu / Debian
sudo apt-get install python3-tk

# Fedora
sudo dnf install python3-tkinter


📦 Compilación a Ejecutable (Windows)

Para convertir el script en un archivo .exe portable: 

pyinstaller --onefile --windowed --name "Xftp" xftp.py


⚠️ Aviso de Seguridad
Las contraseñas se guardan en texto plano dentro del archivo JSON.
Se recomienda precaución si se comparte la carpeta del programa o si se guardan contraseñas críticas. Esta funcionalidad está diseñada para comodidad en entornos de desarrollo o uso personal, no para almacenamiento de credenciales de alta seguridad.

---

📄 Licencia

Este proyecto está licenciado bajo la **GNU General Public License v3.0.

¿Qué significa esto?
1.  Libertad de uso**: Puedes ejecutar el programa para cualquier propósito.
2.  Libertad de estudio**: Tienes acceso al código fuente para estudiarlo y modificarlo.
3.  Libertad de distribución**: Puedes redistribuir copias.
4.  Copyleft**: Si modificas y distribuyes este software, debe ser bajo la misma licencia GNU GPL v3.0, manteniendo el crédito al autor original.

Para más detalles, consulta el archivo `LICENSE` incluido o visita [gnu.org/licenses/gpl-3.0.html](https://www.gnu.org/licenses/gpl-3.0.html).



Desarrollado con 💙 por BY Pr@FeSor X - Rodolfo Hernande Baz

Software Libre para la comunidad.



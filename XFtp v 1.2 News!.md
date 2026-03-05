
## 🚀 Novedades y Cambios Recientes

### Versión 1.2 (Actual)
**Enfoque en la experiencia de usuario y automatización**

*   ☑️ **Diálogo de Sobrescritura Mejorado:** Se ha rediseñado el popup de confirmación para incluir una casilla de verificación **"Aplicar a todos"**.
    *   Permite al usuario decidir sobrescribir (u omitir) todos los archivos restantes de una sola vez durante la subida de carpetas.
    *   Ideal para transferencias masivas donde no se desea confirmar archivo por archivo.
*   ⚡ **Gestión Hilos Segura (Thread-Safe):** Implementación de sincronización de eventos para permitir que los diálogos de confirmación interactúen correctamente con el hilo principal de la interfaz, evitando bloqueos durante la subida recursiva.

### Versión 1.1
**Enfoque en funcionalidad y visualización**

*   📁 **Subida Recursiva de Carpetas:**
    *   Ahora es posible seleccionar una carpeta local y subirla completa al servidor.
    *   El cliente replica automáticamente la estructura de directorios y sube todos los archivos contenidos.
*   ⚠️ **Confirmación de Sobrescritura:**
    *   El sistema detecta si un archivo ya existe (tanto en subida como en descarga) y solicita confirmación antes de reemplazarlo.
*   🔍 **Menú de Vista (Tamaño de Fuente):**
    *   Añadido nuevo menú "Vista" en la barra superior.
    *   Permite cambiar el tamaño de la fuente (Pequeña, Normal, Grande, Muy Grande).
    *   Al aumentar el tamaño de la fuente, los iconos y las filas de los listados se escalan automáticamente para una mejor visualización.

# Setup de Cursor IDE y Extensiones

## Herramientas Instaladas
* **Cursor IDE**: Versión básica y gratuita.
* **Claude Code**: Extensión oficial de asistencia de código.
* **Codex**: Extensión complementaria para desarrollo.

## Pasos Completados
1. Descarga e instalación de Cursor IDE.
2. Configuración de las extensiones Claude Code y Codex en el panel correspondiente.
3. Instalación y configuración de Git en el sistema operativo local.
4. Creación del repositorio público en GitHub y clonación local.
5. Redacción de la documentación técnica en el archivo README.

## Problemas Encontrados y Soluciones
* **Problema 1:** Cursor se inició inicialmente en la interfaz de Multi-Agent Space (Hub), bloqueando la vista clásica del editor y el acceso directo al panel de extensiones.
  * **Solución:** Se forzó el inicio del editor clásico cerrando la app y ejecutando el comando `cursor .` desde la consola de comandos de la computadora.
* **Problema 2:** La terminal integrada de Cursor no reconocía los comandos de `git` debido a que el software no estaba instalado en el sistema operativo.
  * **Solución:** Se descargó e instaló Git para Windows desde el sitio oficial, integrándolo correctamente tras reiniciar el IDE.
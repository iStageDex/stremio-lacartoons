# LACartoons Stremio Addon

Este proyecto es un complemento (addon) de código abierto para [Stremio](https://www.stremio.com/), que permite visualizar el catálogo de series y caricaturas de LACartoons con una integración nativa y fluida.

## Características
* **Catálogo completo:** Acceso a series y episodios.
* **Streaming optimizado:** Extracción automática de enlaces (`.m3u8`, `.mp4`) mediante scraping inteligente.
* **Compatibilidad:** Uso de `yt-dlp` como respaldo para reproductores externos.

## Instalación y Ejecución

Para poner en marcha el addon en tu máquina (Windows), sigue estos pasos desde **PowerShell**:

### 1. Clonar el repositorio
Abre PowerShell y navega a la carpeta donde quieras tener el proyecto, luego clona el repositorio:

```powershell
git clone [https://github.com/TU_USUARIO/stremio-lacartoons.git](https://github.com/TU_USUARIO/stremio-lacartoons.git)
cd stremio-lacartoons

### 2. Instalar dependencias

Dentro de la carpeta del proyecto, instala las librerías necesarias en PowerShell:

npm install

### 3. Ejecutar el Addon

Una vez instaladas las dependencias, inicia el servidor local:
PowerShell

node addon.js

## Requisitos Previos

    - Tener instalado Node.js (v16 o superior recomendado).
    - Tener yt-dlp.exe descargado y configurado en la ruta especificada dentro de addon.js.

## ¿Cómo colaborar?

¡Cualquier aporte es bienvenido para mejorar el scraping y la estabilidad!

    - Haz un Fork del proyecto.
    - Crea una rama con tu nueva funcionalidad (git checkout -b feature/nueva-mejora).
    - Haz un Commit de tus cambios (git commit -m 'Descripción de la mejora').
    - Haz un Push a la rama (git push origin feature/nueva-mejora).
    - Abre un Pull Request.

## Licencia

Este proyecto está bajo la Licencia MIT.


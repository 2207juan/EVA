<p align="center"><a href="README.md">English</a> · <a href="README.es.md">Español</a></p>

![Eva — Phase 1](assets/banner-es.svg)

**Eva es un sistema basado en Arch Linux con su propio escritorio Wayland.** La fase 1 está preparada para pruebas públicas.

https://github.com/user-attachments/assets/0784ac2a-7fd6-427a-851f-a188beb754e6

<p align="center">
<a href="https://github.com/2207juan/EVA/releases"><img src="assets/download-es.svg" alt="Descargar ISO" /></a>
<a href="#vistas-previas"><img src="assets/preview-es.svg" alt="Vistas previas" /></a>
<a href="https://github.com/2207juan/EVA/issues"><img src="assets/issues-es.svg" alt="Informar de un problema" /></a>
<a href="https://www.instagram.com/eva.frik"><img src="assets/instagram-es.svg" alt="Seguinos" /></a>
</p>

## Vistas previas

![Escritorio de Eva — modo oscuro y espacios con naipes](assets/previews/desktop-dark.png)

| Modo negro | Clima |
| :-- | :-- |
| ![Ajustes de apariencia](assets/previews/appearance-dark.png) | ![Clima real de Nueva York](assets/previews/weather-new-york.png) |
| **Dock** | **Lanzador · diseño 2** |
| ![Dock inferior](assets/previews/dock.png) | ![Lanzador orbital](assets/previews/launcher-orbit.png) |
| **Game Center** | **Monitor del sistema** |
| ![Game Center con Portal 2 como ejemplo](assets/previews/game-center.png) | ![Monitor del sistema](assets/previews/system.png) |
| **Mascota animada** | **Hábitat de mascotas** |
| ![Cascarón en el escritorio](assets/previews/pet.png) | ![Hábitat y juegos de mascotas](assets/previews/pet-home.png) |

<details>
<summary>Burbujas y vista de espacios</summary>

![Escritorio negro con burbujas](assets/previews/workspace-bubbles.png)

![Vista de espacios](assets/previews/workspace-overview.png)

</details>

Las capturas muestran la interfaz real de Eva en inglés, con Glass desactivado y un perfil de demostración separado. El clima usa Nueva York y Game Center muestra una biblioteca de ejemplo. Los juegos no están incluidos.

## Qué incluye

- Apariencia oscura, clara y Liquid Glass; barra, dock, widgets y espacios personalizables.
- Game Center, explorador Prisma, capturas de pantalla y grabación de video.
- Mascotas animadas con conversación opcional mediante IA. Necesitas tu propia clave API; la disponibilidad depende del proveedor.
- Instalador Calamares y menú de arranque personalizado.

## Animaciones

| Glitch RGB | Lámpara |
| :-- | :-- |
| ![RGB glitch opening animation](assets/previews/glitch.gif) | ![Lamp closing animation](assets/previews/lamp.gif) |

## Descarga

**[Descarga los archivos de la fase 1 desde Releases](https://github.com/2207juan/EVA/releases).** x86_64 · BIOS / UEFI.

Guarda todas las partes de la ISO, `release.json` y `reconstruir.py` en una misma carpeta. Únelas y verifícalas con Python 3:

```sh
python3 reconstruir.py --join release.json
```

Usa el archivo `.iso` resultante para crear tu USB de instalación. En Windows, usa `python` en lugar de `python3`.

> La fase 1 es una versión de pruebas. Haz una copia de tus archivos antes de instalar. Puedes informar de errores indicando tu equipo, cómo reproducirlos y una captura sin datos personales.

## Actualizaciones

Eva guarda los ajustes personales en tu perfil de usuario. Las actualizaciones del paquete de Eva crean copias locales para recuperarlos antes de actualizar. Reinstalar o formatear una partición es una operación distinta; conserva una copia de tus archivos.

[Informar de un problema](https://github.com/2207juan/EVA/issues) · [Seguinos en redes sociales](https://www.instagram.com/eva.frik)

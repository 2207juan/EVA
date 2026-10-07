<p align="center"><a href="README.md">English</a> · <a href="README.es.md">Español</a></p>

![Eva — Phase 1](assets/banner.svg)

**Eva is an Arch Linux system with its own Wayland desktop.** Phase 1 is available for public testing.

https://github.com/user-attachments/assets/0784ac2a-7fd6-427a-851f-a188beb754e6

<p align="center">
<a href="https://github.com/2207juan/EVA/releases"><img src="assets/download.svg" alt="Download ISO" /></a>
<a href="#preview"><img src="assets/preview.svg" alt="Previews" /></a>
<a href="https://github.com/2207juan/EVA/issues"><img src="assets/issues.svg" alt="Report a bug" /></a>
<a href="https://www.instagram.com/eva.frik"><img src="assets/instagram.svg" alt="Follow us" /></a>
</p>

## Preview

![Eva desktop — dark theme and card workspaces](assets/previews/desktop-dark.png)

| Dark theme | Weather |
| :-- | :-- |
| ![Appearance settings](assets/previews/appearance-dark.png) | ![Live weather in New York](assets/previews/weather-new-york.png) |
| **Dock** | **Launcher · design 2** |
| ![Bottom dock](assets/previews/dock.png) | ![Orbit launcher](assets/previews/launcher-orbit.png) |
| **Game Center** | **System monitor** |
| ![Game Center with a Portal 2 example](assets/previews/game-center.png) | ![Live system monitor](assets/previews/system.png) |
| **Animated companion** | **Pet habitat** |
| ![Cascarón on the desktop](assets/previews/pet.png) | ![Pet habitat and games](assets/previews/pet-home.png) |

<details>
<summary>Bubbles and workspace overview</summary>

![Dark desktop with bubble workspaces](assets/previews/workspace-bubbles.png)

![Workspace overview](assets/previews/workspace-overview.png)

</details>

Screenshots show the actual Eva interface in English with Glass disabled, using an isolated demo profile. Weather uses New York; the Game Center shows an example library. Games are not included.

## Inside Eva

- Dark, light and Liquid Glass appearance; configurable bars, dock, widgets and workspaces.
- Game Center, Prisma file manager, screenshots and screen recording.
- Animated pets with optional AI conversation. Bring your own API key; availability depends on the provider.
- Calamares installer and themed boot menu.

## Motion

| RGB glitch | Lamp |
| :-- | :-- |
| ![RGB glitch opening animation](assets/previews/glitch.gif) | ![Lamp closing animation](assets/previews/lamp.gif) |

## Download

**[Get the Phase 1 files from Releases](https://github.com/2207juan/EVA/releases).** x86_64 · BIOS / UEFI.

Download all ISO parts, `release.json` and `reconstruir.py` into one folder. Join and verify them with Python 3:

```sh
python3 reconstruir.py --join release.json
```

Use the resulting `.iso` to create your installation USB. On Windows, use `python` in place of `python3`.

> Phase 1 is a testing release. Back up your files before installing. Please report issues with your hardware, steps to reproduce and a screenshot without personal information.

## Updates

Eva keeps personal settings in your user profile. Eva package updates create local recovery snapshots before upgrading. Reinstalling or formatting a partition is a separate operation; keep a backup of your files.

[Report an issue](https://github.com/2207juan/EVA/issues) · [Follow us on social media](https://www.instagram.com/eva.frik)

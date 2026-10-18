# V4 · 2026-10-16

## English

Source changes for the next ISO:

- Compact dashboard with its continuous bar connection restored, including bottom-bar content placement.
- Updated button shapes and colored AI navigation icons.
- Temporary AI attachment picker closes when it loses focus or its owner closes.
- Cleaner Prisma header and normal folder opening from the pet pocket.
- Download indicator fits bars/docks; the Downloads widget now saves correctly and shows percentages when space allows.
- Experimental ATLAS UI hidden; the cover-based game library remains available.
- OCR and window cropping remain available through their keyboard shortcuts.

New native EVA recordings of cursor glitch/trail replace the retired rotation/follow previews. Updated English/Spanish screenshots show the AI, dashboard, Prisma and a library with 12 example Steam covers. No games were installed or run for these captures.

**Checks:** 12 unit tests; live Prisma focus/dialog/workspace checks and AI-owner closure; Home/Network geometry in eight bar/dock placements; 32 download layout/state cases. Tests used an isolated headless EVA session with bounded resources. GRUB helper checks cover eight themes, invalid IDs, privileged delegation and rollback with a mocked boot configuration; a real installed-machine theme change is still untested.

**ISO:** source and gallery update only. No new ISO was built or uploaded. Hardware/GPU and installed-system checks remain necessary before release.

## Español

Cambios de código para la próxima ISO:

- Dashboard compacto con la unión continua a la barra restaurada y los controles colocados dentro del panel cuando la barra está abajo.
- Nuevas formas de botones e iconos de navegación de la IA con color.
- El selector temporal de adjuntos se cierra al perder foco o cerrar la IA.
- Cabecera de Prisma más limpia y apertura normal de carpetas desde la mascota.
- Indicador de descargas ajustado a barras y docks; ya se puede guardar el widget Descargas y se muestra el porcentaje cuando cabe.
- ATLAS experimental oculto; se conserva la biblioteca de carátulas.
- OCR y recorte de ventanas siguen disponibles mediante sus atajos.

Grabaciones nuevas del cursor glitch/estela en EVA sustituyen las de giro/seguimiento eliminadas. Capturas actualizadas en inglés/español de IA, dashboard, Prisma y biblioteca con 12 carátulas de Steam de ejemplo. No se instalaron ni ejecutaron juegos para estas capturas.

**Comprobaciones:** 12 tests unitarios; pruebas reales de foco/diálogos/escritorios en Prisma y cierre desde la IA; geometría de Inicio/Redes en ocho posiciones de barra/dock; 32 casos de distribución/estado de descargas. Se usó una sesión EVA headless aislada con recursos limitados. Los tests del helper GRUB cubren ocho temas, IDs inválidos, delegación de privilegios y restauración con una configuración de arranque simulada; falta un cambio real en un sistema instalado.

**ISO:** son cambios de código y galería. No se construyó ni subió una ISO nueva. Quedan las pruebas de hardware/GPU y sistema instalado antes de publicar una nueva imagen.

## Welcome video · Vídeo de bienvenida · 2026-10-17

- Added the original `eva-welcome.mp4` to the public repository, with a direct playback link in both READMEs when GitHub does not show its embedded player.
- Se añadió el original `eva-welcome.mp4` al repositorio público y un enlace de reproducción directo en ambos idiomas cuando GitHub no muestra el reproductor integrado.
- H.264/AAC, 960×540, aproximadamente 79 segundos; sin modificar la ISO ni duplicar el reproductor.

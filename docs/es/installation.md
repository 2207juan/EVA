[← EVA](https://github.com/2207juan/EVA/blob/main/docs/es/README.md) · [Español](https://github.com/2207juan/EVA/blob/main/docs/es/README.md) / [English](https://github.com/2207juan/EVA/blob/main/docs/en/README.md)

# Probar e instalar EVA

1. En la presentación, pulsa **Descargar ISO (64)** para un PC de 64 bits o **ISO (32)** para uno de 32 bits. Si tienes dudas, consulta [Tu PC](compatibility.md).
2. Prepara un USB con [Ventoy](https://www.ventoy.net/en/doc_start.html). Instalar Ventoy borra el USB: guarda antes sus archivos. Después, copia la ISO al USB **sin descomprimirla**.
3. Reinicia y abre el **menú de arranque** del equipo: suele ser **F11, F12, Esc o F9**, según el fabricante. Selecciona el USB y, en Ventoy, la ISO de EVA.
4. Elige **Start Eva Live** para probar EVA. Comprueba que funcionan la pantalla, la red y el sonido; después abre **Instalar EVA** para iniciar Calamares.
5. Sigue el asistente: idioma, zona horaria, teclado, usuario y contraseña. En **Particiones**, elige el disco y la instalación que necesitas; puedes usar las opciones automáticas o el particionado manual. Guarda una copia de tus archivos y revisa el resumen antes de instalar, especialmente si conservas Windows u otro sistema.
6. Al terminar, reinicia y retira el USB cuando se indique. EVA arrancará desde el disco donde la instalaste.

La ISO de 32 bits requiere **i686 con SSE2** y **BIOS o UEFI de 32 bits**. Para un procesador de 64 bits, usa la ISO (64), aunque tenga poca RAM.

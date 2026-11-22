[← EVA](https://github.com/2207juan/EVA/blob/main/docs/en/README.md) · [Español](https://github.com/2207juan/EVA/blob/main/docs/es/README.md) / [English](https://github.com/2207juan/EVA/blob/main/docs/en/README.md)

# Try and install EVA

1. On the presentation page, choose **Download ISO (64)** for a 64-bit PC or **ISO (32)** for a 32-bit PC. Not sure? Check [Your PC](compatibility.md).
2. Prepare a USB drive with [Ventoy](https://www.ventoy.net/en/doc_start.html). Installing Ventoy erases the USB drive: back up its files first. Then copy the ISO onto it **without extracting it**.
3. Restart and open your computer’s **boot menu**, usually **F11, F12, Esc or F9**, depending on the manufacturer. Select the USB drive, then choose the EVA ISO in Ventoy.
4. Select **Start Eva Live** to try EVA. Check that your display, network and audio work; then open **Install EVA** to start Calamares.
5. Follow the wizard: language, time zone, keyboard, account and password. Under **Partitions**, select the disk and installation you need; automatic and manual partitioning options are available. Back up your files and review the summary before installing, especially if keeping Windows or another system.
6. When installation finishes, restart and remove the USB drive when prompted. EVA will boot from the disk where you installed it.

The 32-bit ISO requires **i686 with SSE2** and **BIOS or 32-bit UEFI**. For a 64-bit processor, use ISO (64), even with little RAM.

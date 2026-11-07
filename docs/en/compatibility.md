[← EVA](https://github.com/2207juan/EVA/blob/main/docs/en/README.md) · [Español](https://github.com/2207juan/EVA/blob/main/docs/es/README.md) / [English](https://github.com/2207juan/EVA/blob/main/docs/en/README.md)

# PC compatibility

| Component | Current target |
| :-- | :-- |
| CPU / architecture | 64-bit Intel or AMD **x86_64**. This is not an ARM image. |
| Boot | BIOS or UEFI. Secure Boot support has not been certified. |
| Graphics | Intel, AMD or NVIDIA with a driver supported by the GPU and EVA's Wayland compositor. XWayland handles compatible X11 apps. |
| RAM | For a first trial, **8 GiB is a practical recommendation**, especially with a browser. A measured minimum has not been established. |
| Storage | An SSD is recommended. Reserve **30 GiB or more** for a trial installation plus space for your own files and applications. This is guidance, not a measured minimum. |
| Network | Required for downloads, updates and online services. Local tools remain available offline. |

## CPU and graphics details

The current profile builds for `x86_64`; it does not publish separate x86-64-v3/v4 builds or claim CachyOS kernel optimizations. Intel and AMD microcode, Linux firmware, Mesa/Vulkan and NVIDIA components are included in the build profile. An installed package does not guarantee support for every GPU generation. Confirm your hardware in the Live session before installing.

## Desktop and laptop

Backlight, keyboard illumination, battery and other controls depend on detected capabilities. Laptop workspace shortcuts avoid function keys; desktop defaults are documented separately in the shortcut reference.

**Beta status:** there is no published certification matrix or comparable performance benchmark yet. These are current targets and trial recommendations, not universal compatibility guarantees.

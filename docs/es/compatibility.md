[← EVA](https://github.com/2207juan/EVA/blob/main/docs/es/README.md) · [Español](https://github.com/2207juan/EVA/blob/main/docs/es/README.md) / [English](https://github.com/2207juan/EVA/blob/main/docs/en/README.md)

# Compatibilidad del PC

| Componente | Objetivo actual |
| :-- | :-- |
| CPU / arquitectura | Intel o AMD de 64 bits **x86_64**. Esta imagen no es para ARM. |
| Arranque | BIOS o UEFI. La compatibilidad con Secure Boot no está certificada. |
| Gráficos | Intel, AMD o NVIDIA con un controlador compatible con la GPU y el compositor Wayland de EVA. XWayland permite aplicaciones X11 compatibles. |
| RAM | Para una primera prueba, **8 GiB es una recomendación práctica**, especialmente con navegador. No se ha establecido un mínimo medido. |
| Almacenamiento | Se recomienda SSD. Reserva **30 GiB o más** para una instalación de prueba, más espacio para tus archivos y aplicaciones. Es orientación, no un mínimo medido. |
| Red | Necesaria para descargas, actualizaciones y servicios en línea. Las herramientas locales se pueden usar sin conexión. |

## CPU y gráficos

El perfil actual construye para `x86_64`; no publica variantes x86-64-v3/v4 ni atribuye a EVA las optimizaciones del kernel de CachyOS. El perfil incluye microcódigo Intel y AMD, firmware Linux, Mesa/Vulkan y componentes NVIDIA. Tener un paquete instalado no garantiza admitir todas las generaciones de GPU. Comprueba tu equipo en la sesión Live antes de instalar.

## PC y portátil

Brillo, iluminación del teclado, batería y otros controles dependen de las capacidades detectadas. Los atajos de escritorios en portátil evitan las teclas de función; la referencia separa los valores de PC y portátil.

**Estado beta:** aún no hay una matriz pública de equipos certificados ni un benchmark comparativo. Son objetivos actuales y recomendaciones de prueba, no una garantía para cualquier equipo.

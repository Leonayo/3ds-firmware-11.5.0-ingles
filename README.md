# Firmware 3DS en inglés 11.5.0

Paquete de firmware para consolas **Nintendo 3DS** orientado a convertir el sistema de **japonés a inglés**. Está pensado para quienes tienen una 3DS de región japonesa y quieren usarla en inglés con menús, mensajes y configuración más accesibles.

## ¿Para qué sirve?

Este firmware ayuda a **modificar y adaptar consolas 3DS japonesas al idioma inglés**, facilitando la configuración del sistema, la navegación por los menús y el uso diario de la consola sin depender del japonés.

**También puede usarse para cambiar el idioma del sistema a español.** Aunque el paquete está basado en firmware en inglés (v11.5.0), el mismo proceso de transferencia de región/idioma sirve si tu objetivo es dejar la consola en **español** en lugar de inglés. Es decir: no solo JP → EN, también **JP → ES** (o adaptar una base en inglés hacia español según el flujo que sigas con GodMode9).

Es útil si:

- Tienes una 3DS japonesa y quieres cambiar el idioma del sistema a **inglés**.
- Tienes una 3DS japonesa y quieres cambiar el idioma del sistema a **español**.
- Buscas un firmware estable (v11.5.0) para preparar o actualizar tu consola.
- Necesitas una base adecuada antes de instalar homebrew, CFW u otras herramientas.

## Descarga

### Opción 1 — 3ds Nayo HackToolkit (recomendado)

Descarga e instala desde el programa **3ds Nayo HackToolkit** (Windows):

- Marca **Firmware 11.5.0 (JP→EN/ES)** y pulsa *Descargar seleccionados*
- Con **Instalar en SD Card** activado, los archivos del firmware van **directamente a la raíz de la SD** (junto a `mset9.py`, `boot.firm`, etc.) — **no** se crea la carpeta `Firmware-3DS-11.5.0/` en la tarjeta
- El ZIP se extrae en el PC y solo se copian los archivos necesarios a la SD

### Opción 2 — Release de GitHub

👉 [Descargar v11.5.0](https://github.com/Leonayo/3ds-firmware-11.5.0-ingles/releases/tag/v11.5.0)

Archivo: `3ds.Firmware.Ingles.11.5.0.zip` (~714 MB)

Tras extraer manualmente, coloca los archivos del firmware (`.bin`, `.sha`, etc.) en la **raíz de la SD** de la 3DS, no dentro de una subcarpeta.

## Archivos típicos en la SD

En la raíz de la tarjeta deberías tener, entre otros:

- `11.5.0-38U_ctrtransfer_o3ds.bin`
- `11.5.0-38U_ctrtransfer_o3ds.bin.sha`

Estos pueden coexistir con el pack MSET9 del repositorio [Nayo-3DS-Herramientas-Completas](https://github.com/Leonayo/Nayo-3DS-Herramientas-Completas).

## Notas

- Usa este firmware bajo tu propia responsabilidad.
- Haz copia de seguridad de tu NAND antes de modificar la consola.
- Asegúrate de que el modelo y la versión de tu 3DS sean compatibles con el proceso que vayas a seguir.
- Para el cambio de idioma/región, sigue una guía fiable (por ejemplo [3ds.hacks.guide](https://3ds.hacks.guide)) y usa GodMode9 con el pack MSET9 si lo necesitas.

---

**Repositorio:** [Leonayo/3ds-firmware-11.5.0-ingles](https://github.com/Leonayo/3ds-firmware-11.5.0-ingles) · **Pack MSET9:** [Leonayo/Nayo-3DS-Herramientas-Completas](https://github.com/Leonayo/Nayo-3DS-Herramientas-Completas)
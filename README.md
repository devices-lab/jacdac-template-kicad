# jacdac-template-kicad

Jacdac RGB module KiCad project files for use as a template when creating new Jacdac modules. 

Based on Altium schematics from the [jacdac-ddk](https://github.com/jacdac/jacdac-ddk) and the [Jacdac KiCad library](https://github.com/mac-aron/jacdac-kicad).

#### Usage
- The script `library/convert.sh` can be used to download component symbols and footprints from LCSC (JLCPCB).
- The jobfile `export-fab-files.kicad_jobset` generates fabrication files to `gerbers/` with the correct settings
  - The column names in the CPL (component placement list) are incorrect for JLCPCB

Check the [neopixel-gerbersockets](../../tree/neopixel-gerbersockets) branch for a version with GerberSockets added.

> [!NOTE]
> The hardware has not been tested yet

<img width="305" alt="image" src="https://github.com/user-attachments/assets/423bf6c6-366c-44d1-ba45-c44d8af13a06" />
<img width="289" alt="image" src="https://github.com/user-attachments/assets/447b0e74-a62d-4660-91b7-2d63118ed6e3" />
<img width="1221" height="843" alt="image" src="https://github.com/user-attachments/assets/1df044b2-9ca8-4070-97ba-e5c04ffd9964" />

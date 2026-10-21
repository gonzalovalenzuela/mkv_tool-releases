# mkv_tool-releases
mkv tool for a cleaner movies and tv shows libraries

all the releases will be published

see more info at http://www.mkvtool.com


# Componentes de terceros

mkv_tool incluye, para no depender de nada instalado en el equipo:

| Componente | Licencia | Dónde |
|---|---|---|
| **MKVToolNix** (`mkvmerge`, `mkvpropedit` y sus librerías) | GPL-2.0-or-later | carpeta `mkvtoolnix/` dentro de la app; texto en `LICENSE-mkvtoolnix.txt` |
| **Python** (intérprete embebido por PyInstaller) | PSF-2.0 | dentro del ejecutable |
| **PyInstaller** (bootloader) | GPL-2.0 con excepción para programas empaquetados | dentro del ejecutable |
| **pywebview** (ventana nativa) | BSD-3-Clause | dentro del ejecutable (macOS/Windows) |

mkv_tool ejecuta MKVToolNix como programas independientes (no enlaza con ellos).

## Código fuente de MKVToolNix (oferta de la GPL)

El código fuente de la versión incluida (ver `mkvtoolnix/VERSION`) está disponible en
<https://mkvtoolnix.download/sources/> y <https://gitlab.com/mbunkus/mkvtoolnix>.
Quien reciba esta aplicación puede pedirlo también a info@mkvtool.com.
Las librerías de sistema copiadas junto a MKVToolNix (Boost, FLAC, libebml, libmatroska, Qt Core, ICU, etc.)
conservan sus propias licencias; consulta los paquetes de origen de tu distribución.

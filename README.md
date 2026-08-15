# EasySampler

Página pública de **EasySampler**, el sampler VST3 de [WDG Technologies](https://github.com/WDG-Technologies).

## Qué es

EasySampler convierte **un archivo de audio** (WAV, FLAC o MP3) en un instrumento MIDI. Lo cargas, eliges o dejas detectar la **root note**, y lo tocas en el piano roll, con un teclado o con el pedal de sustain (CC64).

Sirve para melodizar un one-shot, un chord o una frase sin armar un sampler grande. Un sample a la vez, hasta 16 voces. El audio queda guardado en el proyecto de la DAW.

También incluye una app **Standalone** para probarlo sin abrir el host.

## Descarga

- **Windows 10 / 11**, 64-bit
- Plugin **VST3** + instalador MSI + Standalone
- [Descargar EasySampler-0.2.0.msi](https://github.com/WDG-Technologies/EasySample/releases/download/v1.0/EasySampler-0.2.0.msi)
- [Todas las versiones](https://github.com/WDG-Technologies/EasySample/releases)

Tras instalar: el VST3 queda en `C:\Program Files\Common Files\VST3\` y el Standalone en el menú Inicio. En la DAW, rescanea plugins.

## Página web

`index.html` es la landing de descarga (logo, mock de la UI y botón del MSI). Si activas GitHub Pages en este repo (branch `main`, carpeta `/`), se publica en:

https://wdg-technologies.github.io/EasySample/

## Licencia

El plugin es **código cerrado**. Este repositorio solo publica la página y el instalador, no el source.

VST es marca de Steinberg Media Technologies GmbH.

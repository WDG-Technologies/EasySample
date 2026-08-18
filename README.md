# EasySampler

**Tu sample. Todas las notas.**

EasySampler es un instrumento VST3 de [WDG Technologies](https://github.com/WDG-Technologies): cargas un WAV, FLAC o MP3 y lo tocas como un synth. Un hit, un chord, una voz, un pad — lo melodizas en el piano roll, con teclado MIDI o con el pedal.

No es un rompler. No hay librerías ni capas. Es el sampler de canal que abres, cargas y ya estás escribiendo.

## El problema

Tienes un audio que suena bien. Quieres tocarlo en otras notas, con cola, con pedal, en modo mono si hace falta. Montar eso en un sampler grande te frena. EasySampler no.

## Cómo trabaja

Cargas el archivo. Detecta (o tú eliges) la **root note**: esa tecla suena al tono original; el resto transpone limpio, con resample sinc. Hasta **16 voces**. Al soltar, el **release** funde la cola. El **pedal** (CC64) sostiene. **Cortar nota anterior** apaga la de atrás para bajos y leads.

El sample va **dentro del proyecto**. Cierras la DAW, la abres, sigue ahí.

Si la tecla dura más que el archivo, el audio se acaba (one-shot, como un sampler de canal). Si sueltas antes, entra el release.

## Qué incluye

- Plugin **VST3 64-bit** para Windows 10 / 11  
- App **Standalone** (MIDI o teclas Z–M)  
- Instalador MSI  

[**Descargar EasySampler**](https://github.com/WDG-Technologies/EasySample/releases/download/v1.0/EasySampler-0.2.0.msi) · [Versiones](https://github.com/WDG-Technologies/EasySample/releases) · [Página](https://wdg-technologies.github.io/EasySample/)

Tras instalar: VST3 en `C:\Program Files\Common Files\VST3\`. Rescanea plugins en tu DAW.

Código cerrado. VST es marca de Steinberg Media Technologies GmbH.

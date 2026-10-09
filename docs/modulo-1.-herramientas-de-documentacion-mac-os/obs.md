---
description: Cómo grabé mi pantalla con OBS, paso a paso
icon: circle-dot
---

# OBS : Screen record

## Índice

1. [Introducción](obs.md#introduccion)
2. [Instalar OBS](obs.md#instalar-obs)
3. [Configurar la captura de pantalla](obs.md#configurar-la-captura)
4. [Dar permisos en Mac OS](obs.md#dar-permisos)
5. [Grabar](obs.md#grabar)
6. [Editar la grabación](obs.md#editar-la-grabacion)
7. [Resultado](obs.md#resultado)
8. [Problemas que tuve y cómo los resolví](obs.md#problemas-que-tuve)

## 1. Introducción <a href="#introduccion" id="introduccion"></a>

Para grabar la pantalla elegí **OBS** (Open Broadcaster Software), un programa gratuito y de código abierto.

La Mac ya trae QuickTime para grabar la pantalla, pero OBS ofrece más:

* Grabar el audio de la computadora, no solo el micrófono.
* Combinar varias fuentes, como la pantalla y la cámara web.
* Elegir el formato, la resolución y la calidad del archivo.

Lo usé para grabar el proceso de edición de mi imagen de portada en Affinity.

## 2. Instalar OBS <a href="#instalar-obs" id="instalar-obs"></a>

{% stepper %}
{% step %}
### Descargar

Descargar la versión para Mac OS desde [obsproject.com](https://obsproject.com/) y arrastrar la aplicación a la carpeta Aplicaciones.
{% endstep %}

{% step %}
### Primer inicio

Si aparece el asistente de configuración, elegir **Optimize just for recording**.
{% endstep %}
{% endstepper %}

## 3. Configurar la captura de pantalla <a href="#configurar-la-captura" id="configurar-la-captura"></a>

{% stepper %}
{% step %}
### Agregar una fuente

En el panel **Sources**, abajo, hacer clic en **+** y elegir **macOS Screen Capture**. Ponerle un nombre y aceptar.
{% endstep %}

{% step %}
### Elegir qué capturar

En **Method** elegir:

* **Display Capture** para toda la pantalla.
* **Window Capture** para una sola ventana.
* **Application Capture** para un solo programa.
{% endstep %}

{% step %}
### Ajustar al lienzo

Seleccionar la fuente y presionar **Cmd + F** (clic derecho → **Transform → Fit to screen**) para que toda la pantalla entre en la grabación.
{% endstep %}

{% step %}
### Elegir el formato

En **Settings → Output → Recording Format** elegir **MP4**, que es el formato que se sube sin problemas a Gitbook y se abre en cualquier editor.
{% endstep %}
{% endstepper %}

<figure><img src="../.gitbook/assets/Screenshot 2026-10-09 at 8.45.58 AM (1).png" alt=""><figcaption></figcaption></figure>

## 4. Dar permisos en Mac OS <a href="#dar-permisos" id="dar-permisos"></a>

La primera vez, Mac OS bloquea la grabación de pantalla.

1. Ir a **System Settings → Privacy & Security → Screen & System Audio Recording**.
2. Activar **OBS**.
3. Cerrar y volver a abrir OBS.

## 5. Grabar <a href="#grabar" id="grabar"></a>

{% stepper %}
{% step %}
### Revisar el audio

En **Audio Mixer**, la barra "Mic/Aux" se mueve al hablar. Se silencia desde el ícono del parlante si no se quiere grabar la voz.
{% endstep %}

{% step %}
### Empezar

Hacer clic en **Start Recording**, en el panel Controls (abajo a la derecha), y pasar a la ventana que se quiere mostrar.
{% endstep %}

{% step %}
### Terminar

Volver a OBS y hacer clic en **Stop Recording**.
{% endstep %}

{% step %}
### Encontrar el archivo

Ir a **File → Show Recordings**. Por defecto los videos se guardan en la carpeta Movies.
{% endstep %}
{% endstepper %}

<figure><img src="../.gitbook/assets/Screenshot 2026-10-09 at 8.44.11 AM.png" alt=""><figcaption></figcaption></figure>

## 6. Editar la grabación <a href="#editar-la-grabacion" id="editar-la-grabacion"></a>

OBS solo graba, no edita. Para recortar el video usé iMovie. El proceso está en la página [iMovie : Video editing](capcut.md).

## 7. Resultado <a href="#resultado" id="resultado"></a>

Grabación de pantalla de la edición de imagen en Affinity:

{% embed url="https://youtu.be/rkUOayVnlc8" %}

{% file src="../.gitbook/assets/Video recording with OBS.mp4" %}

## 8. Problemas que tuve y cómo los resolví <a href="#problemas-que-tuve" id="problemas-que-tuve"></a>

<details>

<summary>Solo se grababa una parte de la pantalla</summary>

La pantalla de la Mac tiene más píxeles que el lienzo de OBS (1920 × 1080), así que solo entraba la esquina superior izquierda. Se resuelve seleccionando la fuente y presionando **Cmd + F** (Fit to screen).

</details>

<details>

<summary>La vista previa mostraba una pantalla dentro de otra, como un túnel</summary>

Es normal: OBS se está grabando a sí mismo. Desaparece al minimizar OBS o al pasar a otra ventana.

</details>

<details>

<summary>No encontraba cómo recortar el video en OBS</summary>

OBS no tiene herramientas de edición. El recorte se hace después, en un editor como iMovie o QuickTime.

</details>

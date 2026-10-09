---
description: Cómo edité la imagen de portada de mi wiki con Affinity, paso a paso
icon: camera
---

# Affinity: Image editor

## Índice

1. [Introducción](picsart.md#introduccion)
2. [Instalar y abrir Affinity](picsart.md#instalar-y-abrir-affinity)
3. [Crear el documento](picsart.md#crear-el-documento)
4. [Diseñar la portada](picsart.md#disenar-la-portada)
5. [Exportar la imagen](picsart.md#exportar-la-imagen)
6. [Resultado](picsart.md#resultado)

## 1. Introducción <a href="#introduccion" id="introduccion"></a>

Para la edición de imagen elegí **Affinity**, un programa de diseño para Mac que permite trabajar con vectores y con fotos en el mismo archivo. Lo usé para diseñar la imagen de portada (header) de la página "Acerca de mí" de esta wiki, a partir de una foto.

En este video se ve todo el proceso de edición, grabado con OBS:

{% embed url="https://youtu.be/rkUOayVnlc8" %}

## 2. Instalar y abrir Affinity <a href="#instalar-y-abrir-affinity" id="instalar-y-abrir-affinity"></a>

{% stepper %}
{% step %}
### Descargar

Affinity se descarga desde [affinity.studio](https://www.affinity.studio/) y se instala arrastrando la aplicación a la carpeta Aplicaciones.
{% endstep %}

{% step %}
### Abrir

Al abrirlo aparece la pantalla de inicio, desde donde se crea un documento nuevo o se abre uno existente.
{% endstep %}
{% endstepper %}

## 3. Crear el documento <a href="#crear-el-documento" id="crear-el-documento"></a>

{% stepper %}
{% step %}
### Nuevo documento

En la pantalla de inicio, hacer clic en el botón verde **+** (o ir a **File → New**, Cmd + N).
{% endstep %}

{% step %}
### Definir el tamaño

Gitbook recomienda que las portadas midan **1990 × 480 px**. En el panel de la derecha configuré:

* **Document units:** Pixels
* **Page width:** 1990 px
* **Page height:** 480 px
* **Color format:** RGB/8
{% endstep %}

{% step %}
### Crear

Hacer clic en **Create Document**.
{% endstep %}
{% endstepper %}

<figure><img src="../.gitbook/assets/Screenshot 2026-10-09 at 8.53.25 AM.png" alt="Ventana de nuevo documento en Affinity con las medidas 1990 por 480 px"><figcaption><p>Affinity, crear nuevo documento 1990 x 480 px</p></figcaption></figure>



{% hint style="warning" %}
Gitbook recorta la portada según el ancho de la pantalla. Conviene dejar lo importante en el centro y no poner texto pegado a los bordes.
{% endhint %}

## 4. Diseñar la portada <a href="#disenar-la-portada" id="disenar-la-portada"></a>

La portada tiene tres capas: una foto de fondo, un degradado oscuro y los textos.

{% stepper %}
{% step %}
### Colocar la foto de fondo

Arrastrar la foto al lienzo (o **File → Place**) y ajustarla hasta que cubra todo el documento. Usé una foto de un dinosaurio de MDF cortado con láser.
{% endstep %}

{% step %}
### Dibujar un rectángulo para el degradado

Con la herramienta de rectángulo, dibujar una forma que cubra todo el lienzo, por encima de la foto.
{% endstep %}

{% step %}
### Aplicar el degradado

1. Seleccionar el rectángulo.
2. Presionar **G** para activar la herramienta de relleno (Fill Tool).
3. Hacer clic y arrastrar de izquierda a derecha. El arrastre define la dirección y el largo del degradado.
4. Hacer clic en cada extremo de la línea y elegir su color: transparente a la izquierda y negro a la derecha.

En esta captura oculté la foto para que se vea solo el degradado:

<figure><img src="../.gitbook/assets/Screenshot 2026-10-09 at 8.54.31 AM.png" alt="Rectángulo con degradado de transparente a negro en Affinity"><figcaption><p>El degradado solo, con la capa de la foto oculta</p></figcaption></figure>
{% endstep %}

{% step %}
### Revisar el degradado sobre la foto

Al volver a mostrar la foto, el lado derecho queda oscuro. Ese espacio sirve para que el texto blanco se lea bien.

<figure><img src="../.gitbook/assets/Screenshot 2026-10-09 at 8.55.01 AM.png" alt="Foto del dinosaurio con el degradado negro a la derecha"><figcaption><p>La foto con el degradado encima</p></figcaption></figure>
{% endstep %}

{% step %}
### Agregar los textos

Con la herramienta de texto, escribir el nombre y el correo en color blanco sobre la zona oscura, y ajustar su posición respecto a los bordes.

<figure><img src="../.gitbook/assets/Screenshot 2026-10-09 at 8.56.13 AM.png" alt="Portada con los textos Soledad Benitez y el correo en blanco"><figcaption><p>La portada con los textos</p></figcaption></figure>
{% endstep %}

{% step %}
### Ajustar el color

Agregué una capa de ajuste de saturación y tono para corregir los colores de la foto.
{% endstep %}
{% endstepper %}

## 5. Exportar la imagen <a href="#exportar-la-imagen" id="exportar-la-imagen"></a>

{% stepper %}
{% step %}
### Exportar

Ir a **File → Export**, elegir el formato **JPEG** y guardar.
{% endstep %}

{% step %}
### Subir a Gitbook

En Gitbook, abrir la página, hacer clic en **Add cover** arriba del título y subir la imagen.
{% endstep %}
{% endstepper %}

## 6. Resultado <a href="#resultado" id="resultado"></a>

Esta es la imagen final, que funciona como header de mi wiki:

<figure><img src="../.gitbook/assets/cover_dinayor_gitbook.jpg" alt="Portada de la wiki editada en Affinity"><figcaption><p>Portada editada en Affinity</p></figcaption></figure>

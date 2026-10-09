---
description: Cómo edité el video del recorrido del FabLab con iMovie, paso a paso
icon: video
---

# iMovie : Video editing

## Índice

1. [Introducción](capcut.md#introduccion)
2. [Instalar iMovie](capcut.md#instalar-imovie)
3. [Importar el video](capcut.md#importar-el-video)
4. [Cortar el video](capcut.md#cortar-el-video)
5. [Acelerar el video](capcut.md#acelerar-el-video)
6. [Exportar](capcut.md#exportar)
7. [Resultado](capcut.md#resultado)
8. [Problemas que tuve y cómo los resolví](capcut.md#problemas-que-tuve)

## 1. Introducción <a href="#introduccion" id="introduccion"></a>

Para la edición de video elegí **iMovie**, el editor de Apple. Es gratuito, no agrega marca de agua y alcanza para cortar, unir y acelerar clips.

Lo usé para editar el video del recorrido del FabLab, donde muestro todas las máquinas que nos presentaron el primer día. El video lo grabé con mi iPhone y lo pasé a la computadora como archivo `.mov`.

## 2. Instalar iMovie <a href="#instalar-imovie" id="instalar-imovie"></a>

{% stepper %}
{% step %}
### Descargar

Abrir el **App Store** de la Mac, buscar "iMovie" y hacer clic en **Obtener**. Es una descarga de varios GB.
{% endstep %}

{% step %}
### Abrir

Al abrirlo, elegir **Create New → Movie** para empezar un proyecto.
{% endstep %}
{% endstepper %}

## 3. Importar el video <a href="#importar-el-video" id="importar-el-video"></a>

{% stepper %}
{% step %}
### Importar

iMovie no tiene un comando "Abrir". Los videos se traen con **File → Import Media**, o arrastrando el archivo a la ventana.
{% endstep %}

{% step %}
### Llevar a la línea de tiempo

Arrastrar el clip desde la biblioteca hasta la línea de tiempo, en la parte inferior.
{% endstep %}
{% endstepper %}

<figure><img src="../.gitbook/assets/Screenshot 2026-10-09 at 8.49.28 AM.png" alt=""><figcaption><p>Video cortado con Cmd + B</p></figcaption></figure>

## 4. Cortar el video <a href="#cortar-el-video" id="cortar-el-video"></a>

**Para recortar el inicio o el final:** pasar el cursor por el borde del clip hasta que aparezcan dos flechas y arrastrar hacia adentro.

**Para quitar una parte del medio:**

{% stepper %}
{% step %}
### Primer corte

Mover el cabezal (la línea blanca vertical) hasta donde empieza la parte que sobra y presionar **Cmd + B**.
{% endstep %}

{% step %}
### Segundo corte

Mover el cabezal hasta donde termina esa parte y presionar **Cmd + B** otra vez.
{% endstep %}

{% step %}
### Borrar

Seleccionar el pedazo del medio y presionar **Delete**. Los clips restantes se unen solos.
{% endstep %}
{% endstepper %}

## 5. Acelerar el video <a href="#acelerar-el-video" id="acelerar-el-video"></a>

El recorrido era largo, así que lo aceleré.

{% stepper %}
{% step %}
### Seleccionar el clip

Hacer clic sobre el clip en la línea de tiempo.
{% endstep %}

{% step %}
### Abrir el control de velocidad

Hacer clic en el ícono de **velocímetro**, arriba de la vista previa.
{% endstep %}

{% step %}
### Elegir la velocidad

En el menú **Speed** elegir **Fast** y luego 2x, 4x, 8x o 20x. Con **Custom** se puede escribir otro porcentaje.
{% endstep %}
{% endstepper %}

{% hint style="warning" %}
Al acelerar, el audio suena más agudo. Se corrige tildando **Preserve Pitch**, o silenciando el clip si el sonido no importa.
{% endhint %}

<figure><img src="../.gitbook/assets/Screenshot 2026-10-09 at 8.50.13 AM.png" alt=""><figcaption><p>Acercamiento del menu de velocidad (mirar iconos y menu arriba)</p></figcaption></figure>

## 6. Exportar <a href="#exportar" id="exportar"></a>

{% stepper %}
{% step %}
### Compartir

Hacer clic en el ícono **Share** (arriba a la derecha) y elegir **Export File**.
{% endstep %}

{% step %}
### Configurar

Dejar la resolución en 1080p y la calidad en High, y hacer clic en **Next**.
{% endstep %}

{% step %}
### Guardar

Poner un nombre, elegir la carpeta y hacer clic en **Save**. El archivo se exporta en `.mp4`. El proyecto en sí se guarda automáticamente.
{% endstep %}
{% endstepper %}

## 7. Resultado <a href="#resultado" id="resultado"></a>

Video del recorrido del FabLab, editado y acelerado en iMovie:

{% embed url="https://youtu.be/ZZDohFmEaRg" %}

{% file src="../.gitbook/assets/Video-speed-up-del-recorrido.mp4" %}



## 8. Problemas que tuve y cómo los resolví <a href="#problemas-que-tuve" id="problemas-que-tuve"></a>

<details>

<summary>No encontraba cómo abrir un video en iMovie</summary>

iMovie no abre archivos directamente. Hay que crear un proyecto y traer el video con **File → Import Media**.

</details>

<details>

<summary>iMovie no acepta videos .mkv</summary>

Algunas versiones de OBS graban en `.mkv`, un formato que iMovie no lee. Se convierte desde OBS con **File → Remux Recordings**, que genera un `.mp4`.

</details>

---
description: Cómo creé mi wiki de la pasantía con GitHub y GitBook, paso a paso
icon: github
---

# Github y Gitbook

## Índice

1. [Introducción](github-y-gitbook.md#introduccion)
2. [Crear una cuenta en Github](github-y-gitbook.md#crear-una-cuenta-en-github)
3. [Crear una cuenta en Gitbook](github-y-gitbook.md#crear-una-cuenta-en-gitbook)
4. [Conectar Github a Gitbook](github-y-gitbook.md#conectar-github-a-gitbook)
5. [Crear mi wiki](github-y-gitbook.md#crear-mi-wiki)
6. [Problemas que tuve y cómo los resolví](github-y-gitbook.md#problemas-que-tuve)

## 1. Introducción <a href="#introduccion" id="introduccion"></a>

Esta guía muestra cómo armé la wiki donde documento mi pasantía en el FabLab. Para hacerlo usé dos herramientas que trabajan juntas:

* [**Github**](https://github.com/) es donde se guardan los archivos de la wiki y el historial de todos los cambios. Cada página es un archivo de texto en formato Markdown.
* [**Gitbook**](https://www.gitbook.com/) es donde se escribe y se publica la wiki. Convierte esos archivos en un sitio web con menú, buscador y diseño.

Las dos se conectan con una función llamada **Git Sync**: lo que edito en Gitbook se guarda en Github, y lo que cambia en Github aparece en Gitbook.

Mis enlaces:

* [Mi Github](https://github.com/solbenitezca/Soledad-Benitez)
* [Mi Gitbook](https://sol-benitez.gitbook.io/soledad-benitez)

Utilicé a Claude para que me ayude con el setup. Este fue el prompt que le di:

<figure><img src="../.gitbook/assets/Screenshot 2026-10-06 at 10.49.27 AM.png" alt="Prompt que le di a Claude para el setup"><figcaption><p>Prompt para Claude</p></figcaption></figure>

## 2. Crear una cuenta en Github <a href="#crear-una-cuenta-en-github" id="crear-una-cuenta-en-github"></a>

{% stepper %}
{% step %}
### Registrarse

Entrar a [github.com](https://github.com/) y hacer clic en **Sign up**. Pide un correo, una contraseña y un nombre de usuario. Después llega un código de verificación al correo.
{% endstep %}

{% step %}
### Crear un repositorio

Un repositorio es la carpeta donde vive el proyecto. Se crea con el botón **New** (o el signo **+** arriba a la derecha → **New repository**).

* **Nombre:** el mío se llama `Soledad-Benitez`.
* **Visibilidad:** Public, para que el FabLab pueda verlo.
* **Rama principal:** `main`.
{% endstep %}

{% step %}
### Verificar

Al terminar, el repositorio queda disponible en una dirección como `github.com/usuario/nombre-del-repositorio`.
{% endstep %}
{% endstepper %}

<figure><img src="../.gitbook/assets/Screenshot 2026-10-09 at 9.35.57 AM.png" alt=""><figcaption><p>Crear nuevo repositorio</p></figcaption></figure>



<figure><img src="../.gitbook/assets/Screenshot 2026-10-09 at 9.36.15 AM.png" alt=""><figcaption><p>Repositorio creado</p></figcaption></figure>



## 3. Crear una cuenta en Gitbook <a href="#crear-una-cuenta-en-gitbook" id="crear-una-cuenta-en-gitbook"></a>

{% stepper %}
{% step %}
### Registrarse

Entrar a [gitbook.com](https://www.gitbook.com/) y hacer clic en **Sign up**. Conviene elegir **Sign up with GitHub**, porque así las dos cuentas quedan vinculadas desde el principio.
{% endstep %}

{% step %}
### Crear la organización y el sitio

Gitbook pide un nombre para la organización y crea el primer sitio. El mío se llama "Soledad Benitez" y tiene un espacio de contenido llamado "Docs".
{% endstep %}

{% step %}
### Tener en cuenta el plan

La cuenta empieza con una prueba gratuita de 14 días del plan más completo. Al terminar la prueba hay que revisar qué funciones siguen disponibles en el plan gratuito.
{% endstep %}
{% endstepper %}

<figure><img src="../.gitbook/assets/Screenshot 2026-10-09 at 9.38.03 AM.png" alt=""><figcaption><p>gitbook en modo de edicion</p></figcaption></figure>

## 4. Conectar Github a Gitbook <a href="#conectar-github-a-gitbook" id="conectar-github-a-gitbook"></a>

{% stepper %}
{% step %}
### Abrir Git Sync

Dentro del espacio "Docs", abrir la opción de **Git Sync** en la barra superior y elegir **GitHub**.
{% endstep %}

{% step %}
### Autorizar a Gitbook

Github pide permiso para instalar la aplicación de Gitbook. Se puede dar acceso solo al repositorio de la wiki, que es lo más seguro.
{% endstep %}

{% step %}
### Elegir repositorio y rama

Seleccionar el repositorio (`Soledad-Benitez`) y la rama (`main`).
{% endstep %}

{% step %}
### Elegir la dirección de la primera sincronización

* **GitHub → GitBook** si el contenido ya está en el repositorio.
* **GitBook → GitHub** si el contenido ya está escrito en Gitbook.

En mi caso la estructura de módulos ya estaba en Github, así que elegí GitHub → GitBook.
{% endstep %}

{% step %}
### Verificar

Cuando termina, arriba aparece el estado **Synced**. Desde ese momento los cambios viajan en las dos direcciones.
{% endstep %}
{% endstepper %}

## 5. Crear mi wiki <a href="#crear-mi-wiki" id="crear-mi-wiki"></a>

{% stepper %}
{% step %}
### Armar la estructura

Organicé la wiki en módulos, y cada módulo tiene sus páginas:

* Acerca de mí
* Módulo 1. Herramientas de documentación (Mac OS)

Los demás módulos los voy a ir agregando a medida que avance la pasantía.

Cada página tiene un ícono, que se elige haciendo clic al lado del título.
{% endstep %}

{% step %}
### Editar una página

Con Git Sync activado, las páginas están en modo lectura. Para editar:

1. Hacer clic en **Edit** (arriba a la derecha). Esto abre un _change request_, que es un borrador de los cambios.
2. Escribir sobre la página. Con la tecla `/` se insertan imágenes, títulos, videos y otros bloques.
3. Hacer clic en **Merge** para aplicar los cambios.
{% endstep %}

{% step %}
### Agregar una portada

Arriba del título de la página está la opción **Add cover**. El tamaño recomendado para la imagen es de 1990 × 480 px. La mía la diseñé en Affinity.
{% endstep %}

{% step %}
### Publicar

Con el botón **Publish** el sitio queda público y Gitbook le asigna una dirección. La mía es [sol-benitez.gitbook.io/soledad-benitez](https://sol-benitez.gitbook.io/soledad-benitez).
{% endstep %}
{% endstepper %}

<figure><img src="../.gitbook/assets/Screenshot 2026-10-09 at 9.38.49 AM.png" alt=""><figcaption></figcaption></figure>

## 6. Problemas que tuve y cómo los resolví <a href="#problemas-que-tuve" id="problemas-que-tuve"></a>

<details>

<summary>No me dejaba editar las páginas</summary>

Estaba en modo lectura. Con Git Sync activado hay que hacer clic en **Edit** para abrir un change request antes de poder escribir.

</details>

<details>

<summary>Hice Merge y el sitio publicado seguía mostrando la versión anterior</summary>

Los cambios sí estaban aplicados, pero el navegador mostraba una copia guardada en caché. Se resuelve recargando sin caché (en Safari, **Cmd + Option + R**) o abriendo el sitio en una ventana privada.

</details>

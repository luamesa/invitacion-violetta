# Invitación de Cumpleaños — Violeta

Invitación web interactiva desarrollada con **HTML, CSS y JavaScript**, diseñada para presentar información de un evento de cumpleaños de manera visual, responsive e interactiva.

El proyecto incorpora una cuenta regresiva, confirmación de asistencia mediante WhatsApp y animaciones generadas con JavaScript y Canvas.

## Características

* Diseño responsive para dispositivos móviles y computadores.
* Invitación digital personalizada.
* Cuenta regresiva para el evento.
* Confirmación de asistencia mediante WhatsApp.
* Animaciones de globos y corazones.
* Elementos gráficos generados mediante HTML5 Canvas.
* Diseño visual basado en una temática de cumpleaños.
* Metadatos Open Graph para compartir la invitación en redes sociales y aplicaciones de mensajería.
* Favicon personalizado.
* Interfaz desarrollada sin frameworks de frontend.

## Tecnologías

* HTML5
* CSS3
* JavaScript
* HTML5 Canvas
* Responsive Web Design
* Open Graph
* WhatsApp Web API

## Estructura

```text
invitacion-violetta/
│
└── index.html
```

El proyecto está desarrollado en un único archivo HTML que contiene la estructura, estilos y funcionalidades JavaScript de la invitación.

## Funcionalidades

### Cuenta regresiva

JavaScript calcula dinámicamente el tiempo restante hasta la fecha configurada del evento y actualiza:

* Días
* Horas
* Minutos
* Segundos

La función utiliza `setInterval()` para actualizar el contador cada segundo.

### Confirmación mediante WhatsApp

La invitación genera dinámicamente un enlace de WhatsApp con un mensaje predefinido para facilitar la confirmación de asistencia.

La URL utiliza el formato:

```text
https://wa.me/
```

y permite abrir la conversación directamente desde el botón de confirmación.

### Animaciones con Canvas

El proyecto utiliza el elemento HTML5:

```html
<canvas>
```

para generar una animación de fondo con diferentes elementos decorativos.

JavaScript controla:

* Posición de los elementos.
* Velocidad de movimiento.
* Tamaño.
* Tipo de figura.
* Color.
* Animación mediante `requestAnimationFrame()`.

Las figuras utilizadas incluyen corazones y globos.

### Diseño responsive

Se incluyen reglas CSS mediante `@media` para adaptar la interfaz a dispositivos móviles.

En pantallas pequeñas se ajustan:

* Tamaño de los títulos.
* Tamaño de las tarjetas.
* Botones.
* Distribución del contenido.

## Compartir en redes sociales

El proyecto incluye metadatos Open Graph y Twitter Card para controlar la información mostrada cuando la invitación se comparte mediante plataformas compatibles.

Se configuran elementos como:

* Título.
* Descripción.
* Imagen.
* Tipo de contenido.
* URL.

## Ejecución

El proyecto es una aplicación web estática y no requiere:

* Backend.
* Base de datos.
* Node.js.
* Servidor de aplicaciones.

Para ejecutarlo localmente basta con abrir:

```text
index.html
```

en un navegador web.

También puede publicarse mediante servicios de hosting estático como GitHub Pages o Netlify.

## Objetivo del proyecto

El proyecto fue desarrollado como una experiencia práctica de creación de interfaces web interactivas, aplicando conocimientos de:

* HTML.
* CSS.
* JavaScript.
* Manipulación del DOM.
* Eventos.
* Animaciones.
* Canvas.
* Diseño responsive.
* Integración con enlaces externos.

## Autor

**Luis Mesa**

Proyecto personal de desarrollo web.

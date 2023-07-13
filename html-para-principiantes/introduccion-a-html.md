## ¿Qué es HTML?

HTML (HyperText Markup Language) es el lenguaje de marcado estándar utilizado para crear y estructurar el contenido de las páginas web. Permite definir la estructura y presentación de los elementos en una página, como encabezados, párrafos, enlaces, imágenes y más. HTML utiliza etiquetas para marcar los diferentes elementos y proporciona instrucciones al navegador sobre cómo mostrar el contenido.

## Estructura básica de un documento HTML

Un documento HTML sigue una estructura básica que consta de las siguientes partes:

```html
<!DOCTYPE>
<html>
  <head>
    <title>Título de la página</title>
  </head>
  <body>
    <!-- Contenido de la página -->
  </body>
</html>
```

- `<!DOCTYPE html>`: Esta declaración define la versión de HTML que se utilizará en el documento (HTML5 en este caso).
- `<html>`: La etiqueta `<html>` es el contenedor principal de todo el contenido de la página.
- `<head>`: La sección `<head>` proporciona información sobre el documento, como el título de la página que se muestra en la barra de título del navegador.
- `<title>`: La etiqueta `<title>` define el título de la página, que aparecerá en la pestaña del navegador.
- `<body>`: El elemento `<body>` contiene el contenido visible de la página web, como texto, imágenes, enlaces, etc.

## Etiquetas y elementos HTML

HTML utiliza etiquetas para marcar y definir diferentes elementos en una página web. Aquí tienes algunos ejemplos de etiquetas comunes:

- Encabezados: Los encabezados se utilizan para estructurar el contenido de la página en diferentes niveles de importancia. Los encabezados van desde `<h1>` (más importante) hasta `<h6>` (menos importante).

```html
<h1>Este es un encabezado de nivel 1</h1>
```

- Párrafos: Los párrafos se definen con la etiqueta `<p>`.

```html
<p>Este es un párrafo de ejemplo.</p>
```

- Enlaces: Los enlaces se crean con la etiqueta `<a>`, y se utiliza el atributo `href` para especificar la URL de destino.

```html
<a href="https://www.ejemplo.com">Este es un enlace a Ejemplo</a>
```

- Imágenes: Las imágenes se insertan utilizando la etiqueta `<img>`, y se utiliza el atributo `src` para especificar la URL de la imagen.

```html
<img src="ruta-de-la-imagen.jpg" alt="Texto alternativo" />
```

Estos son solo algunos ejemplos de etiquetas y elementos HTML. HTML ofrece una amplia gama de etiquetas y atributos para dar formato y estructura al contenido de una página web.

Recuerda que en HTML, las etiquetas se abren con `<etiqueta>` y se cierran con `</etiqueta>`. El contenido se coloca entre las etiquetas de apertura y cierre.

## Repite lo que aprendiste

Completa los campos de las siguientes etiquetas:

```html
<!DOCTYPE html>
<html>
    <head>
        <{title}>Título de la página</{title}>
    </head>
    <body>
        <{h1}>Este es un encabezado de nivel 1</{h1}>
        <{h2}>Este es un encabezado de nivel 2</{h2}>
        <{h3}>Este es un encabezado de nivel 3</{h3}>
        <{h4}>Este es un encabezado de nivel 4</{h4}>
        <{h5}>Este es un encabezado de nivel 5</{h5}>
        <{h6}>Este es un encabezado de nivel 6</{h6}>
        <{p}>Este es un párrafo de ejemplo.</{p}>
        <{a} href="https://www.ejemplo.com">Este es un enlace a Ejemplo</{a}>
        <{img} src="ruta-de-la-imagen.jpg" alt="Texto alternativo">
    </body>
</html>
```

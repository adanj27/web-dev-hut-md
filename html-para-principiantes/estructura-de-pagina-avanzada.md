## Estructura de página avanzada

La estructura de página avanzada se refiere a organizar el contenido utilizando etiquetas semánticas como `<header>`, `<nav>`, `<main>`, `<footer>`, `<section>` y `<article>` para mejorar la claridad, accesibilidad y significado del contenido.

```html
<header>
  <h1>Nombre del sitio</h1>
  <nav>
    <ul>
      <li><a href="“#”">Inicio</a></li>
      <li><a href="“#”">Acerca de</a></li>
      <li><a href="“#”">Contacto</a></li>
    </ul>
  </nav>
</header>
```

- `<header>`: La etiqueta `<header>` se utiliza para representar el encabezado de una página o sección. Contiene elementos como el logotipo, el título de la página y menús de navegación.
- `nav`: La etiqueta `<nav>` se utiliza para agrupar los enlaces de navegación de una página. Proporciona una sección específica para la navegación del sitio.

```html
<main>
  <h1>Título del contenido principal</h1>
  <p>Contenido principal de la página.</p>
</main>
```

- `<main>`: La etiqueta `<main>` se utiliza para representar el contenido principal de una página. Contiene el contenido central y único de la página, excluyendo la cabecera, el pie de página y la navegación.

```html
<footer>
  <p>© 2023 Nombre del sitio. Todos los derechos reservados.</p>
  <nav>
    <ul>
      <li><a href="“#”">Política de privacidad</a></li>
      <li><a href="“#”">Términos y condiciones</a></li>
    </ul>
  </nav>
</footer>
```

- `<footer>`: La etiqueta `<footer>` se utiliza para representar el pie de página de una página o sección. Contiene información de derechos de autor, enlaces relacionados y otra información similar.

## Agrupación de elementos

La agrupación de elementos se refiere a utilizar las etiquetas `<div>` y `<span>` en HTML para organizar y estructurar elementos relacionados. `<div>` se utiliza para agrupar elementos en bloques, mientras que `<span>` se usa para agrupar elementos en línea.

```html
<div>
  <h2>Título de sección</h2>
  <p>Este es un texto de ejemplo con <span>parte del texto resaltado</span>.</p>
</div>
```

- `<div>`: La etiqueta `<div>` se utiliza para agrupar y contener elementos en bloques. Es útil para aplicar estilos CSS y estructurar el diseño de una página.
- `<span>`: La etiqueta `<span>` se utiliza para agrupar y aplicar estilos a elementos en línea, como texto o fragmentos de texto. No implica ningún cambio estructural en la página.

## Secciones y artículos

Las secciones y los artículos son etiquetas semánticas en HTML que permiten organizar y estructurar el contenido de una página de manera significativa. `<section>` se utiliza para agrupar contenido relacionado temáticamente, mientras que `<article>` se utiliza para representar contenido independiente y autocontenido.

```html
<section>
  <h2>Sección 1</h2>
  <p>Contenido de la sección 1.</p>
</section>

<section>
  <h2>Sección 2</h2>
  <p>Contenido de la sección 2.</p>
</section>
```

- `<section>`: La etiqueta `<section>` se utiliza para agrupar contenido relacionado temáticamente en una página. Proporciona una forma de dividir el contenido en secciones claras y distintas.

```html
<article>
  <h2>Título del artículo</h2>
  <p>Contenido del artículo.</p>
</article>
```

- `<article>`: La etiqueta `<article>` se utiliza para representar contenido independiente y autocontenido en una página. Puede ser un artículo de noticias, un blog, un comentario, etc.

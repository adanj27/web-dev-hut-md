 # Creación de enlaces

La etiqueta `<a>` se utiliza para crear enlaces en HTML. Aquí tienes un ejemplo de cómo se ve su sintaxis básica:
```html
<a href="url_del_destino">Texto del enlace</a>
```
- `href`: El atributo `href` especifica la URL de destino del enlace.

# Enlaces internos y externos
Los enlaces pueden apuntar tanto a páginas internas de un sitio web como a páginas externas en Internet. Aquí tienes información sobre cómo crear enlaces internos y externos:
- Enlaces internos: Para crear un enlace interno, debes especificar la ruta de la página dentro del atributo `href`. Puedes utilizar rutas relativas o absolutas, dependiendo de la estructura de tu sitio web.
- Enlaces externos: Para enlazar a una página externa, simplemente debes proporcionar la URL completa dentro del atributo `href`.

# Enlaces a secciones específicas de una página

HTML permite enlazar secciones específicas de una página utilizando identificadores o anclas. Para hacer esto, sigue estos pasos:
- Agrega un identificador único a la sección objetivo utilizando el atributo `id`.
```html
<section id="section1">Contenido de la sección 1</section>
```
- Crea un enlace que apunte a ese identificador utilizando el símbolo `#` seguido del identificador.
```html
<section href="#section1">Ir a la sección 1</section>
```

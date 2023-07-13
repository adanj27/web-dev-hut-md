## Elementos de formulario

Los formularios son una parte fundamental de las páginas web, ya que permiten a los usuarios enviar información al servidor. Estos son algunos de los elementos básicos que se utilizan en los formularios:

```html
<input type="text" name="nombre" placeholder="Ingresar su nombre" />
```

`<input>`: Este elemento se utiliza para crear campos de entrada de datos. Hay varios tipos de `<input>` que se pueden utilizar, como `text` para campos de texto, `password` para contraseñas, `email` para direcciones de correo electrónico, `number` para números, etc.

```html
<textarea name="mensaje" rows="4" cols="40">Ingrese su mensaje aquí</textarea>
```

- `<textarea>`: Se utiliza para crear un campo de texto de varias líneas en el que los usuarios pueden escribir comentarios, mensajes largos, etc.

```html
<select name="ciudad">
  <option value="Madrid">Madrid</option>
  <option value="Barcelona">Barcelona</option>
  <option value="Valencia">Valencia</option>
</select>
```

- `<select>`: Este elemento se utiliza para crear listas desplegables, donde los usuarios pueden seleccionar una opción de una lista.

## Botones

Los botones son elementos interactivos que permiten a los usuarios enviar formularios, realizar acciones o activar eventos específicos.

```html
<button type="submit">Enviar</button>
```

- `<button>`: Se utiliza para crear botones en HTML.
- `type`: Se establece en `"submit"` para indicar que este botón es el botón de envío del formulario.

## Uso de atributos en los elementos de formulario

Los atributos son valores adicionales que se pueden agregar a los elementos de formulario para proporcionar información adicional o configurar su comportamiento. Algunos atributos comunes para los elementos de formulario son:

```html
<input type="text" name="nombre" placeholder="Ingresar su nombre" />
```

- `name`: Define un nombre para el elemento de formulario, que se utilizará para identificar el valor del campo cuando se envíe el formulario.
- `placeholder`: Proporciona un texto de ejemplo o una pista para el usuario sobre lo que se espera en el campo de entrada.

```html
<input type="text" name="nombre" value="Nombre" />
```

- `value`: Establece un valor predeterminado para el campo de entrada.

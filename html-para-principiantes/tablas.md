## Creación de tablas

Las tablas en HTML se crean utilizando las etiquetas `<table>`, `<tr>` y `<td>`. Aquí tienes un ejemplo básico de cómo crear una tabla con dos filas y dos columnas:

```html
<table>
  <tr>
    <td>Celda 1</td>
    <td>Celda 2</td>
  </tr>
  <tr>
    <td>Celda 3</td>
    <td>Celda 4</td>
  </tr>
</table>
```

- `<table>`: La etiqueta `<table>` se utiliza para crear una tabla en HTML. Esta etiqueta delimita el inicio y el final de la tabla. Todos los elementos de la tabla deben estar contenidos dentro de esta etiqueta.
- `<tr>`: La etiqueta `<tr>` (table row) se utiliza para crear filas dentro de la tabla. Cada fila de la tabla debe estar contenida dentro de una etiqueta `<tr>`. Esta etiqueta marca el inicio y el final de una fila.
- `<td>`: La etiqueta `<td>` (table data) se utiliza para crear celdas dentro de una fila de la tabla. Cada celda debe estar contenida dentro de una etiqueta `<td>`. Esta etiqueta marca el inicio y el final de una celda.

## Encabezados de tabla

Para agregar encabezados a una tabla, se utiliza la etiqueta `<th>`. Por convención, los encabezados suelen ubicarse en la primera fila de la tabla, dentro de la etiqueta `<tr>`. Aquí tienes un ejemplo de cómo agregar encabezados a una tabla:

```html
<table>
  <tr>
    <th>Encabezado 1</th>
    <th>Encabezado 2</th>
  </tr>
  <tr>
    <td>Celda 1</td>
    <td>Celda 2</td>
  </tr>
  <tr>
    <td>Celda 3</td>
    <td>Celda 4</td>
  </tr>
</table>
```

- `<th>`: La etiqueta `<th>` (table header) se utiliza para crear encabezados de tabla. A diferencia de la etiqueta `<td>`, que se utiliza para datos regulares, `<th>` se utiliza específicamente para los encabezados de la tabla. Por convención, los encabezados se suelen colocar en la primera fila de la tabla dentro de la etiqueta `<tr>`.

## Combinación de celdas

En HTML, es posible combinar celdas horizontal o verticalmente para crear estructuras más complejas. Esto se logra mediante el uso de los atributos colspan y rowspan en las etiquetas `<td>` o `<th>`. Aquí tienes un ejemplo de cómo combinar celdas:

```html
<table>
  <tr>
    <th colspan="2">Encabezado 1 y 2 combinados</th>
  </tr>
  <tr>
    <td rowspan="2">Celda 1<br />combinada</td>
    <td>Celda 2</td>
  </tr>
  <tr>
    <td>Celda 3</td>
    <td>Celda 4</td>
  </tr>
</table>
```

- `colspan`: El atributo `colspan` se utiliza para combinar celdas horizontalmente. Se agrega a la etiqueta `<td>` o `<th>` y especifica cuántas columnas debe ocupar la celda combinada. Por ejemplo, `colspan="2"` indica que la celda se extenderá a lo largo de dos columnas.
- `rowspan`: El atributo `rowspan` se utiliza para combinar celdas verticalmente. Se agrega a la etiqueta `<td>` o `<th>` y especifica cuántas filas debe ocupar la celda combinada. Por ejemplo, `rowspan="2"` indica que la celda se extenderá a lo largo de dos filas.

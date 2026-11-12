# Proyecto de Clase

## Información personal

**Nombre:** Irene Gómez García

**Usuario de GitHub:** Irenegmez04

**Tema elegido:** Harry Potter

## ¿Por qué he elegido este tema?

He elegido Harry Potter porque es mi saga favorita desde siempre y me apasiona todo su universo mágico. Me encanta su historia, sus personajes y los valores de amistad y valentía que transmite. Además, trabajar en un proyecto sobre algo que me gusta hace que disfrute más del proceso.

## Palabra del día

**Palabra:** Día

## Mapa del sitio

| Página | Archivo | Descripción |
|--------|---------|-------------|
| Inicio | `index.html` | Página principal con información general e imágenes del mundo de Harry Potter. |
| Quién soy | `quien-soy.html` | Información personal sobre la autora del proyecto. |
| Películas | `peliculas.html` | Las películas de la saga, con una tabla de datos (UD5). |
| Personajes | `personajes.html` | Información sobre algunos de los personajes. |
| Contacto | `contacto.html` | Formulario de contacto (UD5). |

## ¿Qué he hecho en esta entrega?

En esta primera entrega he creado una página web sobre Harry Potter utilizando HTML y XML. He organizado el proyecto en diferentes páginas para mostrar la información de una forma más clara.

He creado las siguientes páginas HTML:

- **`index.html`:** página principal con información general sobre el mundo de Harry Potter e imágenes.
- **`quien-soy.html`:** página con información personal sobre la autora del proyecto.
- **`peliculas.html`:** página dedicada a las películas de la saga.
- **`personajes.html`:** página con información sobre algunos de los personajes de Harry Potter.

También he añadido imágenes, textos, listas y enlaces para facilitar la navegación entre las páginas.

Además, he creado el archivo `datos.xml`, donde he organizado la información de las ocho películas de la saga, incluyendo sus títulos, números y duración.

## UD5 · Tablas y formularios

**Tabla y formulario**

En la página `peliculas.html` he añadido una tabla con los datos de las ocho películas de la saga, como el título, el año, el director y la duración. El formulario de `contacto.html` sirve para que los visitantes puedan apuntarse al club de fans y enviarme sus consultas sobre el universo de Harry Potter.

**¿Por qué `post` y no `get`?**

Utilizo el método `post` porque el formulario recoge datos personales, como el nombre, el correo electrónico y el teléfono. Con `post`, los datos se envían en el cuerpo de la petición y no aparecen en la dirección URL. En cambio, con `get`, los datos se añaden a la URL y pueden quedar visibles en la barra de direcciones.

**Prueba con `get`**

Al cambiar temporalmente el método del formulario a `get` y pulsar «Enviar», el navegador mostró esta URL:
file:///C:/Users/irene/Documents/Proyecto%20Integrador%20LM/Proyecto-Integrador-LM-2026/proyecto/contacto.html?nombre=Irene&apellidos=G%C3%B3mez+Garc%C3%ADa&correo=irenegomezgarcia%40gmail.com&telefono=666666666&fecha=2004-08-29&pais=espana&conocer=familia&veces=32&libro=algunos&peliculas=azkaban&personaje=harry&villano=bellatrix&criatura=hipogrifo&hechizo=expecto&casa=gryffindor&intereses=hechizos&valoracion=fan&mensaje=Si+no+te+has+visto+harry+potter%2C+hazlo+&condiciones=acepto#

Después de realizar la prueba, volví a dejar el formulario con `method="post"`.

**Errores del validador del W3C**

| Página | Error del validador | Cómo lo corregí |
|--------|---------------------|-----------------|
| `peliculas.html` | Sin errores | No hizo falta corregir nada. |
| `contacto.html` | Sin errores | No hizo falta corregir nada. |

Pasé las dos páginas por el validador del W3C mediante la opción «Validate by File Upload» y ambas dieron 0 errores a la primera.

**Qué he hecho en esta unidad**

En esta unidad he añadido a mi web una tabla con los datos de las películas de Harry Potter, utilizando elementos como `caption`, `thead`, `tbody`, `tfoot`, `colgroup`, `colspan` y `rowspan`. También he creado la página `contacto.html` con un formulario organizado mediante `fieldset` y distintos tipos de controles. He utilizado atributos como `required`, `placeholder` y `maxlength`. Por último, he enlazado la página de contacto desde `index.html`, he validado las páginas con el validador del W3C y he subido los cambios a GitHub mediante commits.

## Herramientas utilizadas

- **Visual Studio Code:** para escribir y editar el código.
- **HTML:** para crear la estructura de las páginas web.
- **XML:** para organizar los datos de las películas.
- **Git y GitHub:** para controlar los cambios y guardar el proyecto en un repositorio.
- **Live Server:** para visualizar las páginas web.
- **Validador del W3C:** para comprobar que el HTML no tiene errores.
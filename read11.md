## ¿Qué es el DOM?

El DOM (Document Object Model o Modelo de Objeto del Documento) es una representación estructurada de un documento HTML o XML. El DOM permite a los programas (como JavaScript) acceder y manipular el contenido, la estructura y el estilo de un documento web.

## Describe brevemente la relación entre el DOM y JavaScript.

JavaScript utiliza el DOM para interactuar con las páginas web. Puede acceder a los elementos del DOM, modificarlos, agregar o eliminar elementos, y cambiar sus estilos. Esto permite crear páginas web dinámicas e interactivas.

## ¿Qué método usarías para seleccionar un elemento del DOM por su ID y cómo se utiliza?

El método que se usaría para seleccionar un elemento del DOM por su ID es `getElementById()`. Se utiliza de la siguiente manera:


`let elemento = document.getElementById("miElemento"); // Selecciona el elemento con el ID "miElemento"`

Si el elemento con el ID especificado existe, la variable elemento contendrá una referencia a ese elemento. Si no existe, elemento será null.

## ¿Qué método utilizarías para cambiar el color de fondo de un elemento en el DOM y cómo se implementaría?

El método que se utilizaría para cambiar el color de fondo de un elemento en el DOM es modificando la propiedad `style.backgroundColor` del elemento. Se implementaría de la siguiente manera:

`let elemento = document.getElementById("miElemento");`

`elemento.style.backgroundColor = "red"; // Cambia el color de fondo del elemento a rojo`

También puedes usar otros valores de color, como códigos hexadecimales (`"#FF0000"`), valores RGB (`"rgb(255, 0, 0)"`), o nombres de colores CSS (`"red"`).


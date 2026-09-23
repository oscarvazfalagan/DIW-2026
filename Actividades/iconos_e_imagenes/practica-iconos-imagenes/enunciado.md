# Práctica: iconos y composición de imágenes en una interfaz web

## Contexto

En el tema hemos visto que elegir bien los iconos y las imágenes no es una
cuestión estética menor: afecta a la accesibilidad, al tiempo de carga de la
página y a cómo interpreta el usuario el mensaje. En esta práctica vas a
aplicar esas ideas directamente sobre una plantilla HTML/CSS ya construida.

## Objetivos

- Usar correctamente una fuente de iconos (Font Awesome) en HTML y CSS.
- Aplicar los consejos de elección de iconos del apartado 8.2: estilo
  consistente, tamaño consistente y alternativas de texto accesibles.
- Reconocer y aplicar la regla de los tercios en la elección de imágenes.
- Identificar el ángulo fotográfico usado en distintas imágenes y justificar
  cuándo convendría usar cada uno en una web real.

## Punto de partida

Trabaja sobre los archivos `index.html` y `styles.css` de la plantilla. No
hace falta escribir nada desde cero: todo lo que tienes que completar está
marcado con un comentario `<!-- TODO ... -->` en el HTML.

## Desarrollo de la actividad

### 1. Barra de iconos

La plantilla ya tiene 4 iconos de Font Awesome funcionando (inicio, buscar,
carrito y GitHub), todos con el mismo tamaño, el mismo estilo circular y una
alternativa de texto (`aria-label`) para accesibilidad.

Tu tarea: añade **al menos 2 iconos más** buscándolos en
[fontawesome.com/icons](https://fontawesome.com/icons) (usa solo los
marcados como "Free"). Mantén exactamente el mismo formato que los que ya
existen — un `<a>` con su `aria-label`, y dentro un `<i>` con la clase del
icono elegido.

### 2. Regla de los tercios

Cada imagen de este bloque tiene superpuesta una rejilla roja dibujada solo
con CSS (fíjate en `.marco-tercios::after` dentro de `styles.css`), que
marca los cuatro "puntos de fuerza" de la imagen.

Tu tarea: sustituye las dos imágenes de ejemplo por **dos imágenes propias**
(tuyas, o libres de derechos de un banco como Unsplash o Pexels) y escribe
en el pie de foto si el sujeto principal cae cerca de algún punto de fuerza
de la rejilla. Si no es así, prueba con otra imagen o recórtala hasta que sí
lo esté.

### 3. Ángulos fotográficos

Tu tarea: añade **dos imágenes más** (además de la que ya está), cada una
mostrando un ángulo fotográfico distinto de los vistos en el apartado 9.2
(normal, contrapicado, picado, nadir o cenital). Para cada una:

- Selecciona en el desplegable el ángulo que crees que se ha usado.
- Escribe una frase justificando en qué tipo de página web usarías una
  imagen con ese ángulo (por ejemplo: *"un contrapicado transmite autoridad,
  útil en la web de un despacho de abogados"*).

### 4. Reflexión final

En 3-4 líneas, explica con tus palabras por qué es mejor usar una fuente de
iconos en vez de imágenes sueltas para los iconos de una web. Relaciona tu
respuesta con lo explicado en el apartado 8 del tema.

## Qué tienes que entregar

El enlace de tu página (en GitHub) en la tarea del Aula Virtual.

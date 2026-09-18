# Actividad: Elección de paleta de colores y tipografía

## Contexto
Toda página web transmite una sensación antes de que nadie lea una sola palabra: la elección de colores y tipografías comunica seriedad, cercanía, lujo, diversión o confianza mucho antes que el propio contenido. En esta actividad vas a experimentar con ese lenguaje visual, trabajando sobre una plantilla ya construida con variables CSS, de forma que puedas centrarte por completo en las decisiones de diseño sin tener que tocar la estructura HTML.

## Objetivos
Aplicar criterios de armonía cromática al elegir una paleta de colores.
Combinar dos tipografías (una para títulos y otra para el cuerpo del texto) de forma coherente.
Reconocer la diferencia entre combinaciones de color seguras y combinaciones de alto contraste, y valorar su efecto en la legibilidad.

## Punto de partida
Trabaja sobre tu copia personal del repositorio de la plantilla (la que creaste con "Usa esta plantilla" y clonaste en VS Code). El archivo que vas a modificar es styles.css, concretamente el bloque :root situado al principio, donde están definidas todas las variables de color y tipografía.

## Desarrollo de la actividad
1. Elige un tema (videojuegos, viajes, ...) para tu página y adapta el texto del documento al tema escogido.
2. Elige una paleta de color que sea coherente con el tema escogido aplicando a la teoría del color.
Entra en [coolors.co](https://coolors.co) y genera paletas hasta encontrar una que te convenza (pulsa la barra espaciadora para generar combinaciones aleatorias, o parte de un color que te guste y deja que la herramienta proponga el resto).

Tu paleta debe cubrir las siete variables de color definidas en la plantilla:

| Variable                 |                              Qué controla                              |
|--------------------------|------------------------------------------------------------------------|
| --color-fondo 	       | Fondo general de la página                                             |
| --color-fondo-alterno	   | Fondo de las secciones que se diferencian del resto                    |
| --color-bloque	       | Fondo de las tarjetas y bloques destacados                             |
| --color-texto	           | Color del texto principal                                              |
| --color-texto-secundario | Color del texto secundario (descripciones)                             |
| --color-boton-primario   |                                                                        |
| (+ su versión hover)     | Color del botón de la acción principal                                 |    
| --color-acento	       | Un color usado con moderación como detalle                             |

Sustituye los valores hexadecimales de estas variables por los de tu paleta y guarda los cambios.

3. Elige la tipografía

Entra en [Google Fonts](https://fonts.google.com) y elige dos tipografías: una para los títulos (--font-titulos) y otra para el cuerpo del texto (--font-cuerpo). Deben ser tipografías distintas entre sí, pero que combinen bien — por ejemplo, una tipografía con carácter para los títulos junto con una tipografía sencilla y muy legible para el cuerpo.

Para aplicarlas correctamente tienes que cambiar dos sitios, no solo uno:

El enlace <link> a Google Fonts en el <head> de index.html, sustituyéndolo por el que te proporciona Google Fonts para las tipografías que elegiste.

Las variables --font-titulos y --font-cuerpo en styles.css, para que apunten a los nombres exactos de esas tipografías.
Si solo cambias uno de los dos sitios, la tipografía no se aplicará correctamente — es un error habitual, así que revisa ambos.

4. Compara y reflexiona
Una vez tengas tu paleta y tipografía aplicadas, haz la siguiente comparación:

Crea una variante "segura": elige colores del mismo tono pero con distinto brillo (por ejemplo, varios verdes, del más claro al más oscuro).
Crea una variante de alto contraste: combina colores muy alejados entre sí en el círculo cromático (por ejemplo, un fondo oscuro con texto muy claro, o colores complementarios).

Crea un documento de texto y responde por escrito a estas preguntas:

    - ¿Con qué combinación se lee mejor el texto de cuerpo? ¿Por qué crees que pasa eso?

    - ¿Qué combinación transmite una sensación más "segura" o "corporativa", y cuál más "llamativa" o "arriesgada"?


# Qué tienes que entregar
En tu repositorio debes tener un documento HTML con su correspondiente CSS para la paleta original cada una de sus variantes
Un documento de texto que contenga un párrafo breve (5-8 líneas) respondiendo a las preguntas de reflexión del apartado anterior.
Cómo entregarlo

 Entrega el enlace a tu repositorio.

# Criterios de evaluación
|               Criterio                  |	                            Qué se valora                           |
|-----------------------------------------|--------------------------------------------------------------------------------------------------------_|
|Coherencia de la paleta	              | Los colores elegidos guardan armonía entre sí y se aplican correctamente a las siete variables          |
|Combinación tipográfica	              | Las dos tipografías elegidas son distintas pero compatibles, y están correctamente enlazadas y aplicadas|
|Comparativa segura vs. alto contraste    |	Ambas variantes están correctamente diferenciadas y accesibles en el repositorio                       | 
|Reflexión escrita	                      | Las respuestas muestran comprensión real de los conceptos de legibilidad y percepción del color, no solo una descripción superficial |
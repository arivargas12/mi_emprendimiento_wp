# Análisis de rendimiento con Lighthouse

## Página analizada

Se analizó la página de inicio del sitio web de LUMÉ utilizando Lighthouse 13.6.0.

## Condiciones de la prueba

- Dispositivo emulado: Moto G Power
- Tipo de prueba: móvil
- Red simulada: 4G lenta
- Navegador utilizado: HeadlessChromium 157.0.8103.38
- Fecha de análisis: 25 de noviembre de 2026
- Hora del análisis: 15:43, GMT-3

## Resultados

| Categoría | Puntuación |
|---|---:|
| Rendimiento | 74/100 |
| Accesibilidad | 100/100 |
| Recomendaciones | 96/100 |
| SEO | 92/100 |
| Navegación con agentes | 2/2 |

## Métricas de rendimiento

- First Contentful Paint: 0,9 segundos.
- Largest Contentful Paint: 4,2 segundos.
- Total Blocking Time: 430 milisegundos.
- Cumulative Layout Shift: 0.
- Speed Index: 3,4 segundos.

## Diagnóstico

El sitio obtuvo una puntuación de 74 en rendimiento. La página comienza a mostrar contenido rápidamente, con un First Contentful Paint de 0,9 segundos. Sin embargo, el Largest Contentful Paint fue de 4,2 segundos, por lo que el contenido principal tarda más en aparecer completamente.

El Cumulative Layout Shift fue de 0, lo que indica que los elementos de la página no se movieron inesperadamente durante la carga. Esto proporciona una experiencia visual estable para los visitantes.

El Total Blocking Time fue de 430 milisegundos. Lighthouse también detectó siete tareas largas en el subproceso principal y un tiempo de ejecución de JavaScript de aproximadamente 1,5 segundos.

## Oportunidades de mejora

Lighthouse identificó las siguientes oportunidades:

- Reducir el código JavaScript que no se utiliza. El ahorro estimado es de 341 KiB.
- Reducir el tiempo de ejecución de JavaScript.
- Reducir el código CSS que no se utiliza. El ahorro estimado es de 33 KiB.
- Evitar las tareas largas en el subproceso principal.
- Mejorar la entrega de imágenes. El ahorro estimado es de aproximadamente 20 KiB.
- Reducir las solicitudes que bloquean la representación. El ahorro estimado es de aproximadamente 220 milisegundos.
- Mejorar la visualización de la fuente, con un ahorro estimado de aproximadamente 490 milisegundos.
- Revisar el uso de bibliotecas JavaScript.
- Revisar los errores registrados en la consola del navegador.

## Accesibilidad

El sitio obtuvo una puntuación de 100/100 en accesibilidad. Las auditorías automáticas fueron aprobadas correctamente.

Lighthouse recomienda realizar comprobaciones manuales adicionales, como revisar:

- Que los controles sean accesibles mediante el teclado.
- Que los elementos interactivos indiquen claramente su función.
- Que el orden de navegación sea lógico.
- Que los controles personalizados tengan etiquetas asociadas.
- Que los elementos utilicen roles ARIA adecuados cuando sea necesario.
- Que la estructura de la página utilice correctamente elementos de navegación y regiones.

## Recomendaciones y buenas prácticas

El sitio obtuvo una puntuación de 96/100 en recomendaciones. Se detectaron algunos aspectos para revisar:

- Se registraron errores en la consola del navegador.
- Se detectaron bibliotecas JavaScript.
- Se recomienda revisar la política de seguridad de contenido.
- Se recomienda utilizar una política HSTS sólida.
- Se recomienda revisar las medidas de protección contra clickjacking y ataques XSS.

## SEO

El sitio obtuvo una puntuación de 92/100 en SEO. La mayoría de las auditorías fueron aprobadas.

La principal observación fue que el documento no tiene una metadescripción. Para mejorar este aspecto, se debe agregar una descripción breve y clara de la página principal de LUMÉ. Esta descripción debe explicar que LUMÉ es una marca o tienda de velas aromáticas enfocada en el bienestar, la aromaterapia y la decoración del hogar.

Ejemplo de metadescripción:

> Descubre LUMÉ, una tienda de velas aromáticas artesanales para crear ambientes de bienestar, relajación y armonía en tu hogar.

## Conclusión

El sitio de LUMÉ presenta un buen nivel general de calidad. Destaca especialmente en accesibilidad, con una puntuación de 100/100, y en recomendaciones, con 96/100. El SEO también obtuvo un resultado positivo de 92/100.

La principal área de mejora es el rendimiento en dispositivos móviles. Se recomienda optimizar JavaScript y CSS, mejorar la carga de imágenes, revisar las tareas largas y agregar una metadescripción a la página principal.



# Análisis de rendimiento con Lighthouse

## Página analizada

Se analizó la página de inicio del sitio web de LUMÉ utilizando Lighthouse 13.6.0.

## Condiciones de la prueba

- Dispositivo emulado: Moto G Power.
- Tipo de prueba: móvil.
- Red simulada: 4G lenta.
- Fecha del análisis: 25 de noviembre de 2026.
- Hora del análisis: 15:43, GMT-3.

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

El sitio obtuvo una puntuación de 74/100 en rendimiento. El contenido inicial aparece rápidamente, con un First Contentful Paint de 0,9 segundos. Sin embargo, el contenido principal tarda más en cargarse completamente, ya que el Largest Contentful Paint fue de 4,2 segundos.

El Cumulative Layout Shift fue de 0, lo que indica que los elementos permanecieron estables durante la carga. El Total Blocking Time fue de 430 milisegundos y se detectaron siete tareas largas en el subproceso principal.

## Oportunidades de mejora

- Reducir el código JavaScript que no se utiliza.
- Reducir el tiempo de ejecución de JavaScript.
- Reducir el código CSS no utilizado.
- Optimizar la entrega de imágenes.
- Reducir las solicitudes que bloquean la representación.
- Revisar las tareas largas del subproceso principal.
- Comprobar los errores de la consola del navegador.
- Mantener configurado W3 Total Cache.

## Accesibilidad

El sitio obtuvo 100/100. Las auditorías automáticas fueron aprobadas correctamente. Se recomienda revisar manualmente la navegación con teclado, el orden de los elementos, las etiquetas de los controles y los roles ARIA.

## Recomendaciones

El sitio obtuvo 96/100. Lighthouse detectó errores en la consola y recomendó revisar las políticas de seguridad, como CSP, HSTS y protección contra ataques XSS y clickjacking.

## SEO

El sitio obtuvo 92/100. La principal observación fue que la página no tiene una metadescripción. Se recomienda agregar una descripción como la siguiente:

> Descubre LUMÉ, una tienda de velas aromáticas artesanales para crear ambientes de bienestar, relajación y armonía en tu hogar.

## Conclusión

El sitio presenta un buen nivel general de calidad. Destaca en accesibilidad, con 100/100, y en recomendaciones, con 96/100. La principal mejora pendiente es optimizar el rendimiento móvil y agregar una metadescripción para mejorar el SEO.


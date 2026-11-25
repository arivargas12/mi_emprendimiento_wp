# LUMÉ · Sitio WordPress

> **Este README es tuyo.** Complétalo mientras construyes tu sitio y borra las instrucciones entre paréntesis. Las instrucciones del proyecto están en [`indicaciones/README.md`](indicaciones/README.md).

- **Sitio en producción:** https://lume.infinityfree.me
- **Prototipo en Stitch:** https://stitch.google.com/projects/5380580207788885438
- **Repo del Parcial 02:** https://github.com/arivargas12/mi-emprendimiento.git
- **Autor/a:** Arianna Vargas

## Contexto de la web

LUMÉ es un emprendimiento de velas aromáticas bonitas y de buena calidad para decorar, relajarse y crear ambientes acogedores. Su público principal son jóvenes como Catalina, una estudiante universitaria que busca bienestar, aromas agradables y regalos especiales. El sitio permite conocer la marca, sus velas, aromas y diseños desde el celular. También busca entregar una experiencia cálida y sencilla, facilitar el contacto y motivar a los visitantes a seguir a LUMÉ en redes sociales.


## Mi tema

Tema descargado: Twenty Twenty-Five

---

## Instrucciones si uso un tema descargado

*(Borra esta sección si usas un tema propio.)*

### Requisitos del tema

## Requisitos del tema

| Dato | Mi tema |
|---|---|
| Nombre y enlace a la ficha | Twenty Twenty-Five — tema oficial de WordPress |
| Gratis o de pago | Gratis |
| Tipo (clásico o de bloques) | De bloques |
| Versión de WordPress que requiere | WordPress 7.1.5 |
| Versión de PHP que requiere | PHP 8.4.28 |
| Plugins que necesita (si alguno) | Ninguno obligatorio |
| Licencia | GPL |


## Cómo llevar mi sitio de Local a producción

### Plugin de migración

Plugin de migración que uso: All-in-One WP Migration and Backup  
Ficha oficial: https://wordpress.org/plugins/all-in-one-wp-migration/  
Costo: versión gratuita, con extensiones de pago disponibles.  
Límites: la versión gratuita tiene un límite de importación que puede depender de la versión instalada y de la configuración del servidor. En mi caso, el tamaño también está limitado por InfinityFree y por los recursos disponibles del hosting.

### Qué se exporta

El archivo de migración incluye las páginas, entradas, imágenes, menús, configuraciones, tema, plugins y demás archivos necesarios del sitio WordPress.

### Pasos

1. **En Local:** instalé y activé All-in-One WP Migration. Luego seleccioné la opción de exportar el sitio y descargué el archivo generado en formato `.wpress`.

2. **En producción:** instalé un WordPress limpio en InfinityFree. Después instalé y activé All-in-One WP Migration, junto con el tema Twenty Twenty-Five y el plugin Contact Form 7.

3. **Importación:** entré a All-in-One WP Migration → Importar, seleccioné el archivo `.wpress` exportado desde Local y esperé a que terminara el proceso. Después guardé nuevamente los enlaces permanentes e inicié sesión otra vez en WordPress.

4. **Revisión:** comprobé que funcionaran los enlaces permanentes, el menú principal, la página de inicio, las imágenes, el tema, las páginas del sitio y el formulario de contacto.

5. **Problemas que tuve y cómo los resolví:** durante la revisión, InfinityFree mostró algunas limitaciones del hosting, como errores 500, 429, problemas de API REST, loopback y el aviso de conexión no completamente segura. El sitio continuó visible en producción. El envío del formulario quedó pendiente de revisión porque el hosting gratuito puede limitar el correo; como alternativa, se puede configurar SMTP o migrar el sitio a un hosting profesional.

---

## Respaldo y reinstalación en otro servidor

El respaldo permite conservar los archivos y la base de datos del sitio para poder reinstalarlo en otro servidor si es necesario.

### Qué respaldar

Se deben respaldar los archivos de WordPress, incluyendo el tema Twenty Twenty-Five, los plugins instalados y las imágenes subidas a la biblioteca multimedia. También se debe respaldar la base de datos, porque contiene las páginas, entradas, menús, configuraciones y usuarios del sitio.

### Cómo respaldo mi sitio

Utilizo el plugin All-in-One WP Migration and Backup. En WordPress entro a All-in-One WP Migration → Exportar, selecciono Exportar a → Archivo y descargo el archivo `.wpress` generado.

Guardo el archivo en una ubicación segura, además de conservar una copia del repositorio del proyecto. Realizaría un respaldo antes de cambios importantes y, mientras el sitio sea pequeño, al menos una vez al mes.

### Cómo lo reinstalo en un servidor nuevo

1. **Requisitos del servidor:** el servidor debe ser compatible con WordPress, PHP y una base de datos MySQL o MariaDB. También debe contar con espacio suficiente para los archivos, las imágenes y el respaldo `.wpress`. Utilizaría las versiones de PHP, WordPress y base de datos compatibles con el sitio original.

2. **Instalar WordPress limpio:** creo una base de datos en el servidor nuevo e instalo una copia limpia de WordPress. Después ingreso al panel de administración e instalo el tema Twenty Twenty-Five y el plugin All-in-One WP Migration and Backup.

3. **Restaurar el respaldo:** entro a All-in-One WP Migration → Importar, selecciono el archivo `.wpress` y espero a que termine la importación. Luego vuelvo a iniciar sesión y guardo dos veces los enlaces permanentes en Ajustes → Enlaces permanentes.

4. **Ajustar el sitio:** reviso la URL del sitio, la página de inicio, el menú principal, los enlaces permanentes, el tema activo, los plugins y las imágenes. También compruebo que la página Contacto contenga el shortcode de Contact Form 7.

5. **Probar:** abro la página de inicio y las demás páginas, reviso las imágenes, pruebo la navegación en celular y envío un mensaje de prueba desde Contacto. También compruebo si aparece el mensaje de confirmación y si el correo llega a la dirección configurada.



## Plugins instalados

| Plugin | Para qué lo uso | Gratis o de pago | Versión |
|---|---|---|---|
| Contact Form 7 | Crear y mostrar el formulario de contacto de la página Contacto | Gratis | 6.2.6 |
| Loginizer | Proteger el acceso a WordPress contra intentos de fuerza bruta | Gratis | 2.1.2 |
| Loginizer Pro | Añadir funciones avanzadas de seguridad para el inicio de sesión | Pro | 2.1.2 |
| W3 Total Cache | Mejorar el rendimiento del sitio mediante caché y optimización | Gratis | 2.11.0 |

No tengo un plugin SEO instalado en esta etapa.

## Páginas y entradas

- **Páginas:**
  - Inicio
  - Nosotros
  - Contacto
  - Blog

- **Entradas del blog:**
  - Velas personalizadas para ocasiones especiales
  - Cómo elegir el aroma ideal para tu espacio
  - Beneficios de las velas artesanales

## Cómo me organicé

Mi plan y mi plan B están en [`decisiones.md`](proyecto/decisiones.md).

Durante el desarrollo mantuve la identidad visual y la estructura general de LUMÉ. Algunos plugins quedaron planificados para una fase posterior, mientras que el formulario de contacto y las funciones principales del sitio se implementaron en la etapa actual.

## Plan de continuidad y rendimiento

- **Plan de continuidad (etapa 2 de mi web):** [`plan-de-continuidad.md`](proyecto/plan-de-continuidad.md)
- **Análisis de rendimiento con Lighthouse:** [`lighthouse.md`](proyecto/lighthouse.md)

## Uso de IA

- **(Herramienta):** para qué la usé y qué ajusté yo.

![image](http://anclastudio.com/masnew/wp-content/themes/AnclaStudio/library/img/AnclaStudio.svg)

#Checklist de Lanzamiento para Sitios Web

Estos son los lineamientos que se deben de cumplir al entregar un sitio web en [ANCLA Studio](http://www.anclastudio.com).
Antes de mostrarle algo al cliente, se debe repasar para estar seguros de que el sitio coincide con las especificaciones técnicas originales, y los diseños son representados de manera correcta al brief original.

***

##Contenido

Se debe revisar que el contenido del sitio cumpla con los siguientes requisitos:
- **Ortografía**: Revisar y revisar de nuevo. De preferencia más de un solo responsable. Hay que verificar que no haya errores de gramática ni ortografía en el contenido. A su vez revisar que no haya palabras comidas ni duplicadas y que los parrafos esten completos.
- **Copy**: Asegurar que se está presentando contenido real y que todo los contenido de ejemplos esten removidos. No debe de salir nada con contenido "Lorem Ipsum".
- **Detalles de contacto**: Revisar numeros de teléfono, direcciones de correo electronico y direcciones postales. De preferencia hacer una prueba de que estos datos son correctos (Hacer una llamada o enviar un correo de prueba).
- **Términos y condiciones**: Si se esta ofreciendo un servicio o una promocion, se deben de tener términos y condiciones accesibles al usuario.
- **Privacidad**: Si el sitio usa cookies, captura o distribuye datos, se requiere que haya una política de privacidad. Se debe establecer que datos se estan recolectando y como se puede contactar para proveer más detalles.

***

##Funcionalidad

Un sitio puede presentar bugs menos cuando los visitantes usan el sitio por primera vez, asi que se deben de revisar los siguientes puntos:
- **Compatibilidad**: Revisar que el sitio funciona en las plataformas y exploradores previamente definidos. Se pueden usar plataformas como [Responsivator](http://dfcb.github.com/Responsivator/) y [BrowserStack](http://www.browserstack.com/) para hacer las pruebas necesarias.
- **Favicon**: El sitio debe de contar con los iconos de acceso directo generados de [RealFaviconGenerator](http://realfavicongenerator.net).
- **Logo**: El logotipo debe de ligar a la página principal del sitio.
- **Página 404**: El sitio debe de contar con una página default para enlaces no encontrados o mal escritos, asegurarse de que la página invite al usuario a regresar al sitio o sugerir enlaces de interés.
- **Redireccionamiento**: Si está redirigiendo páginas utilizan una redirección 301 en vez de 302.
- **Formularios**: Asegúrese de que no están enviando a los buzones de correo de spam, o devolver un error una vez enviado. Incluir un mensaje de agradecimiento para dar a conocer al usuario que su mensaje fue enviado exitosamente y asegurar que la dirección de correo del cliente sea correca y esten llegando de manera satisfactoria.
- **Enlaces**: Todos los enlaces internos deben de funcionar correctamente. Los enlaces externos ademas, deben de abrirse en una pestaña nueva.

***

##Estandares y Validación

Este apartado tiene que ser considerado **dentro** del diseño y programación. Cambios dentro de esta sección después de haberse entregado el proyecto se consideran como trabajo extra.

- **Tamaño del Texto**: Hacer texto claro y fácil de leer, ajustar el espaciado de línea y permitir suficiente espacio en blanco.
- **Etiquetas Alt**: Asegúrese de que todas las imágenes tienen etiquetas ALT descriptivas claras para los discapacitados visuales y los motores de búsqueda.
- **Compatibilidad de Dispositivos**: Considere cómo se utilizará la página web a través de múltiples dispositivos, responsivo o no su sitio web debe funcionar para los usuarios de escritorio y web móvil.
- **Validación**: El sitio debe de pasar la [prueba de validación](https://validator.w3.org).
- **JavaScript**: Asegúrese de que su sitio es totalmente funcional y que formularios aún realizan comprobaciones de validación del lado del servidor.
- **Flash**: Por motivos de seguridad, rendimiento y compatibilidad, no se utlizará Flash en ningun sitio.

***

##Sitemaps

Incluir mapas de sitio. Estos ayudan a los motores de búsqueda a indexar su sitio web correctamente durante el proceso de rastreo.

- **XML Sitemaps**: Estos son utilizados por los motores de búsqueda como Google, Bing y Yahoo. Se debe de crear un [XML Sitemap](http://webdesign.tutsplus.com/articles/general/all-you-need-to-know-about-xml-sitemaps/) sencillo y mandarlo a los Webmaster Tools. Estos serán utilizados para informar a los motores de búsqueda sobre las páginas que ha publicado.

***

##Rendimiento

Es importante revisar el rendimiento del sitio. Se debe procurar reducir el tiempo de carga del sitio bajo condiciones normales de la conexión a internet.

- **Revisar Velocidad del Sitio**: Usar servicios como [Google Page Speed](https://developers.google.com/speed/pagespeed/) o [Blame Stella](https://www.blamestella.com/) para revisar los tiempos de carga de los sitios web.
- **Tamaños de Imágenes**: Mantén las imágenes lo mas ligeras posibles. Procura comprimir imágenes para reducir los tiempos de carga.

***

##Analytics

Es importante medir el trafico que recibe el sitio, asi como identifcar la audiencia y usuarios.

- **Monitoreo**: Se debe de implementar el script de rastreo de trafico de [Google Analytics](http://www.google.com/analytics/) para el sitio.

***


##Entregables

Estos puntos se consideran como un proyecto completamente entregado al cliente.

- **Sitio web en producción**
- **Hosting**: Se entregará un paquete básico de Hosting con las siguientes caracteristicas: 5GB de espacio en disco, 10GB de ancho de banda, 10 cuentas de correo, 1 base de datos y 1 subdominio o dominio adicional.
- **Assets e iconos**: Cualquier set de iconos, ilustraciones e infografías creados para el sitio web. Entregarlos en distintos formatos para que el cliente pueda utilizarlos en futuros trabajos/proyectos si así lo desea.
- **Cuentas externas**: Como Google Analytics, cuentas creadas para e-shops / Paypal
- **Alta en Google Webmaster Tools**: El sitio debe estar dado de alta en el servicio de Google, en caso de que el mantenimiento no corra por cuenta de Ancla, enlazarlo a una cuenta gmail de parte del cliente.

***


##Mantenimiento Continuo (Opcional)

Una vez que se haya lanzado el sitio, es necesario darle mantenimiento y asegurarse que el proyecto esté corriendo 100%. La siguiente es una lista de lo que puede ser considerado como mantenimiento.

- **Backups / Copia offline**: Cada mes generar un backup del sitio web enteramente (Código, Base de Datos, etc.)
- **Monitoreo**: Monitoreo de servicios externos usados en el proyecto web como APIs de terceros, librerías enlazadas, etc. Es necesario actualizarlas si han sido cambiadas.
- **SEO**: Esto puede ser considerado un proyecto aparte. Es necesario monitorear el contenido del sitio web y su ranking en Google así como hacer mejoras continuas en el código directamente relacionado con el SEO, como agregar etiquetas para descripciones, mejora de titulos, texto en imágenes, formatos enriquecidos, etc. Monitoreo semanal.

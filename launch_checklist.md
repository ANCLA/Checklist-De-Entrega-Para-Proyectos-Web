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

Estas dos cosas deben ser considerados en todo el diseño y construcción para hacer cada experiencia a los usuarios en su sitio tan buena como sea posible.

- **Tamaño del Texto**: Hacer texto claro y fácil de leer, ajustar el espaciado de línea y permitir suficiente espacio en blanco.
- **Etiquetas Alt**: Asegúrese de que todas las imágenes tienen etiquetas ALT descriptivas claras para los discapacitados visuales y los motores de búsqueda.
- **Compatibilidad de Dispositivos**: Considere cómo se utilizará la página web a través de múltiples dispositivos, responsivo o no su sitio web debe funcionar para los usuarios de escritorio y web móvil.
- **Validación**: El sitio debe de pasar la [prueba de validación](https://validator.w3.org).
- **JavaScript**: Asegúrese de que su sitio es totalmente funcional y que formularios aún realizan comprobaciones de validación del lado del servidor.
- **Flash**: Por motivos de seguridad, rendimiento y compatibilidad, no se utlizará Flash en ningun sitio.

***

##Sitemaps

Asegúrese de incluir mapas de sitio. Estos ayudan a los motores de búsqueda a indexar su sitio web correctamente durante el proceso de rastreo.

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

##Legal

Before you start any project a signed contract should be in place. The contract should clearly outline the project deliverables and processes so both parties are 100% clear on what will be achieved as an end result. As part of that contract make sure the following has been agreed to cover any unforeseen circumstances.

- **Image/Content Rights**: Clearly state that any supplied content or imagery that is handled by you remains the clients responsibility. Make clear that you will not be held liable for publishing content and images that they do not have the rights to use. Also educate the client that they should be using images or content that are either paid for or they have the rights to use.
- **Payment Terms**: Set fair and staged payment terms at clearly defined milestones of a project (at the end of the design phase - before any development starts for example), never move on to the next phase of a project until the agreed payment is in.
- **Timelines**: Set reasonable timelines that are fair to your client as well as manageable for you and your team. Clearly state that you will not be held responsible for any loss or damages as a result of a delay in the schedule caused by the client. It is a good idea to use something like [Basecamp](http://basecamp.com/) to manage your projects so all work and conversations are recorded should you need them to fall back on in the future.
- **Intellectual Property Rights**: This will be different depending on who you are, what you’re offering, or the project in question. Clearly state what is owned by you and the client once the project is complete and payment has been made in full. Consider the rights to any software or code written by you that you wouldn’t want sold on, or anything similar that you feel you need to retain the rights to.

***

##Entregables

In the project contract clearly explain what the client will physically receive once a project is complete. The following is what we’d recommend.

- **Hosting**: Se entragará un paquete básico de Hosting con las siguientes caracteristicas: 5GB de espacio en disco, 10GB de ancho de banda, 10 cuentas de correo, 1 base de datos y 1 subdominio o dominio adicional.
- **Live Website**: This is the bare minimum. Make sure their website is up and live and fully functioning as intended.
- **Assets & Icons**: Any icons, illustrations, or infographics design and created for the website may be helpful to your client going forward. Supply them the files in different formats so they can use them in presentations or future design work.
- **Offline Copy**: If requested by the client provide a copy of the site. Remember websites are a living document that should be continually updated and improved, so unless the site is static you will have to be making regular offline backups for the client.

***

##Lanzamiento del sitio

Remember: never hand over a project or files without sign off and any outstanding payments settled. You will have no come back at this point if you do without either of these. Handing over a project without payment is the equivalent of a shop owner letting a customer walk out of a shop with a trolley full of goods on the promise that they will ‘pay you later’.

Now everything is in place you are ready to launch. But when should you? We try our very best to never launch a site within two days of a weekend. Sometimes this practice has to go out the window on occasions but we always try and aim for a Monday to Wednesday launch slot. This will give you the opportunity to iron out any live bugs that surface during a working week. Trying to fix these during a weekend when either you or your developers are not around will only cause you headaches when you have a client who needs their site to be fully functional. Trust us, you will only learn the hard way if you don’t adopt this approach.

***

##Mantenimiento Continuo (Opcional)

So you’ve launched the site, it’s working great and the client is happy, now what? You need to make sure that it continues to run without a hitch. Things can go wrong or get missed, server security compromised, or it could fall over. Make sure you’re ready for every eventuality.

- **Version Control**: Try running a project through [Git](http://git-scm.com/), it’s a great version control system for teams of developers working in collaboration. Source code history is saved meaning that you can refer or revert back to previous versions if and when needed. For an introduction to Git read this in-depth article [Easy Version Control with Git](http://net.tutsplus.com/tutorials/other/easy-version-control-with-git/).
- **Analytics**: In order to suggest improvements going forwards ask to be set up on the client's analytics, this way you can monitor traffic and site stats for the client and suggest improvements over the following month and year after launch.

***
Let us know your launch checklist recommendations [on Webdesigntuts+](http://enva.to/XpDQqR)

### E.2.2 Funcionalidades

* Es una aplicación web de escritura colaborativa \(de notas\) en tiempo real que utiliza el lenguaje de marcado.

* Cuenta con un completo **sistema de permisos de acceso** configurables por el autor inicial de la nota:

  * **Libre**: Cualquier persona puede editar la nota.

  * **Editable**: un usuario que haya iniciado sesión puede editar la nota.

  * **Limitado**: las personas deben iniciar sesión para ver y editar la nota.

  * **Bloqueado**: Cualquiera puede ver la nota, pero sólo el propietario puede editarla.

  * **Protegido**: las personas deben iniciar sesión para ver la nota pero sólo el propietario puede editarla.

  * **Privado**: Sólo el propietario puede ver y editar esta nota.

* Permite **inicio de sesión** a través de Facebook, Twitter, GitHub, o Dropbox.

* Permite **ver** el **texto** en **3 modos**:

  * **Edición**: Ver solo el editor.

  * **Vista**: Ver solo el resultado.

  * **Ambos**: Ver ambos en modo división.

* Soporta **Emojis**

* Permite subir **imágenes** de distintas formas: a través del formulario, arrastrando y soltando o pegando una imagen. Por defecto las guarda en el servicio externo privativo imgur[^1].

* Se pueden **exportar** el resultado final \(las notas\) a través de Dropbox o descargando un fichero markdown en local.

* Se pueden **importar** notas a través de Dropbox o del portapapeles.

* Se pueden **embeber** notas en otras webs a través de iframes

* Permite **convertir** una **nota** **en** una **presentación** con una sintaxis especial.

* Permite **configurar automáticamente** una **tabla de contenidos**.

* El **editor** cuenta **con autocompletado** de ayuda de markdown de emojis, encabezados, imágenes, etc.

* **Integra automáticamente contenido de sitios externos** \(YouTube, Vimeo, Gist, SlideShare y Speakerdeck\), formatos \(PDF\) y sintaxis en diferentes lenguajes \(MathJax, diagramas UML, diagramas de secuencia, gráficos de flujo, Graphviz, Mermaid, Abc\).

* Incorpora la posibilidad de trabajar de forma fuera de línea \(_offline_\).

Se trata por tanto de un aplicativo de elaboración de documentos de forma colaborativa y en tiempo real que incluye funcionalidades avanzadas como la que convierte los documentos en presentaciones o la inclusión de imágenes y emojis.

Destacan también otras funcionalidades innovadoras con respecto a otras herramientas de su clase, como son la posibilidad de configurar automáticamente una tabla de contenidos o índices a partir del contenido introducido, o las de exportar/importar el resultado final a ficheros en local o compartirlos en múltiples formatos a través de servicios como Dropbox, Google Drive, Markdown, etc.

Sin embargo, al tratarse de un aplicativo reciente, que se encuentra aún en su fase inicial \(beta\) de desarrollo, no cuenta con soporte básico de confirmación de correo electrónico de usuarios, por lo tanto no cuenta con funcionalidades estándares como por ejemplo la de "ha olvidado su contraseña" y en su propia documentación se menciona que se encuentran en un estado inicial de desarrollo, por lo que se pueden encontrar errores de programación \(bugs\)

Cuenta con imágenes docker para su instalación.


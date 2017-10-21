# Alcance y Metodología

El presente estudio se ha centrado exclusivamente en aplicativos web libres, es decir, aquellos que están protegidos por una licencia avalada por la Open Source Initiative[^1], licencias que permiten tanto su estudio como su modificación y/o adaptación y distribución, así como su instalación y análisis desde la perspectiva del usuario en sus distintos perfiles: usuario final, administrador, moderador, etc.

Así mismo, los aplicativos seleccionados para el estudio han sido o están siendo utilizados en la práctica por experiencias concretas de gobierno en distintas escalas \(ciudad, provincia, estado, etc\), así como por organizaciones sociales, cívicas y políticas, no obstante lo cual se han incluido también "pruebas de concepto" que se consideran especialmente relevantes para los fines del presente documento.

La información recogida \(recopilada\) para cada uno de las aplicativos se presenta con la siguiente estructura:

1. Metadatos

2. Funcionalidades

3. Capturas de pantallas

4. Análisis

5. Arquitectura

6. Modelos de datos

Los **metadatos** recopilados son:

* Nombre: nombre completo del aplicativo

* URL: dirección web donde puede encontrarse el software funcionando o la explicación del proyecto en el caso en que lo tenga.

* URL repositorio: dirección web donde puede encontrarse el código del aplicativo.

* Resumen \(Inglés\): una sinopsis de para qué sirve el software.

* Resumen \(Castellano\): idem anterior, traducido al castellano.

* Lenguaje: en que lenguaje de programación se ha realizado.

* Framework: que conjunto de librerías se ha utilizado para su desarrollo.

* Fecha primer commit: mes y año en que ha comenzado ha desarrollarse.

* Versión analizada: versión analizada en el marco de este informe.

* Nº de releases: cantidad de versiones publicadas del aplicativo.

* Nº de tablas en la BBDD: cantidad de tablas en la Base de Datos \(BBDD\), sirve como indicador de la complejidad del aplicativo \(a mayor número de tablas más complejo\).

* Nº de contribuidores: cantidad de programadores que han contribuido código al aplicativo.

* Nº de stars: indicador de popularidad en GitHub

* Licencia: que tipo de licencia es la que tiene el proyecto.

* Mantenido: si cuenta con un desarrollo activo \(algún commit en los últimos 6 meses\).

* Diseño responsivo: si su diseño es adaptable a dispositivos con distintas anchuras \(móviles, tablets, equipos de escritorio\).

A continuación se hace un análisis de las distintas **funcionalidades** que ofrece el aplicativo, así como una serie de **capturas de pantallas** con una explicación simple de las mismas.

Con respecto al **análisis**, se detalla en qué casos se ha usado y qué funcionalidades son especialmente reseñables de cara a Decidim.

Posteriormente se documentan a nivel de **arquitectura** los grados de personalización, el soporte de temas de diseño, de modularización y extensión a través de plugins, addons o complementos y los distintos servicios que deben configurarse para el correcto funcionamiento de la herramienta, entre ellos pueden encontrarse servicios del tipo:

1. Servidor web

2. Servidor de aplicación

3. Servidor de base de datos

4. Servidor de caché

5. Servidor de envío de correo SMTP

6. Binarios necesarios

7. Servicios externos o APIs a los que se requiera para acceder \(por ejemplo Google Maps o Bing Maps\)

Por último se agrega información relativa al **modelo de datos**, con un esquema de la base de datos así como un listado de las tablas utilizadas por la aplicación.


### G.1.4 Arquitectura

Aunque el código se haya liberado, y cuenta con un repositorio dedicado a la documentación, así como una web para la misma[^1], ésta sólo explica el funcionamiento de la herramienta de cara a un usuario. 

Los ficheros README con los que cuentan los distintos repositorios que cuenta la aplicación da fallos al seguir las instrucciones, el más llamativo es el siguiente: 

*/polisServer$ npm install*

*(...)*

*npm WARN remote: Invalid username or password.*

*npm WARN fatal: Authentication failed for 'https://github.com/colinmegill/polisServerBrand.git/'*

*npm WARN*

*npm WARN polis@0.0.0 No license field.*

Al realizar la instalación, busca un repositorio que no existe en GitHub: polisServerBrand. Sin dicho componente el procedimiento de instalación del servidor no funciona. 

En su repositorio principal (PolisServer) cuentan con la siguiente explicación de 5 líneas[^2]

*Polis*

*Pol.is una plataforma de reunión de sentimiento impulsado por **AI**. Más orgánico que las encuestas, menos esfuerzo que los grupos focales.*

*Si no desea implementar su propia instancia de Polis, puede utilizar nuestra versión SaaS [aquí] (https://pol.is/home)*

*Polis [se puede incrustar fácilmente] (http://docs.pol.is/usage/Embedding.html) en su página como iframe.*

Al no conseguir instalarlo en un servidor propio y no contar con documentación que recomiende un proceso de despliegue, no se ha podido instalar y analizar la arquitectura del aplicativo. 



[^1]: http://docs.pol.is/
[^2]: https://github.com/pol-is/polisServer
Texto original: 
 Polis pol.is an AI powered sentiment gathering platform. More organic than surveys, less effort than focus groups.
 If you don't want to deploy your own instance of Polis, you can use our SaaS version [here](https://pol.is/home)
 Polis [can be easily embedded](http://docs.pol.is/usage/Embedding.html) on your page as an iframe.), sin explicar el proceso de instalación, algo no estándar en proyectos de software libre: 


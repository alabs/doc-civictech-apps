## Propuestas

### 1. Permitir agregar documentos, imágenes y URLs a una propuesta

En los último años las aplicaciones analizadas han implementado la posibilidad de agregar enlaces de forma enriquecida, mostrando un título, una descripción y una imagen \(thumbnail\) de esta URL a través del estándar Open Graph[^1]   o similar, con el objetivo de mostrar los metadatos de la página a la que se hace referencia de forma enriquecida.

Una funcionalidad útil todavía no desarrollada es la posibilidad de agregar tanto imágenes como documentos de forma adjunta a una propuesta o a un comentario. Se puede ver un ejemplo de esta funcionalidad en el uso de adjuntos de Loomio.

### 2. Distintas fases para propuestas

Un problema que se ha detectado en la dinámica de propuestas es la falta de posibilidad de que los comentarios de otros usuarios puedan enriquecer las mismas si se cuenta con una única fase de creación y priorización. Este problema no se soluciona sólo permitiendo la edición de la misma por parte del creador original sino que hay que permitir que una misma propuesta pueda ir mejorando a través del tiempo en función de las aportaciones de otros usuarios expresadas a través de los comentarios u otros elementos.

En ese sentido se reconoce como un paso en la buena dirección el proceso llevado a cabo por Open Ministry, en el que una misma propuesta cuenta con varias fases en función del consenso logrado a través de la discusión, utilizando el feedback que reciben a través de sus comentarios para ir mejorando la Iniciativa o Propuesta de Ley en distintas fases: Se comienza siendo una Idea, luego se pasa a Borrador, según se redacta ya es una Propuesta y al aprobarse pasa a ser una Iniciativa.

### 3. Punto de recogida de apoyos

Un problema común en estas aplicaciones es la desconexión entre las dinámicas de participación digital y presencial \(online y offline\). Aunque en el caso de Decidim se han realizado importantes avances en esta dirección a través del proceso del Plan Municipal mediante las Citas presenciales, estos avances no se han visto reflejados en la misma medida que resultan de la aplicación de otras tipologías de apoyo \(Ayuntamiento, Ciudadanas, Organizaciones\).

Esta situación puede mejorarse a través de la inclusión de dinámicas presenciales de participación similares a las aplicadas en Open Ministry, donde se facilita la recogida de apoyos y comentarios a través de puntos de recogida presenciales.

Este procedimiento es similar al que se puede encontrar en la aplicación de Gobierno Abierto "Decide Madrid" del Ayuntamiento de Madrid[^2]:

_**¿Existen mecanismos presenciales para participar? ¿Se ha planteado llegar a los ciudadanos y ciudadanas con dificultades de acceso a Internet o en situación de exclusión?**_

_Todas las acciones relacionadas con el proceso de propuestas ciudadanas pueden realizarse presencialmente en cualquiera de las 26 Oficinas de Atención al Ciudadano repartidas por todos los distritos de Madrid. Además, el proceso de recogida de apoyos de una propuesta puede realizarse también a través de hojas de firmas, cuyo modelo puede ser descargado en este documento PDF _[^3] _. Adicionalmente se ha creado en el Área de Gobierno de Participación Ciudadana, Transparencia y Gobierno Abierto el Servicio de Inclusión, Neutralidad y Privacidad que pondrá en marcha una mesa de inclusión con personal del Ayuntamiento y asociaciones que trabajan con colectivos en situación de exclusión, para diseñar mecanismos especiales para que puedan participar dichos colectivos._

Aparte de las Oficinas de Atención al Ciudadano ya existentes en Barcelona se debería estudiar su integración con los encuentros presenciales de participación ya existentes en la ciudad, como las Audiencias Públicas y Consells de Barris.

### 4. Rectificar el apoyo

Loomio, Adhocracy y Your Priorities permiten cambiar el apoyo que se le ha dado a una propuesta, con el razonamiento de que en base a la discusión y deliberación de la misma se puede cambiar de opinión sobre el tema que se está debatiendo.

### 5. Mejoras en la interfaz de argumentos a favor y en contra

En Your Priorities se ve claramente cuando un usuario aporta argumentos a favor y/o en contra en una propuesta ya que la interfaz facilita esta dinámica. Aunque en Decidim se cuenta con dicha posibilidad, ya que un mismo comentario puede marcarse como "A favor", “Neutral” o “En contra”, se debería estudiar un rediseño de la interfaz de presentación de estos comentarios en un próximo rediseño, donde a su vez se permita también responder dichos comentarios y continuar con la discusión.

![image alt text](image_11.png)

**Figura H.1.8** \(H.1 Your Priorities\): Página de idea

### 6. Mejoras en la interfaz de anotación de textos

Comparando la interfaz de anotación de textos entre lo que se tiene en Consul y en otras herramientas especializadas en eso se puede ver bastante diferencia en la usabilidad y visualización de las mismas.

### 7. Permitir agregar noticias a una propuesta

Uno de los puntos fuertes para el proceso de deliberación puede ser permitir agregar noticias asociadas a una propuesta. Se puede ver aplicado en Your Priorities, donde cuentan con una pestaña diferenciada que también sirve para votar a favor o en contra y hacer comentarios sobre la misma.

![image alt text](image_12.png)

**Figura H.1.11 \(H.1 Your Priorities\): **Página de noticias en ideas

### ~~8. Permitir agregar documentos, imágenes y URLs a una propuesta~~

~~~~Una funcionalidad útil todavía no desarrollada es la posibilidad de agregar tanto imágenes como documentos de forma adjunta a una propuesta o a un comentario. Se puede ver un ejemplo de esta funcionalidad en el uso de adjuntos de Loomio.~~ ~~

PROPUESTA REPETIDA \(VER PROPUESTA 1\) ... HE INTEGRADO AMBAS PROPUESTAS EN LA Nº 1. Habría que renumerar las prouestas a partir dde aquí.

### 9. Mejora contenidos iniciales post-instalación

En muchas de las aplicaciones estudiadas se facilita la creación de contenidos iniciales de cara a poder comprender mejor la aplicación y los tipos de contenidos soportados. En el caso de algunas, como Decidim y Consul, estos contenidos iniciales \(también llamados seeds o semillas en el caso del framework Ruby on Rails\), se tratan de contenidos generados automáticamente por una librería basada en "Lorem ipsum", textos sin sentido que sirven para poder visualizar el diseño final a falta de los contenidos reales.

Por otra parte, en el caso de Discourse, esos contenidos iniciales son la propia explicación de la herramienta: cómo personalizarla inicialmente, preguntas frecuentes, textos de bienvenida a ciertas categorías, etc. Esto facilita la entrada de los usuarios iniciales \(administradores\) a la herramienta, ya que no deben buscar en la documentación de la herramienta sino que directamente se encuentran en la misma.

![image alt text](image_13.png)

**Figura D.1.7 \(D.1 Discourse\):** Página principal con sesión de administrador iniciada


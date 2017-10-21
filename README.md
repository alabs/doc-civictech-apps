![image alt text](image_0.png)

Análisis de plataformas de participación ciudadana y comunidades digitales

# ¿Qué es este documento?

El presente documento recoge los análisis realizados a distintos aplicativos web desarrollados para facilitar y modelizar la participación ciudadana en procesos de gobernanza, con el objetivo de mejorar y ampliar en su caso, las funcionalidades de la plataforma de participación Decidim \([https://decidim.org](https://decidim.org)\) así como avanzar en dinámicas innovadoras de participación ciudadana mediadas por las tecnologías de la información \(TICs\).

Los análisis se han realizado sobre la situación de los aplicativos a fecha de octubre de 2017.

# Metadatos

## Autoría

Este documento ha sido escrito por Andrés Pereira de Lucena. El autor es a su vez el editor del texto. Las contribuciones de terceras personas serán aceptadas o rechazadas y en su caso reconocidas en este apartado.

## Revisores

Daniel Vázquez \(Asociación aLabs\), Txema Laullón \(Asociación aLabs\), Pablo Aragón.

![image alt text](image_1.png)

## Resumen ejecutivo

El presente estudio recoge los análisis realizados a distintos aplicativos web de participación ciudadana con el objetivo de servir de base para mejorar y ampliar, en su caso, las funcionalidades de la plataforma de participación Decidim \([https://decidim.org](https://decidim.org)\) así como avanzar en dinámicas innovadoras de participación ciudadana.

Al tratarse de aplicativos protegidos con licencias libres o de código abierto se han podido realizar instalaciones de pruebas de los mismos así como un análisis pormenorizado de las acciones que pueden realizarse con distintos perfiles de usuario.

Con el fin de facilitar la navegación y comparación entre aplicativos, se han categorizado los mismos según el tipo de dinámica participativa con la que cuentan: Integral, Comentario de texto, Mapeo colaborativo, Debate, Escritura colaborativa en tiempo real, Transparencia, Propuestas \(votación a pares\), Propuestas \(priorización\), Voto electrónico, eGroupware y Dinamización de asambleas.

Así mismo se ha realizado una comparativa de ciertos metadatos de los aplicativos, como son su URL, URL de su repositorio, resumen \(en inglés y castellano\), lenguaje y framework en el que se encuentra programado, fecha del inicio del desarrollo, cantidad de versiones publicadas, cantidad de tablas en la base de datos \(BBDD\), popularidad en GitHub y estado del mantenimiento, todo ello con el objetivo de simplificar, en la medida de lo posible, la toma de decisiones sobre las mejoras y/o ampliaciones a realizar en la plataforma Decidim.

Por último se proponen una serie de recomendaciones con el fin de mejorar ciertos aspectos funcionales del desarrollo de Decidim.

Por cada aplicativo estudiado se recogen sus metadatos, funcionalidades y capturas de pantallas. A continuación se realiza un análisis de en qué contextos se ha utilizado, el estado de su arquitectura así como de los servicios necesarios para hacerlo funcionar,  y finalmente se analiza su modelo de datos \(modelos relevantes, listado de tablas y gráficos UML de las mismas\).

Los aplicativos estudiados para la elaboración de este análisis han sido:

* Decidim

* Open Irekia

* Consul

* DemocracyOS

* COMT

* Open Ministry

* Ushahidi

* FixMyStreet

* Discourse

* Loomio

* Etherpad

* HackMD

* Pombola

* Alaveteli

* pol.is

* All Our Ideas

* Your Priorities

* e-petitions \(gov.uk\)

* Agora Voting

* Helios Voting

* elgg

* Adhocracy

* Turnometro

## Palabras clave

Democracia participativa, software, participación ciudadana, comentarios de texto, e-democracy, liquid democracy, text annotation, citizens proposals, crowdsourcing, deliberación, discusión, consenso, Decidim, Open Irekia, Consul, DemocracyOS, COMT, Open Ministry, Ushahidi, FixMyStreet, Discourse, Loomio, Etherpad, HackMD, Pombola, Alaveteli, pol.is, All Our Ideas, Your Priorities, e-petitions \(gov.uk\), Agora Voting, Helios Voting, elgg, Adhocracy, Turnometro, Integral, Comentario de texto, Mapeo colaborativo, Debate, Escritura colaborativa en tiempo real, Transparencia, Propuestas \(votación a pares\), Propuestas \(priorización\), Voto electrónico, eGroupware, Dinamización de asambleas.

## Cómo citar este documento

Pereira de Lucena, A. \(2017\) _Análisis de plataformas de participación ciudadana y comunidades digitales_. https://www.gitbook.com/book/alabs/doc-civictech-apps/details 

## Licencia

Copyright 2017 Andrés Pereira de Lucena, bajo las licencias Creative Commons BY-SA \(Reconocimiento compartir Igual\) y GFDL \(Licencia de Documentación Libre de GNU\):

### CC BY-SA: Creative Commons Reconocimiento Compartir Igual 4.0 Internacional

Usted es libre de copiar y redistribuir el material en cualquier medio o formato, remezclar, transformar y crear a partir del material, para cualquier finalidad, incluso comercial. El licenciador no puede revocar estas libertades mientras cumpla con los términos de la licencia. Bajo las siguientes condiciones: a\) Reconocimiento: debe reconocer adecuadamente la autoría, proporcionar un enlace a la licencia e indicar si se han realizado cambios. Puede hacerlo de cualquier manera razonable, pero no de una manera que sugiera que tiene el apoyo del licenciador o lo recibe por el uso que hace. b\) Compartir Igual: Si remezcla, transforma o crea a partir del material, deberá difundir sus contribuciones bajo la misma licencia que el original. No hay restricciones adicionales, no puede aplicar términos legales o medidas tecnológicas que legalmente restrinjan realizar aquello que la licencia permite. Puede encontrarse la licencia completa en:[ https://creativecommons.org/licenses/by-sa/4.0/deed.es\_ES](https://creativecommons.org/licenses/by-sa/4.0/deed.es_ES)

### GFDL: Licencia de Documentación Libre de GNU

Se concede permiso para copiar, distribuir y/o modificar este documento bajo los términos de la licencia de documentación libre GNU, versión 1.3 o cualquier otra versión posterior publicada por la Free Software Foundation; sin secciones invariantes ni textos de cubierta delantera, tampoco textos de contraportada. Puede encontrar una copia de la licencia en[ http://www.gnu.org/copyleft/fdl.html](http://www.gnu.org/copyleft/fdl.html)


{% include "./SUMMARY.md" %}


## Criterios de autoría y cómo participar en este documento [^1]

Este documento se abrirá a la participación. Podrás contribuir a este documento de varias formas diferentes. Excepto la función de edición el resto de las formas de participación y los niveles y criterios de autoría se especifican a continuación:

* *Editor/a:* Se encarga de la monitorización del texto, sus versiones, correcciones, estructuración, etc. Puede coincidir o no con alguna de las autoras. Se trata, en definitiva de un/a coordinador/a de la colaboración del texto. Es función del editor/a solicitar las revisiones y leerlas.

* *Autoras/es*: Son autoras/es quienes propiamente han redactado el texto. El orden de los autores refleja la contribución de los mismos siendo el primer nombre el de quien más ha escrito. El/la autor/a habrá leído y revisado el texto en su versión final o en versiones anteriores pero no tiene por qué estar de acuerdo con la configuración final del texto, labor que queda en manos del o la editora.

* *Contribuidor/a*: Aquí pueden considerarse dos grupos de contribuidores. Por una parte, los y las revisoras académicas del documento (en caso de que su contribución sea considerable) y, por otra, colaboradores/as externos/as cuya contribución haya sido de valor y se haya consolidado en partes de texto incluidas en el documento. La diferencia entre contribuidor y autor queda en manos del editor o del resto de autores pero, en todo caso, la contribución debe ser menor a la del resto de autoras/es. Como regla general, si un autor ha escrito menos del 10% del texto debería considerarse contribuidor/a. A su vez, ser contribuidor/a requiere al menos haber escrito dos o tres párrafos.

* *Participante*: Se trata de una persona que, sin haber contribuido con una parte de texto específica al documento, ha realizado contribuciones de valor, como comentarios pertinentes al mismo o ha proporcionado criterios, referencias o elementos de discusión valiosos.

* *Revisor/a*: Esta labor incluye una lectura minuciosa de todo el texto, la corrección de errores y la propuesta de mejoras al mismo. Por lo general, es un trabajo por encargo (solicitado a una persona que se considera competente en la materia), aunque es posible que alguien contribuya haciendo una revisión sin solicitud expresa. En tal caso, la profundidad y calidad de la misma pueden calificar para considerar a esta persona revisora.

[^1]: Esta división y especificación de niveles de autoría se ha copiado directamente de los criterios establecidos en el proyecto FLOK Society - Buen conocer (véase: Barandiaran et al. 2015, pp.38-39).)



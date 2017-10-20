### G.2.3 Implantación

Aplica el método de la comparación a pares (pair-wise comparison[^1]), donde se comparan múltiples opciones para ver cual es la preferida. 

Entre los múltiples beneficios que tienen este tipo de votación es el de evitar el efecto arrastre o bandwagon[^2], en el que las personas al ver múltiples opciones terminan escogiendo las que tienen mayor aceptación. 

Otro punto positivo de este tipo de votación es que dificulta que el proceso sea cooptado por un lobby o grupo de presión organizado, como ha ocurrido en el proceso de Open for Questions organizado por la Casa Blanca (Administración de Barack Obama), cuya pregunta más votada ha sido sobre la legalización de la marihuana, ya que la National Organization for the Reform of Marijuana Laws (NORML) ha movilizado a sus simpatizantes para que voten por dicha temática. En el caso de las votaciones con el método de comparación a pares, estos usuarios deberían pasar por muchas otras opciones antes de llegar a la que su organización les ha llamado a votar. 

A nivel gubernamental, se ha utilizado en distintos procesos: 

Por parte del estado de Rio Grande do Sul de Brasil en el contexto del Governador Pregunta[^3]: 

*El proceso se inició cuando los ciudadanos sugirieron 1.300 ideas relacionadas con cinco diferentes aspectos de la atención de salud (por ejemplo, el acceso a la atención, la salud familiar). A continuación, la oficina del gobernador puso en marcha una importante campaña de difusión pública para alentar a los residentes a priorizar estas ideas a través de un proceso de votación en línea. Para ampliar la participación, hubo actos públicos e incluso una "furgoneta de votación" con ordenadores conectados a Internet que llegaron a todo el Estado. En tan sólo 30 días, Governador Pregunta recogió 120.000 votos, y estos votos se utilizaron para seleccionar las 10 mejores ideas de cada una de las cinco categorías. *

Cuenta con una API[^4] dónde aplicaciones externas pueden crear preguntas, ideas, presentar elecciones binarias y analizar los resultados, a través de distintos métodos[^5]:

* usando un cliente para la API de ejemplo.

* creando una aplicación Rails para actuar como cliente.

* operando una instalación propoia del código de allourideas.org

* creando una aplicación en cualquier lenguaje que se comunica con la API a través del protocolo HTTP: 

En Calgary (Canada) se ha utilizado para la priorización y propuesta de qué servicios de la ciudad tienen más valor para los ciudadanos.[^6]

Se ha utilizado para involucrar a los  ciudadanos en la preparación de  PlaNYC, el plan de sostenibilidad a largo plazo de la ciudad de New York, a través de la pregunta "¿Qué crees que es mejor para tener una ciudad de New York más verde y mejor?"[^7]. De las diez ideas más votadas, ocho fueron propuestas por la ciudadanía. 

A nivel de integración se recomienda estudiar el aplicativo pairwise-api[^8] en caso de considerarlo interesante para algún proceso que cuente con cientos o miles de propuestas que deban priorizarse. 


[^1]: https://en.wikipedia.org/wiki/Pairwise_comparison
[^2]: https://es.wikipedia.org/wiki/Efecto_arrastre
[^3]: http://blog.allourideas.org/post/14248022671/governor-genro-tops-president-obama-on-citizen
[^4]: https://github.com/allourideas/pairwise-api
[^5]: https://github.com/allourideas/pairwise-api/wiki/Using-The-API
[^6]: http://www.calgarycitynews.com/2011/04/which-city-services-matter-most.html
[^7]: http://blog.allourideas.org/post/6326304438/making-new-york-greener-and-greater 
[^8]: https://github.com/allourideas/pairwise-api

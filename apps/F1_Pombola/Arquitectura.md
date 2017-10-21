### F.1.4 Arquitectura

Está desarrollado con el framework Django del lenguaje de programación python.

Permite tener distintas instancias y presentar un diseño, contenidos o código en función de la configuración que tenga en la variable COUNTRY\_APP del fichero conf/general.yml \(por ejemplo _ghana_, _kenya_ o _nigeria_\). Cada una de estas configuraciones son librerías \(aplicaciones en la jerga de Django\) que permite un grado de personalización profundo. Para cada uno de los ejemplos:

_pombola\# ls pombola/ghana/_

_contextprocessors.py  data  data.py  forms.py  \_init.py  management  models.py  static  templates  tests.py  urls.py  utils.py  views.py_

_pombola\# ls pombola/kenya/_

_2013-election-data  forms.py     **init**.pyc  management  shujaaz.pyc  tests.py  views\_facebook\_experiments.py   views\_iebc\_office\_locator.pyc_

_budget-data         forms.pyc    lib.py        migrations  static       urls.py   views\_facebook\_experiments.pyc  views.py_

_electiondata2017  \_\_init.py  lib.pyc       shujaaz.py  templates    urls.pyc  views\_iebc\_office\_locator.py    views.pyc_

_pombola\# ls pombola/nigeria/_

_data  initialimport  \_init.py  lib.py  management  static  templates  tests.py  urls.py  views.py_

En su propia documentación comentan que esta forma de personalizar no es la óptima sino como se encuentra funcionando actualmente[^1]:

_Estas notas cubren cómo funciona actualmente el estilo, pero es casi seguro que no es el mejor camino y necesita mejoras, lo que se espera que se haga como parte de una refactorización más amplia para facilitar la reutilización de la base de código en varios países._

A nivel de servidores se recomienda el uso del servicio de SaaS \(_Software as a Service_\) Heroku[^2], aunque también cuenta con ejemplos de configuración en servidores web para tener una instalación propia.

![image alt text](image_1.png)

**Figura F.1.4.1:** Arquitectura de servidores de Pombola

Original: These notes cover how the styling currently works, but it is almost certainly not the best way and needs improving, which will hopefully be done as part of a larger refactor to make it easier to reuse the codebase across several countries.


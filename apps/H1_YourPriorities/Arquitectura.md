### H.1.4 Arquitectura

Se trata de una aplicación web hecha con nodeJS y el framework javascript para frontend Polymer.

El analisis se ha realizado sobre la tercera versión:

* **Open Active Democracy**[^1]: de 2009 a 2012. Hecha con Ruby on Rails.

* **Your Priorities**[^2]: de 2013 a 2016. Hecha con Ruby on Rails.

* **Your Priorities App**[^3]: desde 2016. Hecha con NodeJS.

A nivel de documentación no cuenta con una explicación exhaustiva de cómo proceder con la instalación inicial. Siguiendo los pasos detallados en el fichero README del proyecto[^4], se concluye la instalación con el siguiente mensaje de error:

_$ ./start_

_\(...\)_

* at Function.Promise.bind \(/home/ubuntu/your-priorities-app/node\_modules/bluebird/js/release/bind.js:65:20\)\*

_Executing \(default\): SELECT "id", "name", "hostname", "access", "deleted", "default\_locale", "google\_analytics\_code", "description", "website", "ip\_address", "user\_agent", "weight", "status", "counter\_posts", "counter\_points", "counter\_groups", "counter\_users", "counter\_organizations", "only\_admins\_can\_create\_groups", "theme\_id", "other\_social\_media\_info", "configuration", "created\_at", "updated\_at", "domain\_id", "user\_id" FROM "communities" AS "Community" WHERE "Community"."hostname" = 'yrpri.compas' AND "Community"."deleted" = false LIMIT 1;_

_\[2017-08-30T16:27:16.309Z\]  WARN: your-priorities/1523 on dev-yourpriorities:_

* Cant find community { user: null,\*

* context: 'setYpCommunity',\*

* err: 'Community not found',\*

* errorStatus: 404 }\*

Al no conseguir instalarlo en un servidor propio y no contar con documentación que recomiende un proceso de despliegue, no se ha podido instalar y analizar la arquitectura del aplicativo.


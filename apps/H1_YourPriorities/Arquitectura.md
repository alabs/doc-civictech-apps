### H.1.4 Arquitectura

Se trata de una aplicación web hecha con nodeJS y el framework javascript para frontend Polymer.

Esta se trata de la tercera versión: 

* **Open Active Democracy** (NOTE:  https://github.com/rbjarnason/open-active-democracy ): de 2009 a 2012. Hecha con Ruby on Rails. 

* **Your Priorities** (NOTE:  https://github.com/rbjarnason/your-priorities ): de 2013 a 2016. Hecha con Ruby on Rails. 

* **Your Priorities App** (NOTE:  https://github.com/rbjarnason/your-priorities-app/ ): desde 2016. Hecha con NodeJS. 

A nivel de documentación no cuenta con una explicación exhaustiva de cómo proceder con la instalación inicial. Siguiendo los pasos detallados en el fichero README del proyecto (NOTE:  https://github.com/rbjarnason/your-priorities-app/ ), se concluye la instalación con el siguiente mensaje de error:  

*$ ./start*

*(...)*

* at Function.Promise.bind (/home/ubuntu/your-priorities-app/node_modules/bluebird/js/release/bind.js:65:20)*

*Executing (default): SELECT "id", "name", "hostname", "access", "deleted", "default_locale", "google_analytics_code", "description", "website", "ip_address", "user_agent", "weight", "status", "counter_posts", "counter_points", "counter_groups", "counter_users", "counter_organizations", "only_admins_can_create_groups", "theme_id", "other_social_media_info", "configuration", "created_at", "updated_at", "domain_id", "user_id" FROM "communities" AS "Community" WHERE "Community"."hostname" = 'yrpri.compas' AND "Community"."deleted" = false LIMIT 1;*

*[2017-08-30T16:27:16.309Z]  WARN: your-priorities/1523 on dev-yourpriorities:*

*	Cant find community { user: null,*

*  	context: 'setYpCommunity',*

*  	err: 'Community not found',*

*  	errorStatus: 404 }*

Al no conseguir instalarlo en un servidor propio y no contar con documentación que recomiende un proceso de despliegue, no se ha podido instalar y analizar la arquitectura del aplicativo.



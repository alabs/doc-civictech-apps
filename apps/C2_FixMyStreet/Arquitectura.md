### C.2.4 Arquitectura

A nivel de personalizaciones cuentan con la posibilidad de sobreescribir tanto el código HTML como CSS, e incluso se puede agregar código hecho en el lenguaje del servidor (perl). En su propia página dan los motivos por lo que recomiendan realizarlo de esta manera: 

*Le recomendamos encarecidamente que siga este sistema, en lugar de simplemente editar los archivos existentes, porque significa que podrá actualizar FixMyStreet sin que las actualizaciones sobreescriban sus cambios.*[^1]

Cuentan con documentación muy detallada de cómo ha de realizarse la instalación y configuración inicial de la aplicación[^2], e incluso con extras no técnicos como materiales de marketing de guerrilla para extender el conocimiento de la herramienta[^3].

A nivel de servidores recomiendan la siguiente configuración: 

* Servidor web: nginx/Apache

* Servidor de aplicaciones: PostgreSQL 

* Servidor SMTP

* Servidor de envío de notificaciones (send_report/Open311)

* Tareas programadas (cron)

* API de MapIt

* Claves de conexión al servicio de mapas (Google Maps o Bing)

![image alt text](image_2.png)

**Figura C.2.4.1:** Esquema a nivel de servidores de FixMyStreet

[^1]: Traducido de http://fixmystreet.org/customising/ 
Texto original: We strongly recommend you follow this system – rather than just editing existing files – because it means that you’ll be able to upgrade FixMyStreet without the updates overwriting your unique changes.
[^2]: http://fixmystreet.org/customising/checklist/
[^3]: https://www.fixmystreet.com/about/posters


# kfp-clickcount
Cuenta los clicks que se producen en una web, de momento todos, pronto selectivamente.

Al instalar el plugin se crea una tabla para almacenar los enlaces que se han ido pulsando y las veces que se ha pulsado cada uno, así como la fecha en que se pulsó el enlace por primera vez.

A partir de este momento cada vez que se pulse un enlace en el fronted este se agregará a la tabla si no existe o se incrementará el contador si el enlace ya estaba registrado.

El plugin crea un nuevo menú en el escritorio que muestra la lista de enlaces con sus contadores. 

![Tabla con enlaces y contadores](img/kfp-clickcount-admin.png)

## Tareas pendientes 
Aunque en esta primera versión la implementación es muy básica sería sencillo modificar el plugin para que registrara enlaces marcados con una **clase** determinada, distinguir enlaces con la misma URL pero con distinto **id**, etc.

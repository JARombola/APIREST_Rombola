# API REST - Rombolá Julián

## Login
La pass para acceder es siempre **1234**.

Para acceder como "Administrador", el nombre de usuario a ingresar es: **admin** -> Tiene todos los permisos.

Cualquier otro nombre de usuario permitirá acceder como usuario "común" -> Sólo puede visualizar el listado de alumnos.

## Menú lateral
A la izquiera siempre estará disponible el menú de acciones, pero el guard determinará si se puede acceder a ellos o no, según el tipo de usuario.

## Servicio REST
El listado de alumnos se obtiene de **mockapi**, en el servicio *alumnos service*.

## Lazy loading
El lazy loading se encuentra aplicado en el app.module.
En este caso no tiene demasiado sentido, pero igualmente está implementado.

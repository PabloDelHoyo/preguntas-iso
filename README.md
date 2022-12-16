# Preguntas tipo test de ISO-2

## Cómo contribuir
Lo que se pretende al utilizar Github es que cualquiera que quiera subir sus preguntas pueda hacerlo
pero solo aquellas a las que una persona con rol de colaborador en el repositorio les haya dado su visto
bueno puedan ser incorporadas junto a las demás.

La dinámica que se debe seguir para colaborar no es muy diferente a lo que se ha desarrollado en el proyecto
de laboratorio de ISO2. Los pasos que se van a detallar a continuación se pueden llevar perfectamente a cabo a
través de la aplicación web de Github. Si se quisiera saber cómo hacerlo desde la línea de comandos, consulta [1].

1. Crea un _fork_ de este repositorio pulsando el botón en el que pone _fork_, situado arriba a la derecha. Un _fork_, 
en Github, es una copia privada de un repositorio que sigue guardando relación con el original. En la terminología de Git, el repositorio original
se conoce como _upstream_.
2. Sitúate dentro del _fork_ y crea una nueva rama con el nombre que consideres. Cámbiate a esa rama y añade las preguntas
como archivo de texto plano y en formato Aiken (el que los profesores han indicado para que Moodle las reconoza automáticamente sin ninguna modificación) en los directorios
que corresponda. Se pueden crear los commits que consideres porque, en caso de que la rama sea fusionada con la rama principal de _upstream_, en esta solo habrá un solo commit que contendrá
todos los cambios unificados llevados a cabo en la rama.
3. Crea un pull request de la rama que has creado. Es muy recomendable añadir un título y una descripción descriptiva. Una
vez hecho esto, en el repositorio _upstream_ aparecerá, en la pestaña de pull requests, el pull request que acabas de crear. Los cambios
que hayas hecho se incorporarán a la rama principal de _upstream_ si alguien en el repositorio con rol de colaborador les da su visto bueno.
Si se llegara a fusionar tu rama con el `main` de _upstream_, es recomendable eliminarla para que no se vayan acumulando.
4. Un _fork_ no se sincroniza automáticamente cada vez que su _upstream_ cambia por lo que esta operación hay que hacerla manualmente. Pare sincronizarlo,
hay que pulsar el botón en el que pone _Syn fork_. Si no se han añadido commits a la rama `main` del _fork_, esta operación no debería fallar.

Por último, si cualquiera que consultase las preguntas encontrase cualquier tipo de fallo, que no dude en abrir un _issue_ o, en caso de que
pueda solucionarlo, un pull request.
### Fuentes: 
* [1] Chacon, S y Straub, B.(2014). Contributing to a project, [*Pro Git*](https://git-scm.com/book/en/v2/GitHub-Contributing-to-a-Project)  pp. 170-190

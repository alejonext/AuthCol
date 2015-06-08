#propuesta de pasos a segir

para poder organizarnos e ir construyendo la idea de lo que debería ser el sistema podríamos:

* estudiar modelos de correo electronico como el de [lavabit](https://darkmail.info/downloads/dark-internet-mail-environment-december-2014.pdf) 
y proyectos similares como el del [gobierno aleman](http://www.bmi.bund.de/EN/Topics/IT-Internet-Policy/New-Identity-Card/new-identity-card_node.html).
* organizar en un diagrama de caso de usos las funciones que se desean del sistema y los
actores que intervienen en el mismo(podemos usar el software Dia que es opensource para que podamos ir modificandolo).
* definir los permisos de los diferentes actores del sistema(que pueden hacer, modificar, consultar, guardar)
* definir alguna información inicial para guardar sobre los usuarios(diseño de db)
* definir los recursos a exponer en el api, las politicas para su consumo y los metodos permitidos para cada recurso
* diseño de backend(si es un sistema p2p es el diseño del nodo) y diseño de clientes(en un sistema p2p no necesariamente es un nodo)

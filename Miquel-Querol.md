# 18/04/2023
Hemos estado configurando la red fisicamente para tener conexión externa. Hemos configurado el ordenador de Kevin para que pueda conectarse a la red 192.0.2.33/29 que estara dentro de nuestro rango de ips de la sede hasta la 192.0.2.41/29, y funciona porque nos da una ip.

# 26/04/2023
Hemos vuelto a ir al taller en clase de redes en la que yo me he puesto a configurar que el cable ethernet que viene desde la roseta tenga internet en la subred que esta configurado y luego configurar el mickrotick con winbox y una vez dentro borrar toda la configuracion hasta dejarla en zero y luego intentar volver a conectarme con winbox gracias a la MAC pero se complico porque no encontraba el mickro tick en el winbox despues de resetear loguearme borrar configuracion y probar el winbox.

# 27/04/2023
Hoy hemos vuelto a entrar al taller en la clase de Redes y por ello me vuelvo a poner con el mickrotick a volver a probar si funciona el winbox y al final resulta que con mi ordenador el protocolo que utiliza el winbox para visualizar la mac del mikro tick y funciona correctamente desde el de Kevin . 

# 02/05/2023
El Mikrotick se ha quedado a punto de estar configurado con internet despues de conseguir entrar al menu de configuracion gracias al winbox en el ordenador de Kevin ya que el mio no encontraba la mac y he empezado a configurar la ip, dns, firewall...

# 03/05/2023
Hoy he seguido probando la configuracion del mikrotick con las ip que son y escogiendo de subrango 192.168.50.1 para otro puerto y despues de que todo me funcionase he cambiado el cable de red del TP-Link al mikrotick y ha funcionado bien ahora voy a comenzar a ordenar la red completa y dejarla bien a la vista.
Pero al final me he puesto a probar el funcionamiento de las vlan en el mikrotick para ver que funcionen bien y se vean dos vlan diferentes.

# 04/05/2023
Hoy hemos ido al taller en las horas de redes y he empezado a ver el funcionamiento en las vlan para empezar a configurar el switch que he reseteado para probar su funcionamiento y configurarlo a medida para que tenga las vlan que tengan que ser Tagged Y las que no Untagged y conectadas al id vlan que es.

# 05/05/2023
Hoy hemos ido al taller en las 3 horas de redes. Hoy he creado un esquema para comprender las vlans que vamos a utilizar en el mikrotick y el switch y tambien he creado un esquema para saber que vlan necesitamos y cuales pondremos en cada departamento, me falta comprender como configurar el mikrotick y el switch para que todo funcione correctamente

# 10/05/2023
Hoy hemos ido al taller en las horas de ISO y he seguido probando el funcionamiento de la red para que funcione, Alvaro se ha venido a ayudarme.

# 11/05/2023
Hoy hemos ido tansolo 2 horas al taller y hemos seguido con el mikrotick solo que ahora nos hemos puesto a hacer que desde el puerto 4 del microtick de internet al punto de acceso y de este a los ordenadores para que se pongan a hacer cosas los demas compañerosç

# 15/05/2023
Hoy al fin hemos conseguido configurar las vlan para que funcionen y el internet con ellas gracias a la sede de galicia que me ayudaron a la comprensión de la configuracion de la red y tambien funciona el switch que tiene configurada todas las vlans en cada puerto y los departametos conjuntos con el servidor.

# 16/05/2023
Hoy hemos ido al taller 4 horas y al llegar he cogido a Alvaro y nos hemos puesto a acabar de hacer el pads panel ya que solo hicieron 6 puertos y nos faltaban 9-10, lo hemos acabado y ahora voy a poner a organizar a la gente porque parece que pasa el tiempo y aun no han comenzado a configurar usuarios, directivas, firewall, permisos... Y a este paso voy a irme a configuracion para hacerlo yo y organizar y si pongo a instalar algo no me siento a ver como va la barrita cargando y me busco cosas para hacer como la intranet pero parece que no :v.

# 17/05/2023
Hemos ido al taller a la hora despues del patio en redes y he probado el dhcp en el mickrotik y lo he dejado completamente configurado para que el switch tenga todas las vlans con dhcp, solo me faltaria configurar un trunck en el switch para que redirija la vlan de produccion hacia el otro switch que no es configurable para poder conectar los supuestos 30 clientes. Al haber acabado de configurar y probar el dhcp rapido voy a empezar la intranet para lenguaje hecha en bootstrap.


# 19/05/2023
El dia de hoy he llegado y he aprendido a acceder al switch cisco desde el serial port y configurarlo desde la terminal de putty, pero como hemos tenido que probar que se vean las vlans me he quedado a medias haciendolo el lunes seguire probando las vlan y configurare el cisco.

# 22/05/2023
Hoy lunes he llegado y he seguido probando configuraciones en el switch cisco para que pueda repetir la vlan 90 en todos los puertos menos en el 1 que es el que recibe y he estado toda la clase probando configuraciones que he encontrado en youtube y en foros pero no me repite el dhcp que tengo configurado en la vlan y desde el puerto que conecta el switch si que me da el dhcp pero al conectarlo y configurarlo no, me parece que el ritmo de mi grupo es lamentable en cuanto a los 3 compañeros que llegan al taller y se pasan jugando con el movil o ordenador o mirando como se intala el sistema operativo en vez de ir a trello ver que hay que hacer o simplemente preguntar, no creo que llegemos al ultimo dia con todo lo que piden.

# 23-26/05/2023
En esta semana he conseguido saber el funcionamiendo del switch cisco en el que voy a configurar todos los departamentos y tambien he estado haciendo diseños en fisico y luego pasandolos a digital para saber que va en cada puerto del cisco y para organizarlo desde el principio para poder explicarselo a los demas compañeros que hablando de esto kevin ha adelantado bastate bien los documentos de la red y alvaro ha adelantado el servidor Zabix pero los demas del equipo entre que se quedan mirando cuando algo esta insalando o a jugar a el movil en vez de ponerse a ver el funcionamiento de toda la red o simplemente ver que todo esta a punto o lo que falta por hacer...

# 29/05/2023
Hoy lunes he llegado al taller como siempre y me he puesto a probar el funcionamiento de todos los dispositivos de red y me funcionaban raro el cisco pero despues de probarlo funciona bien solo que tarda uno minutos en configurarse y darte internet. Y despues de probar configure el switch del backup haciendole un trunk al switch tp-link para que salga hacia el switch pequeño el departamento de backup y funciona perfectamente. Por ultimo tambien configure el trunk hacia el switch de produccion y despues de probarlo tambien funciona perfectamente dando la vlan 90 y internet en todos los puertos. Voy a hacer un diseño de la red para saber como funciona y me pondre a hacer tareas de instalacion y configuracion porque faltaran bastantes.

# 29/05/2023-02/06/2023
Esta semana he estado revisando la red mas a fondo probando cosas que no funcionan y tambien probando el bonding ya que tendra que tener uno minio y tambien he hecho diagramas de toda la red, vlans y rutas para que los demas componentes del grupo puedan entenderlo tambien el funcionamiento completo de la red.
Y bueno no por nada pero adrian se pasa las clases d taller con en movil :v.

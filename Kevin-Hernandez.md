# 18/04/2023
He estado configurando el acceso a Internet junto a Álvaro y Miquel para tener conexión externa. Tenemos un servidor de internet global para las 4 sedes y luego las dividimos en subredes, en nuestro caso hemos conectado nuestro adaptador con el cableado que va hasta nuestra sede. En nuestro caso, desde la 192.0.2.33/29 hasta la 192.0.2.41/29. Hemos comprobado con mi portátil que tenía acceso a internet, por lo que todo está correcto.

# 20/04/2023
Hemos estado instalando los sistemas operativos en los 3 servidores que luego internamente virtualizaremos más servidores. Hemos tenido algunos problemas principalmente porque las ISO que habíamos grabado era MBR y las BIOS estaban en GPT, luego cuando ya las teníamos en GPT, pues la configuración en algunas BIOS están con algún tipo de Secure Boot y no nos detectaba los USB para instalar los sistemas. También me he puesto a configurar en el Servidor 2 el netplan para que tenga internet, cuando he acabado ese me he ido a ayudar a Rafa que estaba intentándolo en el servidor 3.

# 26/04/2023
He estado configurando la red que me quedaba del servidor 3, pero no lo hemos conseguido porque el cable que tiene el internet lo estaban utilizando para intentar configurar el mikrotik Miquel, mientras tanto Álvaro y yo hemos estado reiniciando el router de TP-Link y lo hemos conseguido hacer funcionar. Adrián ha probado a ver si daba internet y si había.

# 27/04/2023
He estado diseñando el esquema de red y hemos estado viendo un poco el futuro del proyecto.

# 28/04/2023
He estado mirando el Mikrotik con Miquel, pero hemos visto que hay un problema por el que no nos da internet, no hemos conseguido solucionarlo, probaremos el próximo día o si no nos esperaremos al miércoles para que Raúl nos ayude a identificar el problema porque hemos estado reiniciando varias veces y comprobando que las máscaras de red estaban bien. Luego he estado mirando porque el Servidor 1 no funcionaba, a la hora de arrancar no cogía el S.O. instalado, al final según nos ha explicado Juan era un problema del Legacy Mode.

# 02/05/2023
He estado mirando un poco más el Mikrotik, pero he dejado que continuase Miquel mientras que yo ponía etiquetas a los servidores, cables, etc… El próxima día organizaré el cableado antes de encenderlo todo y así tenerlo ya organizado, además he estado con Álvaro atornillando el Switch 1 al rack. Luego hemos vuelto a hacer alguna prueba con el Mikrotik, pero sin lograrlo, entonces vamos a esperarnos a mañana con Raúl.

# 03/05/2023
Hemos conseguido obtener internet en el Mikrotik, Álvaro y yo hemos estado crimpando los cables que irán directamente al patch panel, también hemos movido un slot arriba el Switch que pusimos ayer y al entrar a clase he acabado de organizar los cables antes de encender los ordenadores. Luego he estado mirando porque habíamos instalado el Servidor de Dominio con interfaz y lo hemos cambiado a sin interfaz para tener más potencia y consumir menos.

# 04/05/2023
He estado instalando el sistema operativo del cliente, además que he estado revisando como íbamos en general y comprobando el trello. Hoy ha sido más un día de organización y verificar como vamos, que de trabajo.

# 05/05/2023
He estado junto a Álvaro acabando de crimpar 4 cables más al patch panel y fijarlo en el rack, luego hemos movido e instalado un switch más y así se ha quedado todo el rack anclado, hemos movido el mikrotik. El lunes reorganizaremos todo el cableado del rack.

# 09/05/2023 
Hoy hemos estado organizando el cableado del rack, hemos puesto unas canaletas por el suelo, pisemos no se partan los cables y por dentro de ella hemos pasado los 8 cables rj-45 del patch panel. He cambiado el SAI de lugar también y hemos movido un poco los switches del rack. Pero ya está todo con bridas, sujeto y agradable para la vista.

# 10/05/2023
He empezado el servidor de web externa en AWS y finalmente lo he acabado, está hecha la estructura básica hasta que Jorge nos diga como era la web externa porque nos explicó que teníamos que poner nuestros nombres, etc… Entonces hasta que le pregunte lo dejamos así. Y me he puesto con el servidor de monitorización Zabbix, pero como no habían instalado el servidor de monitorización, pues me he puesto a instalarlo. Mañana intentaré dejarlo instalado.

# 11/05/2023
He estado mirándome un poco la documentación de Zabbix para cuando esté instalado empezar a monitorizar todo. Mientras acabamos de conseguir internet, he estado creando el servidor de copias de seguridad en AWS, de momento tengo muchas dudas. Sobre la web externa AWS, Jorge me ha dicho que nos lo explicará más adelante, entonces de momento está en el aire.

# 12/05/2023
He estado reformando el trello y he estado haciendo la parte del CPD de la práctica 3.1 de Juan (distribución del rack y CPD)

# 15/05/2023
He estado mirando para configurar el servidor de datos, he dibujado el esquema y mañana empezaré con la instalación

# 16/05/2023
He estado instalando el servidor de datos (FreeNAS), me ha dado varios problemas y estoy resolviéndolos porque por ejemplo necesitamos el DHCP. Supongo que tardaré un par de días aún hasta tenerlo todo funcionando con AWS

# 17/06/2023
He empezado a instalar el SSH en todos los servidores, pero me he dado cuenta de que el servidor 2 estaba mal instalado (las particiones) y nos ha tocado volver a instalarlo, mientras tanto he empezado a pasar a limpio para imprimir la hoja de conexiones del rack, donde va cada cosa y cada puerto, etc.

# 18/06/2023
He acabado la hoja de conexiones del rack, cada puerto donde irá y que equipo tendrá conectado. Esta en digital por lo que lo imprimiremos.

# 19/05/2023
He reorganizado todos los latiguillos del patch panel, los he cambiado todos. Además los he identificado y he comprobado que nos funcionan y los que no han funcionado los he apartado.

# 22/05/2023
He estado ayudando a Álvaro a instalar el cliente de Zabbix para comprobar la monitorización mientras él instalaba el servidor, y también he estado instalado todo el servidor de almacenamiento y he configurado el TrueNAS

# 23/05/2023
He reorganizado todos los cables de red desde el patch panel hasta los equipos y he cambiado también los latiguillos. He cambiado un par de departamentos en las VLAN porque estaban mal o faltaban, y también he distribuido las IP. He creado un esquema para saber cada cable donde va conectado.
![RACK drawio](https://github.com/Kamara-ASIX/proyecto-integrador/assets/128040590/3243d671-ce01-4c09-8c3a-33d99bda9a21)

# 24/05/2023
Hoy hemos tenido poco tiempo porque han cortado la luz, pero me ha dado tiempo a colgar la hoja que hice ayer en el patch panel y a seguir con la práctica de Juan 3.1 que la tenemos para mañana.

# 25/05/2023
He probado con Álvaro si desde un cliente teníamos conexión SSH con el Servidor 1, una vez comprobado que funcionaba, he estado con Miquel cambiando todos los cables del Patch Panel a los diferentes switches, uno de ellos no funcionaba y Raúl nos lo ha cambiado, y por último he actualizado la hoja de conexiones.

![RACK drawio](https://github.com/Kamara-ASIX/proyecto-integrador/assets/128040590/e78b7c2b-d2c5-4d3e-86d6-7a269488628d)

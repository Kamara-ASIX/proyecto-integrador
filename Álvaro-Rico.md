# - **18/04/2023**
Hemos ido Kevin, Miquel y yo a dividir las subredes y probar el correcto funcionamiento de Internet del servidor de comunicaciones para nuestra sede (Madrid).
Hemos conectado toda la red fisicamente para tener conexión externa. En nuestro caso, el rango de la primera subred del subneting es de la IP 192.0.2.33/29 hasta la 192.0.2.41/29, y ha funcionado correctamente.

# - **20/04/2023**
Hoy al volver al taller, hemos estado instalando los 3 sistemas operativos (Lubuntu 22.04) de los servidores físicos en los cuales luego internamente virtualizaremos más servidores y tardamos más de lo que esperabamos por ciertos problemas que nos surgieron, ya que las ISO's que habíamos grabado eran MBR, cuando la BIOS/UEFI de los servidores estaba en GPT.

# - **26/04/2023**
Hoy nos hemos puesto a intentar configurar el MikroTik empezando por resetearlo, para más tarde con winbox dejar la configuración en zero y configurarlo, pero al estar ya en ello otros de mis compañeros, Kevin y yo aprovechamos para resetear y configurar lo que será nuestro punto de acceso inalámbrico.

# - **28/04/2023**
Hoy nada más empezar, nos hemos dado cuenta de que el Servidor 1 de nuestra sede no arrancaba con su Sistema Operativo y me he puesto a instalarlo de nuevo, después al no conseguir mi compañero Miquel configurar el MikroTik para conseguir internet a través de él, me he puesto a intentarlo yo hasta conseguir algún avance pero no lo hemos conseguido por lo que aún es necesario configurar algo más para ello.

# - **02/05/2023**
Hoy en la única hora que hemos podido ir al taller, hemos dejado instalados algunos de los Sistemas Operativos Virtualizados en cada servidor y Kevin y yo hemos empezado a montar nuestro CPD empezando por acoplar el Swtich Principal.

# - **03/05/2023**
Hoy hemos dejado totalmente configurado por fin el Mikrotik, con acceso a Internet y totalmente funcional y mientras Rafa, Alejandro y Adrián acababan de instalar todos los Sistemas Operativos Virtualizados, Kevin y yo hemos crimpado y arreglado los cables que irán conectados al Patch Panel que utilizaremos, además de arreglar la estructura y distribución de nuestro CPD.

# - **04/05/2023**
Hoy nada más llegar, Rafa se ha puesto a  crear el dominio en el Servidor DC y Alejandro el BDC para unirlo al dominio, pero al no conseguiro, me he puesto a intentarlo yo y he conseguido unirlo al Dominio. Antes de unir el BDC al Dominio Principal, me he puesto a instalar nuestro primer cliente (Windows) pero al tener un fallo con el USB lo instalaré el próximo día.

# - **05/05/2023**
Hoy en las 3 horas de taller, Kevin y yo nos hemos puesto a organizar de nuevo los servidores a virtualizar debido a una confusión que tuvimos el grupo anteriormente y después hemos dejado todo el CPD montado y arreglado, previamente crimpando otros 4 cables más al Patch Panel, con todos los dispositivos necesarios para la sede.

# - **09/05/2023**
Hoy Kevin y yo hemos estado organizando el cableado del rack y hemos puesto unas canaletas por el suelo para que al pisar no se partan los cables y por ella hemos pasado los 8 cables rj-45 que vienen del patch panel. Entre todos hemos decidido cambiar el SAI de lugar y mover un poco los switches. Finalmente ya está todo con bridas, sujeto y agradable para la vista.

# - **10/05/2023**
Hoy me he puesto a instalar 2 de los 5 clientes que serán necesarios para la sede y al finalizar la instalación de ambos, me he puesto con Miquel a intentar configurar las VLAN del Mikrotik.

# - **11/05/2023**
Hoy en el taller, Miquel y yo hemos seguido intentando configurar el internet del Mikrotik para las VLANS y además he empezado a instalar algún servicio dentro del servidor 1.

# - **12/05/2023**
Hoy, hemos estado Miquel y yo las 3 horas de taller intentando que funcionasen las VLAN.

# - **15/05/2023**
Hoy, Miquel y yo hemos estado intentando que todos los equipos tuviesen internet después de configurar las VLAN's en el Mikrotik.

# - **16/05/2023**
Hoy en las horas de taller, después de dejar el Mikrotik totalmente echo y funcional con todas las VLAN's y acceso a internet, Miquel, Rafa y yo nos hemos puesto a crimpar 11 cables restantes que nos faltaban del Patch Panel, lo cúal nos ha llevado bastante tiempo, ya que, solo disponíamos de 8 ya crimpados entre varios días.

# - **17/06/2023**
Hoy, después de haber crimpado los 11 cables más al Patch Panel, he conectado con la ayuda de Rafa el Patch Panel al CPD y hemos organizado todos los cables por las canaletas y todo el recorrido de ellos hasta los equipos finales.

# - **18/06/2023**
Hoy he echo con la ayuda de Alejandro todo el script para crear e implementar todos los Usuarios, Grupos y OU's de nuestro servidor DomainController aunque no nos ha llegado a funcionar del todo por ciertos errores con 3 usuarios.

# - **19/06/2023**
Hoy he dejado terminado y totalmente funcional el script de los usuarios de la sede.

# - **22/05/2023**
Hoy he estado instalando desde 0 el Servidor de monitorización en Virtualbox, configurandólo y instalando los paquetes necesario para hacer un servidor Zabbix.

# - **23/05/2023**
Hoy he me he puesto a documentarme un poco para poder configurar el servidor Zabbix, pero por un problema no lo he podido dejar totalmente funcional.

# - **24/05/2023**
Al solucionar el problema que se trataba de una línea que faltaba en el fichero de configuración (/etc/zabbix/zabbix_server.conf), he dejado el servidor funcionando, además he conseguido añadir el Mikrotik para monitorearlo y no he podido añadir los clientes, por un fallo que tuvimos al instalarlos.

# - **25/05/2023**
Hoy, he estado con Kevin probando la conexión ssh para acceder remotamente desde el cliente 3 al servidor 1. También he ayudado a Miquel a cambiar los cables del switch TP Link y organizarlos para conectarlos al switch Cisco.

# - **26/05/2023**
Hoy, he intentado ponerme a agregar un cliente cualquiera al servidor Zabbix porque la última vez ya tuve problemas pero con el poco tiempo que he tenido debido a un fallo en el cuadro eléctrico, nos han cortado la luz continuamente y no he podido hacer mucho.

# - **29/05/2023**
Hoy, me he puesto a configurar el Domain Controller desde RSAT (Cliente 3), he estado arreglando el script de usuarios y he intentado unir un cliente al servidor de monitorización Zabbix.

# - **31/05/2023**
Hoy, me he intentado poner para seguir configurando el Domain Controller para empezar a dejar echos los perfiles móviles, obligatorios, GPO's... Pero hemos tenido un problema con la conexión y con el cliente de RSAT, el cúal debía de estar unido al dominio principal, lo cúal nos ha echo perder tiempo investigando que pasaba, hasta que hemos conseguido arreglar el problema.

# - **01/06/2023**
Hoy, he seguido intentando que funcionase el Domain Controller.

# - **02/06/2023**
Hoy, he intentado unir el Cliente 3 al Dominio, pero al seguir sin funcionar en todos los servidores y clientes, he restaurado la instantanea de cuando funcionaba perfectamente.

# - **05/06/2023**
Hoy, ha vuelto a fallar el Cliente 3 sin razón alguna y Miquel y yo hemos arreglado el error. También he montado la pool de TrueNas del Backup en el servidor de Datos (Windows Server) y he intentado añadir un cliente para monitorizar en el Servidor Zabbix.

# **18/04/2023**
Hemos ido Kevin, Miquel y yo a dividir las subredes y probar el correcto funcionamiento de Internet del servidor de comunicaciones para nuestra sede (Madrid).
Hemos conectado toda la red fisicamente para tener conexión externa. En nuestro caso, el rango de la primera subred del subneting es de la IP 192.0.2.33/29 hasta la 192.0.2.41/29, y ha funcionado correctamente.

# **20/04/2023**
Hoy al volver al taller, hemos estado instalando los 3 sistemas operativos (Lubuntu 22.04) de los servidores físicos en los cuales luego internamente virtualizaremos más servidores y tardamos más de lo que esperabamos por ciertos problemas que nos surgieron, ya que las ISO's que habíamos grabado eran MBR, cuando la BIOS/UEFI de los servidores estaba en GPT.

# **26/04/2023**
Hoy nos hemos puesto a intentar configurar el MikroTik empezando por resetearlo, para más tarde con winbox dejar la configuración en zero y configurarlo, pero al estar ya en ello otros de mis compañeros, Kevin y yo aprovechamos para resetear y configurar lo que será nuestro punto de acceso inalámbrico.

# **28/04/2023**
Hoy nada más empezar, nos hemos dado cuenta de que el Servidor 1 de nuestra sede no arrancaba con su Sistema Operativo y me he puesto a instalarlo de nuevo, después al no conseguir mi compañero Miquel configurar el MikroTik para conseguir internet a través de él, me he puesto a intentarlo yo hasta conseguir algún avance pero no lo hemos conseguido por lo que aún es necesario configurar algo más para ello.

# **02/05/2023**
Hoy en la única hora que hemos podido ir al taller, hemos dejado instalados algunos de los Sistemas Operativos Virtualizados en cada servidor y Kevin y yo hemos empezado a montar nuestro CPD empezando por acoplar el Swtich Principal.

# **03/05/2023**
Hoy hemos dejado totalmente configurado por fin el Mikrotik, con acceso a Internet y totalmente funcional y mientras Rafa, Alejandro y Adrián acababan de instalar todos los Sistemas Operativos Virtualizados, Kevin y yo hemos crimpado y arreglado los cables que irán conectados al Patch Panel que utilizaremos, además de arreglar la estructura y distribución de nuestro CPD.

# **04/05/2023**
Hoy nada más llegar, Rafa se ha puesto a configurar el servidor principal DC para crear el dominio y Alejandro el BDC para unirlo al dominio, pero al no conseguir Alejandro unirlo, me he puesto yo a investigar y he conseguido unirlo al Dominio exitosamente. Antes de unir el BDC al Dominio Principal, me he puesto a instalar nuestro primer cliente (Windows) pero al tener un fallo con el USB me he quedado haciendolo bootable y lo instalaré el próximo día.

# **05/05/2023**
Hoy en las 3 horas de taller, Kevin y yo nos hemos puesto a organizar de nuevo los servidores a virtualizar debido a una confusión que tuvimos el grupo anteriormente y después hemos dejado todo el CPD montado y arreglado con todos los dispositivos necesarios para la sede.

# Proyecto Integrador

# Introducción 
Vamos a empezar el trabajo, de momento tenemos el inventario hecho (*inventario.md*) y tambien internet configurado, ahora durante los proximos dias configuraremos las redes, decidiremos que sistemas operativos ponemos etc...

## 20/04/2023
Hemos empezado a instalar los sistemas operativos para los servidores, hemos puesto Lubuntu 20.04, y el servidor 2 ya tiene internet. El servidor 3 nos quedamos casi finalizando el que tenga internet, mientras Álvaro y Miquel estubieron buscando informacion y probando como se resetea un mickrotick y como se empieza a configurar para configurarlo desde zero y quitarle la configuracion incial de dhcp y otras configuraciones que nos puedan molestar o dar errores.

## 26/04/2023
Hemos estado configurando el internet en los servidores. Miquel sigue intentando conectarse al mickrotick mediante winbox despues de quitarle la configuracion inicial de dhcp y utilizando el winbox para que con un protocolo parecido al del ARP Winbox encuentre la MAC y con ella conectarse al menu de configuracion pero no aparece despues de resetearlo unas cuantas veces y probando.
Y Mientras Álvaro, Kevin, Adrián y Alejandro hemos estado con el TP-Link haciendolo funcionar y así ha sido.

## 28/04/2023
Hoy nos hemos puesto a instalar de nuevo el Sistema Operativo del Servidor 1 y hemos vuelto a intentar configurar el MikroTik para conseguir internet a través de él.
Además hemos instalado VirtualBox en los 3 servidores.

## 02/05/2023
Hemos instalado el VirtualBox en todos los servidores para virtualizar, además de instalar el Extension pack para cifrar los discos de las máquinas virtuales. También hemos organizado un poco el cableado aunque aún falta organizar algunas cosas, Y por último hemos atornillado el Switch 1 al rack. El Mikrotick se ha quedado a punto de estar configurado con internet despues de conseguir entrar al menu de configuracion gracias a winbox en el ordenador de Kevin ya que el de Miquel no encontraba la mac.

## 03/05/2023
Hoy se ha quedado totalmente configurado el Mikrotik (Con acceso a Internet) gracias a Miquel ya lo ha acabado de configurar y ha dejado el mikro tick conectado a el punto de acceso para tener internet mientras termina de configurar toda la red. Rafa, Alejandro y Adrián han instalado todos los Sistemas Operativos que faltaban y Kevin y Álvaro han crimpado y arreglado los cables del Patch Panel, además de la estructura y distribución del CPD.

## 04/05/2023
Hoy se han reinstalado los servicios en el Windows Server Core (1 Servidor). Hemos unido el Servidor 2 al dominio principal. Hemos instalado el Primer Cliente en una maquina aparte de los servidores. Miquel ha empezado a probar las vlan como funcionan y tambien ha empezado a hacer un esquema de red final para aclarar todos los cables y saber como va a quedar fianlmente todo configurado.

## 05/05/2023
Miquel ha estado configurando las vlan, Alejandro y Adrián han reinstalado un sistema operativo porque faltaba los volúmenes, Rafa ha estado instalando el RSAT. Mientras tanto, Kevin y Álvaro han estado acabando de reorganizar el rack y han instalado 4 cables más en el patch panel. El lunes reorganizaremos TODOS los cables.

## 10/05/2023
Alvaro y miquel siguen configurando el microtick para que funcionen las vlans. Kevin ha empezado a hacer el Sitio web de AWS.

## 11/05/2023
Hemos seguido haciendo la configuracion del microtick y switch para que funcionen las vlans probando las configuraciones que salen el los videos de Redes pero no funciona por lo que hemos optado por probar la configuracion de otro grupo que les funcionen y restaurar un backup y configurarlo para nuestra sede. Kevin tambien ha seguido creando el sitio web en AWS.

## 15/05/2023
Hoy han conseguido que se configure la red internet por las vlans y tambien hemos conseguido que se distribullan por todo el switch, nos faltaria volver a hacer el pads pabel debido a que Alvaro y Kevin solo crimparon 5 cables ethernet y necesitariamos 15 en total aproximadamente pero para el proximo dia ya quedaran la red totalmente configurada y los servicios totalmente instalados para empezar a configurar todos los servicios y maquinas.

## 16/05/2023
El dia de hoy hemos ido 4 horas al taller las cuales hemos cogido el patch panel y hemos acabado de crimparle las conexiones que nos faltaban mientras que la red funciona perfectamente con la vlas, el mickrotick y el switch para que siguan intalando aplicaciones y servicios.

## 17/05/2023
Hemos seguido configurando vlan y nos hemos puesto con el DHCP, además hemos estado haciendo la hoja de conexiones y hemos reinstalado el S.O del servidor 2

## 18/05/2023
Hemos acabado la hoja de conexiones, hemos reinstalado el servidor 2 y hemos empezado a instalar el backup de dominio que teníamos, también hemos estado instalando el ssh en los servidores y equipos. Y por último hemos hecho el script de usuarios

## 19/05/2023
Kevin, ha reorganizado todos los latiguillos del patch panel, los ha cambiado todos. Además los ha identificado y ha comprobado que funcionan y los que no, los ha apartado. Álvaro y Alejandro han dejado terminado y totalmente funcional el script de los usuarios de la sede. Miquel ha aprendido a acceder al switch cisco desde el serial port y configurarlo desde la terminal de putty y Adrián ha instalado el servidor 2 en virtual box.

## 22/05/2023
Adrian ha reinstalado el cliente 4. Kevin ha estado ayudando a Álvaro a instalar el cliente de Zabbix, después de haber instalado el servidor, para comprobar la monitorización mientras él instalaba el servidor, y también ha estado instalado todo el servidor de almacenamiento y ha configurado el TrueNAS. Miquel mientras tanto, ha seguido probando la configuración en el switch cisco, la cúal es complicada, para que pueda repetir la vlan 90 en todos los puertos.

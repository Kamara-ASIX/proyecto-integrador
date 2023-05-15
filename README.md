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

# 15/05/2023
Hoy han conseguido que se configure la red internet por las vlans y tambien hemos conseguido que se distribullan por todo el switch, nos faltaria volver a hacer el pads pabel debido a que Alvaro y Kevin solo crimparon 5 cables ethernet y necesitariamos 15 en total aproximadamente pero para el proximo dia ya quedaran la red totalmente configurada y los servicios totalmente instalados para empezar a configurar todos los servicios y maquinas.

# Registro del proyecto

Este es un registro del proyecto que hemos estado llevando a cabo, dividido por fechas.

## 18/04/2023
Mientras que Kevin, Álvaro y Miquel iban al taller para dividir las subredes, Alejandro, Adrián y yo decidiamos que sistema operativo íbamos a instalar en cada servidor y que servicios iba a proporcionar cada uno de estos. Concluimos en instalar un Lubuntu 20.04 en los tres servidores y después virtualizar Windows Server Core 2022 en ellos. Y los servicios los distribuímos de la siguiente manera: 

1er Servidor Físico: SO Lubuntu GUI
- Servidor empresarial y monitorització: Windows Server Core 2022

2º Servidor Físico: SO Lubuntu GUI
- Servidor empresarial secundari o adicional: Windows Server Core 2022
- Servidors de dades: 
- Servidor web intranet: 

3er Servidor Físico: SO Lubuntu GUI 
- Servidor web extern: 
- Servidor d’aplicacions i utilitats


## 20/04/2023
Empezamos instalando los sistemas operativos en los servidores, hemos elegido Lubuntu 20.04 como SO principal por sus bajos requisitos y posteriormente instalaremos en VirtualBox el sistema operativo con el cual administraremos los servidores. Estuvimos un buen rato intentando instalar los SO porque al hacer las ISO nos equivocamos de formato y tuvimos que volver a instalarlos todos. Después de tener todo instalado me puse a hacer el netplan en el servidor 3 para establecer conexión a internet, sin exito.


## 26/04/2023
Hemos vuelto a probar con netplan la conexión a internet, pero ahora el servidor 1 que funcionaba correctamente había dejado de funcionar. Por tanto dejamos el netplan aparte y configuramos la red con el entorno gráfico de Lubuntu. Una vez ya nos funcionaba internet en todos los equipos (los servidores) me puse a ver con Miquel si podíamos configurar el Mikrotik. Por alguna razón no el Winbox no lo detectaba, lo reiniciamos y restauramos de fábrica varias veces pero no hubo manera.


## 28/04/2023
Hemos llegado y el servidor 1 que funcionaba correctamente por alguna razón no instalaba el S.O. Después según nos ha dicho Juan era un problema del Legacy Mode.


## 02/05/2023
Primero hemos puesto atornillado el Switch al Rack para tenerlo ya puesto. Después me he puesto a instalar la máquina virtual que contendrá Windows Server del Primer Servidor. Posteriormente me puse a instalar y configurar los servicios necesarios como DHCP, DNS, Active Directory... Por un error de comunicación instalé Windows Server con entorno gráfico y se requería Windows Server Core.


## 03/05/2023
En el poco tiempo que hemos estado hoy he vuelto a instalar el Windows Server, esta vez Core.


## 04/05/2023
Hoy he creado el dominio de nuevo e instalado los servidores necesarios como DHCP, DNS, Active Directory... Esta vez no los he configurado porque hemos decidido que ya lo haremos con el RSAT. Una vez hecho esto, hemos intentado añadir varias veces el Segundo Servidor al domino. Al principio no nos ha funcionado pero finalmente hemos podido unirlo cambiando el DNS a la IP del Servidor 1.


## 05/05/2023
Nos hemos puesto Álvaro y yo a finalizar la instalación del primer cliente. Posteriormente me he puesto a instalar el RSAT y entre todos nos hemos puesto a organziar un poco el cableado. 

## 09/05/2023

Con Adrián y Alejandro, hemos puesto las dos regletas bajo la mesa para organizar todo un poco mejor. Una vez hecho esto, hemos decidido mover los PC clientes de forma que los cables les lleguen desde debajo de la mesa, pasando por el centro de estas. Los PC servidores los hemos movido abajo.

## 11/05/2023

He empezado reorganizando un poco el Trello. Después me he puesto a mirar un poco como funcionaba el SAI. Según la página del proveedor me he tenido que descargar la aplicación Winpower para poder configurarlo y monitorizarlo. A falta de un cable para conectar el SAI al PC, no se pudo realizar ninguna configuración.

## 12/05/2023

Hoy nada más empezar, le he pedido a Juan a ver si tenia un cable para poderme conectar al SAI. Me lo ha dado y he empezado a mirar configuraciones en Winpower. Tras estar varias horas buscando en manuales, preguntando a Chat GPT y probando configuraciones, me he rendido y le he dicho a Juan que quizás la configuración de orden de prioridad de apagado del SAI podría no estar disponible en este modelo. Me ha comentado que lo investigará y me informará de si se puede o no.

## 15/05/2023

Junto con Álvaro y Miquel nos hemos puesto a crimpar de nuevo el Patch Panel ya que nos faltaban cables.

## 16/05/2023

Con Álvaro y Miquel hemos acabado de crimpar lo poco que nos quedaba del Patch Panel y después con Álvaro y Alejandro hemos probado los cables y etiquetado estos. Después el Patch Panel lo hemos puesto en el rack, le hemos puesto las bridas y pasado los cables por la canaleta del suelo.

## 17/05/2023

He estado probando a conectar por ssh un cliente con el servidor 3 (Aplicaciones y características). He creado reglas en el firewall de ambos equipos pero no ha habido manera. He recurrido a Miquel por si era un error de red pero no hemos podido encontrar que fallaba.

## 18/05/2023

He seguido intentando probar lo del ssh pero al ver que no funcionaba me he dado por vencido y he empezado a configurar el servidor 3 (Aplicaciones y características).

## 19/05/2023

He visto en la documentacion que el servidor 3 (Aplicaciones y características) estaba mal instalado, ya que habían puesto un Debian y debe ser un Windows Server. Por tanto me ha tocado reinstalarlo y añadirlo al dominio tras haber tenido varios problemas con la red.

## 22/05/2023

Por alguna razón al Miquel cambiar un parámetro de la red la máquina host servidor 3 (Aplicaciones y características) ha dado un error y no iniciaba ni dejaba abrir la consola bash. Tras estar probando un rato con Juan si se podía solucionar, se decide que reinstalaremos la máquina host.

## 23/05/2023

Empiezo a instalar Windows Server en el servidor 3 (Aplicaciones y características). Lo configuro y uno al dominio. Nos quitan la luz y no podemos continuar trabajando.

## 25/05/2023

Instalo en el servidor 3 (Aplicaciones y características) los paquetes de Gimp y LibreOffice que después serán publicados para que los clientes puedan decidir si instalarlos o no.

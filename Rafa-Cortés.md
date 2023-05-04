*18/04/2023*

Mientras que Kevin, Álvaro y Miquel iban al taller para dividir las subredes, Alejandro, Adrián y yo decidiamos que sistema operartivo ibamos a instalar en cada servidor y que servicios iba a proporcionar cada no de estos. Concluimos en instalar un Lubuntu 20.04 en los tres servidores y después virtualizar Windows Server Core 2022 en ellos. Y los servicios los distribuímos de la siguiente manera: 

1er Servidor Físico: SO Lubuntu GUI
  1. Servidor empresarial y monitorització: Windows Server Core 2022

2º Servidor Físico: SO Lubuntu GUI
  2. Servidor empresarial secundari o adicional: Windows Server Core 2022
  5. Servidors de dades: 
  6. Servidor web intranet: 

3er Servidor Físico: SO Lubuntu GUI 
  7. Servidor web extern: 
  3. Servidor d’aplicacions i utilitats


*20/04/2023*

Empezamos instalando los sistemas operativos en los servidores, hemos elegido Lubuntu 20.04 como SO principal por sus bajos requisitos y posteriormente instalaremos en VirtualBox el sistema operativo con el cual administraremos los servidores. Estuvimos un buen rato intentando instalar los SO porque al hacer las ISO nos equivocamos de formato y tuvimos que volver a instalarlos todos. Después de tener todo instalado me puse a hacer el netplan en el servidor 3 para establecer conexión a internet, sin exito.


*26/04/2023*

Hemos vuelto a probar con netplan la conexión a internet, pero ahora el servidor 1 que funcionaba correctamente había dejado de funcionar. Por tanto dejamos el netplan aparte y configuramos la red con el entorno gráfico de Lubuntu. Una vez ya nos funcionaba internet en todos los equipos (los servidores) me puse a ver con Miquel si podíamos configurar el Mikrotik. Por alguna razón no el Winbox no lo detectaba, lo reiniciamos y restauramos de fábrica varias veces pero no hubo manera.


*28/04/2023*

Hemos llegao y el servidor 1 que funcionaba correctamente por alguna razón no instalaba el S.O. Después según nos ha dicho Juan era un problema del Legacy Mode.


*02/05/2023*

Pirmero hemos puesto atornillado el Switch al Rack para tenerlo ya puesto. Después me he puesto a instalar la máquina virtual que contendrá Windows Server del Primer Servidor. Posteriormente me puse a instalar y configurar los servicios necesarios como DHCP, DNS, Active Directory... Por un error de comunicación instalé Windows Server con entorno gráfico y se requería Windows Server Core.

*3/05/2023*

En el poco tiempo que hemos estado hoy he vuelto a instalar el Windows Server, esta vez Core.

*04/05/2023*

Hoy he creado el dominio de nuevo e instalado los servidores necesarios como DHCP, DNS, Active Directory... Esta vez no los he configurado porque hemos decidido que ya lo haremos con el RSAT. Una vez hecho esto, hemos intentado añadir varias veces el Segundo Servidor al domino. Al principio no nos ha funcionado pero finalmente hemos podido unirlo cambiando el DNS a la IP del Servidor 1.

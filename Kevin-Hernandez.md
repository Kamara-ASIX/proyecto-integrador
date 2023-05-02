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

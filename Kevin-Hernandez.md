# 18/04/2023
He estado configurando el acceso a Internet junto a Álvaro y Miquel para tener conexión externa. Tenemos un servidor de internet global para las 4 sedes y luego las dividimos en subredes, en nuestro caso hemos conectado nuestro adaptador con el cableado que va hasta nuestra sede. En nuestro caso, desde la 192.0.2.33/29 hasta la 192.0.2.41/29. Hemos comprobado con mi portátil que tenía acceso a internet, por lo que todo está correcto.

# 20/04/2023
Hemos estado instalando los sistemas operativos en los 3 servidores que luego internamente virtualizaremos más servidores. Hemos tenido algunos problemas principalmente porque las ISO que habíamos grabado era MBR y las BIOS estaban en GPT, luego cuando ya las teníamos en GPT, pues la configuración en algunas BIOS están con algún tipo de Secure Boot y no nos detectaba los USB para instalar los sistemas. También me he puesto a configurar en el Servidor 2 el netplan para que tenga internet, cuando he acabado ese me he ido a ayudar a Rafa que estaba intentándolo en el servidor 3.

# 26/04/2023
He estado configurando la red que me quedaba del servidor 3, pero no lo hemos conseguido porque el cable que tiene el internet lo estaban utilizando para intentar configurar el mikrotik Miquel, mientras tanto Álvaro y yo hemos estado reiniciando el router de TP-Link y lo hemos conseguido hacer funcionar. Adrián ha probado a ver si daba internet y si había.

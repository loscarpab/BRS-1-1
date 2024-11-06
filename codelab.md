author: Carlos Cordero Moreno
summary: Una guía para bastionar la BIOS/UEFI del HP Laptop 15s-fq2010ns
id: 1
categories: codelab,markdown,bios,hp,uefi,bastionar,seguro
environments: Web
status: Published

# Proyecto 1.1

## Introducción
Duration: 00:02:00

En esta guía vamos a ver como proteger la BIOS del HP Laptop 15s-fq2010ns, la bios es lo primero que ejecuta el ordenador, sino queremos que nadie manipule el arranque debemos configurarla con las opciones que trae nuestro portatil, para securizar lo máximo posible el arranque.

Para entrar en la BIOS debemos pulsar la tecla F12, una vez pulsamos el botón de encendido



## Contraseña de administrador
Duration: 00:02:00

Para poder configurar la contraseña debemos irnos al apartado de seguridad de la BIOS
![bios](/images/bioseguridad.jpg)
 
Una vez ahí presionamos la tecla Enter donde pone contraseña de administrador

![inputpasswdadmin](/images/adminpwdconf.jpg)

Rellenamos los dos campos con la contraseña que queremos que tenga

![adminpasswdest](/images/adminpwd.jpg)


## Contraseña de arranque
Duration: 00:01:00

Desde la pantalla anterior, bajamos y presionamos la tecla Enter donde pone contraseña de administrador  

![inputpasswdboot](/images/bootpwd.jpg)

Rellenamos los dos campos con la contraseña que queremos que tenga  

![bootpasswdest](/images/bootpwd.conf.jpg)

## Arranque USB
Duration: 00:02:00

Nos vamos a la pestaña de opciones de arranque 

![boot](/images/boot.jpg)

Nos vamos hasta donde pone Arranque USB y pulsamos la tecla Enter 

![bootusb](/images/bootusb.jpg)

## Secure Boot
Duration: 0:01:00

Desde la pantalla del paso anterior, bajamos hasta Secure Boot, y en mi caso, estaba ya activado, pero si no lo está pulsamos la tecla Enter

![secureboot](/images/secureboot.jpg)

Ya estaría bastionada al máximo la BIOS de este dispositivo.



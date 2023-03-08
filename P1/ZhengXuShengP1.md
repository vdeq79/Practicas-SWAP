# 1. Instalación de máquinas virtuales
Comenzamos con la instalación de las máquinas virtuales, puesto que vamos a realizar el mismo procedimiento en ambas máquinas, vamos a centrarnos en la configuración de una de ellas:
<p align="center"><img src="images/1.png"><p>
Le damos 4GB de RAM:
<p align="center"><img src="images/2.png"><p>
Y 10GB de disco duro:
<p align="center"><img src="images/3.png"><p>
Vamos a instalar Ubuntu Server, en mi caso, será la 20.04:
<p align="center"><img src="images/4.png"><p>
Arrancamos e introducimos nuestros datos:
<p align="center"><img src="images/5.png"><p>
Dejamos también que nos instale SSH:
<p align="center"><img src="images/6.png"><p>

## 1.1 Instalación de Apache+PHP+MySQL
Una vez instalado la máquina virtual, instalamos Apache, PHP y MySQL:
<p align="center"><img src="images/7.png"><p>
Una vez finalizada la instalación comprobamos:
<p align="center"><img src="images/8.png"><p>
Podemos ver que el servidor está inactivo, lo activamos:
<p align="center"><img src="images/9.png"><p>
De mismo modo con MySQL:
<p align="center"><img src="images/10.png"><p>


Activamos el adaptador NAT y solo-anfitrión:
<p align="center"><img src="images/11.png"><p>
<p align="center"><img src="images/12.png"><p>
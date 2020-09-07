#Configuración Debian 10

1. Configuración del archivo Sources.list

	Ubicación: `etc/apt/sources.list`
	Fuente: [link](https://computingforgeeks.com/add-debian-10-buster-official-repositories-to-sources-list/)

	
	sources.list: 
	```bash
	deb http://deb.debian.org/debian buster main contrib non-free
	deb-src http://deb.debian.org/debian buster main contrib non-free
	
	deb http://security.debian.org/debian-security buster/updates main contrib
	deb-src http://security.debian.org/debian-security buster/updates main contrib
	```

2. Instalador antena WiFi TP-WN722N
	Fuente: [link](https://erickcion.wordpress.com/2011/09/11/instalador-antena-wifi-usb-tp-link-tl-wn722n-para-linux/)
	Código fuente: https://github.com/erickcion/tlwn722n-linux-install

	```
	cd carpeta_descomprimida
	chmod +x ./install.sh
	su root -c ./install.sh
	```


# Programas instalados

1. **Editor de texto Vim**
	
	```
	sudo apt-get install vim
	```

2. **Build-essential**
	
	```
	sudo apt-get install build-essential
	```

3. **Python3**

	```
	sudo apt-get install python3
	```

6. **Telegram Desktop**
	
	```
	sudo apt-get install telegram-desktop
	```

7. **Java**
	
	Fuente: [link](https://chachocool.com/como-instalar-java-openjdk-en-debian-10-buster/)

8. **Visual Studio Code**

	Fuente: [Link](https://linuxize.com/post/how-to-install-visual-studio-code-on-debian-10/)

9. **Node js**

	Fuente: [Installing Using a PPA](https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-debian-10)

10. **Turtl**

	Descargar paquete de la [página oficial](https://turtlapp.com/download/) y descomprimirla con:

	```
	tar -xjvf compresedFileName.tar.bz2
	```

	Acceder a la carpeta generada y ejecutar:

	```
	./install.sh
	```

	 La aplicación usa el paquete 'libgconf-2-4', que se usó para el sistema de base de datos de configuración GNOME (bibliotecas compartidas), pero no estaba disponible, así que instalé 'gconf-gsettings-backend' que la reemplazó:


	```
	sudo apt-get install gconf-gsettings-backend
	```

11. **Pandoc**

	```
	sudo apt-get install pandoc texlive-latex-base texlive-fonts-recommended texlive-extra-utils texlive-latex-extra
	```
	
	```
	pandoc text.md -o text.pdf
	```


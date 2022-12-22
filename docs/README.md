# Olimpica
##### Imagen Desktop

![](https://github.com/Andrezgrondona/olimpicaItGloblers/blob/main/assets/img/desktop.png?raw=true)

##### Olimpica es un E-commerce que se desarrollo en su diagramacion y funcionalidad con la plataforma VTEX IO
----------------------
### Configuracion
------------
1. Accede de configuracion de VTEX IO, se debera instalar ell CLI (Command Line Interface) de VTEX IO ,

2. Clona este repositorio en tu maquina local para poder trabajar y accede a el por tu terminal.

	Ya clonado el repositorio se deberan hacer modificaciones en el 	 manifest.json.
	Se debera modificar el `vendor` y en `name`
	`"vendor": "name-vendor"`, `"name": "my-test-theme"`
	
3. Para usar Store Framework , ejecute vtex list y verifique si esas aplicaciones ya están instaladas, Si no lo están, ejecute el siguiente comando para instalarlos: vtex install vtex.store-sitemap vtex.store -f.

4. Adicionalmente tendras que instalar las siguientes aplicaciones customizadas de la tienda
5. Aplicaciones  Customizadas
	- "itgloberspartnercl.whatsapp-button": "0.x",
	- "itgloberspartnercl.bullets-diagramation": "0.x",
	- "itgloberspartnercl.add-to-cart-info": "0.x",
	- "itgloberspartnercl.custom-deparment-search": "0.x",
	- "itgloberspartnercl.quick-order": "0.x",
	- "itgloberspartnercl.special-diagramation": "0.x",
	- "itgloberspartnercl.pdf-reader": "0.x"

-------

# Olimpica

**Olimpica** es un E-commerce que se desarrollo en su diagramacion y funcionalidad con la plataforma  VTEX IO

--------------------------------------

Imagen desktop 
![](https://github.com/Andrezgrondona/olimpicaItGloblers/blob/main/assets/img/desktop.png?raw=true)

--------------------------------------

###  Configuracion

1.
Acceda  de configuracion de VTEX IO, se debera instalar ell CLI (Command Line Interface) de VTEX IO


2.
Clona este repositorio en tu maquina local para poder trabajar y accede a el por tu terminal. 



3.
Ya clonado el repositorio se deberan hacer modificaciones en el `manifest.json`.

Se debera modificar el `vendor` y en `name`

--------------------------------------
`"vendor": "name-vendor",
  "name": "my-test-theme",`.
  
  --------------------------------------
  4.
Para usar Store Framework , ejecute vtex list y verifique si esas aplicaciones ya están instaladas.

Si no lo están, ejecute el siguiente comando para instalarlos: vtex install vtex.store-sitemap vtex.store -f.

Adicionalmente tendras que instalar las siguientes aplicaciones customizadas de la tienda

 --------------------------------------

### Aplicaciones customizadas

    
    
    "itgloberspartnercl.whatsapp-button": "0.x",
    "itgloberspartnercl.bullets-diagramation": "0.x",
    "itgloberspartnercl.add-to-cart-info": "0.x",
    "itgloberspartnercl.custom-deparment-search": "0.x",
    "itgloberspartnercl.quick-order": "0.x",
    "itgloberspartnercl.special-diagramation": "0.x",
    "itgloberspartnercl.pdf-reader": "0.x"
-----

  5.
Al ejecutar vtex list, puede verificar si algún tema está instalado.

Es común tener ya instalado un vtex.store-theme cuando inicia el proceso de desarrollo frontal de la tienda.

Por lo tanto, si lo encuentra en la lista de aplicaciones, copie su nombre y version, luego utilícelo junto con el comando vtex uninstall. Por ejemplo:

`vtex uninstall vtex.store-theme@0.0.1`

---------------

 6.
Para iniciar el entorno de trabajo o un preview de la tienda, ejecute el comando `vtex link` en la terminal.

---------------

### Store components
    
    "vtex.store": "2.x",
	"vtex.store-header": "2.x",
    "vtex.product-summary": "2.x",
    "vtex.store-footer": "2.x",
    "vtex.store-components": "3.x",
    "vtex.styleguide": "9.x",
    "vtex.slider": "0.x",
    "vtex.carousel": "2.x",
    "vtex.shelf": "1.x",
    "vtex.menu": "2.x",
    "vtex.minicart": "2.x",
    "vtex.product-details": "1.x",
    "vtex.product-kit": "1.x",
    "vtex.search-result": "3.x",
    "vtex.login": "2.x",
    "vtex.my-account": "1.x",
    "vtex.flex-layout": "0.x",
    "vtex.rich-text": "0.x",
    "vtex.store-drawer": "0.x",
    "vtex.locale-switcher": "0.x",
    "vtex.product-quantity": "1.x",
    "vtex.product-identifier": "0.x",
    "vtex.product-specification-badges": "0.x",
    "vtex.product-review-interfaces": "1.x",
    "vtex.telemarketing": "2.x",
    "vtex.order-placed": "2.x",
    "vtex.stack-layout": "0.x",
    "vtex.tab-layout": "0.x",
    "vtex.responsive-layout": "0.x",
    "vtex.slider-layout": "0.x",
    "vtex.iframe": "0.x",
    "vtex.breadcrumb": "1.x",
    "vtex.sticky-layout": "0.x",
    "vtex.add-to-cart-button": "0.x",
    "vtex.store-image": "0.x",
    "vtex.modal-layout": "0.x",
    "vtex.search": "1.x",
    "vtex.store-link": "0.x",
    "vtex.disclosure-layout": "1.x",
    "vtex.product-list": "0.x",
    "vtex.store-icons": "0.x",
    "vtex.product-price": "1.x",
    "vtex.store-form": "0.x",
    "vtex.store-newsletter": "1.x"
		

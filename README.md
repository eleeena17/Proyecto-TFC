# Proyecto-TFC
**SORILABI**

![image](https://github.com/eleeena17/Proyecto-TFC/assets/113434495/f9baccb2-a945-4922-bc7e-bb0f666c6b78)


**Descripción**

Sorilabi es una tienda de ropa online destinada principalmente a los jóvenes, aunque cuenta con ropa válida para cualquier edad, ya que son prendas muy fáciles de combinar con cualquier tipo de ropa y estilo.
Cuenta además con varias formas para contactar con la empresa, ya que en numerosas ocasiones a los usuarios les gustaría poder hablar de forma directa y sencilla con los creadores para tratar sobre dudas en los productos que vienen, por lo que ofrecemos un formulario de contacto por correo electrónico además de la posibilidad de poder hablar por whatsapp.
También cuenta con una interfaz muy sencilla y facilmente navegable para cualquier tipo de usuario, ya que así les proporcionamos una mayor comodidad al navegar por mi web.

**Funcionalidades**

* Compra de productos
* Envío de mensajes por correo electrónico
* Aplicación de descuentos

**Estado del proyecto**

<h4 >
:construction: Proyecto en construcción :construction:
</h4>
Aún faltan funcionalidades para aplicar en un futuro, como el uso de tarjeta de compra para efectuar los pagos finales.

![image](https://github.com/eleeena17/Proyecto-TFC/assets/113434495/a14ccc23-ccc8-49c8-83ff-6e4b575e4e65)

**Acceso al proyecto**

Para poder visualizar la tienda de sorilabi hay que seguir estos pasos:

1.Descargar los archivos subidos en el repositorio y ponerlos en una carpeta llamada "wordpress".

2.Instalar el gestor de bases de datos XAMPP.

3.Lanzar Mysql y Apache desde XAMPP pulsando en el botón de Start.

4.Acceder a localhost en tu navegador.

  Puede que te salga algún error debido a que el número del puerto que usa XAMPP de default ya está en uso, por lo que hay que pulsar en Config -> my.ini
  
  ![image](https://github.com/eleeena17/Proyecto-TFC/assets/113434495/6698f5ae-2965-49ff-b633-614f6a480a3b)
  
  Una vez dentro habrá que cambiar el puerto 3306 por el puerto deseado, en mi caso lo cambié por el puerto 3307.
  
  ![image](https://github.com/eleeena17/Proyecto-TFC/assets/113434495/bbb1027b-4721-4d4c-a915-3b460e1fb954)
  
  Posteriormente habrá que acceder a Config -> phpMyAdmin.ini 
  
  ![image](https://github.com/eleeena17/Proyecto-TFC/assets/113434495/c7887f64-fa9d-461f-a1eb-21a0d1a3e66b)
  
  Una vez dentro habrá que agregar al lado de la IP el puerto que hayamos seleccionado, o bien poner localhost y el número del puerto seleccionado.
  
  ![image](https://github.com/eleeena17/Proyecto-TFC/assets/113434495/e34bb165-87ed-45f4-9a21-404c9ab0f50f)
  
   Una vez hechas estas modificaciones, cuando accedamos a localhost nos llevará a una página default de XAMPP.
   
   5.Acceder a la opción phpMyAdmin situada en la parte superior.
   
   6.Acceder a Bases de Datos y crear una nueva llamada tiendawordpress.
   
   7.Una vez creada le importamos los datos de la base de datos de Sorilabi. Estos se encuentran en el archivo tiendawordpress.sql en el resposotorio junto a los demás archivos.
   
   8.Acceder a la carpeta donde se encuentra xampp  en nuestro explorador de archivos y llegar al archivo xampp -> htdocs. 
   
   9.Pegar la carpeta wordpress creada en el paso 1 dentro de htdocs.
   
   10.Buscar en el navegador localhost/wordpress.
   
**Tecnologías utilizadas**
   
   Wordpress

 




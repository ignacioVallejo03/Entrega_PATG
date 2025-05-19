# Entrega_PATG
Trabajo PATG realizado por Daniel Quico e Ignacio Vallejo. Pagina web dirigida a usuarios que busquen Parkings de caravanas.

### Inicialización 
#### 1. Infraestructura de la aplicación 
Decomprimir archivos camperspark.zip , images.zip y guia.zip  
-Camperspark: codigo de la aplicación y carpeta principal  
-Images: carpeta de imagenes que se debe ubicar dentro de la carpeta public quedando camperspark/public/images  
-guia: carpeta de imagenes de la guia de uso que se debera ubicar dentro de images  quedando camperspark/public/images/guia uso (*) dentro de guia deben estar localizadas todas la imagenes en caso de existir otra carpeta dentro de esta, se deberan sacar los archivos a la carpeta guia principal. quedando finalmente camperspark/public/images/guia/( imagenes de la guia.png)  

![image](https://github.com/user-attachments/assets/0f9f34f0-f027-46f7-ac3c-96eb4acde68a)



#### 2. Creación base de datos en Mongo 

Descargar Mongo DB junto con mongo DB compas https://www.mongodb.com/try/download/community  
Abrir Mongo DB compass y crear base de datos de nombre camperspark.  
Abrir una terminal cmd y dirigirse al directorio del archivo camperpark.  
Ejecutar un npm install en caso de no tener instalado node.   
Dentro del directorio camperspark, ejecutar los siguientes comandos en el orden indicado:  
 - node importar_parkings.js  
 - node añadir_centros.js  
 - node añadir_hospitales.js
 - node cargar_gasolineras.js  
Finalmente ejecutar la aplicacion con el comando npm start pudiendo visualizar la página escribiendo http://localhost:3000



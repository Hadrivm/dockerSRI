
## Ejemplo 1: Construcción de imágenes con una página estática

####  Desde una imagen base

El primer paso es crear un directorio para alojar los [ficheros](https://github.com/josedom24/curso_docker_ies/tree/main/ejemplos/modulo5/ejemplo1/version1) de esta página

![image](https://user-images.githubusercontent.com/91189372/223420794-4709149d-7064-40ac-9ce0-83479f4904b4.png)

Creo todos los ficheros necesarios:

![image](https://user-images.githubusercontent.com/91189372/223423318-e98b63c1-508f-4024-acb5-5e3508daa8da.png)

El contenido del `Dockerfile` es el siguiente:

![image](https://user-images.githubusercontent.com/91189372/223423215-e3f8a88d-68aa-4c50-b438-11acc03c91d7.png)

Para crear la imagen:

![image](https://user-images.githubusercontent.com/91189372/223424139-ebe71c40-729e-4807-a63c-719c9567fdda.png)

Listo las imagenes, para ver que se ha creado correctamente:

![image](https://user-images.githubusercontent.com/91189372/223424290-dc075cb0-5359-479d-b58f-d3a72e536abd.png)

Creo el contenedor y compruebo que se está ejecutando:

![image](https://user-images.githubusercontent.com/91189372/223425005-657f430c-a9b3-42aa-878f-54bd0fbd42bc.png)

Finalmente, desde el navegador compruebo el resultado de la página con Docker

![image](https://user-images.githubusercontent.com/91189372/223425237-921389d4-fb00-49d8-8d04-782867a4bc2a.png)


## Ejemplo 2: Construcción de imágenes con una una aplicación PHP

####  Desde una imagen base

Creo el directorio para esta página, en mi caso "Pagina2" y en su interior meto los [ficheros](https://github.com/josedom24/curso_docker_ies/tree/main/ejemplos/modulo5/ejemplo2/version1) necesarios:

![image](https://user-images.githubusercontent.com/91189372/223429189-342edfaa-6020-4eb7-bdc7-6cb2e4cd5093.png)

Creo la imagen

![image](https://user-images.githubusercontent.com/91189372/223429571-6b98e82f-cf2e-49a0-be3e-f5705f7770f1.png)

Compruebo que la imagen se ha creado:

![image](https://user-images.githubusercontent.com/91189372/223429679-8ad76aac-7ddb-42d5-83d8-390448675315.png)

Creo el contenedor y compruebo que se está ejecutando:

![image](https://user-images.githubusercontent.com/91189372/223429859-392a5b69-18de-4f27-80eb-20ea79d19ecb.png)

Desde el navegador accedo a la página PHP

![image](https://user-images.githubusercontent.com/91189372/223430030-8265b033-ff29-424b-b9de-9c7dffadcf09.png)

Si accedo al fichero `info.php` me da información sobre PHP

![image](https://user-images.githubusercontent.com/91189372/223430212-6960d25c-f595-4360-9153-207a65e6c3c6.png)


## Ejemplo 3: Construcción de imágenes con una una aplicación Python

Creo el directorio para alamacenar los ficheros necesarios

![image](https://user-images.githubusercontent.com/91189372/223430577-65095d07-bd30-4a26-b1ca-25613e423f23.png)

Los [ficheros ](https://github.com/josedom24/curso_docker_ies/tree/main/ejemplos/modulo5/ejemplo3) los copio y pego dentro del directorio 

![image](https://user-images.githubusercontent.com/91189372/223433416-a59ec519-60a1-4430-8101-4292148db5c1.png)

Creo la imagen:

![image](https://user-images.githubusercontent.com/91189372/223434110-9eb70fe7-b63f-45cd-8497-5a789d842336.png)

Compruebo que se ha creado correctamente la imagen:

![image](https://user-images.githubusercontent.com/91189372/223434232-f5ef0348-bbd0-429b-969a-9720b76f1bb3.png)

Finalmente, creo el contenedor:

![image](https://user-images.githubusercontent.com/91189372/223434615-cda40219-9b6a-40d2-a104-6ea177e5748a.png)



## Ejemplo 1: Despliegue de la aplicación Guestbook

Los dos contenedores tienen que estar en la misma red y deben tener acceso por nombres (resolución DNS) ya que de principio no sabemos que ip va a coger cada contenedor. Por lo tanto cre los contenedores en la misma red:

![image](https://user-images.githubusercontent.com/91189372/223145321-61ea5ea7-566f-41b7-ad22-46f38f0a2781.png)

Luego ejecuto los contenedores

![image](https://user-images.githubusercontent.com/91189372/223146388-d458dff8-4aa9-469c-b14a-40de90b13bd3.png)

El segundo contenedor también lo ejecuto con

```bash
docker run
```

![image](https://user-images.githubusercontent.com/91189372/223163992-e8ae335c-e9e7-464c-8868-44afd0375d4b.png)

Finalmente, desde el navegador con la IP de mi equipo visualizo el contenido del contenedor Docker

![image](https://user-images.githubusercontent.com/91189372/223178732-d95e725b-2635-4407-9501-80f58cfa805a.png)


## Ejemplo 2: Despliegue de la aplicación Temperaturas

Primero creo una red para conectar los dos contenedores:

![image](https://user-images.githubusercontent.com/91189372/223179477-aeebf853-31e8-428d-87db-54f3cedfacd1.png)

A continuación, ejecuto los dos contenedores:

![image](https://user-images.githubusercontent.com/91189372/223180609-bfdb9bdb-b605-420e-bac8-5d5194b87cc4.png)

El segundo contenedor también lo ejecuto con

```bash
docker run
```

![image](https://user-images.githubusercontent.com/91189372/223181661-f3e49c73-411a-443e-acf3-d1f979e73930.png)

Finalmente, desde el navegador con la misma IP accedo al contenido del contenedor. 

![image](https://user-images.githubusercontent.com/91189372/223181939-647718c4-a167-40c4-b96a-584cb4f7d489.png)

El cual te da la temperatura de la localización que especifique

![image](https://user-images.githubusercontent.com/91189372/223182100-afa4b895-44e9-44bc-ae1e-6e747fad7619.png)


## Ejemplo 3: Despliegue de Wordpress + mariadb

Creo los dos contenedores en la misma red:

![image](https://user-images.githubusercontent.com/91189372/223184527-43df3bf2-0d62-4916-8785-632d52df2f0c.png)

A continuación, ejecuto los dos contenedores:

![image](https://user-images.githubusercontent.com/91189372/223190402-76fd909d-3f0a-4e77-821c-416aa561640c.png)

![image](https://user-images.githubusercontent.com/91189372/223191092-51e0b268-3a04-481d-b3d6-cac1976fda28.png)

Finalmente desde el navegador puedo visualizar la aplicación Wordpress

![image](https://user-images.githubusercontent.com/91189372/223191362-ba5d60b2-cc9a-4e5c-a245-963f1a9a710b.png)


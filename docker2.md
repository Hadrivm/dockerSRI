# Docker Actividad 2

#### 1. Ejecuta la imagen "hello-world"

![image](https://user-images.githubusercontent.com/91189372/223068408-d38cc017-dd44-468d-bd6b-986cfc42eb96.png)

#### 2. Muestra las imágenes Docker instaladas

```bash
docker images
```

#### 3. Muestra los contenedores Docker

```bash
docker ps
```

#### 4. Edita el fichero Dockerfile

![image](https://user-images.githubusercontent.com/91189372/223055155-5cb86702-0a8e-4bdf-9409-0a8debbf8830.png)

#### 5. Construye el contenedor

![image](https://user-images.githubusercontent.com/91189372/223055434-4cdfeaa0-4a37-4e13-8c62-d07582d6c5f2.png)

#### 6. Ejecútalo

```bash
docker run -dp 3000:3000 getting-started
```

A continuación, desde el navegador si accedo a localhost:3000 visualizo la aplicación Docker

![image](https://user-images.githubusercontent.com/91189372/223055779-e5d21e7f-a50a-4e70-af81-36be6149a71a.png)


La cual es una lista de la compra 

![image](https://user-images.githubusercontent.com/91189372/223063735-cb6e28ec-eec3-4fca-b4a2-784f71c0674e.png)

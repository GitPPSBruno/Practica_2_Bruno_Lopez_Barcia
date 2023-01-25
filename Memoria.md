# Memoria Practica 2 Bruno Lopez Barcia 

----

## PreRequisitos

Lo primero que debemos de hacer es crear es el repositorio de git e inicializar el repositorio en local.

Para crear un nuevo repositorio en GitHub debemos de ir a nuestro perfil de GitHub y darle a __Añadir un nuevo repositorio__. Una vez creada nos aparecera esta pantalla:

![Salida al crear un repositorio](./images/imagen_0.png)

Una vez nos salga eso debemos de ir a la carpeta donde queremos inicializar nuestro repositorio en local y ejecutar los siguiente:

![Inicializando el repositorio en local](./images/imagen_1.png)

## Ejercicio 1

**
1. Crea un Dockerfile que partiendo de una imagen PHP genera una imagen que:
  1. Copia una aplicacion en PHP a un directorio del contenedor. Esta aplicacion se debe copiar directamente desde un directorio del anfitrión. Para facilitar las cosas, debe de ser una aplicacion sencilla que no emplee bases de datos (ya que sino tambien habría que instalar un Mysql)
**

Una vez que tenemos los prerequisitos hechos debemos de crear la carpeta del Ejercicio 1. En esta carpeta añadiremos el Dockerfile del ejercicio1, del que luego generaremos la imagen. 

Contenido carpeta Ejercicio1:

![Contenido carpeta Ejercico1](./images/imagen_3.png)
El contenido del Dockerfile es el siguiente:

![Contenido Dockerfile ejercicio1](./images/imagen_2.png)

En la linea uno lo que hacemos en usar una imagen de PHP en su version 7.4 con apache. En la linea 2 copiamos la carpeta PHP de nuestra maquina y por ultimo debemos de exponer el puerto 80.



# Entrega Final - Sistemas Operativos

## Marina Garayoa 1º GSS

### Por qué utilizar GitHub:

Podemos usar GitHub para controlar un proyecto localmente por estas razones:

1. Por si se nos rompe el PC 
2. Para compartir codigo
3. Para subir cosas tanto 
publicas como privadas
4. Para contactar con expertos
5. Para organizar tus temas

### Instalación de GitHub:
1. Creamos una cuenta nueva de GitHub e iniciamos sesión
2. Abrimos el terminal(CMD) de Ubuntu y escribimos lo siguiente:

        sudo apt update
        sudo apt install git
    Seguidamente configuramos nuestro GitHub con:

        git config --global Marina
        git config --global marina.garayoa@outlook.es
 
    Y ya tenemos nuestro GitHub configurado y podemos iniciar sesión en: https://github.com/.

### Estructura del Proyecto:
Creamos un directorio llamado, en mi caso, **Proyecto Final - Marina Garayoa**
<img src="cap2.png"/>

Después de crear el directorio creamos el archivo llamado, en mi caso,
**Proyecto Final - Marina Garayoa** dentro del directorio anterior.

<img src="cap3.png"/>

### Inicialización de GitHub:
Creamos un **repostorio** nuevo en GitHub para poder subir nuestro directorio con el archivo en su interior,
 clickando en **"Nuevo Repostorio"**.

 Seguidamente le ponemos nombre, en mi caso, **Entrega-Final-Sistemas-Operativos** y le damos a crear.

<img src="cap1.png"/>

 ### Como crear un "Commit":
 1. Primero inicializamos Git con:

        git init

2. Después añadimos los archivos:

        git add. 

3. Creamos el Commit con este comando:

        git commit -m "Esto es un Commit"

4. Agregamos el repositorio remoto:

        git remote add origin https://github.com/MarinaGarayoa/Entrega-Final-Sistemas-Operativos.git

5. Y por último lo empujamos a GitHub con:

        git push -u origin main

Y ya tendríamos el **Commit** subido a GitHub.


*Marina Garayoa*


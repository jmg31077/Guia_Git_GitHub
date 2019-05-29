# Guia_Git_GitHub

## Qué es Git
Git es un proyecto de **código abierto**, satisface las necesidades a la plazo de los usuarios regulares que realizan mejoras, **usabilidad y funcionalidad de un proyecto.**

## Qué es GitHub

Es un servicio en la nube que ayuda a almacenar mantener y administrar
**nuestro código seguro** el cual lleva un registro y control de los cambios que se realiza a este código.

## Beneficios del control de versiones

Los sistemas de control de versiones son una categoría de herramientas de software que ayudan a un equipo de software a administrar los cambios en el código fuente a lo largo del tiempo.}

El control de versiones protege el código fuente de la catástrofe y la degradación casual del error humano y las consecuencias no deseadas.

Los puntos de alto nivel que cubrirá esta guía son:

- Inicializando un nuevo repositorio de Git
- Clonando un repositorio de Git existente
- Confirmando una versión modificada de un archivo al repositorio.
- Configurando un repositorio de Git para colaboración remota
- Comandos comunes de control de versiones de Git

## git init

Para crear un nuevo repositorio inserte git init un comando que se usa una sola vez durante la configuración inicial de un nuevo repositorio La ejecución de este comando creará un nuevo gitsubdirectorio en su directorio de trabajo actual Esto también creará una nueva
rama maestra

Primero irá a la carpeta del proyecto raíz y luego ejecutará el git init

**/Guia_Git_GitHub$ git init**

## git clone

Si un proyecto ya se ha configurado en un repositorio central, el comando de clonación es la forma más común para que los usuarios obtengan un clon de desarrollo local

Guardar cambios en el repositorio: git add y git commit
Ahora que tiene un repositorio clonado o inicializado, puede enviarle cambios en la versión del archivo
 [/Guia_Git_GitHub$ git clone] (https://github.com/jmg31077/Guia_Git_GitHub.git)

### pasos para ejecutar un nuevo repositorio

- touch README.md
- git init
- git add README.md
- git commit -m "comentario"
- git remote add origin (https://github.com/jmg31077/Repositorio.git)
- git push -u origin master

**git add**
comando agrega un cambio en el directorio de trabajo al área de preparación

### Git remote

El git remote comando le permite crear, ver y eliminar conexiones a otros repositorios

### Configuraciones remotas de git

**/Guia_Git_GitHub$git remote**
Listar las conexiones remotas que tiene con otros repositorios.

**git remote -v**
Igual que el comando anterior, pero incluye la URL de cada conexión

## git fetch

Recupera todas las ramas del repositorio. Esto también descarga todos los archivos y confirmaciones necesarios del otro repositorio

Igual que el comando anterior, pero solo recupera la rama especificada.

**/Guia_Git_GitHub$ git fetch --all**
Un movimiento de poder que recupera todos los controles remotos registrados y sus ramas:

**/Guia_Git_GitHub$git fetch --dry-run**
La --dry-run opción realizará una ejecución demo del comando

## git push

comando se utiliza para cargar el contenido del repositorio local en un repositorio remoto.

**Uso de Git Push**
**/Guia_Git_GitHub$git push**  
Empuje la rama especificada a remoto, junto con todos los objetos internos y confirmaciones necesarios.

**/Guia_Git_GitHub$git push  --force**
Igual que el comando anterior, pero fuerce el empuje incluso si resulta en una fusión sin avance rápido.

## Git Chechout

Comando que sirve para volver a una version anterior de nuestro proyecto

Guia_Git_GitHub$git checkout

git checkout

# Manual de Uso GIT by Edwin

Para comprender mejor lo que son estas tecnologías primero repasaremos algunos conceptos básicos acerca de 

## Rquerimientos

* GIT

## Intalar Git

```
sudo apt-get install git 
```


## Que es Git?


Es un software que nos sirve para el control de versiones.


## Que es control de version?


Control de cambios o configuraciones de una Aplicacion o Pagina Web.


## Ventajas de Git


* Velocidad
* Gestión distribuida
* Gestión eficiente
* Re almacenamiento periódico de paquetes.


A continuación realizaremos un manual de ejemplos del uso de Git.

## Pasos para Clonar un Proyecto con Git (CLON)

### Que es CLON?

Clon en Git es la copia de un proyecto existente en la nube, se realiza para poder copiar proyectos y trabajar envase a estos.

* Para empezar a trabajar con git debemos ubicarnos en la carpeta del donde se guardara el Proyecto (En este caso la carpeta es laravel-proyect)

```
daniel@dquenallata:~/laravel-proyect$ 
```
 * Inicializar el Git

 ```
daniel@dquenallata:~/laravel-proyect$ git init
```

* Clonar el Proyecto

```
daniel@dquenallata:~/laravel-proyect$ git clone git://github.com/schacon/grit.git Nombre_Proyecto
```
* Ingresar al Proyecto 

``` 
daniel@dquenallata:~/laravel-proyect$ cd Nombre_Proyecto
daniel@dquenallata:~/laravel-proyec/Nombre_Proyecto$
```
Ahora ya tenemos el proyecto Clonado en nuestro Equipo

## Pasos para Clonar un Proyecto con Git (FORK)

### Que es FORK?

Fork en Git es la copia exacta de un proyecto, se lo reliza para poder contribuir a un proyecto.

* Realizamos un fork desde la pagina de Guit-Hub

Buscamos la pagina y a continuacion pulsamos en el boton fork, seguidamente ingresamos al proyecto que se creara en nuestra cuenta como contenedor y procedemos a clonar con los siguientes pasos.

* Para empezar a trabajar con git debemos ubicarnos en la carpeta del donde se guardara el Proyecto al cual debemos contribuir  (En este caso la carpeta es laravel-proyect)

```
daniel@dquenallata:~/laravel-proyect$ 
```
 * Inicializar el Git

 ```
daniel@dquenallata:~/laravel-proyect$ git init
```

* Clonar el Proyecto

```
daniel@dquenallata:~/laravel-proyect$ git clone git://github.com/dequenallata/grit.git 
```
* Ingresar al Proyecto 

``` 
daniel@dquenallata:~/laravel-proyect$ cd grit
daniel@dquenallata:~/laravel-proyec/grit$
```
Ahora ya tenemos el proyecto en nuestro equipo para poder contribuir a este proyecto.

## Actualizar un repositorio Propio

* Tenemos que ubicarnos en la carpeta donde esta el proyecto(En este caso laravel-proyect)

* Inicializar Git
 ```
daniel@dquenallata:~/laravel-proyect$ git init
```
* Para adicionar todos los cambios y archivos.

 ```
daniel@dquenallata:~/laravel-proyect$ git add .
```

* Para adicionar un archivo en especifico

 ```
daniel@dquenallata:~/laravel-proyect$ git add nombredelarchivo+extension
```
* A continuacion realizamos el commit a nuestros cambios

 ```
daniel@dquenallata:~/laravel-proyect$ git commit -m "Descripcion_del_Cambio"
```

* Seguidamente adicionamos remotamente al proyecto.

 ```
daniel@dquenallata:~/laravel-proyect$ git remote add origin https://github.com/dequenallata/Guia_Git_GitHub.git
```
* Y por ultimo subimos todo a la nube

 ```
daniel@dquenallata:~/laravel-proyect$ git push -U origin master
 ```
## Actualizar un repositorio para Contribuir un Proyecto

* Tenemos que ubicarnos en la carpeta donde esta el proyecto(En este caso laravel-proyect)

* Inicializar Git
 ```
daniel@dquenallata:~/laravel-proyect$ git init
```
* Para adicionar todos los cambios y archivos.

 ```
daniel@dquenallata:~/laravel-proyect$ git add .
```

* Para adicionar un archivo en especifico

 ```
daniel@dquenallata:~/laravel-proyect$ git add nombredelarchivo+extension
```
* A continuacion realizamos el commit a nuestros cambios

 ```
daniel@dquenallata:~/laravel-proyect$ git commit -m "Descripcion_del_Cambio"
```

* Y por ultimo subimos todo a la nube

 ```
daniel@dquenallata:~/laravel-proyect$ git push -U origin master
 ```
* Una vez realizado todos estos pasos el autor debera de aceptar o rechazar los cambios realizados en la pagina de Git-Hub

## Eliminar datos de un proyecto GIT

* Verificamos todos los commits realizados.

 ```
daniel@dquenallata:~/laravel-proyect$ git log
 ```

* Reset Soft : Solo borra archivos del repositorio

 ```
daniel@dquenallata:~/laravel-proyect$ git reset --soft nombrearchivo+extension
 ```
* Reset Hard : Solo borra archivos del repositorio y del area de trabajo local

 ```
daniel@dquenallata:~/laravel-proyect$ git reset --hard nombrearchivo+extension
 ```
>>>>>>> 3cad362d68f626386db5f00b338d6ca7a891e6a3

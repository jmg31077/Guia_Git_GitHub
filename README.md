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

Para crear un nuevo repositorio inserte git initcomando git inites un comando que se usa una sola vez durante la configuración inicial de un nuevo repositorio La ejecución de este comando creará un nuevo gitsubdirectorio en su directorio de trabajo actual Esto también creará una nueva
rama maestra

Primero irá cda la carpeta del proyecto raíz y luego ejecutará el git initcomando

/Guia_Git_GitHub$ git init

### git clone

Si un proyecto ya se ha configurado en un repositorio central, el comando de clonación es la forma más común para que los usuarios obtengan un clon de desarrollo local

Guardar cambios en el repositorio: git add y git commit
Ahora que tiene un repositorio clonado o inicializado, puede enviarle cambios en la versión del archivo
 [/Guia_Git_GitHub$ git clone] (https://github.com/jmg31077/Guia_Git_GitHub.git)

### pasos para ejecutar un nuevo repositorio

touch README.md
git init
git add README.md
git commit -m "comentario"
git remote add origin (https://github.com/jmg31077/Repositorio.git)
git push -u origin master.

**/Guia_Git_GitHub$ git add**
comando agrega un cambio en el directorio de trabajo al área de preparación.
/Guia_Git_GitHub$ git add .

/Guia_Git_GitHub$ git add [nombre del archivo]

**/Guia_Git_GitHub$ git diff**

es un comando de Git de uso múltiple que cuando se ejecuta ejecuta una función diff en las fuentes de datos de Git.

### Git remoto

El git remoto comando le permite crear, ver y eliminar conexiones a otros repositorios.

### Configuraciones remotas de git

Listar las conexiones remotas que tiene con otros repositorios.

**/Guia_Git_GitHub$ git remote -v**
Igual que el comando anterior, pero incluye la URL de cada conexión.

### git fetch

comando descarga confirmaciones, archivos y referencias de un repositorio remoto a su repositorio local.

/Guia_Git_GitHub$ git fetch

Recupera todas las ramas del repositorio. Esto también descarga todos los archivos y confirmaciones necesarios del otro repositorio

**/Guia_Git_GitHub$ git fetch**
Igual que el comando anterior, pero solo recupera la rama especificada.

**/Guia_Git_GitHub$ git fetch --all**
Un movimiento de poder que recupera todos los controles remotos registrados y sus ramas:

**/Guia_Git_GitHub$ git fetch --dry-run**
La --dry-run opción realizará una ejecución demo del comando

## git push

comando se utiliza para cargar el contenido del repositorio local en un repositorio remoto.

**Uso de Git Push**
**git push**  
Empuje la rama especificada a remoto, junto con todos los objetos internos y confirmaciones necesarios.

**git push  --force**
Igual que el comando anterior, pero fuerce el empuje incluso si resulta en una fusión sin avance rápido.

# Guia_Git_GitHub

## ¿Qué es Git?
Git es un proyecto **de código abierto**, que satisface las necesidades de los usuarios habituales que realizan mejoras, **facilidad de uso y funcionalidad de un proyecto.**

## ¿Qué es GitHub?

Es un servicio en la nube que ayuda a almacenar, mantener y administrar.
**nuestro código de seguridad** que mantiene un registro y control de los cambios realizados en este código.

## Beneficios del control de versiones

Los sistemas de control de versiones son una categoría de herramientas de software que ayudan a un equipo de software a administrar los cambios en el código fuente a lo largo del tiempo.}

El control de versión protege el código fuente de la catástrofe y la degradación casual del error humano y las consecuencias no deseadas.

Los puntos de alto nivel que cubrirá esta guía son:

- Inicializando un nuevo repositorio Git.
- Clonando un repositorio Git existente
- Confirmando una versión modificada de un archivo al repositorio.
- Configuración de un repositorio Git para la colaboración remota.
- Comandos comunes para el control de versiones de Git.

## git init

Para crear un nuevo repositorio, inserte git initcomando git en un comando que se usa solo una vez durante la configuración inicial de un nuevo repositorio. La ejecución de este comando creará un nuevo gitsubdirectory en su directorio de trabajo actual. Esto también creará un nuevo repositorio.
rama maestra

Primero, ve a la carpeta del proyecto raíz y luego ejecuta git initcomando

/ Guia_Git_GitHub $ git init

### git clone

Si un proyecto ya se ha configurado en un repositorio central, el comando de clonación es la forma más común para que los usuarios obtengan un clon de desarrollo local

Guardar cambios en el repositorio: git add y git commit
Ahora que tiene un repositorio clonado o inicializado, puede enviar cambios a la versión del archivo
** / Guia_Git_GitHub $ git clone <https://github.com/jmg31077/Guia_Git_GitHub.git> Guia_Git_GitHub **

### estado de git

El comando git status muestra el estado del directorio de trabajo y el área de preparación

**/ Guia_Git_GitHub $ git status**
En la rama proceso
Tu rama está actualizada con 'origen / proceso'.

Archivos sin seguimiento:
  (usa "git add [archivo] ..." para incluirlo a lo que se confirmará)
README2.MD

no hay nada agregado al cometer pero hay archivos sin seguimiento presente (usa "git add" para hacerles seguimiento)

### pasos para ejecutar un nuevo repositorio

toca README.md
git init
git add README.md
git commit -m "comentario"
git remoto agregar origen <https://github.com/jmg31077/Repositorio.git>
git push -u maestro de origen

**/ Guia_Git_GitHub $ git add**

comando agrega un cambio en el directorio de trabajo al área de preparación.
**/ Guia_Git_GitHub $ git add.**

**/ Guia_Git_GitHub $ git add [nombre de archivo]**

## Git Diff
# Guia_Git_GitHub

## ¿Qué es Git?
Git es un proyecto ** de código abierto **, que satisface las necesidades de los usuarios habituales que realizan mejoras, ** facilidad de uso y funcionalidad de un proyecto. **

## ¿Qué es GitHub?

Es un servicio en la nube que ayuda a almacenar, mantener y administrar.
** nuestro código de seguridad ** que mantiene un registro y control de los cambios realizados en este código.

## Beneficios del control de versiones

Los sistemas de control de versiones son una categoría de herramientas de software que ayudan a un equipo de software a administrar los cambios en el código fuente a lo largo del tiempo.}

El control de versión protege el código fuente de la catástrofe y la degradación casual del error humano y las consecuencias no deseadas.

Los puntos de alto nivel que cubrirá esta guía son:

- Inicializando un nuevo repositorio Git.
- Clonando un repositorio Git existente
- Confirmando una versión modificada de un archivo al repositorio.
- Configuración de un repositorio Git para la colaboración remota.
- Comandos comunes para el control de versiones de Git.

## git init

Para crear un nuevo repositorio, inserte git initcomando git en un comando que se usa solo una vez durante la configuración inicial de un nuevo repositorio. La ejecución de este comando creará un nuevo gitsubdirectory en su directorio de trabajo actual. Esto también creará un nuevo repositorio.
rama maestra

Primero, ve a la carpeta del proyecto raíz y luego ejecuta git initcomando

/ Guia_Git_GitHub $ git init

### git clone

Si un proyecto ya se ha configurado en un repositorio central, el comando de clonación es la forma más común para que los usuarios obtengan un clon de desarrollo local

Guardar cambios en el repositorio: git add y git commit
Ahora que tiene un repositorio clonado o inicializado, puede enviar cambios a la versión del archivo
** / Guia_Git_GitHub $ git clone <https://github.com/jmg31077/Guia_Git_GitHub.git> Guia_Git_GitHub **

### estado de git

El comando git status muestra el estado del directorio de trabajo y el área de preparación

** / Guia_Git_GitHub $ git status **
En la rama proceso
Tu rama está actualizada con 'origen / proceso'.

Archivos sin seguimiento:
  (usa "git add [archivo] ..." para incluirlo a lo que se confirmará)
README2.MD

no hay nada agregado al cometer pero hay archivos sin seguimiento presente (usa "git add" para hacerles seguimiento)

### pasos para ejecutar un nuevo repositorio

toca README.md
git init
git add README.md
git commit -m "comentario"
git remoto agregar origen <https://github.com/jmg31077/Repositorio.git>
git push -u maestro de origen

** / Guia_Git_GitHub $ git add **

comando agrega un cambio en el directorio de trabajo al área de preparación.
** / Guia_Git_GitHub $ git add. **

** / Guia_Git_GitHub $ git add [nombre de archivo] **

## Git Diff

es un comando de Git de usos múltiples que cuando se ejecuta ejecuta una función diff en las fuentes de datos de Git.
** / Guia_Git_GitHub $ git diff **

### Git remoto

El comando git remoto le permite crear, ver y eliminar conexiones a otros repositorios.

### Configuraciones de git remotas

Listar las conexiones remotas que tiene con otros repositorios.

** / Guia_Git_GitHub $ git remote -v **
Igual que el comando anterior, pero incluye la URL de cada conexión.

### git fetch

El comando descarga confirmaciones, archivos y referencias desde un repositorio remoto a su repositorio local.

/ Guia_Git_GitHub $ git fetch

Recupera todas las ramas del repositorio. Esto también descarga todos los archivos necesarios y confirmaciones del otro repositorio.

** / Guia_Git_GitHub $ git fetch **
Igual que el comando anterior, pero solo recupera la rama especificada.

** / Guia_Git_GitHub $ git fetch --todos **
Un movimiento de poder que recupera todos los controles remotos registrados y sus ramas:

** / Guia_Git_GitHub $ git fetch --dry-run **
La opción --dry-run realizará una ejecución de demostración del comando

## git push

El comando se utiliza para cargar el contenido del repositorio local en un repositorio remoto.

**Uso de Git Push**
**/ Guia_Git_GitHub $ git push**
Empuje la rama especificada a remoto, junto con todos los objetos internos y las confirmaciones necesarias.

**/ Guia_Git_GitHub $ git push --force**
Igual que el comando anterior, pero fuerce el empuje incluso si resulta en una fusión sin avance rápido.

## git diff

es un comando de Git de usos múltiples que cuando se ejecuta ejecuta una función diff en las fuentes de datos de Git.
**/ Guia_Git_GitHub $ git diff**

## git remoto

El comando git remoto le permite crear, ver y eliminar conexiones a otros repositorios.

**Configuraciones de git remotos**

Listar las conexiones remotas que tiene con otros repositorios.

**/Guia_Git_GitHub $ git remote -v**
Igual que el comando anterior, pero incluye la URL de cada conexión.

## git fetch

El comando descarga confirmaciones, archivos y referencias desde un repositorio remoto a su repositorio local.

**/Guia_Git_GitHub $ git fetch**

Recupera todas las ramas del repositorio. Esto también descarga todos los archivos necesarios y confirmaciones del otro repositorio.

**/Guia_Git_GitHub $ git fetch**
Igual que el comando anterior, pero solo recupera la rama especificada.

**/ Guia_Git_GitHub $ git fetch --all**
Un movimiento de poder que recupera todos los controles remotos registrados y sus ramas:

** / Guia_Git_GitHub $ git fetch --dry-run **
La opción --dry-run realizará una ejecución de demostración del comando

## git push

El comando se utiliza para cargar el contenido del repositorio local en un repositorio remoto.

**/ Guia_Git_GitHub $ git push**
Empuje la rama especificada a remoto, junto con todos los objetos internos y las confirmaciones necesarias.

**/ Guia_Git_GitHub $ git push --force**
Igual que el comando anterior, pero fuerce el empuje incluso si resulta en una fusión sin avance rápido.



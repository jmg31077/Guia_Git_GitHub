# Guia_Git_GitHub

## What is Git
Git is an **open source** project, satisfying the needs of regular users who make improvements, **usability and functionality of a project.**

## What is GitHub

It is a cloud service that helps to store maintain and manage
**our secure code** which keeps a record and control of the changes made to this code.

## Benefits of version control

Version control systems are a category of software tools that help a software team manage changes in the source code over time.}

Version control protects the source code of the catastrophe and the casual degradation of human error and unintended consequences.

The high-level points that this guide will cover are:

- Initializing a new Git repository
- Cloning an existing Git repository
- Confirming a modified version of a file to the repository.
- Configuring a Git repository for remote collaboration
- Common commands for version control of Git

## git init

To create a new repository insert git initcomando git inites a command that is used only once during the initial configuration of a new repository Execution of this command will create a new gitsubdirectory in your current working directory This will also create a new
master branch

First, go to the root project folder and then run the git initcomando

/ Guia_Git_GitHub $ git init

### git clone

If a project has already been configured in a central repository, the cloning command is the most common way for users to obtain a local development clone

Save changes in the repository: git add and git commit
Now that you have a cloned or initialized repository, you can send changes to the file version
 **/Guia_Git_GitHub$ git clone <https://github.com/jmg31077/Guia_Git_GitHub.git> Guia_Git_GitHub**

### git status

The git status command displays the state of the working directory and the staging area

**/Guia_Git_GitHub$ git status**
En la rama proceso
Tu rama está actualizada con 'origin/proceso'.

Archivos sin seguimiento:
  (usa "git add [archivo]..." para incluirlo a lo que se será confirmado)
README2.MD

no hay nada agregado al commit pero hay archivos sin seguimiento presentes (usa "git add" para hacerles seguimiento)

### steps to run a new repository

touch README.md
git init
git add README.md
git commit -m "comment"
git remote add origin <https://github.com/jmg31077/Repositorio.git>
git push -u origin master

**/Guia_Git_GitHub$ git add**

command adds a change in the working directory to the preparation area.
**/Guia_Git_GitHub $ git add .**

**/Guia_Git_GitHub $ git add [file name]**

## Git Diff

is a multi-use Git command that when executed executes a diff function in the Git data sources.
**/Guia_Git_GitHub $ git diff**

### Remote Git

The remote git command allows you to create, view and delete connections to other repositories.

### Remote git configurations

List the remote connections you have with other repositories.

**/ Guia_Git_GitHub $ git remote -v**
Same as the previous command, but it includes the URL of each connection.

### git fetch

command downloads confirmations, files and references from a remote repository to your local repository.

/ Guia_Git_GitHub $ git fetch

Retrieve all branches of the repository. This also downloads all the necessary files and confirmations from the other repository

**/ Guia_Git_GitHub $ git fetch**
Same as the previous command, but only retrieves the specified branch.

**/ Guia_Git_GitHub $ git fetch --all**
A power movement that recovers all registered remotes and their branches:

**/ Guia_Git_GitHub $ git fetch --dry-run**
The --dry-run option will perform a demo execution of the command

## git push

command is used to load the content of the local repository in a remote repository.

**Use of Git Push**
**/ Guia_Git_GitHub $git push**
Push the specified branch to remote, along with all internal objects and necessary confirmations.

**/ Guia_Git_GitHub $ git push --force**
Same as the previous command, but force the push even if it results in a merger without fast forward.

## git blame

command is a versatile troubleshooting utility that has extensive usage options
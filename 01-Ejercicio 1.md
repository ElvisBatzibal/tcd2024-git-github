# Descripcion. 
Inicializar y configurar un repositorio local en Git y posteriormente conectarlo con un repositorio remoto en GitHub:
```
cd C:
mkdir TCD2024
cd TCD2024
mkdir app.api
cd app.api
```

# Descripcion. 

Configurar git con tu nombre de usuario y dirección de correo electrónico.

```
git config --global user.name "Nombre"
git config --global user.email correo@example.com


git config  user.name "Nombre"
git config  user.email correo@example.com
```


```
Crear repositorio. 

git init

Crear ramas. 
main => master
developer => dev, develop, developer
release => r_1.0.0
feature => feature_login, feature_migration
bugfix => bugfix_release
hotfix => hotfix_recovery, hotfix_login
support


git status

git add filename

git status

git add FolderName
git add *name
git add .


git commit -m "Mi primer commit"

HASH: Identificador unico. Fotografia unica. 

git status

git commit -a -m "Mi segundo commit"

git log 

Modificacion de archivo. 

checkout regresar a un cambio especifico 
puede aplicarse a archivo o rama
git reset
git checkout FileName

git add .
git commit -m "Modificacion de archivos"

git log 

git log --graph
git log --graph --pretty=oneline
git log --graph --decorate --all --oneline

Creacion de alias

git config --global alias.tree "log --graph --decorate --all --oneline"

git tree

Creacion de .gitignore
.json
Agregar archivo json
Corregir gitignore
*.json




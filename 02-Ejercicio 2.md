## RAMAS O Branch

Un commit siempre nos lleva hacia adelante. 




```
main => master
developer => dev, develop, developer
release => r_1.0.0
feature => feature_login, feature_migration
bugfix => bugfix_release
hotfix => hotfix_recovery, hotfix_login
support

```

```
git branch login
git status
git tree
git switch login
git add .
git commit -m "Add login"
git log 
git switch main
git add . 
git commit - "Version 2"
git tree
git switch login
Traer los datos de main a login
git merge main
git tree

```

Conflictos
Modificar un archivo en main 
Modificar el mismo archivo en la rama login

```
git switch login
git merge main
git commit -m "Correcion conflictos"

```

Integracion de ramas

```
git switch main
git diff login 
git merge login
git branch -d login
```
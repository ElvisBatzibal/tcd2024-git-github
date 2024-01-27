# Git. 

# Principales conceptos. 

- Repository (Repo):
- Commit:
- Branch:
- Merge: 
- Pull Request (PR):
- Clone: 

# Metodos para establecer una clonacion segura. 
- HTTPS:
- SSH: 

# Flujo de trabajo básico de Git

- Clone: copie un repositorio remoto a su máquina local.
- Branch: cree una nueva rama para una característica específica o corrección de errores.
- Commit: realice cambios en los archivos y confírmelos con un mensaje descriptivo.
- Push: envía tus confirmaciones a un repositorio remoto.
- PullRequest -Solicitud de extracción: proponer cambios e iniciar una discusión.
- Review: colaborar con los miembros del equipo para revisar los cambios propuestos.
- Merge - Fusionar: integra los cambios en la rama principal.

# Comandos Basicos de Git
git init: inicializa un nuevo repositorio de Git.
git clone: copia un repositorio remoto a tu máquina local.
git add: cambios de etapa para la confirmación.
git commit: registra los cambios con un mensaje de confirmación.
git push: envía confirmaciones locales a un repositorio remoto.
git pull: recupera cambios de un repositorio remoto y los fusiona localmente.
git merge: combina cambios de diferentes ramas.

## Configuracion. 

$ git config --global user.name "Nombre"
$ git config --global user.email correo@example.com
git config --global --editar
Abra el archivo de configuración global en un editor de texto para editarlo manualmente.


# Obtener y crear proyectos

git init : Inicializa un repositorio local de git. 
git clone https://github.com/ElvisBatzibal/tcd2024-git-github.git : 




# Snapshotting basicos:
git status:  Verificar estado de una rama.
git add [file-name.txt]:  Agrega un archivo al área de preparación
ggit add -A: agrega todos los archivos nuevos y modificados al área de preparación
git commit -m "[commit message]" : Confirmar cambios
git rm -r [file-name.txt] :  Eliminar un archivo (o carpeta)


# Ramificación y fusión
git status: comprueba el estado de tu directorio de trabajo.
git branch: lista de ramas.
git checkout <branch_name>: cambia a una rama diferente.
git checkout -b <branch_name>: Crea una nueva rama y cambia a ella.
git merge <branch_name>: fusiona cambios de una rama en otra.
git bisect: encuentra la confirmación que introduce un error.
git reflog: vea un registro de todos los comandos de Git ejecutados.

## Actualizacion y Publicacion
git pull : Actualizar el repositorio local a la commit más reciente.
git fetch 
git push : Enviar cambios al repositorio remoto (rama recordada)
git remote -v : Listar todos los controles remotos configurados recientemente
git fetch origin <branchname> recupera cambios desde un repositorio remoto.
git pull origin <branchname> recupera y fusiona cambios desde un repositorio remoto.
git push origin <branchname>  envía cambios a un repositorio remoto.

## Historial de Commits. 
git log  : ver el historial de confirmaciones.
git log -p <file_name> : Mostrar cambios durante un tiempo para un archivo específico
git blame <file_name> : Quién cambió qué y cuándo en un archivo específico

## Inspección y comparación:
git log - : ver cambios
git log --summary - : Ver cambios detallados. 
git log --oneline - : Ver cambios brevemente
git diff [source branch] [target branch] - Vista previa de los cambios antes de fusionarlos

## Deshacer Cambios
git revert <commit>
git reset <nombre_archivo>: Elimine <archivo> del área del Stage.


# Crear repositorio. 

git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/ElvisBatzibal/tcd2024-git-github.git
git push -u origin main

# push an existing repository from the command line

git remote add origin https://github.com/ElvisBatzibal/tcd2024-git-github.git
git branch -M main
git push -u origin main

# import code from another repository



# Temas avanzados de Git
 
Git Hooks: Los hooks de Git permiten a los desarrolladores ejecutar scripts personalizados durante eventos de Git.

Estrategias de Rebase:
Gitignore: El archivo .gitignore especifica archivos o directorios de los que Git no debe realizar un seguimiento intencional, lo que ayuda a mantener limpio el repositorio.

Mensajes de confirmación significativos: proporcione mensajes detallados con cada confirmación.
Estrategias de ramificación: elija estrategias de ramificación adecuadas según los requisitos del proyecto.

Revisiones de código: utilice plataformas como GitHub para revisiones de código efectivas a través de solicitudes de extracción.

# Recomendaciones para un repositorio
Include a 
README, 
LICENSE, and 
.gitignore.

# Fase 2. 
Colaboración con Git
La colaboración en Git implica bifurcaciones, solicitudes de extracción y una gestión eficaz de las sucursales.

Bifurcaciones y solicitudes de extracción
Plataformas como GitHub o GitLab permiten flujos de trabajo colaborativos a través de bifurcaciones y solicitudes de extracción. La bifurcación crea una copia personal de un repositorio y las solicitudes de extracción proponen cambios en el repositorio original.

Flujos de trabajo colaborativos
Los equipos adoptan varios flujos de trabajo de Git según las necesidades del proyecto. La ramificación de funciones, GitFlow y el desarrollo basado en troncales son estrategias populares.

Manejo de conflictos
La fusión de cambios puede generar conflictos. La resolución de conflictos garantiza que los cambios de código se integren armoniosamente.
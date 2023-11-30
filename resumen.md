## Resumen de comandos git

Comando | Función | Ejemplo
--------|---------|---------
init | Inicia un repositorio | git init
config | Para configurar los datos del git | git config --global user.name "Tu Nombre"
add | Para añadir al stage un archivo/directorio | git add README.md
commit | Para añadir al repositorio un archivo o directorio | git commit -m "Añado README.md"
status | Para saber en qué estado está nuestro git | git status 
log | Para ver el historial de commits realizados | git log --oneline 
diff | Para ver la diferencia entre un commit y otro | git diff (commit1) (commit2)
show | Para mostrar información sobre el objeto que estás consultando | git show (nombre etiqueta)
tag | Para crear etiquetas | git tag v1.0.0
restore | Para restaurar archivos en tu directorio de trabajo | git restore archivo.txt
revert | Para deshacer cambios realizados en una confirmación específica | git revert HEAD
reset | Para deshacer cambios en el historial de confirmaciones | git reset --soft HEAD~1
branch | Para crear una rama o para ver qué ramas tenemos en git | git branch (nueva rama)
switch | Para cambiar de una rama a otra | git switch main
merge | Para fusionar dos ramas | git merge (rama)
remote | Para administrar conexiones remotas a repositorios | git remote show origin
clone | Para clonar un repositorio remoto y crear una copia local de ese repositorio en tu máquina | git clone (URL)
push | Para enviar los cambios locales realizados en tu rama a un repositorio remoto | git push origin main
pull | Para recuperar cambios desde un repositorio remoto y fusionarlos automáticamente en tu rama local | git pull origin main
fetch | Para descargar cambios desde un repositorio remoto | git fetch origin main
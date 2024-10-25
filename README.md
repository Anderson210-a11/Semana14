# Semana14
Actividad Anderson Mejía 

# Comando Básicos 
git pull --rebase
Trae actualizaciones del repositorio remoto y aplica tus cambios locales sobre los cambios remotos sin generar un merge commit.

git stash
Guarda temporalmente tus cambios locales no confirmados para poder cambiar de rama sin perder tu trabajo.

git cherry-pick [commit-id]
Aplica los cambios de un commit específico a la rama actual sin necesidad de fusionar toda la rama de donde proviene.

git rebase -i [rama-base]
Rebasa interactivamente para modificar el historial de commits (reordenar, combinar, editar o eliminar commits).

git reset --hard [commit-id]
Deshace todos los cambios hasta el commit especificado, tanto en el directorio de trabajo como en el historial de commits. ¡Ten cuidado con esto, ya que es irreversible!

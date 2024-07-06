# Comandos Git Más Usados

Este archivo contiene una lista de los comandos Git más utilizados junto con una breve descripción de cada uno.

| **Comando Git**         | **Descripción**                                                                          |
|-------------------------|------------------------------------------------------------------------------------------|
| `git init`              | Inicializa un nuevo repositorio Git.                                                     |
| `git clone <url>`       | Clona un repositorio en un nuevo directorio.                                             |
| `git status`            | Muestra el estado del repositorio (archivos modificados, preparados, etc.).              |
| `git add <archivo>`     | Añade archivos al área de preparación (staging).                                         |
| `git commit -m "<msg>"` | Confirma los cambios en el repositorio con un mensaje descriptivo.                       |
| `git push`              | Envía los commits al repositorio remoto.                                                 |
| `git pull`              | Descarga cambios desde el repositorio remoto y los fusiona.                              |
| `git fetch`             | Descarga cambios desde el repositorio remoto sin fusionar.                               |
| `git merge <branch>`    | Fusiona la rama especificada con la rama actual.                                         |
| `git branch`            | Lista todas las ramas en el repositorio.                                                 |
| `git branch <nombre>`   | Crea una nueva rama.                                                                     |
| `git checkout <branch>` | Cambia a la rama especificada.                                                           |
| `git checkout <commit>` | Cambia a un commit específico (modo `detached HEAD`).                                    |
| `git reset --hard <commit>` | Restablece el repositorio al estado de un commit específico (perdiendo cambios no confirmados). |
| `git reset <archivo>`   | Deshace `git add` para el archivo especificado.                                           |
| `git rm <archivo>`      | Elimina un archivo del repositorio y del área de preparación.                            |
| `git log`               | Muestra el historial de commits.                                                         |
| `git show <commit>`     | Muestra los detalles de un commit específico.                                            |
| `git diff`              | Muestra las diferencias entre los commits o entre el estado actual y el área de preparación. |
| `git stash`             | Guarda temporalmente los cambios actuales sin confirmarlos.                              |
| `git stash pop`         | Aplica los cambios guardados con `git stash` y los elimina del stash.                    |
| `git remote`            | Administra las conexiones a repositorios remotos.                                         |
| `git remote -v`         | Muestra las URLs de los repositorios remotos.                                            |
| `git tag`               | Crea, lista o elimina etiquetas (tags).                                                  |
| `git rebase <branch>`   | Reaplica commits sobre la base de otra rama.                                             |
| `git bisect`            | Usa búsqueda binaria para encontrar el commit que introdujo un bug.                      |
| `git cherry-pick <commit>` | Aplica los cambios de un commit específico a la rama actual.                        |
| `git revert <commit>`   | Crea un nuevo commit que revierte los cambios de un commit específico.                   |
| `git mv <archivo>`      | Mueve o renombra un archivo.                                                             |
| `git config`            | Configura las opciones de Git a nivel global o de repositorio.                           |
| `git blame <archivo>`   | Muestra quién hizo qué cambio en cada línea de un archivo.                               |
| `git clean -fd`         | Elimina archivos no rastreados y directorios del repositorio de trabajo.                 |

## Instrucciones para Uso

Puedes usar este `README.md` como referencia rápida en tus proyectos de Git. Simplemente copia y pega el contenido en el archivo `README.md` de tu repositorio en GitHub.

## Contribuciones

Las contribuciones son bienvenidas. Si deseas añadir más comandos o mejorar las descripciones, siéntete libre de crear un Pull Request.

## Licencia

Este proyecto está licenciado bajo la Licencia MIT - consulta el archivo [LICENSE](LICENSE) para más detalles.

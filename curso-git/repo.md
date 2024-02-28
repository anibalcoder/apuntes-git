# Repositorio

Proyecto de software que se compone de múltiples archivos y sub carpetas que es controlado por Git.

<img src='../img/git/repo.png' alt="repositorio" width="350" style="border-radius: 10px;">

## Comandos

| Comando | Explicación |
|---------|-------------|
| `git init` | Inicializa Git es decir, convierte el proyecto en un repositorio. |
| `git config --global init.defaultBranch branch-name` | Cambia el nombre de la rama por defecto. Los cambios se efectúan a partir del siguiente repositorio. |
| `rm -rf .git/` | Elimina el repositorio actual. La carpeta oculta (.git) almacena toda la información relacionada con Git del proyecto. |

Al crear el archivo **.gitignore** se indica a Git qué **archivos y directorios ignorar en un repositorio**, evitando que se rastreen o incluyan en los commits.
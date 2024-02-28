# Configurar usuario y correo

Cada vez que creas un commit se registra tu información personal (usuario y correo).

Se puede configurar de dos formas:

- Para todos los repositorios alojados en tu computadora.
- Para un repositorio en particular.

## Usuario

| Comando | Descripción |
|---------|-------------|
| `git config --global user.name "username"` | Agrega el nombre de usuario para todos los repositorios. |
| `git config user.name` | Muestra el nombre del usuario. |

## Correo

| Comando | Descripción |
|---------|-------------|
| `git config --global user.email "email"` | Agrega un correo para todos los repositorios. |
| `git config user.email` | Muestra el correo. |

## Recordatorio

- Omitir **global** si deseas que la configuración sea para un repositorio en específico.
- Evita usar tu correo personal, ya que será parte de todo el historial de commit y visible para otros desarrolladores.
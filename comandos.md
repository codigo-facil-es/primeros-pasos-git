# Chuleta: los comandos de Git del tutorial

| Comando | Qué hace |
|---|---|
| `git init` | Convierte la carpeta en un repositorio de Git |
| `git status` | Muestra qué archivos han cambiado y cuáles no está guardando Git |
| `git add .` | Elige **todos** los cambios para el próximo commit (`git add archivo` para uno solo) |
| `git commit -m "mensaje"` | Guarda una «foto» del proyecto con un mensaje que explica el cambio |
| `git commit -am "mensaje"` | Atajo: `add` + `commit` de los archivos que Git ya conocía |
| `git diff` | Muestra qué ha cambiado desde el último commit (rojo: antes, verde: ahora) |
| `git restore archivo` | Recupera el archivo tal y como estaba en el último commit (¡pierdes los cambios sin guardar!) |
| `git log --oneline` | El historial: un commit por línea |

## Primera vez en tu ordenador

```bash
git config --global user.name "Tu Nombre"
git config --global user.email "tu@email.com"
```

## La regla de oro con agentes de IA

Haz un **commit antes de cada encargo** al agente. Si algo sale mal, `git restore .` o `git log` + `git checkout` te devuelven a un punto bueno.

Más en VS Code: el panel **Control de código fuente** (`Ctrl + Shift + G`) hace lo mismo con clics, y muestra el antes y el después lado a lado.

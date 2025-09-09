# Guía Básica de Git y GitHub
---

## Configuración Inicial

```bash
# Configurar nombre de usuario y correo
$ git config --global user.name "Tu Nombre"
$ git config --global user.email "tu.email@example.com"
```

---

## Comandos Básicos de Git

### 1. Clonar un repositorio
```bash
$ git clone <url-del-repositorio>
```

### 2. Ver estado de archivos
```bash
$ git status
```

### 3. Añadir archivos para commit
```bash
$ git add <archivo-o-directorio>
# Para añadir todos los cambios:
$ git add .
```

### 4. Hacer un commit
```bash
$ git commit -m "Mensaje descriptivo del cambio"
```

### 5. Ver historial de commits
```bash
$ git log
```

### 6. Crear y cambiar de rama
```bash
$ git branch <nombre-rama>  # Crear rama
$ git checkout <nombre-rama>  # Cambiar a la rama
# Alternativamente:
$ git checkout -b <nombre-rama>  # Crear y cambiar a la rama
```

### 7. Fusionar ramas
```bash
$ git checkout main  # Cambiar a rama principal
$ git merge <nombre-rama>  # Fusionar rama al main
```

### 8. Subir cambios a GitHub
```bash
$ git push origin <nombre-rama>
```

### 9. Actualizar repositorio local con cambios remotos
```bash
$ git pull origin <nombre-rama>
```

---

## Uso Básico de GitHub

- Crear repositorios nuevos para cada proyecto.
- Usar Pull Requests para integrar cambios y revisión de código.
- Abrir Issues para reportar errores o discutir mejoras.
- Usar GitHub Actions para automatizar pruebas y despliegues.

---

## Buenas Prácticas

- Mensajes de commit claros y descriptivos.
- Trabajar en ramas para cada nueva funcionalidad o corrección.
- Revisar y aprobar Pull Requests antes de fusionar.
- Mantener el repositorio limpio y ordenado.

---

## Recursos adicionales
- [Documentación oficial de Git](https://git-scm.com/doc)
- [Guía de GitHub](https://docs.github.com/es)

# Guía Rápida de Git

## Comandos Esenciales

### Inicialización y Configuración
```bash
git init                    # Inicializa un nuevo repositorio
git status                  # Muestra el estado actual
```

### Trabajo con Archivos
```bash
git add <archivo>           # Añade un archivo al staging
git add .                   # Añade todos los archivos
git commit -m "mensaje"     # Crea un nuevo commit
```

### Trabajo con Ramas
```bash
git branch                  # Muestra todas las ramas
git branch <nombre>         # Crea una nueva rama
git checkout <nombre>       # Cambia de rama
git merge <nombre>          # Fusiona ramas
```

### Historial
```bash
git log                     # Muestra el historial completo
git log --oneline          # Historial resumido
```

## Buenas Prácticas

1. **Commits atómicos**: Un commit por cambio lógico
2. **Mensajes claros**: Describe qué y por qué del cambio
3. **Branches para features**: Usa ramas para nuevas funcionalidades
4. **Commits frecuentes**: No acumules muchos cambios
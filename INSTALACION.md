# Guía de Instalación y Configuración

## Instalación de Git en macOS
```bash
xcode-select --install
```

## Configuración Inicial
```bash
git config --global user.name "Tu Nombre"
git config --global user.email "tuemail@estudiantedaw.es"
```

## Comandos Básicos de Git
- `git init` - Inicializar repositorio
- `git add .` - Añadir todos los archivos
- `git commit -m "mensaje"` - Guardar cambios
- `git push` - Subir a GitHub
- `git pull` - Descargar cambios
- `git status` - Ver estado actual

## Configuración SSH
1. Generar clave: `ssh-keygen -t ed25519 -C "tuemail"`
2. Añadir a GitHub: Settings → SSH and GPG keys
3. Verificar: `ssh -T git@github.com`

## Flujo de Trabajo Recomendado
1. `git pull` - Actualizar antes de trabajar
2. `git add .` - Añadir cambios
3. `git commit -m "descripción"` - Guardar
4. `git push` - Subir a GitHub
```

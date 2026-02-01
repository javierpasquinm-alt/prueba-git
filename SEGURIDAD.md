# Políticas de Seguridad

## Rama Principal Protegida
- La rama `main` está protegida
- Requiere Pull Request para cambios
- Necesita 1 aprobación mínimo
- Los tests deben pasar

## Archivos Excluidos (.gitignore)
- Archivos de entorno (.env)
- Dependencias (node_modules/)
- Archivos temporales del sistema

## Autenticación SSH
- Se utiliza SSH en lugar de HTTPS
- Clave Ed25519 generada localmente
- Verificación de conexión activa

## Buenas Prácticas
1. Nunca subir credenciales
2. Usar ramas para nuevas funcionalidades
3. Revisar código antes de merge
4. Mantener .gitignore actualizado


# Decider - Sistema de Actualizaciones

Este repositorio contiene los archivos necesarios para el sistema de actualizaciones automáticas de Decider.

## Estructura

- `updates/latest.json` - Información de la última versión disponible
- `releases/` - Archivos de instalación por versión (usando GitHub Releases)

## Versiones

### v1.0.3 (Actual)
- Sistema de actualizaciones automáticas
- Mejoras en la interfaz
- Corrección de errores

## Para desarrolladores

### Actualizar versión

1. Subir nuevo instalador como GitHub Release
2. Actualizar `updates/latest.json` con la nueva información
3. El sistema detectará automáticamente la nueva versión

### Estructura del latest.json

```json
{
  "version": "1.0.X",
  "download_url": "https://github.com/TomPi-2/Decider/releases/download/vX.X.X/DeciderSetup-X.X.X.exe",
  "release_notes": "Descripción de cambios...",
  "required": false
}

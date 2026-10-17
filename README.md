# View360 — descargas

Aquí se publican los instaladores de **View360 Desktop**, la app que ensambla tus fotos en panoramas 360° en tu propio equipo y los guarda en tu cuenta de View360.

> Plataforma web: https://view360.iguzman.com.mx

## Descargar

Ve a la sección **[Releases](../../releases/latest)** y baja el archivo de tu sistema:

| Sistema | Archivo |
|---|---|
| Windows | `View360-Setup-<versión>.exe` |
| macOS | `View360-<versión>.dmg` |
| Linux | `View360-<versión>.AppImage` o `view360_<versión>_amd64.deb` |

### Linux por terminal

```bash
curl -fsSL https://view360.iguzman.com.mx/install.sh | bash
```

## Primer arranque

Entra con la misma cuenta que usas en la web. No hay nada que emparejar: el motor de ensamblado viene incluido.

### Windows
Al abrir el instalador puede aparecer «Windows protegió su PC» porque la app aún no está firmada. Pulsa **Más información → Ejecutar de todos modos**.

### macOS
La primera vez, haz **clic derecho sobre la app → Abrir** y confirma. Si macOS la bloquea, ve a **Ajustes del Sistema → Privacidad y seguridad → Abrir de todos modos**.

### Linux (AppImage)
```bash
chmod +x View360-*.AppImage
./View360-*.AppImage
```

## Soporte

Este repositorio solo contiene los instaladores. Para dudas, escribe desde tu cuenta en la plataforma web.
